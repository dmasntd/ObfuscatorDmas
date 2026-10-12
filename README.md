# Dmas Obfuscator - Encryt Code

### Owner Nguyễn Tấn Dũnh

----

# Giới thiệu
- Hao A Du mấy con vợ, có lẽ các em đang cần một công cụ mã hóa mã nguồn python chống lại việc sao chép bản quyền và muốn bảo vệ trí tuệ tài nguyên và api riêng tư của mấy con vợ, cũng như một số api công cụ mà các con vợ phải trả phí.
- Tôi xin trơ cháo giới thiệu món hàng bảo vệ mã nguồn cho mấy con vợ, tôi đem đến con hàng siêu bá đạo chống lại việc đọc trộm dịch ngược móc méo mã nguồn nhằm đánh cắp, crack bản quyền của mấy con vợ, con hàng này sẽ giúp con vợ an toàn không lo về việc bị đánh cắp mã nguồn và bị crack công cụ của các con vợ.
- Với việc bản thân tôi cũng từng là thằng crack mã nguồn để nhằm mục đích né tránh trả phí, mua key hoặc vượt link để lấy key, vì đa số key quá ngắn hạn mà bản thân còn phải vượt link nữa, nhưng tôi vẫn làm để bảo vệ mã nguồn tránh bị đánh cắp mã nguồn do tôi cũng thiết kế mã nguồn trên chất xám của mình và nó thuộc tài sản trí tuệ của tôi lên việc mã nguồn cần được bảo vệ là ưu tiên hàng đầu.
- Việc này sẽ làm ae crack sẽ đau đầu vì ngồi tìm cách phá giải vì mọi mã đều phải thực thi được, và khi họ lắm quyền kiểm soát thì nó vẫn bị dịch ngược, mọi thứ chỉ làm khó và gây tốn thời gian kèm tài nguyên cho thứ vô ích nhưng được đến đâu hay đến đó.

----

# Những gì tôi bảo vệ
- Tôi khá quan tâm đến việc API bị lôi ra đọc để xem client giao tiếp với server cái gì như nào lên tôi bảo vệ mã hóa mọi requests
- Khóa chặn thực thi khi bị hook, crack, dịch ngược một cách toàn diện
- Phát hiện môi trường debug local sanbox
- Khóa phiên bản tránh bảo vệ yếu kém cũ mà vẫn còn được lưu hành

----

# Chú ý
- Vì công cụ bảo vệ này có cơ chế khóa hoàn toàn toàn diện lên nếu bị hack bạn có thể bị gặp vấn đề người dùng báo lỗi
- Kẻ xấu có thể ngăn chặn bạn phát hành công cụ qua cơ chế này
- Một số môi trường cần được đăng ký để cho phép chạy
- Phải chấp nhận cam kết về một số điều khoản điều lệ nếu chạy trên môi trường không được phép
- Bản thân tôi không cam kết hoàn toàn vì mã nguồn phải xuất hiện để chạy, việc tôi làm là ngăn chặn qua nhiều lớp và hệ thống bảo vệ
- Đôi khi sẽ phát hiện nhầm tý mấy con vợ chịu khó báo cáo về cho anh nhé anh fix

----

# Hệ thống và thuật toán
- Cái lòng xào dưa tôi tự tạo ra một số thuật toán biến ảo siêu dị hợm
- Hệ thống bảo vệ siêu cấp vip pro
- Bảo vệ requests siêu cấp vip pro fifai mắc
- Thuật toán xử lý nhận diện siêu cạc lỏ
- Tóm lại tôi dùng toàn hàng lỏ để bảo kê mã nguồn

----

# New í
- Vẫn nhắc lại việc bảo vệ mã nguồn chỉ bảo vệ được có hạn mã nguồn vẫn phải xuất hiện để chạy việc tôi làm là ngăn cản kẻ xấu dump code và dịch ngược code cũng như hook.
- Mọi thuật toán lạ cũng chỉ gây dối tạm thời nó vẫn sẽ bị giải ngược
- Kẻ tấn công nếu quyết tâm và có nhiều thời gian thì vẫn giải được
- Lưu ý phiên bản mã hóa sẽ được thay đổi theo lần vá nó sẽ tự động xóa các phiên bản mã hóa cũ để bảo vệ việc khôi phục gần như bằng 0 vì mất các tham chiếu cũ
- Tôi sẽ không thông báo về việc mã hóa được nâng cấp lên hãy check thử

----

# Anti và cách report
- Anti ở đây là anti mã nguồn dạng malware, trojan, botnet, virus
- Anti đánh cắp thông tin tài nguyên máy tính mạng máy tính
- Anti đánh cắp dữ liệu
- Khi thấy có dấu hiệu khả nghi hãy báo cáo dãy số mã định danh cho admin để khóa chết con mẹ nó
- Trường hợp bị chơi đểu hãy liên hệ admin để xác minh mã ( admin sẽ không chia sẻ mã nguồn của bạn xem xong xóa xxx )
- Admin có cơ chế đọc mã nguồn riêng lên con vợ trơ tráo admin khóa chết con vợ luôn
- Các con vợ khi đã dùng công cụ đã được xem là cam kết điều khoản của admin không bàn cãi
- Điều khoản có hiệu lực với mọi người dùng không phân biệt quốc gia
