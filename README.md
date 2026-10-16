**Họ và tên:** Phạm Thành Đạo\
**Lớp:** HCM-KS26-CNTT1\
**Môn học:** IT-101 -- Nhập môn Công nghệ thông tin\
**Session:** 10\
**Bài tập:** Exercise 04 -- Thiết kế Prompt tối ưu cho AI Assistant

# PHẦN 1. THIẾT KẾ PROMPT THEO CÔNG THỨC 3 PHẦN

## 1. Bối cảnh

Bạn là gia sư AI cá nhân, có kinh nghiệm hướng dẫn sinh viên năm nhất
ngành Công nghệ thông tin. Tôi là sinh viên năm nhất và đang gặp khó
khăn khi tìm hiểu **mô hình IPO trong trang trại thông minh (Smart
Farm)**. Tôi cần lời giải thích đơn giản, dễ hiểu, có ví dụ gần gũi và
không yêu cầu kiến thức chuyên môn nâng cao.

## 2. Nội dung

Hãy giải thích mô hình IPO (Input -- Process -- Output) trong một trang
trại thông minh. Sử dụng ví dụ về hệ thống tưới nước tự động cho cây
trồng để minh họa cách dữ liệu được thu thập, xử lý và tạo ra kết quả.

## 3. Yêu cầu

Hãy thực hiện các yêu cầu sau:

-   [ ] Giải thích IPO là gì bằng tiếng Việt đơn giản.
-   [ ] Trình bày rõ ba thành phần: **Input (Đầu vào)**, **Process (Xử
    lý)** và **Output (Đầu ra)**.
-   [ ] Dùng ví dụ hệ thống tưới nước tự động trong trang trại để minh
    họa từng thành phần.
-   [ ] Tạo một bảng gồm ba cột: Thành phần IPO, Ý nghĩa và Ví dụ trong
    trang trại.
-   [ ] Mô tả quy trình hoạt động theo thứ tự Input → Process → Output.
-   [ ] Đưa ra một ví dụ hoàn chỉnh, chẳng hạn cảm biến phát hiện đất
    khô, bộ điều khiển xử lý thông tin và máy bơm được bật để tưới cây.
-   [ ] Kết thúc bằng phần tóm tắt ngắn và ba câu hỏi tự kiểm tra kèm
    đáp án.
-   [ ] Giải thích thuật ngữ tiếng Anh bằng tiếng Việt ngay lần đầu xuất
    hiện; chỉ giữ lại những thuật ngữ thực sự cần thiết.
-   [ ] Giữ câu trả lời trong khoảng **400--600 từ**, chia thành các mục
    rõ ràng, tránh lặp ý.
-   [ ] Nếu có thông tin chưa đủ để kết luận, hãy nêu rõ giả định; không
    tự bịa số liệu hoặc khẳng định kỹ thuật không cần thiết.

## 4. Không cần

-   Không sử dụng công thức toán học phức tạp hoặc thuật toán lập trình.
-   Không đi sâu vào vi điều khiển, giao thức mạng, kiến trúc phần cứng
    hay mã nguồn.
-   Không dùng quá nhiều thuật ngữ tiếng Anh chuyên ngành. Nếu bắt buộc
    phải dùng, hãy giải thích ngắn gọn bằng tiếng Việt.
-   Không viết câu trả lời quá dài; nếu vượt quá giới hạn 600 từ, hãy tự
    rút gọn.
-   Không đưa thêm thông tin ngoài chủ đề mô hình IPO trong trang trại
    thông minh.
-   Không giả định rằng mọi trang trại đều sử dụng cùng loại cảm biến
    hoặc có cùng cách vận hành.

------------------------------------------------------------------------

# PHẦN 2. KẾT QUẢ AI SAU KHI ÁP DỤNG PROMPT

# Tìm hiểu mô hình IPO trong trang trại thông minh

## 1. Mô hình IPO là gì?

IPO là viết tắt của ba từ tiếng Anh:

-   **Input (Đầu vào):** Thông tin hoặc dữ liệu mà hệ thống nhận được.
-   **Process (Xử lý):** Các bước hệ thống thực hiện để phân tích dữ
    liệu và quyết định hành động.
-   **Output (Đầu ra):** Kết quả mà hệ thống tạo ra sau khi xử lý.

Có thể hiểu đơn giản, IPO giống như cách một người làm vườn quan sát
đất, suy nghĩ xem cây có cần nước hay không, rồi quyết định tưới cây.

Trong trang trại thông minh, mô hình IPO giúp mô tả cách hệ thống nhận
thông tin từ môi trường, xử lý thông tin và thực hiện một hành động phù
hợp.

## 2. Ba thành phần của IPO

  -----------------------------------------------------------------------
  Thành phần              Ý nghĩa                 Ví dụ trong trang trại
  ----------------------- ----------------------- -----------------------
  **Input -- Đầu vào**    Dữ liệu được đưa vào hệ Cảm biến đo độ ẩm đất
                          thống                   và gửi kết quả về bộ
                                                  điều khiển

  **Process -- Xử lý**    Hệ thống phân tích dữ   Bộ điều khiển kiểm tra
                          liệu theo quy tắc đã    xem đất có khô hơn mức
                          thiết lập               cài đặt hay không

  **Output -- Đầu ra**    Kết quả hoặc hành động  Hệ thống bật máy bơm để
                          sau khi xử lý           tưới cây hoặc giữ máy
                                                  bơm ở trạng thái tắt
  -----------------------------------------------------------------------

## 3. Ví dụ: Hệ thống tưới nước tự động

Hãy tưởng tượng một trang trại trồng rau có hệ thống tưới nước tự động.

### Bước 1: Input -- Đầu vào

Cảm biến độ ẩm đất đo lượng ẩm trong đất rồi gửi dữ liệu đến bộ điều
khiển. Đây là thông tin đầu vào để hệ thống xem xét tình trạng đất.

### Bước 2: Process -- Xử lý

Bộ điều khiển so sánh dữ liệu nhận được với ngưỡng độ ẩm đã cài đặt. Nếu
đất khô hơn ngưỡng này, hệ thống xác định rằng cây cần được tưới. Ngưỡng
cụ thể phụ thuộc vào loại cây và cách thiết lập của trang trại.

### Bước 3: Output -- Đầu ra

Nếu điều kiện tưới được đáp ứng, hệ thống bật máy bơm hoặc mở van nước.
Khi điều kiện không đáp ứng, hệ thống có thể giữ máy bơm tắt.

Quy trình có thể tóm tắt như sau:

**Cảm biến đo độ ẩm → Bộ điều khiển phân tích dữ liệu → Máy bơm tưới
nước khi cần.**

## 4. Tóm tắt kiến thức

Mô hình IPO mô tả một quy trình gồm ba bước: **nhận dữ liệu, xử lý dữ
liệu và tạo ra kết quả**. Trong trang trại thông minh, mô hình này giúp
chúng ta hiểu cách cảm biến, bộ điều khiển và thiết bị hoạt động cùng
nhau.

Mẹo ghi nhớ: **Input là nhận vào, Process là xử lý, Output là kết quả
đầu ra.**

## 5. Ba câu hỏi tự kiểm tra

**Câu 1.** Input trong hệ thống tưới nước tự động là gì?

**Đáp án:** Dữ liệu về độ ẩm đất do cảm biến thu thập và gửi đến hệ
thống.

**Câu 2.** Bộ điều khiển thực hiện vai trò nào trong mô hình IPO?

**Đáp án:** Process -- xử lý dữ liệu và kiểm tra điều kiện tưới theo quy
tắc đã cài đặt.

**Câu 3.** Nếu đất khô hơn ngưỡng đã thiết lập và hệ thống bật máy bơm,
máy bơm được bật thuộc thành phần nào?

**Đáp án:** Output -- đầu ra, vì đây là hành động được tạo ra sau khi xử
lý dữ liệu.

------------------------------------------------------------------------

# PHẦN 3. KIỂM THỬ PROMPT VỚI TRƯỜNG HỢP ĐẶC BIỆT (EDGE CASE)

## Tình huống 1: Câu trả lời quá dài

**Rủi ro:** AI có thể giải thích lan man, đưa thêm nhiều ví dụ và vượt
quá độ dài phù hợp với sinh viên mới học.

**Ràng buộc đã sử dụng:** Giới hạn câu trả lời trong khoảng 400--600 từ,
chia thành các mục rõ ràng, không lặp ý và yêu cầu tự rút gọn nếu vượt
quá 600 từ.

## Tình huống 2: Quá nhiều thuật ngữ tiếng Anh

**Rủi ro:** Người học mới có thể không hiểu những từ chuyên ngành như
sensor, controller hoặc threshold.

**Ràng buộc đã sử dụng:** Yêu cầu AI giải thích thuật ngữ bằng tiếng
Việt ngay lần đầu xuất hiện, hạn chế tiếng Anh chuyên ngành và không đi
sâu vào kiến thức kỹ thuật nâng cao.

## Tình huống 3: AI tự thêm thông tin ngoài phạm vi

**Rủi ro:** AI có thể mở rộng sang lập trình, phần cứng hoặc giao thức
mạng khiến câu trả lời khó hiểu.

**Ràng buộc đã sử dụng:** Phần **Không cần** nêu rõ những nội dung không
được đi sâu, yêu cầu bám sát chủ đề IPO và không tự bịa số liệu.

------------------------------------------------------------------------

# KẾT LUẬN

Prompt được thiết kế theo công thức **Bối cảnh -- Nội dung -- Yêu cầu**,
sử dụng tiêu đề Markdown để phân chia cấu trúc và Task List để liệt kê
các nhiệm vụ cụ thể. Phần **Không cần** giúp giới hạn phạm vi kiến thức,
độ dài và mức độ chuyên môn của câu trả lời.

Qua bài tập, có thể thấy một Prompt rõ ràng giúp AI hiểu vai trò, xác
định đúng nội dung cần giải thích và tạo ra câu trả lời phù hợp hơn với
người học. Việc bổ sung giới hạn độ dài, yêu cầu giải thích thuật ngữ và
câu hỏi tự kiểm tra giúp biến AI thành một gia sư học tập hữu ích cho
sinh viên năm nhất.

------------------------------------------------------------------------

# THÔNG TIN REPOSITORY

**Tên repository đề xuất:**

`HCM-KS26-CNTT1_IT-101_Session08_Ex04`

**Tên file đề xuất:**

-   `README.md` -- bản Prompt hoàn chỉnh để tái sử dụng.
-   `KetQua_AI_IPO.md` -- câu trả lời mẫu sau khi áp dụng Prompt.

**Lưu ý:** Nếu giảng viên quy định cách viết tên lớp hoặc tên môn khác,
hãy dùng đúng quy ước trên LMS.
