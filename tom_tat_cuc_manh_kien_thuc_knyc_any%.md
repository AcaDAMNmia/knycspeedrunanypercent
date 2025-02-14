# Tóm tắt cực mạnh kiến thức môn Kỹ nghệ yêu cầu dựa trên mô hình

## Mục lục

- [Tóm tắt cực mạnh kiến thức môn Kỹ nghệ yêu cầu dựa trên mô hình](#tóm-tắt-cực-mạnh-kiến-thức-môn-kỹ-nghệ-yêu-cầu-dựa-trên-mô-hình)
  - [Mục lục](#mục-lục)
  - [0. Ghi chú và thông tin thêm](#0-ghi-chú-và-thông-tin-thêm)
  - [1. Tổng quan về Kỹ nghệ yêu cầu dựa trên mô hình](#1-tổng-quan-về-kỹ-nghệ-yêu-cầu-dựa-trên-mô-hình)
    - [1.1. Khái niệm Kỹ nghệ yêu cầu](#11-khái-niệm-kỹ-nghệ-yêu-cầu)
    - [1.2. Khái niệm Thế giới và Máy](#12-khái-niệm-thế-giới-và-máy)
      - [Mối quan tâm của Kỹ nghệ yêu cầu](#mối-quan-tâm-của-kỹ-nghệ-yêu-cầu)
    - [1.3. Hệ thống hiện thời và Hệ thống mục tiêu](#13-hệ-thống-hiện-thời-và-hệ-thống-mục-tiêu)
    - [1.4. Yêu cầu hệ thống và Yêu cầu phần mềm](#14-yêu-cầu-hệ-thống-và-yêu-cầu-phần-mềm)
      - [Mối quan tâm của KNYC](#mối-quan-tâm-của-knyc)
    - [1.5. Kỹ nghệ yêu cầu trong quy trình phát triển phần mềm](#15-kỹ-nghệ-yêu-cầu-trong-quy-trình-phát-triển-phần-mềm)
    - [1.6. Mô hình](#16-mô-hình)
  - [2. Các loại Phát biểu và Yêu cầu](#2-các-loại-phát-biểu-và-yêu-cầu)
    - [2.1. Các loại phát biểu](#21-các-loại-phát-biểu)
      - [2.1.1. Phát biểu mô tả và Phát biểu mong muốn](#211-phát-biểu-mô-tả-và-phát-biểu-mong-muốn)
      - [2.1.2. Yêu cầu hệ thống và Yêu cầu phần mềm dưới góc độ các phát biểu](#212-yêu-cầu-hệ-thống-và-yêu-cầu-phần-mềm-dưới-góc-độ-các-phát-biểu)
      - [2.1.3. Thuộc tính miền, Giả định, Định nghĩa](#213-thuộc-tính-miền-giả-định-định-nghĩa)
      - [2.1.4 Mô hình 4 biến M-C-I-O và Công thức thỏa mãn](#214-mô-hình-4-biến-m-c-i-o-và-công-thức-thỏa-mãn)
    - [2.2. Các loại yêu cầu: Yêu cầu chức năng và Yêu cầu phi chức năng](#22-các-loại-yêu-cầu-yêu-cầu-chức-năng-và-yêu-cầu-phi-chức-năng)
  - [3. Một số thông tin thêm về Kỹ nghệ yêu cầu](#3-một-số-thông-tin-thêm-về-kỹ-nghệ-yêu-cầu)
    - [3.1. Tóm tắt về quy trình Kỹ nghệ yêu cầu](#31-tóm-tắt-về-quy-trình-kỹ-nghệ-yêu-cầu)
    - [3.2. Các phẩm chất nên có và những lỗi nên tránh](#32-các-phẩm-chất-nên-có-và-những-lỗi-nên-tránh)
    - [3.3. Các loại dự án phần mềm](#33-các-loại-dự-án-phần-mềm)
    - [3.4. Mối quan hệ giữa Kỹ nghệ yêu cầu và các lĩnh vực khác](#34-mối-quan-hệ-giữa-kỹ-nghệ-yêu-cầu-và-các-lĩnh-vực-khác)
  - [4. Quy trình kỹ nghệ yêu cầu](#4-quy-trình-kỹ-nghệ-yêu-cầu)
  - [5. Tiến hóa yêu cầu](#5-tiến-hóa-yêu-cầu)
    - [5.1. Góc độ không gian và thời gian của yêu cầu](#51-góc-độ-không-gian-và-thời-gian-của-yêu-cầu)
  - [6. Kỹ nghệ yêu cầu hướng mục tiêu](#6-kỹ-nghệ-yêu-cầu-hướng-mục-tiêu)
  - [7. Sơ lược về 6 loại mô hình KAOS](#7-sơ-lược-về-6-loại-mô-hình-kaos)
    - [7.1. Mô hình mục tiêu](#71-mô-hình-mục-tiêu)
    - [7.2. Mô hình trở ngại](#72-mô-hình-trở-ngại)
    - [7.3. Mô hình tác tử/trách nhiệm](#73-mô-hình-tác-tửtrách-nhiệm)
    - [7.4. Mô hình đối tượng](#74-mô-hình-đối-tượng)
    - [7.5. Mô hình thao tác](#75-mô-hình-thao-tác)
    - [7.6. Mô hình hành vi](#76-mô-hình-hành-vi)
  - [8. Tích hợp đa góc nhìn hệ thống](#8-tích-hợp-đa-góc-nhìn-hệ-thống)
  - [9. Phương pháp bán hình thức trong Kỹ nghệ yêu cầu](#9-phương-pháp-bán-hình-thức-trong-kỹ-nghệ-yêu-cầu)
  - [10. Phương pháp hình thức trong Kỹ nghệ yêu cầu](#10-phương-pháp-hình-thức-trong-kỹ-nghệ-yêu-cầu)
  - [11. Tổng kết](#11-tổng-kết)

## 0. Ghi chú và thông tin thêm

- Tài liệu này được soạn bởi Bế Trọng Nghĩa, nhằm phục vụ cho việc học tập và ôn tập kiến thức môn **[INT6018] - Kỹ nghệ yêu cầu dựa trên mô hình** (tiếng Anh: Model-based Requirements Engineering) ở bậc Cao học tại Trường Đại học Công nghệ - ĐHQGHN (VNU-UET). Tài liệu này cũng có thể được sử dụng để ôn tập kiến thức cho các môn học tương tự khác, như **Kỹ nghệ yêu cầu** hoặc **Thu thập và phân tích yêu cầu** ở bậc Đại học. Vì tác giả tài liệu này là con người chứ không phải AI, cho nên có thể văn sẽ mượt hơn (hoặc không) và có thể có sai sót. Mọi góp ý, bổ sung, hoặc sửa lỗi xin được thực hiện tại [phần issues của repo này](https://github.com/AcaDAMNmia/knycspeedrunanypercent/issues).

- Tài liệu được xây dựng dựa trên tài liệu tham khảo chính của môn học là cuốn sách [Requirements Engineering](https://www.wiley.com/en-us/Requirements+Engineering%3A+From+System+Goals+to+UML+Models+to+Software+Specifications%2C+1st+Edition-p-9780470012703) của Axel van Lamsweerde, cũng như slides thuyết trình của các nhóm trong lớp KNYC mùa thu năm 2025. Xin gửi lời cảm ơn trân trọng nhất đến với tác giả Axel, thầy Đặng Đức Hạnh, bạn Vũ Đức Hiếu và bạn Đặng Trần Hoàng Hà, cùng các bạn trong lớp đã giúp tôi có được kiến thức và tài liệu tốt nhất. Copy nhớ ghi nguồn, không cần xin phép.

- Ở phiên bản hiện tại, một số nội dung đang bị bỏ qua hoặc chỉ được tóm tắt như 4 bước chính trong quy trình Kỹ nghệ yêu cầu, hoặc chưa được đề cập đến như các phương pháp hình thức/bán hình thức (và những nội dung khác trong cuốn sách của Axel). Vì nội dung trong tài liệu này về cơ bản được soạn trong 3 ngày (và chẳng biết có được cập nhật hay không), cho nên việc thiếu sót là không thể tránh khỏi.

- Một số tài liệu khuyên dùng cho môn học:
  - Về kỹ nghệ yêu cầu nói chung: 
    - [Software Requirements Essentials: Core Practices for Successful Business Analysis](https://www.informit.com/store/software-requirements-essentials-core-practices-for-9780138190286) của tác giả Karl Wiegers và Candase Hockanson trình bày 20 "mẹo" để thực hành KNYC hiệu quả.
  - Về nội dung chính của môn học: 
    - [Requirements Engineering](https://www.wiley.com/en-us/Requirements+Engineering%3A+From+System+Goals+to+UML+Models+to+Software+Specifications%2C+1st+Edition-p-9780470012703) của tác giả Axel van Lamsweerde trình bày nền tảng lý thuyết về KNYC dựa trên mô hình (phương pháp KAOS - một phương pháp KNYC hướng mục tiêu).
    - Bên cạnh đó, có thể tham khảo công cụ hỗ trợ KAOS là [Objectiver](https://objectiver.com/index.php?id=4), với hướng dẫn sử dụng tại [đây](https://www.objectiver.com/fileadmin/download/documents/KaosTutorial.pdf). Dù bạn có định dùng Objectiver hay không, thì vẫn nên đọc qua phần hướng dẫn sử dụng để có thể hiểu hơn về phương pháp KAOS trong ngữ cảnh ví dụ cụ thể.
  - Một số nội dung khác:
    - [Handbook of Requirements and Business Analysis](https://link.springer.com/book/10.1007/978-3-031-06739-6) của tác giả Bertrand Meyer đề cập đến một phương pháp KNYC hiện đại hơn, cũng đã được giới thiệu sơ qua trong khóa học.
    - [i* hay iStar](https://en.wikipedia.org/wiki/I*) là một phương pháp KNYC khác, cũng là KNYC hướng mục tiêu và dựa trên mô hình như KAOS, tuy nhiên i* tập trung vào biệt vào các tác nhân. Bên cạnh đó, cộng đồng iStar hoạt động "năng nổ" hơn KAOS, với nhiều công cụ hỗ trợ và nhiều tài liệu tham khảo hơn. Có thể truy cập một số link sau như [đây](http://istarwiki.org/) hoặc [đây](https://sites.google.com/site/istarlanguage/) để tìm hiểu. Ngoài ra, có [cuốn sách mới được xuất bản gần đây](https://link.springer.com/book/10.1007/978-3-031-72107-6) cũng tập trung vào việc sử dụng i* trong một bài toán cụ thể (social modeling).
    - [Software Engineering](https://software-engineering-book.com/) của Ian Sommerville là cuốn sách kinh điển về Kỹ nghệ phần mềm, có thể tham khảo để lấy nền tảng lý thuyết chung.

## 1. Tổng quan về Kỹ nghệ yêu cầu dựa trên mô hình

### 1.1. Khái niệm Kỹ nghệ yêu cầu

- **Kỹ nghệ yêu cầu** (tiếng Anh: Requirements Engineering - RE, viết tắt: KNYC): Là quá trình xác định, đánh giá, đặc tả, và thẩm định các yêu cầu của hệ thống.

### 1.2. Khái niệm Thế giới và Máy

- **Thế giới** (World) - hay gọi là **Thế giới vấn đề** (viết tắt: TGVD), là nơi nảy sinh các vấn đề cần giải quyết. TGVD có hai thành phần:
  - Thành phần con người: VD: nhân viên, quản lý, khách hàng, ...
  - Thành phần vật lý: VD: các thiết bị (máy tính, máy in, cảm biến, ...), các phần mềm có sẵn (legacy software), các yếu tố môi trường (địa lý, thời tiết, ...).

- **Máy** (tiếng Anh: Machine) - hay gọi là **Không gian máy** (viết tắt: KGM), là thứ được đưa vào để giải quyết các vấn đề của TGVD. Máy có hai thành phần:
  - Phần mềm: Có thể là phần mềm mới được phát triển, hoặc phần mềm được mua từ bên thứ ba.
  - Phần cứng: Nền tảng để chạy phần mềm, hoặc các thiết bị khác như cảm biến (tiếng Anh: Sensor)/bộ truyền động (tiếng Anh: Actuator).

- VD trong ngữ cảnh Trường ĐH Công nghệ: Giả sử với bài toán điểm danh sinh viên (khi chưa có ứng dụng điểm danh):
  - TGVD:
    - Thành phần con người: Sinh viên, giảng viên, trợ giảng, phòng đào tạo.
    - Thành phần vật lý: Phòng học, điện thoại thông minh, máy tính cá nhân, ...
  - Máy:
    - Phần mềm: Ứng dụng điểm danh, hệ thống quản lý sinh viên.
    - Phần cứng: Máy tính cá nhân, máy chủ, camera, ...

#### Mối quan tâm của Kỹ nghệ yêu cầu

- **KNYC** quan tâm đến TGVD và Máy:
  - Máy tác động thế nào đến TGVD?
  - TGVD có những giả định và thuộc tính nào?
  - Bên trong TGVD và Máy đều có những hiện tượng riêng và chung. **KNYC chỉ quan tâm đến các hiện tượng phía TGVD** (bao gồm các hiện tượng chung với Máy); ngược lại với Thiết kế phần mềm chỉ quan tâm đến các hiện tượng phía Máy.

### 1.3. Hệ thống hiện thời và Hệ thống mục tiêu

- **Hệ thống** (tiếng Anh: System): Là một tập hợp các thành phần tương tác với nhau để thực hiện một hoặc nhiều mục tiêu cụ thể.

```txt
- Hệ thống = Phần mềm + Môi trường (Con người, thiết bị, phần mềm khác, ...).
```

- **Hệ thống hiện thời** (tiếng Anh: System-as-is): Là hệ thống đã tồn tại, trước khi Máy được đưa vào để giải quyết vấn đề của TGVD.

- **Hệ thống mục tiêu** (tiếng Anh: System-to-be): Là hệ thống đã sử dụng Máy để giải quyết vấn đề của TGVD.

```txt
- Hệ thống mục tiêu = Hệ thống hiện thời + Máy.

                    = Phần mềm mục tiêu + Môi trường (Con người, thiết bị, phần mềm khác, ...).
```

### 1.4. Yêu cầu hệ thống và Yêu cầu phần mềm

- **Yêu cầu hệ thống** (tiếng Anh: System Requirements, viết tắt: YCHT): Là các yêu cầu của hệ thống mục tiêu mà phải đáp ứng để giải quyết vấn đề của TGVD.
  - YCHT được định nghĩa dưới dạng hiện tượng của TGVD.
  - VD: "Phanh sẽ được thả khi tài xế bắt đầu di chuyển".

- **Yêu cầu phần mềm** (tiếng Anh: Software Requirements, viết tắt: YCPM): Là các yêu cầu của phần mềm mà phải đáp ứng để giải quyết vấn đề của TGVD.
  - YCPM được định nghĩa dưới dạng hiện tượng chung của TGVD và Máy.
  - VD: "Biến `dieuKhienPhanhXe` sẽ có giá trị `off` khi biến `vanTocXe` có giá trị lớn hơn 0".

#### Mối quan tâm của KNYC

- Ba chữ **W**:
  - **WHY**: Tại sao cần một hệ thống mới?
    - Đặt ra các Mục tiêu (Objectives) sau khi xem xét hệ thống hiện tại ở nhiều góc độ: Các cơ hội, thách thức, kiến thức, kỹ thuật, ...
  - **WHAT**: Hệ thống mới sẽ làm gì/cung cấp gì?
    - Đặt ra Chức năng (Functional services) và thỏa mãn các Mục tiêu của hệ thống thông qua các yêu cầu, ràng buộc, giả định, ...
  - **WHO**: Ai sẽ chịu trách nhiệm cho các tác vụ mà hệ thống mới thực hiện/dịch vụ mà hệ thống mới cung cấp?
    - Đặt ra các bên liên quan, các vai trò, các quyền lợi và trách nhiệm, ...

### 1.5. Kỹ nghệ yêu cầu trong quy trình phát triển phần mềm

- Với quy trình cơ bản: **Kỹ nghệ yêu cầu** -> **Thiết kế phần mềm** -> **Cài đặt phần mềm** -> **Tiến hóa phần mềm**.

- **KNYC** vì nằm ở giai đoạn đầu của quy trình phát triển phần mềm, nên có ảnh hưởng lớn đến nhiều khía cạnh của dự án:
  - KNYC là bước **"có được đúng hệ thống như mong muốn"** (Getting the right system), còn Thiết kế phần mềm là bước **"xây dựng được hệ thống đúng cách"** (Getting the system right).
  - KNYC cho kết quả là **Tài liệu yêu cầu** (tiếng Anh: Requirements Document - RD, viết tắt: TLYC). Đây là **chế tác** (tiếng Anh: Artifact) quan trọng nhất của KNYC - vì TLYC ảnh hưởng đến nhiều khía cạnh của dự án, cả về kỹ thuật (thiết kế, cài đặt, kiểm thử, ...) và phi kỹ thuật (quản lý dự án, quản lý chất lượng, hợp đồng, ...).
  - **Thay đổi** ở giai đoạn KNYC có **chi phí thấp nhất** và tăng cao hơn ở các giai đoạn sau. Vì vậy, việc đầu tư nhiều vào KNYC giúp **giảm thiểu rủi ro và chi phí** cho dự án.

### 1.6. Mô hình

- Môn học này tập trung vào **KNYC dựa trên mô hình** (Model-based RE - MBRE), tập trung vào **phương pháp KAOS** (tiếng Anh: Knowledge Acquisition in autOmated Specification hay Keep All Objectives Satisfied), một phương pháp **KNYC hướng mục tiêu** (tiếng Anh: Goal-oriented Requirements Engineering).

- **Mô hình** (tiếng Anh: Model): Là một biểu diễn trừu tượng của một hệ thống.
  - "Trừu tượng" hiểu theo nghĩa "đơn giản hóa" hoặc "tổng quát hóa".
  - Mô hình **biểu diễn những thành phần cốt lõi** của hệ thống mà bài toán cần giải quyết, và **loại bỏ những chi tiết không cần thiết**.
  - VD: Mô hình của một hệ thống điểm danh sinh viên, nếu biểu diễn đối tượng sinh viên thì chỉ cần quan tâm đến tên, mã số sinh viên, lớp, ... mà không cần quan tâm đến chiều cao, cân nặng, ...

- Mô hình được dùng để biểu diễn mô hình khác gọi là **Siêu mô hình** (Meta-model). Khái niệm này thường gặp trong lĩnh vực **Kỹ nghệ phần mềm hướng mô hình** (tiếng Anh: Model-driven Software Engineering - MDSE).

- Việc thực hiện **KNYC dựa trên mô hình** giúp quy trình KNYC trở nên hiệu quả hơn:
  - Giúp tập trung vào các **khía cạnh quan trọng** của hệ thống.
  - Cung cấp **cấu trúc** cho các hoạt động KNYC.
  - Hỗ trợ tốt hơn trong việc **thấu hiểu và giao tiếp với các bên liên quan**.
  - Là cơ sở cho việc phân tích và đưa ra quyết định, cũng như tạo dựng **TLYC**.

- **Phương pháp KAOS** sử dụng 6 loại mô hình để biểu diễn nhiều khía cạnh của hệ thống:
  1. **Mô hình mục tiêu** (tiếng Anh: Goal model)
  - Biểu diễn các mục tiêu của hệ thống và mối quan hệ giữa chúng.
  - Trả lời cho câu hỏi **WHY** - "Tại sao cần một hệ thống mới?"
  2. **Mô hình trở ngại** (tiếng Anh: Obstacle model)
  - Biểu diễn các trở ngại mà hệ thống phải vượt qua để đạt được mục tiêu.
  - Trả lời cho câu hỏi **WHY NOT** - "Tại sao hệ thống mới không thể thực hiện được mục tiêu?".
  3. **Mô hình tác tử/trách nhiệm** (tiếng Anh: Agent/Responsibility model)
  - Biểu diễn các trách nhiệm của các đối tượng trong hệ thống.
  - Trả lời cho câu hỏi **WHO** - "Ai sẽ chịu trách nhiệm cho các tác vụ mà hệ thống mới thực hiện?".
  4. **Mô hình đối tượng** (tiếng Anh: Object model)
  - Biểu diễn các đối tượng trong hệ thống và mối quan hệ giữa chúng.
  - Trả lời cho câu hỏi **ON WHAT** - "Hệ thống mới sẽ làm việc với những gì?".
  5. **Mô hình thao tác** (tiếng Anh: Operation model)
  - Biểu diễn các thao tác mà hệ thống thực hiện để đạt được mục tiêu.
  - Trả lời cho câu hỏi **WHAT** - "Hệ thống mới sẽ làm gì/cung cấp gì?".
  6. **Mô hình hành vi** (tiếng Anh: Behavior model)
  - Biểu diễn cách mà hệ thống hoạt động để đạt được mục tiêu.
  - Trả lời cho câu hỏi **HOW** - "Hệ thống mới sẽ hoạt động như thế nào?".

## 2. Các loại Phát biểu và Yêu cầu

### 2.1. Các loại phát biểu

#### 2.1.1. Phát biểu mô tả và Phát biểu mong muốn

- **Phát biểu mô tả** (tiếng Anh: Descriptive statement, viết tắt: PBMT): Là phát biểu mô tả các tính chất có tính "luôn đúng" của hệ thống.
  - Thường là các hiện tượng tự nhiên, ràng buộc vật lý, ...
  - VD 1: "Khi xe đang chạy, vận tốc của xe lớn hơn 0".
  - VD 2: "Nước sôi ở 100 độ C".

- **Phát biểu mong muốn** (tiếng Anh: Prescriptive statement, viết tắt: PBMM): Là phát biểu mô tả các tính chất mà hệ thống cần đạt được.
  - Thường là các mục tiêu, yêu cầu hệ thống, ...
  - VD 1: "Cửa xe phải luôn đóng khi xe đang chạy".
  - VD 2: "Ngắt nguồn đun nước ngay sau khi sôi".

- **Khác biệt quan trọng**: PBMT là "luôn đúng", còn PBMM là "cần đạt được". Do đó **không thể thay đổi hoặc điều chỉnh PBMT**, nhưng có thể thay đổi hoặc điều chỉnh PBMM.

#### 2.1.2. Yêu cầu hệ thống và Yêu cầu phần mềm dưới góc độ các phát biểu

- Từ công thức (1) ```Hệ thống = Phần mềm + Môi trường``` và (2) KNYC chỉ quan tâm đến các hiện tượng ở TGVD (tính cả hiện tượng chung với Máy).
  - Phát biểu trong KNYC có thể **liên hệ đến các hiện tượng** ở Môi trường, hoặc chung giữa Phần mềm và Môi trường.

- **Yêu cầu hệ thống**: Là PBMM liên hệ đến các hiện tượng ở Môi trường (không nhất thiết là chung).
  - Được thực thi bởi phần mềm mục tiêu (và các thành phần khác nếu có).
  - Sử dụng ngôn ngữ mà tất cả các bên đều hiểu (ubiquitous).
  - VD: `XeDangChay -> CuaXeDong`.

- **Yêu cầu phần mềm**: Là PBMM liên hệ đến các hiện tượng chung giữa Phần mềm và Môi trường.
  - Được thực thi hoàn toàn bởi phần mềm mục tiêu.
  - Sử dụng ngôn ngữ mà lập trình viên hiểu (technical).
  - VD: `vanTocXe > 0 -> toanBoCuaXeDong = true`.

- **Yêu cầu phần mềm là yêu cầu hệ thống, nhưng ngược lại không đúng**.

#### 2.1.3. Thuộc tính miền, Giả định, Định nghĩa

- **Thuộc tính miền** (tiếng Anh: Domain property - DOM): Là PBMT về các **hiện tượng của TGVD**.
  - VD: `xeDangChay = true -> vanTocXe > 0`.

- **Giả định** (tiếng Anh: Assumption - ASM): Là phát biểu (thường là PBMM) về các **hiện tượng của Môi trường** và cần được **thỏa mãn bởi Môi trường của Phần mềm mục tiêu**.
  - VD: `if (vanTocXe > 0) then vanTocXeDoDuoc = vanTocXe`.

- **Định nghĩa** (tiếng Anh: Definition - DEF): Là phát biểu cung cấp **khái niệm/thuật ngữ** và **không có tính đúng/sai**.
  - VD: `vanTocXe` là vận tốc thực tế của xe; `vanTocXeDoDuoc` là vận tốc đo được từ tốc kế của xe.

#### 2.1.4 Mô hình 4 biến M-C-I-O và Công thức thỏa mãn

- Môi trường --**Biến được giám sát M** (tiếng Anh: Monitored variable)--> Thiết bị đầu vào (VD: Cảm biến).
  - VD: `M = vanTocXe`.

- Thiết bị đầu vào --**Dữ liệu đầu vào I** (tiếng Anh: Input data)--> Phần mềm mục tiêu.
  - VD: `I = vanTocXeDoDuoc`.

- Phần mềm mục tiêu --**Dữ liệu đầu ra O** (tiếng Anh: Output data)--> Thiết bị đầu ra (VD: Bộ truyền động).
  - VD: `O = trangThaiCuaXe`.

- Thiết bị đầu ra --**Biến được điều khiển C** (tiếng Anh: Controlled variable)--> Môi trường.
  - VD: `C = toanBoCuaXeDong`.

- 2 công thức:
  - $YCHT \subseteq M \times C$ là quan hệ trên biến của môi trường.
  - $YCPM \subseteq I \times O$ là quan hệ trên dữ liệu đầu vào và đầu ra.

- **Công thức thỏa mãn** (tiếng Anh: Satisfaction formula), hay gọi là **"Công thức thỏa"**: 
  - $YCPM, ASM, DOM \models YCHT$.
  - Phát biểu: Nếu yêu cầu phần mềm, giả định, và thuộc tính miền đều thỏa mãn và và nhất quán (không có mâu thuẫn), thì yêu cầu hệ thống cũng được thỏa mãn.

### 2.2. Các loại yêu cầu: Yêu cầu chức năng và Yêu cầu phi chức năng

- **Yêu cầu chức năng** (tiếng Anh: Functional requirement - FR, viết tắt: YCCN): Là yêu cầu mô tả **các chức năng mà hệ thống cần thực hiện**.
  - Mô tả các mong muốn về sự **ảnh hưởng của phần mềm lên môi trường**.
  - Các đơn vị chức năng là kết quả của các **thao tác mà phần mềm thực hiện**.
  - Có thể coi là **yêu cầu nghiệp vụ** (tiếng Anh: Business requirement), mô tả hệ thống dưới góc nhìn người dùng (VD: Người dùng có thể sử dụng những chức năng nào?).
  - VD: "Phần mềm sẽ kiểm soát vận tốc trên mọi xe ô tô của công ty X".

- Ở những giai đoạn đầu YCCN không nhất thiết phải chặt chẽ hay đầy đủ, nhưng **càng về sau càng phải được hoàn thiện và chính xác**.
  - Việc **viết tài liệu** sẽ giúp cho quá trình này.
  - Nếu xảy ra **mơ hồ hay mâu thuẫn** sẽ **ảnh hưởng xấu** đến những giai đoạn sau.
  - VD: "Tắt máy bơm nếu mực nước cao hơn 100 mét sau 4 giây" - Mực nước là trung bình hay tối thiểu?

- **Yêu cầu phi chức năng** (tiếng Anh: Non-functional requirement - NFR, viết tắt: YCPCN): Là yêu cầu mô tả **các ràng buộc mà hệ thống cần đạt được**.
  - Mô tả các mong muốn về **chất lượng của phần mềm** như bảo mật, an toàn, chính xác, hiệu suất, ..., cũng như các ràng buộc khác (pháp lý, chi phí, ...).
  - Tính **an toàn** đặc thù với một số hệ thống như phần mềm y tế, phương tiện giao thông, quân sự, ...
  - Được **định nghĩa bằng các thuật ngữ chuyên biệt** cho từng lĩnh vực.
  - Các YCPCN **có thể trùng lặp nhau** (VD: Xử lý phanh tự động trong môi trường có khả năng gây tai nạn - yêu cầu chính xác và an toàn) hoặc **trùng với YCCN** (VD: Tường lửa vừa là chức năng vừa yêu cầu bảo mật).
  - VD: "Phần mềm sẽ gửi thông tin trạng thái xe ô tô mỗi 1 phút về máy chủ của công ty X".

- Việc **phân loại yêu cầu có hệ thống** (tiếng Anh: Requirements taxonomy) giúp cho việc **quản lý yêu cầu hiệu quả hơn**.

## 3. Một số thông tin thêm về Kỹ nghệ yêu cầu

### 3.1. Tóm tắt về quy trình Kỹ nghệ yêu cầu

- Quy trình Kỹ nghệ yêu cầu gồm **4 bước** chính, không bắt buộc tuân theo thứ tự chặt chẽ (có thể từ bước trước quay về bước sau, hoặc trùng lặp giữa các bước, ...) và có tính lặp lại theo hình xoắn ốc (quay lại bước đầu sau khi xong bước cuối, nhưng để cải thiện thay vì bắt đầu lại từ đầu). Nội dung chi tiết của 4 bước này sẽ được đề cập trong phần [4. Quy trình Kỹ nghệ yêu cầu](#4-quy-trình-kỹ-nghệ-yêu-cầu).
  - **Hiểu miền vấn đề và xác định yêu cầu**.
    - **Tìm hiểu hệ thống hiện tại** để hiểu được **bản chất nghiệp vụ** cũng như **điểm mạnh/yếu** của hệ thống.
    - Xác định được **các bên liên quan** như người sử dụng hệ thống hoặc người vận hành hệ thống.
    - **Khám phá TGVD** để xác định thêm các vấn đề, cũng như các yêu cầu, mục tiêu, hay bối cảnh tương tác của hệ thống.
    - **Kết quả**: Tài liệu yêu cầu sơ bộ (tiếng Anh: Draft proposal) và Bảng thuật ngữ (tiếng Anh: Glossary).
  - **Đánh giá và thống nhất yêu cầu**.
    - Xác định và đánh giá được các **vấn đề** như mâu thuẫn, rủi ro, ...
    - **Đối sánh** các phương án và lựa chọn phương án phù hợp.
    - **Đặt ưu tiên** cho các yêu cầu.
    - **Kết quả**: Tài liệu yêu cầu sơ bộ bản cuối (đã thống nhất các mục tiêu, yêu cầu, giả định).
  - **Đặc tả và viết tài liệu yêu cầu**.
    - **Định nghĩa chính xác** các nội dung của hệ thống như đã thống nhất, cũng như những thông tin liên quan đến quản lý dự án.
    - Quản lý các nội dung trên theo **cấu trúc phù hợp**.
    - Tài liệu phải **có thể hiểu được bởi mọi bên** tham gia dự án.
    - **Kết quả**: Tài liệu yêu cầu (tiếng Anh: Requirements Document).
  - **Kiểm định và thẩm định yêu cầu**.
    - Là quá trình **đảm bảo chất lượng** cho yêu cầu.
    - **Kiểm định** (tiếng Anh: Verification): Đảm bảo rằng yêu cầu không có các vấn đề về kỹ thuật như mâu thuẫn hay thiếu sót.
    - **Thẩm định** (tiếng Anh: Validation): Đảm bảo rằng yêu cầu đáp ứng được nhu cầu của TGVD.
    - Thực hiện **kiểm tra các phẩm chất** và **sửa lỗi** nếu có.
    - **Kết quả**: Tài liệu yêu cầu được củng cố (tiếng Anh: Consolidated Requirements Document), dữ liệu kiểm thử chấp nhận và bản mẫu (tiếng Anh: Prototype), kế hoạch phát triển và hợp đồng dự án.

### 3.2. Các phẩm chất nên có và những lỗi nên tránh

- Một số **phẩm chất** mà các chế tác của KNYC nên có:
  - Hoàn thiện.
  - Nhất quán.
  - Đầy đủ.
  - Không mơ hồ.
  - Đo đếm được.
  - Có liên quan.
  - Khả thi.
  - Dễ hiểu.
  - Có tổ chức tốt.
  - Có thể sửa đổi được.
  - Có thể truy vết được.

- Một số **lỗi** nên tránh:
  - Lỗi nghiêm trọng:
    - Thiếu sót.
    - Mâu thuẫn.
    - Không đầy đủ.
    - Mơ hồ.
  - Các lỗi khác:
    - Không đo đếm được.
    - Đặc tả những thành phần có ở trong TGVD nhưng không có ở trong Máy, hoặc những thành phần không liên quan.
    - Không khả thi.
    - Khó hiểu.
    - Có tổ chức kém.
    - Tham chiếu đến những thành phần chưa được định nghĩa, hoặc định nghĩa muộn.
    - Khó thay đổi.
    - Không giải thích được vì sao lại có yêu cầu đó.

### 3.3. Các loại dự án phần mềm

- Có thể kể đến một số cách chia dự án:
  - **Green field** và **Brown field**: Dự án **Green field** là dự án mới, không có hệ thống hiện tại, còn **Brown field** là dự án mở rộng hoặc cải tiến từ hệ thống hiện tại.
  - **Hướng khác hàng** và **Hướng thị trường**: Dự án **Hướng khách hàng** tập trung vào việc đáp ứng nhu cầu của khách hàng, còn **Hướng thị trường** tập trung vào việc đáp ứng nhu cầu của thị trường.
  - **In-house** và **Outsource**: Dự án **In-house** là dự án được thực hiện bởi nhân viên của công ty, còn **Outsource** là dự án được thực hiện bởi một công ty khác.
  - **Đơn sản phẩm** và **Dòng sản phẩm**: Dự án **Đơn sản phẩm** tập trung vào việc phát triển một sản phẩm duy nhất, còn **Dòng sản phẩm** tập trung vào việc phát triển một dòng sản phẩm.

- Loại dự án cũng **ảnh hưởng** đến việc thực hiện KNYC cũng như các giai đoạn khác trong quá trình phát triển phần mềm.

### 3.4. Mối quan hệ giữa Kỹ nghệ yêu cầu và các lĩnh vực khác

- Chủ yếu KNYC gắn với **Kỹ nghệ phần mềm** (tiếng Anh: Software Engineering - SE) hay Công nghệ phần mềm (viết tắt: CNPM), nhưng cũng có mối quan hệ với các lĩnh vực khác:
  - **Hiểu miền vấn đề và xác định yêu cầu**: Kỹ nghệ hệ thống, lý thuyết điều khiển, khoa học quản lý, tâm lý học hành vi, nhân chủng học, thu thập tri thức trong trí tuệ nhân tạo, ...
  - **Đánh giá và thống nhất yêu cầu**.: Phân tích đa yếu tố, quản lý rủi ro, lý thuyết đàm phán, ...
  - **Đặc tả, viết tài liệu, và đảm bảo chất lượng yêu cầu**: Đặc tả phần mềm, phương pháp hình thức, ...
  - **Tiến hóa yêu cầu**: Quản lý thay đổi, quản lý cấu hình trong CNPM, ...
  - **Mô hình hóa hệ thống**: Mô hình hóa khái niệm trong cơ sở dữ liệu và hệ thống thông tin, mô hình hóa tác vụ trong tương tác người-máy, biểu diễn tri thức trong trí tuệ nhân tạo, ...

## 4. Quy trình kỹ nghệ yêu cầu

- TODO: Nội dung phần này tạm thời chưa được cập nhật. Có thể tham khảo phần tóm tắt ở mục [3.1. Tóm tắt về quy trình Kỹ nghệ yêu cầu](#31-tóm-tắt-về-quy-trình-kỹ-nghệ-yêu-cầu).

## 5. Tiến hóa yêu cầu

### 5.1. Góc độ không gian và thời gian của yêu cầu

- Yêu cầu có thể được **tiến hóa theo hai chiều**:
  - **Chiều không gian**: Gắn với Phiên bản biến thể (tiếng Anh: Variant) của hệ thống.
    - **Biến thể**: Là phiên bản của hệ thống có một số yêu cầu khác nhau so với phiên bản gốc, nhằm **mở rộng/thu hẹp/thích nghi** hoặc tùy chỉnh hệ thống cho một mục đích cụ thể.
    - Phản ánh sự tiến hóa theo **dòng sản phẩm** của hệ thống.
  - **Chiều thời gian**: Gắn với Phiên bản sửa đổi (tiếng Anh: Revision) của hệ thống.
    - **Sửa đổi**: Là phiên bản của hệ thống có sự **sửa lỗi/cải tiến** so với phiên bản gốc.
    - Phản ánh sự tiến hóa theo **thời gian** của hệ thống.
  
- VD: Trong ngữ cảnh ứng dụng lập lịch cuộc họp, sự phát triển theo thời gian có thể hiểu là quá trình phát triển ứng dụng thông thường, còn sự phát triển theo không gian có thể hiểu là việc tùy chỉnh ứng dụng cho từng đối tượng cụ thể (VD: Phiên bản trả phí sẽ có nhiều chức năng hơn phiên bản miễn phí).

### 5.2. Dự đoán thay đổi yêu cầu

- **Tài liệu hóa** các dự đoán thay đổi sẽ hỗ trợ cho việc dự đoán thay đổi yêu cầu.
  - Ở giai đoạn KNYC (giai đoạn trước khi bắt đầu phát triển hệ thống), việc tài liệu hóa sẽ hỗ trợ **ghi chép và truy vết**.
  - Ở giai đoạn phát triển hệ thống, việc tài liệu hóa sẽ hỗ trợ **tham chiếu** các nội dung cần thiết.

- **Phân loại yêu cầu** cũng giúp dự đoán thay đổi yêu cầu tốt hơn.
  - Phân loại theo **thời gian**: Ổn định và Biến động (theo thời gian).
  - Phân loại theo **không gian**: Chung và Đặc thù (theo từng biến thể).

- Khi đã phân loại yêu cầu xong, thực hiện **xếp hạng** các yêu cầu theo tính **Ổn định** và tính **Chung**.
  - **Tính năng ổn định** thường là tính năng xuất hiện trong mọi phiên bản hệ thống.
  - **Yêu cầu chức năng thường ổn định hơn** yêu cầu phi chức năng.
  - **Cần xem xét kỹ lưỡng** trong trường hợp có nhiều lựa chọn.

### 5.3. Quản lý truy vết yêu cầu

#### 5.3.1. Khả năng truy vết và Liên kết truy vết

- **Khả năng truy vết** (tiếng Anh: Traceability) là khả năng xác định được "lịch sử", nguồn gốc của một đối tượng cụ thể, và mối quan hệ giữa đối tượng ấy và các đối tượng khác.
  - VD: Trong bài toán quản lý nguồn gốc nông sản, khả năng truy vết giúp xác định được nguồn gốc của một món hàng cụ thể, từ đâu đến đâu, qua bao nhiêu bước, ...

- Trong ngữ cảnh **quản lý truy vết yêu cầu**, một phần tử trong TLYC **có khả năng truy vết** được nếu ta có thể xác định:
  - **Lý do**: Tại sao phần tử này tồn tại?
  - **Nguồn gốc**: Từ phần tử nào mà có phần tử này?
  - **Đích đến**: Phần tử này dẫn đến phần tử nào?

- **Các kiểu liên kết truy vết**:
  - **Truy vết tiến và lùi**: Mối quan hệ trước-sau giữa các phần tử.
    - VD: Phần tử R1 dẫn đến R2 là truy vết tiến, còn R2 dẫn đến R1 là truy vết lùi.
  - **Truy vết dọc và ngang**: Mối quan hệ giữa các tầng trừu tượng hóa.
    - VD: Phần tử R1 nối đến R2 ở cùng tầng "Kiến trúc hệ thống" là truy vết ngang, còn nối đến R3 ở tầng "Mã nguồn".

- **Các loại liên kết truy vết**:
  - **Liên kết phụ thuộc** (tiếng Anh: Dependency link): Là kiểu liên kết truy vết chung nhất.
    - **Liên kết liên phiên bản** (tiếng Anh: Inter-version link): Liên kết giữa các phiên bản khác nhau của hệ thống theo không gian/thời gian.
      - **Liên kết biến thể**: VD: A2 mở rộng A1.
      - **Liên kết sửa đổi**: VD: A2 sửa đổi A1.
    - **Liên kết cùng phiên bản** (tiếng Anh: Intra-version link): Liên kết trong cùng một phiên bản của hệ thống.
      - **Liên kết sử dụng**: VD: A2 sử dụng A1 thì việc sửa đổi A1 có khả năng ảnh hưởng xấu đến A2.
      - **Liên kết dẫn xuất**: VD: A2 là dẫn xuất từ A1 thì A1 thỏa mãn điều kiện nào đó thì mới xây dựng được A2.

#### 5.3.2. Quy trình Quản lý truy vết yêu cầu

- Quy trình **Quản lý truy vết yêu cầu** gồm **4 bước** chính, có tính lặp lại:
  - **Bước 1**: Định nghĩa **chính sách truy vết**.
    - Xác định sự cân bằng giữa chi phí và lợi ích từ quản lý truy vết; xây dựng phạm vi, độ chi tiết, độ chính xác; phân công trách nhiệm.
    - Bước này giúp duy trì sự **nhất quán** trong quy trình.
  - **Bước 2**: **Tạo lập** các liên kết truy vết.
    - Sử dụng công cụ tự động hóa; tích hợp liên kết từ giai đoạn đầu; khắc phục đa dạng nguồn và định dạng.
    - Việc ứng dụng các công cụ sẽ giúp giảm chi phí và thời gian thực hiện.
    - Bước này giúp **hình thành cơ sở của việc khai thác các liên kết truy vết** ở Bước 3.
  - **Bước 3**: **Khai thác** các liên kết truy vết
    - Phân tích tiến hóa, kiểm tra thay đổi, theo dõi lỗi.
    - Bước này giúp **nâng cao chất lượng; giảm chi phí và thời gian truy ngược thông tin**.
  - **Bước 4**: **Bảo trì** các liên kết truy vết.
    - Cập nhật liên kết theo thay đổi; xử lý các trường hợp đặc biệt.
    - Bước này giúp đảm bảo **truy xuất nguồn gốc và tính phù hợp** của các thành phần trong dự án.

#### 5.3.3. Kỹ thuật hỗ trợ quản lý truy vết yêu cầu

- TODO: Nội dung phần này tạm thời chưa được cập nhật đầy đủ.

- Có thể kể đến một số kỹ thuật và công cụ như:
  - Đồ thị và ma trận truy vết.
  - Biểu đồ tính năng.
  - Cơ sở dữ liệu truy vết.

### 5.4. Quản lý thay đổi yêu cầu

- TODO: Nội dung phần này tạm thời chưa được cập nhật đầy đủ.

- Quy trình **Quản lý thay đổi yêu cầu** gồm **3 bước** chính, có tính lặp lại:
  - Khởi tạo thay đổi.
  - Đánh giá và xếp thứ tự ưu tiên cho thay đổi.
  - Thống nhất thay đổi.

### 5.5. Giám sát yêu cầu trong môi trường thực thi

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

## 6. Kỹ nghệ yêu cầu hướng mục tiêu

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

## 7. Sơ lược về 6 loại mô hình KAOS

### 7.1. Mô hình mục tiêu

- **Mô hình mục tiêu** là trung tâm của KAOS, được biểu diễn dưới dạng **biểu đồ mục tiêu** (tiếng Anh: Goal diagram).

- Biểu đồ mục tiêu gồm các nút và liên kết:
  - Các loại nút:
    - **Nút mục tiêu** : Biểu diễn một mục tiêu cần đạt được. Biểu diễn bằng hình bình hành lệch sang bên phải.
    - **Thuộc tính miền**: Biểu diễn thuộc tính miền (của TGVD). Biểu diễn bằng hình thang cân hoặc hình ngôi nhà (chữ nhật có "mái" tam giác ở trên).
    - Các loại nút khác (Sẽ được nói chi tiết ở những phần tương ứng):
      - **Trở ngại**: Biểu diễn một trở ngại cần vượt qua để đạt được mục tiêu. Biểu diễn bằng hình bình hành lệch sang bên trái.
      - **Tác tử**: Biểu diễn một tác tử trong hệ thống. Biểu diễn bằng hình lục giác bẹt (hai cạnh trên dưới dài ra).
      - **Đối tượng**: Biểu diễn một đối tượng trong hệ thống. Biểu diễn bằng hình chữ nhật.
      - **Thao tác**: Biểu diễn một thao tác cần thực hiện để đạt được mục tiêu. Biểu diễn bằng hình elip.
      - **Hành vi**: Biểu diễn một hành vi cần thực hiện để đạt được mục tiêu. Biểu diễn bằng biểu đồ máy trạng thái hoặc biểu đồ hoạt động.
  - Các loại liên kết:
    - **Liên kết làm mịn** (tiếng Anh: Refinement link): Thể hiện sự phân rã từ một mục tiêu lớn thành các mục tiêu con.
      - **Làm mịn AND**: Các nút con nối với nút cha thông qua một ô tròn chung - thể hiện mọi mục tiêu con phải được thỏa mãn thì mục tiêu cha mới thỏa mãn.
      - **Làm mịn OR**: Mỗi nút con nối lên một ô tròn, ô tròn nối trực tiếp với nút cha - thể hiện chỉ cần một trong các mục tiêu con được thỏa mãn thì mục tiêu cha được thỏa mãn.
      - Các ô tròn ban đầu có màu trắng, nhưng khi việc làm mịn được coi là **đầy đủ**, ô tròn sẽ được tô màu.
    - **Liên kết mâu thuẫn** (tiếng Anh: Conflict link): Thể hiện mâu thuẫn có thể xảy ra giữa các mục tiêu. Được biểu diễn bằng một đường thẳng nối hai mục tiêu, có tia sét ở giữa.
    - **Liên kết giao diện** (tiếng Anh: Interface link): Thể hiện sự liên kết giữa mục tiêu với các mô hình khác (Trở ngại - cản trở, Tác tử - chịu trách nhiệm, Đối tượng - quan tâm đến, Thao tác - thao tác hóa, Hành vi - bao phủ).

### 7.2. Mô hình trở ngại

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

### 7.3. Mô hình tác tử/trách nhiệm

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

### 7.4. Mô hình đối tượng

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

### 7.5. Mô hình thao tác

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

### 7.6. Mô hình hành vi

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

## 8. Tích hợp đa góc nhìn hệ thống

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

## 9. Phương pháp bán hình thức trong Kỹ nghệ yêu cầu

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

## 10. Phương pháp hình thức trong Kỹ nghệ yêu cầu

- TODO: Nội dung phần này tạm thời chưa được cập nhật.

## 11. Tổng kết

- TODO: Nội dung phần này tạm thời chưa được cập nhật.