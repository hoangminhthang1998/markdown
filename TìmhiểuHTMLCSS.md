### 4 thuộc tính cốt lõi có thể được sử dụng trong phần lớn các phần tử HTML (mặc dù không phải toàn bộ) là:
**Thuộc tính id**: để phân biệt giữa 2 phần tử đoạn văn

**Thuộc tính title**: cung cấp một tiêu đề cho một phần tử

**Thuộc tính class**: để liên kết một phần tử với một Style Sheet và xác định kiểu của phần tử

**Thuộc tính style**: cho phép bạn xác định rõ các quy tắc Cascading Style Sheet (CSC) trong phần tử

### Các thuộc tính Global trong HTML

**Thuộc tính dir**: phép bạn chỉ đạo trình duyệt phương hướng mà văn bản hiển thị (chẳng hạn từ trái qua phải). Thuộc tính này nhận một trong 2 giá trị

| Giá trị       | Ý nghĩa       |
| --------------|---------------|
| ltr    | Từ trái qua phải (giá trị mặc định)|
| rtl    | Từ phải qua trái (cho các ngôn ngữ như Hebrew, Arabic… mà được đọc từ phải qua trái)     |
	
**Thuộc tính lang**: cho phép bạn chỉ rõ ngôn ngữ chính sử dụng trong một tài liệu, nhưng thuộc tính này được giữ trong HTML chỉ cho khả năng tương thích ngược với các phiên bản trước của HTML. Thuộc tính này được thay thế bằng thuộc tính xml:lang trong tài liệu XHTML mới.

**Thuộc tính xml:lang**: thay cho thuộc tính lang. Giá trị của thuộc tính xml:lang này có thể là một mã quốc gia trong ISO-639 như đã đề cập ở trên.

### Các thuộc tính chung trong HTML

| **Thuộc tính**       | **Giá trị**       | **Chức năng**|
| --------------|---------------|--------|
| align|right, left, center|Các thẻ căn chỉnh theo chiều ngang|
| valign|top, middle, bottom|Các thẻ căn chỉnh theo chiều dọc trong một phần tử HTML|
|bgcolor|Giá trị số, thập lục phân, RGB|Đặt màu nền phía sau một phần tử|
|background|URL|Đặt ảnh nền phía sau một phần tử|
|id|Người dùng tự định nghĩa|Đặt tên một phần tử để sử dụng với Cascading Style Sheets|
|class|Người dùng tự định nghĩa|Phân loại một phần tử để sử dụng với Cascading Style Sheets|
|width|Giá trị số|Xác định độ rộng của bảng, hình ảnh hoặc ô trong bảng|
|height|Giá trị số|Xác định chiều cao của bảng, hình ảnh hoặc ô trong bảng|
|title|Người dùng tự định nghĩa|"Pop-up" tiêu đề của phần tử|

### Các thẻ cơ bản của html
#### Các phần tử trong HTML
| **Thẻ bắt đầu**       | **Nội dung của thẻ**       | **Thẻ kết thúc**|
| --------------|---------------|--------|
|`<p>`|Đây là nội dung đoạn văn|`</p>`|
|`<h1>`|Đây là tiêu đề bộ dung|`</h1>`|
|`<div>`|Đây là nội dung phân chia|`</div>`|
|`<br/>`|
#### Thẻ tiêu đề 
`<h1>`
# This is h1
`<h2>`
## This is h2
`<h3>`
### This is h3
`<h4>`
### This is h4
`<h5>`
##### This is h5
`<h6>`
##### This is h6

#### Thẻ văn bản
Thẻ `<p>` cung cấp một cách để cấu trúc văn bản thành các đoạn khác nhau 
#### Thẻ ngắt dòng
Mọi thứ theo sau `<br />` đều bắt đầu từ dòng tiếp theo 
#### Thẻ canh giữa
Sử dụng thẻ `<center><center/>` để đặt bất kì nội dùng nào vào giữa trang hoặc bất kì ô bảng nào 
#### Thẻ tạo đường ngang
Thẻ `'<hr>` để phân chia các phần của tài liệu
#### Thẻ giữ nguyên định dạng
Thẻ `<pre></pre>` giữ nguyên định dạng chính xác về cách nó được viết trong tài liệu html
#### Ký tự khoảng trắng
`&nbsp`
