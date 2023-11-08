# XML Tool Extension 🛠️

XML Tool Extension là một extension cho Visual Studio Code giúp bạn thao tác và xử lý tệp tin XML một cách dễ dàng. Extension này cung cấp các chức năng như truy vấn XPath, XML View Dom và chuyển đổi XML thành HTML.

## Cài Đặt 🚀

1. Mở Visual Studio Code.
2. Mở thanh Sidebar bằng cách nhấn `Ctrl + B` (hoặc `Cmd + B` trên macOS).
3. Nhấn vào biểu tượng `Extensions` (hoặc `Ctrl + Shift + X`).
4. Tìm kiếm "XML Tool" trong ô tìm kiếm và chọn extension của chúng ta để cài đặt.

## Sử Dụng Command Palette để Sử Dụng Các Chức Năng Của Tiện Ích 🎨

- **Bằng Phím Tắt:**
  - Nhấn tổ hợp phím `Ctrl + Shift + P` (Windows/Linux) hoặc `Cmd + Shift + P` (macOS).

- **Từ Menu:**
  - Nhấp vào biểu tượng kính hiển vi ở thanh công cụ hoặc điều hướng đến `View > Command Palette`.

## Chức Năng 🛠️

### 1. Truy Vấn XPath

1.1. **Tạo Tệp `queries.xml` Mới:**
   - Sử dụng lệnh `Tạo file truy vấn` để tạo một tệp `queries.xml` mới ngay từ trình soạn thảo của bạn. Tệp này sẽ được tạo với nội dung mẫu để bạn bắt đầu viết các truy vấn.

1.2. **Nhập Đường Dẫn Tệp Tin XML:**
   - Trong tệp `queries.xml`, nhập đường dẫn tệp tin XML bạn muốn truy vấn vào thẻ `<file-path>`.

1.3. **Viết Truy Vấn XPath hoặc XQuery:**
   - Trong tệp `queries.xml`, viết truy vấn XPath hoặc XQuery của bạn trong thẻ `<query>`.

1.4. **Chạy Truy Vấn XPath:**
   - Chạy các truy vấn XPath trên tệp tin XML được mở bằng cách sử dụng lệnh `Run XPath Query`. Kết quả của truy vấn sẽ được hiển thị trong một cửa sổ đầu ra để bạn dễ dàng kiểm tra.

### 2. XML View Dom

Chọn 1 file xml bất kì, bạn có thể sử dụng lệnh `XML View Dom` để xem cấu trúc XML dưới dạng cây các đối tượng

### 3. Chuyển Đổi XML Thành HTML 🖥️

Để chuyển đổi XML thành HTML, bạn có thể sử dụng lệnh `Run XSLT Transformation`. Chức năng này yêu cầu bạn nhập đường dẫn tệp tin XSLT và tệp tin XML cần chuyển đổi.

Sau khi chạy lệnh `Run XSLT Transformation`, VSCode sẽ mở một prompt yêu cầu bạn nhập địa chỉ của tệp tin XSL và tệp tin XML cần chuyển đổi. Sau khi quá trình chuyển đổi thành công, một thư mục `transform` sẽ được tạo. Trong thư mục `transform`, bạn sẽ tìm thấy một tệp HTML và một tệp JavaScript. Bạn có thể mở tệp HTML bằng trình duyệt hoặc sử dụng tiện ích Live Server để xem kết quả chuyển đổi.

Nếu bạn muốn lấy được đoạn code HTML đã được chuyển đổi từ trang web, bạn có thể thực hiện các bước sau:

- Mở Công Cụ Kiểm Tra Của Trình Duyệt (F12 hoặc Ctrl + Shift + I): Bạn có thể mở công cụ kiểm tra của trình duyệt bằng cách nhấn phím F12 hoặc tổ hợp phím Ctrl + Shift + I trên bàn phím của bạn.

- Chọn Tab "Elements": Trong cửa sổ công cụ kiểm tra, chuyển đến tab "Elements". Trong tab này, bạn sẽ thấy cây DOM của trang web.

- Tìm Đến Element Gốc Của Kết Quả HTML Chuyển Đổi: Sử dụng cây DOM, tìm đến element `<div class="root"></div>`

- Copy Đoạn Code HTML: Khi bạn đã tìm thấy element chứa nội dung HTML chuyển đổi, chuột phải vào element đó và chọn lựa chọn "Copy" hoặc "Copy Outer HTML". Điều này sẽ sao chép đoạn code HTML của element đó vào clipboard của bạn.

Như vậy, bạn đã sao chép được đoạn code HTML đã được chuyển đổi từ trang web bằng cách sử dụng công cụ kiểm tra của trình duyệt.

Chúc bạn có những trải nghiệm tuyệt vời với XML Tool Extension! 😊