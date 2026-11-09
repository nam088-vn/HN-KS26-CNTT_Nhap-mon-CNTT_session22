**Bài 3 : Sử dụng AI an toàn khi xử lý lỗi phần mềm**

### 1\. Báo cáo phân tích theo mô hình IPO

* Input : Câu lệnh sửa lỗi "Path not found" do AI tạo ra   
* Process :

  * Dùng Google search kèm toán tử site:docs.python.org hoặc site:stackoverflow.com cùng với tên câu lệnh để đối chiếu với tài liệu chính thức và diễn đàn uy tín.

  * Tra cứu chính xác cú pháp xem câu lệnh đó dành cho hệ điều hành nào

* Output : Kết luận xác nhận câu lệnh có an toàn hay không, có tác dụng phụ làm thay đổi biến môi trường hệ thống hay không trước khi thực thi.

### 2\. Prompt "hỏi ngược lại" AI để kiểm tra độ an toàn

"Trước khi tôi chạy lệnh này, hãy giải thích chi tiết từng tham số trong lệnh có tác dụng gì. Lệnh này dành cho hệ điều hành nào, có làm thay đổi hay xóa vĩnh viễn file hệ thống nào không, và có cách nào an toàn hơn để sửa lỗi Path not found mà không cần can thiệp sâu vào hệ thống không?"  
