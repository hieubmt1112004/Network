Mô hình OSI gồm 7 phân lớp như hình

![image](https://github.com/hieubmt1112004/Network/assets/125638408/bf361d22-8627-4929-b56a-c611536d56dd)



Phương thức giao tiếp TCP/IP chính là ngôn ngữ mà máy tính giao tiếp với nhau thông qua 1 ngôn ngữ chung. ví dụ : IPv4, IPv6

Những lợi ích của mô hình OSI : 
  + Giảm thiểu độ phức tạp của một mô hình mạng
  + Chia nhỏ mô hình để chúng ta có thể phân tích từng phân lớp trong mô hình OSI

Khi một mô hình mạng không kết nối được ( bị lỗi ) dựa vào mô hình OSI ta có thể kiểm tra bằng những cách sau : 
 + Tầng vật lí : là đường đi của các tín hiệu điện khi vào 1 thiết bị dưới dạng bit (1/0)
 + Tầng data link : Ở tầng này liên quan tới card mạng và địa chỉ Mac 
 + Tầng Network : Tầng này liên quan trực tiếp tới IP ( định tuyến ) 
 + Tầng Transport : là tầng giao thức chuyển đổi ( TCP / UDP ) 
 + Tầng session : Tầng phiên ( mở 1 phiên giao tiếp giữa 2 máy tính )
 + Tầng presentation: là tầng mà để giải mã / mã hóa dữ liệu . nén / giải nén
 + Tầng application: Tầng giao diện ( là tầng mà người dùng truy cập trực tiếp .vd web ( http/https) )
    

