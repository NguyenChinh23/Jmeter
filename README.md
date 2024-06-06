Jmeter

Mục tiêu: Kiểm tra hiệu năng của trang web: https://www.wikipedia.org/

Kịch bản kiểm thử: Giả lập 100 người dùng truy cập trang web với thời gian tăng dần là 100 giây và chỉ thực hiện 1 lần truy cập.

Chạy kịch bản kiểm tra

1.	Nhấp vào nút Start để chạy kịch bản kiểm tra.
2.	Quan sát kết quả trong View Results Tree và Aggregate Report.

Phân tích kết quả

•	Nếu mọi thứ được cấu hình đúng, bạn sẽ thấy các kết quả kiểm tra mà không có lỗi 404.

•	Kết quả sẽ bao gồm các thông số như thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.

Kết quả kiểm tra
![anh1](https://github.com/NguyenChinh23/Jmeter/assets/119948744/c25f195b-a78f-4552-bb54-9415d63ac810)
![anh2](https://github.com/NguyenChinh23/Jmeter/assets/119948744/ae3a29da-8e26-4875-956a-0885e9ccbc8a)
View Results Tree:
![anh3](https://github.com/NguyenChinh23/Jmeter/assets/119948744/c39db7b7-610a-4a47-96d3-2066feffaf6b)
•	Tất cả các yêu cầu HTTP tới máy chủ Wikipedia đều thành công.

•	Các biểu tượng màu xanh lá cây chỉ ra rằng không có lỗi nào xảy ra 

Aggregate Report:
![anh4](https://github.com/NguyenChinh23/Jmeter/assets/119948744/56852def-e293-43ad-ab2c-127c64060098)
•	Số lượng mẫu (Samples): 110

•	Thời gian phản hồi trung bình (Average Response Time): 805 ms

•	Thời gian phản hồi trung vị (Median Response Time): 573 ms

•	Thời gian phản hồi 90% (90th Percentile Response Time): 1127 ms

•	Thời gian phản hồi 95% (95th Percentile Response Time): 2131 ms

•	Thời gian phản hồi 99% (99th Percentile Response Time): 4499 ms

•	Tỷ lệ lỗi: 0%

•	Throughput: 25 yêu cầu/phút

Kết luận:

Trang web có hiệu năng tốt với thời gian phản hồi nhanh và ổn định, phù hợp cho môi trường sản xuất.

