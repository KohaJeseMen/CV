# Hướng dẫn chi tiết từng bước cài đặt Git cho Windows
## Bước 1: Tải tập tin cài đặt
Có nhiều cách để đến với trang chủ của Git, bạn có thể tìm kiếm trên Google và lựa chọn trong kết quả tìm kiếm hoặc đến trực tiếp trang chủ bằng cách gõ vào thanh điều hướng trình duyệt đường dẫn

> **https://git-scm.com/**

Bấm vào nút **`Download 2.23.0 for Windows`** để tải tập tin cài đặt về.

*Lưu ý rằng con số __2.23.0__ là phiên bản __Git__ hiện tại được phát hành, nó có thể bị thay đổi bởi các phiên bản mới hơn. Xem thêm ảnh minh họa bên dưới*.

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/febqf8cngp_image.png)

Hệ thống trang tải của Git sẽ tự động gửi tập tin cài đặt phù hợp với hệ điều hành Windows hiện tại của bạn. Ngoài ra, bạn còn có thể tải thêm các phiên bản khác tùy ý. *Xem thêm ảnh minh họa bên dưới.*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/jqgu1asxqh_image.png)

## Bước 2: Cài đặt
Sau quá trình chờ tải về, bạn sẽ có được một tệp thực thi trên máy có tên dạng
**`Git-2.23.0-64-bit.exe`**, trong đó:
* **2.23.0** đã nói ở trên bước 1 rồi, là phiên bản của Git lúc đó.
* **64-bit** là kiến trúc mà hệ điều hành Windows của máy đang dùng để cài Git.

*Xem thêm ảnh minh họa bên dưới.*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/hn5pyxkqo6_image.png)

Thực thi tập tin đó bằng cách `Bấm đôi chuột` hoặc `Bấm chuột phải` lên tệp đó rồi chọn `Open`. Tùy bạn thôi!~

*Nếu như máy của bạn có sử dụng tường lửa hoặc phân quyền để chặn các truy cập không khả tín thì bạn sẽ gặp thông báo Cảnh báo bảo mật, mình cứ chọn* `Run` *cho nó thực hiện cài đặt. Xem thêm hình ảnh minh họa bên dưới.*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/mbcqrjwbvk_image.png)

*Nếu như có cảnh báo bảo mật tiếp theo mà không có hai nút* `Run` và `Cancel` *mà có hai nút khác là* `Yes` và `No` *thì chúng ta chọn* [`Yes`]() *nha bạn!*

Tiếp tục, chúng ta sẽ gặp một "sớ Táo quân", được gọi là `Điều khoản (Giấy phép)`, nếu đọc tốt tiếng Anh thì bạn có thể dành thời gian để đọc cho rõ. Bình thường, chúng ta hay `Đồng ý` mà không đọc gì tất.

Đọc xong rồi thì nhấn nút `Next >`. *Xem thêm ảnh minh họa bên dưới.*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/uk46hrcie8_image.png)

Chương trình cài đặt sẽ cho chúng ta lựa chọn **vị trí lưu trữ để cài đặt chương trình Git**. Bạn có thể nhấn nút `Browse...` để chọn lại hoặc gõ đường dẫn vào ô. Đồng thời, chương trình cài đặt cũng sẽ cho bạn biết mức độ chiếm dụng của dữ liệu sẽ cài lên máy được yêu cầu để chứa là bao nhiêu (*kích cỡ MB tối thiểu*). Chọn xong đường dẫn rồi thì nhấn `Next >` thôi!~ *Xem thêm ảnh minh họa bên dưới.*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/gyrxuvpev1_image.png)

Trình cài đặt lại cho bạn một danh sách các lựa chọn. Ai giỏi tiếng Anh sẽ biết rõ đó là những gì:
* **Các lựa chọn đã được chọn sẵn (tick)**: Bao gồm các trình cơ bản của Git là dòng lệnh, giao diện đồ họa, các gói hỗ trợ, khai báo loại tập tin,... Chúng ta nên để cho nó chọn đi.
* **Nói thêm về các dòng chưa chọn**:
  *  **Additional icon**, bao gồm **On the Desktop**: là cài biểu tượng lên màn hình làm việc để bạn mở giao diện đồ họa và cửa sổ dòng lệnh của Git nhanh hơn. Cũng nên chọn chứ! *Nếu bạn lười vào __Start menu__*.
  *  **Use a TrueType font in all console windows**: là dùng Phông chữ kiểu TrueType cho tất cả các cửa sổ dòng lệnh. Nếu chọn dòng này, Git có thể hỗ trợ tốt hơn tiếng Việt trên các cửa sổ lệnh, bạn dùng giao diện đồ họa thì không cần chọn cũng được.
  *  Cuối cùng, **Check daily for Git for Windows updates**: là kiểm tra phiên bản hằng ngày xem có Git mới không để cập nhật luôn. Nếu bạn là người thích sự ổn định, ít thay đổi thì có thể bỏ qua lựa chọn này, còn nếu bạn là người thích theo đuổi những điều mới mẽ thì chọn để xem các tính năng của Git mới sau này là gì nhé! Ngoài ra, cập nhật thường xuyên cũng là một trong những việc tăng cường bảo mật, khắc phục các lỗi của bản cũ.

Chọn xong chưa? Nhấn `Next >` đi nào!~

*Xem thêm ảnh minh họa bên dưới.*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/vwnaqtzzwy_image.png)

Quá trời nhiều lựa chọn, và tiếp theo là lựa chọn xem nên đạt Git vào `Start menu` như thế nào. Có thể chọn **Don't create a Start Menu folder** để không tạo ra cái thư mục **Git** trên Start Menu, nếu bạn không cần dùng tới. Bình thường, cứ không chọn, để nguyên như vậy rồi bấm `Next >` thôi.

*Xem thêm ảnh minh họa bên dưới.*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/aazb029vjc_image.png)

Sau khi lựa chọn Start Menu, trình cài đặt yêu cầu lựa chọn một chương trình soạn thảo để chúng ta có thể biên tập lệnh cho Git bash. Mặc đinh là dùng Vim. *Xem hình ảnh minh họa bên dưới*. Tuy nhiên tôi sẽ sử dụng **Notepad++** vì máy tính Windows của tôi đã có cài sẵn rồi.

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/va07ctrkkh_image.png)

*Ảnh minh họa bên dưới đã chọn dùng __Notepad++__*. Nhấn `Next >` để tiếp nào!

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/ii72zpjxxd_image.png)

Tiếp theo, trình cài đặt Git yêu cầu chúng ta lựa chọn cài đặt về biến môi trường, nếu không cần dùng biến `PATH` để là môi trường mặc định cho Git thì bạn có thể lựa chọn Use Git from Git Bash only.

Mình cài Git trên Windows, cũng nên tạo một môi trường cho Git để thuận tiện hơn. Vì thế mình vẫn để nguyên lựa chọn là **Git from the command line and also from 3rd-party software**. Rồi còn chờ gì nữa mà không nhấn `Next >`? *Xem hình ảnh minh họa bên dưới.*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/jxu6pjych0_image.png)

Gì nữa đây?

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/h923697p0c_image.png)

Bên trên, là hình ảnh trình cài đặt Git yêu cầu bạn lựa chọn sử dụng phương thức bảo mật nào cho các kết nối giao thức HTTPS (*giap thức web tăng cường bảo mật*). Bạn có thể chọn dùng theo loại chứng chỉ nào mà bạn thích. Ở đây, tôi vẫn sẽ để mặc định là **Use the OpenSSL library** để sử dụng thư viện chứng chỉ bảo mật này (*thư viện mở*).

Nhấn tiếp nút `Next >` nà!

Tiếp theo, lựa chọn chế độ dấu kết thúc dòng (*xuống dòng*). Sở dĩ có lựa chọn này là do dấu xuống dòng trong hệ điều hành *Linux, Unix, MacOS và __Windows__*  là khác nhau.

Chúng ta cứ để mặc định là **Checkout Windows-style, commit Unix-style line endings** để Git tự chuyển qua lại giữa các loại này khi tải mã nguồn lên xuống giữa máy **Windows** của mình và máy chủ lưu trữ **Repository**. *Xem hình ảnh minh họa bên dưới.*

Rồi, bấm tiếp nút `Next >` thôi!

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/mzmsdjoh8l_image.png)

Gì đây?

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/9u304r5qrc_image.png)

Hình ảnh bên trên, trình cài đặt Git yêu cầu chúng ta lựa chọn chương trình hiển thị cửa sổ dòng lệnh để tương tác với chúng ta về sau.

Bạn nào là Fan ruột thật sự ruột của Windows thì chọn **Use Windows' default console window** để chọn cái màn hình đen chữ trắng mặc định của Windows (*mách nhỏ là nó có thể đổi màu*).

Tuy nhiên, để cho thuận tiện hiển thị tiếng Việt và đẹp mắt, chúng ta nên chọn như mặc định là **Use MinTTY (the default terminal of MSYS2)** để Git cài một trình giả lập cửa sổ dòng lệnh tên là **MinTTY** của **MSYS2**. Bấm nút `Next >` tiếp thôi nào!

Tiếp theo là một số cài đặt về lưu trữ (*cài đặt mở rộng*). Cứ mặc định mà bấm `Next >` thôi bạn ơi! *Xem hình ảnh minh họa bên dưới.*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/wpdwpaq4k8_image.png)

Cuối cùng, trình cài đặt Git sẽ cho ta chọn chức năng về tương tác, giúp sử dụng khởi chạy nhanh. Thật sự, điều này cũng không cần thiết vì chúng ta không mất quá nhiều thời gian cho việc gõ lệnh tương tác. *Xem hình ảnh minh họa bên dưới.*

Chọn `Install` để cài đặt Git.

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/gy3oih0xlg_image.png)

Chương trình sẽ hiển thị tiến trình cài đặt. *Xem ảnh minh họa bên dưới*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/e7hrypewmv_image.png)

Thế là bạn đã theo dõi tôi cài đặt **Git 2.23.0** vào máy tính **Windows 64bit** của mình rồi. Còn một lựa chọn cuối cùng sau khi cài đặt xong. *Xem hình ảnh minh họa bên dưới*

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/vqguittekw_image.png)

* Chọn **Lauch Git Bash**: để mở cửa sổ dòng lệnh của Git lên ngay sau đó.
*  Chọn **View Release Notes**: để xem ghi chú về các thay đổi của phiên bản này so với các phiên bản trước đó.

Bấm `Finish` để hoàn tất.

![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/o4jif6wa8f_image.png)

_Bên trên là hình ảnh ghi chú phát hành và cửa sổ dòng lệnh của **Git**_

> Chúc bạn cài đặt **Git** thành công!~
>
> Chân thành cảm ơn bạn đã xem đén đây.
>
> Hãy theo dõi mình để xem nhiều nội dung hay khác nhé!

## Các bài viết liên quan khác
* Cài đặt Git trên môi trường hệ điều hành Linux.
* Kết nối Git tới Github và các thao tác để làm việc với dự án.
* Kết nối Git tới Gitlab và các thao tác để làm việc với dự án.
* Hướng dẫn cài đặt Github Desktop để làm việc với dự án trên Github.

## Nguồn và thông tin tác giả

> Trích hoặc sao chép vui lòng ghi rõ nguồn.
>
> Nguồn: &copy; 2019 bởi [**Nguyễn Hoàng Anh Khoa**](https://www.facebook.com/nguyenhoanganhkhoacntt) thực hiện.
>
> Đăng tải trên [Kipalog.com](https://kipalog.com/posts/Huong-dan-chi-tiet-tung-buoc-cai-dat-Git-cho-Windows), [Github]()
>
> Lưu trữ hình ảnh trên [amazonaws.com/Kipalog.com]()
