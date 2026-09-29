📓 Prompt Log (nhật ký hỏi – đáp với AI)
Học viên: “Giải thích vì sao dùng == lại nguy hiểm trong hệ thống đăng nhập?”
AI: Giải thích về cơ chế Type Coercion, đưa ví dụ 0 == "0" trả về true, dẫn đến lỗ hổng bảo mật.

Học viên: “Falsy values và Truthy values là gì?”
AI: Trình bày danh sách các giá trị Falsy (0, "", null, undefined, NaN, false) và giải thích Truthy là mọi giá trị khác.

Học viên: “Có thể rút gọn khối if-else lồng nhau không?”
AI: Đề xuất dùng else if hoặc toán tử logic ngắn gọn (&&, ||) để làm phẳng luồng điều kiện.

Học viên: “Nếu nhập mật khẩu là [] (mảng rỗng) thì tại sao == báo đúng còn === báo sai?”
AI: Giải thích do == ép kiểu [] thành chuỗi rỗng "", rồi so sánh với "0" hoặc 0 dẫn đến kết quả sai lệch. === thì kiểm tra cả kiểu dữ liệu nên không bị nhầm.

Học viên: “Tại sao biểu thức isVip && hasVoucher lại nhanh hơn if-else lồng nhau?”
AI: Giải thích cơ chế short-circuit evaluation: nếu isVip là false thì JS bỏ qua vế sau, không cần kiểm tra thêm, giúp code gọn và hiệu quả.
