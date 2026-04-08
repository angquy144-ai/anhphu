padding: 0;
Xóa khoảng cách bên trong
Trình duyệt mặc định thường có padding → gây lệch layout
margin: 0;
Xóa khoảng cách bên ngoài
Nếu không xóa → web bị cách viền trắng xung quanh
Đây là lý do nhiều web luôn reset: 
margin:0;
padding:0;
background-color: #f4f4f4;
Màu nền toàn trang (xám rất nhạt)
Giúp:
Không bị chói như nền trắng
Nhìn “pro” hơn
2. PHẦN header (đầu trang)
header{
  background:#35424a;
  color:#ffffff;
  padding-top:30px;
  min-height:70px;
  border-bottom:#e8491d 3px solid;
}
👉 background: #35424a;
Màu nền xanh đậm
Thường dùng cho header vì:
Nhìn chuyên nghiệp
Tạo contrast với nội dung
color: #ffffff;
Màu chữ trắng
Áp dụng cho toàn bộ chữ bên trong header
👉 padding-top: 30px;
Khoảng cách phía trên (bên trong header)

📌 Tác dụng:

Đẩy chữ xuống → không dính sát mép trên
👉 min-height: 70px;
Chiều cao tối thiểu

📌 Quan trọng:

Nếu nội dung ít → vẫn giữ chiều cao 70px
Nếu nhiều → tự giãn ra

👉 Khác với height:

height: cố định → dễ bị tràn
min-height: linh hoạt hơn (tốt hơn
border-bottom: #e8491d 3px solid;

Gồm 3 phần:

Thành phần	Ý nghĩa
3px	độ dày
solid	kiểu viền
#e8491d	màu cam

📌 Tác dụng:

Tạo đường line dưới header
Làm điểm nhấn UI (rất hay dùng)
3. PHẦN footer (cuối trang)
footer{
  padding:20px;
  margin-top:20px;
  color:#ffffff;
  background-color:#e8491d;
  text-align: center;
}
 padding: 20px;
Khoảng cách bên trong (4 phía)
Giúp nội dung không bị sát viền
 margin-top: 20px;
Khoảng cách phía trên footer

📌 Tác dụng:

Tạo khoảng cách với phần nội dung phía trên
 color: #ffffff;
Chữ trắng (giống header)
 background-color: #e8491d;
Màu nền cam

📌 Đây là màu bạn đã dùng ở border header → tạo sự đồng bộ

 text-align: center;
Căn giữa chữ
