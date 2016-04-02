# Sử dụng Wireshark cơ bản

## Wireshark là gì ?
Wireshark là công cụ để phân tích các gói tin lưu thông trên mạng.

## Download và cài đặt
Wireshark được tải về từ trang 

https://www.wireshark.org/download.html

## Cách sử dụng 
- Khởi động Wireshark và chọn Interface cần bắt gói tin

<img src="http://i.imgur.com/5MtZD5B.png">

- Giao diện làm việc chính của chương trình : 

<img src="http://i.imgur.com/iSjBCxc.png">

- Một số chức năng tiêu biểu: 

1. Bắt đầu 1 phiên bắt gói tin
2. Dừng việc bắt gói tin
3. Bắt đầu lại 
4. Chọn Interface
5. Hiển thị các gói tin bắt được trôi theo thời gian
6. Phân biệt các nhóm gói tin bằng màu sắc
7. Thanh lọc các gói tin theo điều kiện 
8. Chi tiết về gói tin 
9. Gói tin dưới dạng mã hóa
 
- Bắt một gói tin 

Click Start để bắt đầu việc bắt gói tin 
Sau khi bắt được một lượng gói tin, click vào Stop
Click đúp vào một gói tin và đọc các thông tin trong đó  

- Lọc gói tin 

Nhập điều kiện lọc vào ô Filter hoặc cũng có thể chuột phải vào một giá trị liên quan của một gói tin và chọn cách thức lọc.

<img src="http://i.imgur.com/xPWqMzI.png">

Để xem cú pháp điều kiện lọc, chọn Expression...

<img src="http://i.imgur.com/HtHYHLE.png">

Ví dụ lọc các gói tin TCP và có ip là 192.168.0.6 và không có ip nguồn là 52.23.149.18

<img src="http://i.imgur.com/hA8vOxN.png">

## Một số công cụ sử dụng dòng lệnh 

- tcpdump, tshark, wireshark: bất gói tin trên mạng
- wireshark-filter : lọc dữ liệu 
- capinfos : thông tin về file bắt được
- editcap : chỉnh sửa và/hoặc biên dịch định dạng file bắt được
- mergecap : trộn 2 hoặc nhiều file gói tin thành một 

## Tham khảo 

https://www.wireshark.org/docs/wsug_html/

