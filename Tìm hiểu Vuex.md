![](https://topdev.vn/blog/wp-content/uploads/2019/02/vuex-la-gi-1.png)


###Cấu Trúc Của Vuex
Đối với Vuex, store chính là nơi quản lý tập trung state của các ứng dụng bao gồm 5 phần chính: State, Getters, Mutation, Actions, Modules

##State (trạng thái)

```const state = {
  numbers: [1, 2, 3, 4, 5]
}```

##Getters (lọc trạng thái)

Điều mang đến sự khác biệt giữa Vuex và Redux chính là việc ta có thể điều chỉnh dữ liệu trước khi trả về state. Đôi khi chúng ta cần lấy các trạng thái dựa vào việc tính toán, lọc bỏ các trạng thái được cung cấp bởi kho lưu trữ, ví dụ:

```
const state = {
  getEvenNumbers: state => {
    return state.numbers.filter(item => item%2 === 0)
  }
  hasNumber : state => num => {
    return state.numbers.include(num)
  }
}
```

Nếu muốn sử dụng trong component thì bạn có thể gọi trực tiếp this.$store.getters.getEvenNumbers hoặc sử dụng mapGetter

##Mutations (thay đổi trạng thái)

Điểm mạnh của store chính là nơi compoment chỉ có thể đọc dữ liệu mà không được phép thay đổi trạng thái một cách trực tiếp. Nếu muốn thay đổi trạng thái thì Mutations là nơi duy nhất đảm nhiệm chức năng này bằng cách thay đổi thông qua commit. Dù không khuyến khích nhằm đảm bảo tính Flow chuẩn tuy nhiên tại compoment, bạn vẫn có thể thực hiện được commit đến mutations.

Điểm cần lưu ý chính là mutations là synchronous nhằm kiểm soát được action đã thay đổi state hay thứ tự thay đổi như thế nào

```
const mutations = {
  add(state, num){
    return state.numbers.push(num)
  }
  remove(state, num) {
    return state.numbers.include(num)
  }
}
```

##Actions (Hành động)
Action cũng tương tự như mutation, tuy nhiên có một vài điểm khác biệt. Thay vì thay đổi trạng thái thì các action commit thay đổi, nó có thể chứa các hoạt động không đồng bộ.

Đây chính là nơi thể hiện bussiness logic, được gọi là API, save vào database, thực hiện các commit (gọi mutation) để thay đổi state…

VD: Thêm một số, nếu số đó đã tồn tại trong state thì xoá rồi thêm lại.

```
const actions = {
  updateNum({commit, state}, num){
    if (state.includes(num)) {
      commit('remove', num)
    }
    commit('add', num)
  }

  foo ({dispatch}, num) {
    dispatch('updateNum', num)
  }
}
```

##Modules

Vuex chỉ sử dụng duy nhất một cây trạng thái, tất cả các trạng thái của ứng dụng sẽ được đưa vào một đối tượng. Điều này cũng có nghĩa là khi ứng dụng của bạn ngày càng phát triển thì store sẽ to lên rất nhiều. Vì thế Vuex cho phép việc chia nhỏ store thành các module nhỏ hơn, các module này cũng có state, mutation, action, getter và thậm chí còn cho phép các module lồng nhau.

##Bạn cần lưu ý điều gì khi sử dụng Vuex

Điều quan trọng nhất khi bạn sử dụng Vuex đó chính là xác định cái nào là state sẽ lưu trữ trong store, cái nào chỉ là local state nằm trong component. Bạn hoàn toàn có thể đưa tất cả vào trong store, tuy nhiên đến khi quy mô của ứng dụng càng lớn kéo theo store cũng sẽ to ra dẫn đến việc khó khăn trong việc quản lý state.