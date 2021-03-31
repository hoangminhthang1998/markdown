##HTML

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
|`<h1>`|Đây là tiêu đề nội dung|`</h1>`|
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

##CSS
###Các thuộc tính Color
Chức năng để thiết lập màu sắc và độ trong suốt của văn bản
|Thuộc tính	|Mô tả|
|----|----|
|color|	Đặt màu sắc cho đoạn văn bản|
|opacity|	Đặt mức độ trong suốt cho một phần tử nào đó|

###Các thuộc tính Background và Border
Chức năng thiết lập các thuộc tính màu nền và đường biên cho các đối tượng trên trang.

|Thuộc tính	|Mô tả|
|-----|-----|
|background|	Một thuộc tính viết tắt để đặt thuộc tính nền trong lời khai báo|
|background-attachment|	Đặt một ảnh nền để cố định hoặc cuộn với phần còn lại của trang|
|background-blend-mode|	Chỉ định các chế độ trộn của mỗi lớp nền(màu sắc/hình ảnh)	|
|background-color|	Chỉ định màu nền của một phần tử	|
|background-image|	Chỉ định một hoặc nhiều hình ảnh nền cho một phần tử|
|background-position|	Chỉ định vị trí của hình ảnh nền|
|background-repeat|	Thiết lập như thế nào một ảnh nền sẽ được lặp đi lặp lại|
|background-clip|	Chỉ định khu vực để sơn màu nền|background-|origin|	Chỉ định nơi các hình nền được định vị|
|background-size|	Chỉ định kích thước của ảnh nền	|
|border	|Thiết lập tất cả các thuộc tính đường viền trong lời khai báo|
| border-bottom |	Thiết lập tất cả các thuộc tính đường viền dưới trong lời khai báo|
|border-bottom-color|	Thiết lập màu của đường viền dưới|
|border-bottom-left-radius|	Xác định hình dạng của các đường viền góc dưới |bên trái	|
|border-bottom-right-radius|	Xác định hình dạng của các đường viền góc dưới bên phải|
|border-bottom-style	|Thiết lập kiểu (style) của đường viền dưới|
|border-bottom-width|	Thiết lập độ rộng của đường viền dưới|
|border-color|	Thiết lập màu sắc của bốn đường viền|
|border-image|	Một thuộc tính viết tắt để thiết lập tất cả các thuộc tính border-image-*|
|border-image-outset|	Chỉ định giá trị khu vực ảnh viền vượt ra ngoài vùng giới hạn của vùng bao|
|border-image-repeat|	Chỉ định ảnh viền nên được lặp đi lặp lại, tròn hoặc kéo dài|
|border-image-slice|	Chỉ định cụ thể như thế nào để cắt ảnh viền|
|border-image-source|	Chỉ định đường dẫn tới hình ảnh để sử dụng như đường viền|
|border-image-width|Chỉ định độ rộng của ảnh-viền	|
|border-left|	Thiết lập tất cả thuộc tính đường viền trái trong lời khai báo|
|border-left-color|	Thiết lập màu sắc của đường viền trái|
|border-left-style|	Thiết lập kiểu ( style) của đường viền trái|
|border-left-width|	Thiết lập độ rộng của đường viền trái	|
|border-radius|	Thuộc tính viết tắt để thiết lập tất cả bốn đường viền-*-thuộc tính radius(bán kính)|
|border-right|	Thiết lập thuộc tính đường viền phải trong lời khai báo|
|border-right-color|Thiết lập màu sắc cho đường viền phải|
|border-right-style	|Thiết lập kiểu (style) cho đường viền phải|
|border-right-width|	Thiết lập độ rộng cho đường viền phải|
border-style|	Thiết lập kiểu (style)  cho bốn đường viền|
border-top|	Thiết lập thuộc tính đường viền trên trong lời khai báo	|
|border-top-color|	Thiết lập màu sắc cho đường viền trên	|
|border-top-left-radius|	Xác định hình dạng của đường viền góc trên bên trái	|
|border-top-right-radius|	Xác định hình dạng của đường viền góc trên bên phải|
|border-top-style|	Thiết lập kiểu (style) cho đường viền trên|
|border-top-width|	Thiết lập độ rộng của đường viền trên|
|border-width|	Thiết lập độ rộng của bốn đường viền|
|box-decoration-break|	Thiết lập dáng vẻ của hình nền và đường |viền của một phần tử  tại trang ngắt, hoặc đối với phần tử in-line , tại  dòng ngắt|
|box-shadow|	Gắn một hoặc nhiều đổ bóng (drop-shadows) vào hộp	|
### Các thuộc tính Basic Box
|Thuộc tính|	Mô tả	CSS|
|-----|----|
|bottom|	Xác định vị trí cuối của phần tử position (vị trí)|
|clear|	Xác định hai bên của phần tử (left,right) nơi mà phần tử float không được cho phép (ngăn cản thành phần không được float trái, phải hay cả hai)	|
|clip|	Xác định đoạn cho phần tử khi sử dụng thuộc tính position có giá trị “absolute“|
|display|	Chỉ định làm thế nào một phần tử HTML nào đó sẽ được hiển thị	|
|float|	Xác định có hay không một box được float(trôi nổi)	|
|height|	Thiết lập chiều cao của thành phần|
|left|	Xác định vị trí bên trái của phần tử position|
|margin|	Thiết lập thuộc tính margin (căn lề cho phần tử) trong một thông báo|
|margin-bottom	|Thiết lập lề dưới của một phần tử|
|margin-left	|Thiết lập lề trái của một phần tử	|
|margin-right	|Thiết lập lề phải của một phần tử	|
|margin-top	|Thiết lập lề trên của một phần tử	|
|max-height|	Thiết lập chiều cao tối đa của một phần tử|
|max-width|	Thiết lập chiều rộng tối đa của một phần tử	|
|min-height|	Thiết lập chiều cao tối thiểu của một phần tử	2|
|min-width|	Thiết lập chiều rộng tối thiểu của một phần tử	2|
|overflow|	Chỉ định những gì sẽ xảy ra nếu nội dung tràn ra ngoài phần tử hộp	|
|overflow-x|	Xác định có hay không để cắt cạnh trái/phải của đoạn văn bản, nếu nó tràn ra khỏi khu vực nội dung của phần tử	|
|overflow-y|	Xác định có hay không để cắt cạnh trên /dưới của đoạn văn bản, nếu nó tràn ra khỏi khu vực nội dung của phần tử	|
|padding|	Thiết lập lại thuộc tính padding (vùng đệm) trong lời khai báo	|
| padding-bottom |	Thiết lập vùng đệm dưới của phần tử	 |
| padding-left |	Thiết lập vùng đệm trái của một phần tử	|
|padding-right|	Thiết lập vùng đệm phải của một phần tử	|
|padding-top|	Thiết lập vùng đệm trên của một phần tử	|
|position|	Xác định kiểu của phương thức định vị được sử dụng cho một phần tử (static, relative, absolute or fixed)	|
|right|	Xác định vị trí phải của phần tử position	|
|top|	Xác định vị trí trên của phần tử position	|
|visibility|	Xác định có hay không một phần tử có thể nhìn thấy được	|
|width|	Thiết lập độ rộng của phần tử|
|vertical-align|	Sắp xếp nội dung theo chiều dọc của phần tử|
|z-index|	Thiết lập thứ tự xếp chồng nhau của phần tử position|

### Thuộc tính cho bố cục Flexible Box
|Thuộc tính|	Mô tả|
|------|-----|
|align-content|	Xác định sự căn chỉnh giữa các dòng bên trong một khối linh hoạt ( flexible container) khi các mục không sử dụng các khoảng cách có sẵn|
|align-items|	Xác định sự căn chỉnh cho các mục bên trong một khối linh hoạt ( flexible container)	|
|align-self|	Xác định sự căn chỉnh cho các mục được chọn bên trong một khối linh hoạt ( flexible container)|
|flex|	Xác định độ dài của các mục, tương đối với phần còn lại|
|flex-basis|	Xác định độ dài ban đầu của một mục linh hoạt (flexible item)|
|flex-direction|	Xác định hướng của các mục linh hoạt (flexible items)|
|flex-flow|	Một thuộc tính viết tắt cho thuộc tính flex-direction và flex-wrap|
|flex-grow|	Chỉ định bao nhiêu mục sẽ tăng tương đối so với phần còn lại	|
|flex-shrink|	Chỉ định bao nhiêu mục sẽ giảm tương đối so với phần còn lại|
|flex-wrap|	Chỉ định liệu các mục linh hoạt (flexible items) nên bọc hay không|
|justify-content|	Xác định sự căn chỉnh giữa các mục bên trong một khối linh hoạt (flexible container) khi các mục không sử dụng tất cả các khoảng cách có sẵn|
|order|	Thiết lập thứ tự của các mục linh hoạt (flexible items), tương đối so với phần còn lại|
### Các thuộc tính Text
|Thuộc tính|	Mô tả	|
|-------|------|
|hanging-punctuation|	Xác định ký tự chấm câu có thể được đặt ở ngoài đường hộp	|
|hyphens|	Thiết lập làm thế nào tách từ để cải thiện cách bố trí của đoạn văn|
|letter-spacing|	Tăng hoặc giảm khoảng cách giữa các ký tự trong một văn bản|
|line-break|	Xác định cách ngắt dòng|
|line-height|	Thiết lập chiều cao của dòng|
|overflow-wrap|	Xác định có hay không trình duyệt có thể ngắt dòng trong các từ để ngăn cản việc tràn (Khi một chuỗi quá dài để phù hợp với hộp chứa nó	|
|tab-size|	Xác định chiều dài của các kí tự tab|
|text-align|	Xác định căn chỉnh nội dung theo chiều ngang|
|text-align-last|	Mô tả cách dòng cuối cùng của mộtđoạn hoặc một dòng ngay trước khi một ngắt dòng là căn chỉnh khi text-align là “justify”|
|text-combine-upright|	Xác định sự kết hợp của đa ký tự vào khoảng cách của một ký tự đơn|
|text-indent|	Xác định rõ sự thụt dòng đầu tiên trong một khối văn bản|
|text-justify|	Xác định phương pháp căn lề thẳng hàng hai bên sử |dụng khi text-align là “justify”|
|text-transform|	Điều khiển các chữ in hoa|
white-space	Xác định cách mà khoảng trắng bên trong một phần tử được xử lý|
|word-break|	Xác định quy tắc ngắt dòng đối với scripts non-CJK	|
|word-spacing|	Tăng hoặc giảm khoảng cách giữa các từ trong đoạn văn	|
|word-wrap	|Cho phép dài, những từ dài được xuống hàng mà không làm vỡ layout	|
### Các thuộc tính Text Decoration
|Thuộc tính|	Mô tả	|
|-------|------|
|text-decoration|	Xác định các trang trí thêm vào văn bản	|
|text-decoration-color|	Xác định màu của văn bản trang trí (text-decoration)|
|text-decoration-line|	Xác định loại của dòng trong text-decoration|
|text-decoration-style|	Xác định kiểu của các dòng trong một văn bản trang trí|
|text-shadow|	Thêm đổ bóng cho văn bản|
|text-underline-position|	Xác định vị trí của các gạch dưới được thiết lập bằng cách sử dụng thuộc tính text-decoration|
### Các thuộc tính Font
|Thuộc tính	|Mô tả|
|-------|------|
|@font-face|	Một quy tắc cho phép các trang web tải và sử dụng các phông chữ khác với phông chữ “web-safe”|
|@font-feature-values|	Cho phép tác giả sử dụng một tên chung trong font-variant-alternate đối với tính năng kích hoạt khác nhau trong OpenType|
|font|	Đặt tất cả các thuộc tính font trong lời khai báo|
|font-family|	Xác định họ phông chữ cho văn bản	|
|font-feature-settings|	Cho phép kiểm soát các tính năng về in tiên tiến trong OpenType fonts|
|font-kerning|	Kiểm soát việc sử dụng các thông tin kerning (cách các từ cách nhau)|
|font-language-override|	Kiểm soát việc sử dụng của ngôn ngữ cụ thể nét trạm (language-specific glyphs) trong kiểu chữ|
|font-size|	Xác định kích thước phông chữ của đoạn văn|
|font-size-adjust|	Duy trì khả năng đọc văn bản khi phông chữ dự phòng xuất hiện|
|font-stretch	|Chọn kiểu normal, condensed,hoặc expanded từ họ phông chữ	|
|font-style|	Xác định kiểu chữ cho văn bản|
|font-synthesis|	Quản lí các kiểu chữ (đậm hoặc nghiêng) có thể được tổng hợp bởi trình duyệt|
|font-variant|	Xác định có hay không một văn bản được hiển thị với phông chữ small-caps	|
|font-variant-alternates|	Kiểm soát việc sử dụng các nét chạm thay thế liên quan đến việc thay tên được định nghĩa trong @font-feature-values	|
|font-variant-caps|	Kiểm soát việc sử dụng nét chạm (glyph)thay thế cho chữ in hoa	|
|font-variant-east-asian|	Kiểm soát việc sử dụng nét chạm (glyph ) thay thế cho các kịch bản Đông Á (ví dụ như Trung Quốc và Nhật Bản)|
f|ont-variant-ligatures|	Kiểm soát các chữ ghép và các biểu mẫu theo ngữ cảnh được sử dụng trong các nội dung văn bản của phần tử mà nó được áp dụng	|
|font-variant-numeric|	Kiểm soát việc sử dụng các họa tiết (glyph) thay thế cho số, phân số và đánh dấu thứ tự	|
|font-variant-position|	Kiểm soát việc sử dụng các họa tiết thay thế kích thước nhỏ hơn vị trí như là chỉ số trên hoặc chỉ số dưới về đường cơ sở của các phông chữ|
|font-weight	|Xác định độ đậm của phông chữ	|
### Các thuộc tính Writing Modes
|Thuộc tính|	Mô tả	|
|-------|------|
|direction|	Xác định hướng văn bản/ hướng bài viết	|
|text-orientation|	Xác định hướng của văn bản trong một dòng	|
|text-combine-upright|	Xác định sự kết hợp của đa ký tự vào khoảng cách của ký tự đơn	|
|unicode-bidi|	Được sử dụng cùng với thuộc tính direction để đặt và trả về  cho dù văn bản nên được ghi đè để hỗ trợ nhiều ngôn ngữ trong cùng một tài liệu	|
|writing-mode	| Xác định liệu dòng văn bản được đặt ra theo chiều ngang hay chiều dọc hay hướng mà khối tiến tới	|
### Các thuộc tính Table
|Thuộc tính|	Mô tả|	
|-------|------|
|border-collapse|	Xác định liệu có hay không đường viền của bảng nên tách biệt|
|border-spacing|	Xác định khoảng cách giữa đường viền của các ô lân cận	|
|caption-side|	Xác định vị trí của một chú thích bảng	|
|empty-cells|	Xác định có hay không để hiển thị đường viền và nền trên ô trống trong một bảng|
|table-layout|	Thiết lập thuật toán bố trí (layout algorithm) được sử dụng cho bảng	|
### Các thuộc tính Lists và Counters
|Thuộc tính|	Mô tả|
|-------|------|
|counter-increment	|Gia tăng một hoặc nhiều counters	|
|counter-reset|	Tạo hoặc thiết lập lại một hay nhiều counters	|
|list-style|	Thiết lập tất cả các thuộc tính cho danh sách trong lời khai báo	|
|list-style-image|	Xác định một hình ảnh như đánh dấu mục danh sách	|
|list-style-position|	Xác định nếu đánh danh mục sẽ xuất hiện bên trong hoặc bên ngoài nội dung	|
|list-style-type|	Xác định loại của đánh dấu danh mục|
### Các thuộc tính Animation
|Thuộc tính	|Mô tả|	
|-------|------|
|@keyframes	|Xác định mã animation |
|animation|	Một thuộc tính viết tắt cho các thuộc tính animation  (ngoại trừ animation-play-state và animation-fill-mode)|
|animation-delay|	Xác định sự chậm trễ đối với sự bắt đầu của một chuyển động của hình ảnh hoặc tag (animation)	|
|animation-direction|	Xác định có hay không các chuyển động nên chạy ngược lại trên chu kỳ thay thế|
|animation-duration	|Xác định có bao nhiêu giây hoặc mili giây một chuyển động cần để hoàn thành một chu kỳ|
|animation-fill-mode|	Xác định kiểu cho các phần tử khi các chuyển động không chạy (Khi nó dừng lại , hoặc khi nó bị trễ)	|
|animation-iteration-count|	Xác định số lần một chuyển động được thực hiện	|
|animation-name	|Xác định tên của @keyframes animation	|
|animation-play-state|	Xác định xem các chuyển động đang được chạy hay tạm dừng	|
|animation-timing-function|	Xác định tốc độ cong của một chuyển động của hình ảnh hoặc tag|
### Các thuộc tính Transform
|Thuộc tính|	Mô tả	|
|-------|------|
|backface-visibility|	Xác định có hay không một phần tử nên được nhìn thấy khi không ở chế độ toàn màn hình	|
|perspective|	Xác định chiều sâu	|
|perspective-origin|	Xác định vị trí dưới của phần tử 3D	|
|transform|	Áp dụng một chuyển đổi  2D hoặc 3D đến một phần tử|
|transform-origin|	Cho phép bạn thay đổi vị trí trên phần tử transform	|
|transform-style|	Xác định các phần tử lồng nhau sẽ thế nào trong không gian 3D|
### Các thuộc tính Transitions
|Thuộc tính|	Mô tả|
|-------|------|
|transition|	Một thuộc tính viết tắt để thiết lập cho 4 thuộc tính chuyển đổi	|
|transition-property|	Xác định tên của thuộc tính CSS trong hiệu ứng của quá trình chuyển đổi(none, width, height, all)	|
|transition-duration|	Xác định bao nhiêu giây hoặc mili giây một hiệu ứng chuyển đổi hoàn thành	|
|transition-timing-function|	Xác định đường cong tốc độ của hiệu ứng chuyển đổi|
|transition-delay|	Xác định khi nào hiệu ứng chuyển đổi sẽ bắt đầu	|
### Các thuộc tính Basic User Interface
|Thuộc tính	|Mô tả|
|-------|------|
|box-sizing|	Báo cho trình duyệt các thuộc tính sizing (độ rộng và độ cao) nên có	|
|content|	Sử dụng với :before và :after pseudo-elements, để chèn nội dung được tạo ra	|
|cursor	|Xác định kiểu con trỏ chuột sẽ được hiển thị khi di chuyển vào phần tử nào đó	|
|ime-mode|	Điều khiển trạng thái của trình soạn thảo phương thức nhập cho trường văn bản	|
|nav-down|	Xác định nơi để di chuyển khi sử dụng phím mũi tên xuống	|
|nav-index|	Xác định thứ tự tab của phần tử	|
|nav-left|	Xác định nơi để di chuyển khi sử dụng phím mũi tên sang trái	|
|nav-right|	Xác định nơi để di chuyển khi sử dụng phím mũi tên sang phải	|
|nav-up|	Xác định nơi để di chuyển khi sử dụng phím mũi tên lên	|
|outline|	Thiết lập thuộc tính đường viền trong lời khai báo	|
|outline-color|	Đặt màu sắc của đường viền bao ngoài	|
|outline-offset|	Đệm đường viền bao ngoài, và rút nó ra bên ngoài cạnh đường viền (border)	|
|outline-style|	Thiết lập kiểu của đường viền bao ngoài	|
|outline-width|	Thiết lập độ rộng của đường viền bao ngoài	|
|resize|	Xác định có hay không một phần tử là thay đổi kích thước bởi người dùng|	|
|text-overflow|	Xác định các vấn đề khi văn bản tràn khỏi các phần tử container	|
### Các thuộc tính Multi-column Layout
|Thuộc tính|	Mô tả|
|------|------|
|break-after|	Xác định cách xử lý ngắt trang, ngắt cột hoặc ngắt đoạn sau khi tạo hộp	|
|break-before|	Xác định cách xử lý ngắt trang, ngắt cột hoặc ngắt đoạn trước khi tạo hộp	|
|break-inside|	Xác định cách xử lý ngắt trang, ngắt cột hoặc ngắt đoạn bên trong hộp được tạo ra	|
|column-count|	Xác định số cột phần tử nên được chia thành	|
|column-fill|	Xác định như thế nào để điền vào cột	|
|column-gap|	Xác định khoảng cách giữa các cột	|
|column-rule|	Một thuộc tính viết tắt để thiết lập thuộc tính column-rule-* cho các đường kẻ giữa các cột	|
|column-rule-color|	Xác định màu sắc của các đường kẻ giữa các cột	|
|column-rule-style|	Xác định kiểu của các đường kẻ giữa các cột	|
|column-rule-width|	Xác định độ rộng của các đường kẻ giữa các cột	|
|column-span|	Xác định có bao nhiêu cột chứa phần tử được trải dài	|
|column-width|	Xác định độ rộng của cột	|
|columns|	Một thuộc tính viết tắt để thiết lập độ rộng cột (column-width) và số cột (column-count)|
|widows	|Xác định số dòng tối thiểu phải còn lại trên một trang khi ngắt trang xảy ra bên trong phần tử	|
### Paged Media
|Thuộc tính	|Mô tả|
|------|------|
|orphans|	Thiết lập số dòng tối thiểu phải còn lại ở cuối của một trang khi ngắt trang xảy ra bên trong phần tử|
|page-break-after|	Thiết lập chế độ ngắt trang sau một phần tử	|
|page-break-before|	Thiết lập chế độ ngắt trang trước một phần tử	|
|page-break-inside|	Thiết lập chế độ ngắt trang bên trong một phần tử|
### Generated Content cho trang đa phương tiện
|Thuộc tính	|Mô tả	|
|------|------|
|marks|	Thêm đoạn văn bản được đánh dấu và/hoặc sử dụng cho tài liệu	|
|quotes|	Thiết lập các loại dấu bao ngoài khi nhúng một trích dẫn	|
### Các thuộc tính Filter Effects
|Thuộc tính|	Mô tả	|
|------|------|
|filter|	Xác định hiệu ứng (vd: làm mờ hoặc chuyển đổi màu sắc) trên một phần tử trước khi nó được hiển thị|
### Image Values và Replaced Content
|Thuộc tính	|Mô tả	|
|------|------|
|image-orientation|	Xác định sự quay theo bên phải hoặc theo chiều kim đồng hồ  do người dùng áp dụng cho một ảnh  (Thuộc tính này có khả năng bị phản đối và chức năng của nó chuyển sang cho HTML)	|
|image-rendering|	Gợi ý cho các trình duyệt về các khía cạnh của một ảnh là rất quan trọng để bảo vệ khi hình ảnh được thu nhỏ lại	|
|image-resolution|	Xác định độ phân giải nội tại của các ảnh raster được sử dụng trong/ trên phần tử	|
|object-fit|	Xác định làm thế nào nội dung của một phần tử thay thế  nên được trang bị hộp được tạo bởi độ cao và độ rộng	|
|object-position|	Xác định căn chỉnh của phần tử thay thế bên trong hộp của nó	|
### Các thuộc tính Masking
|Thuộc tính|	Mô tả|
|------|------|
|mask	|
|mask-type		|
### Các thuộc tính Speech
|Thuộc tính|	Mô tả	|
|------|------|
|mark|	Một thuộc tính viết tắt để thiết lập thuộc tính  mark-before và mark-after	|
|mark-after|	Cho phép đánh dấu tên được gắn liền với những dòng âm thanh	|
|mark-before|	Cho phép đánh dấu tên được gắn liền với những dòng âm thanh	|
|phonemes|	xác định cách phát âm cho các văn bản chứa các phần tử tương ứng	|
|rest|	Một thuộc tính viết tắt để thiết lập thuộc tính the rest-before và rest-after	|
|rest-after|	Xác định phần còn lại hoặc ranh giới điệu tính được quan sát sau khi nói phần tử nội dung	|
|rest-before|	Xác định phần còn lại hoặc ranh giới điệu tính để quan sát trước khi nói phần tử nội dung	|
|voice-balance|	Xác định sự cân bằng giữa các kênh trái và phải|
|voice-duration|	Xác định nó phải mất bao lâu để trả lại các lựa chọn phần tử nội dung	|
|voice-pitch|	Xác định mức độ trung bình (tần số) của giọng nói	|
|voice-pitch-range|	Xác định sự thay đổi của tần số	|
|voice-rate|	Điều khiển tốc độ nói	|
|voice-stress|	Chỉ ra cường độ của sự nhấn mạnh được áp dụng	|
|voice-volume|	Đề cập đến biên độ của dạng sóng đầu ra của các bài phát biểu	|
### Các thuộc tính Marquee
Chức năng tạo chữ chạy trong HTML

|Thuộc tính	|Mô tả	|
|------|------|
|marquee-direction|	Thiết lập hướng di chuyển nội dung	|
marquee-play-count	Thiết lập bao nhiêu lần di chuyển nội dung	|
|marquee-speed|	Thiết lập cách nhanh chóng cuộn nội dung	|
|marquee-style|	Thiết lập kiểu di chuyển nội dung	|
