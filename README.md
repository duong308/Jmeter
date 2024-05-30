# Jmeter

1.Mục tiêu:

-Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://phenikaa-uni.edu.vn/vi.

-Chạy kịch bản kiểm tra và ghi lại kết quả.

-Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.

-Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

2.Kịch bản kiểm tra:

-Thread Group:

Số lượng thread: 100

Thời gian chạy: 60 giây

Ramp-up period: 10 giây

-HTTP Request:

URL: https://phenikaa-uni.edu.vn/vi

Method: GET

Content encoding: UTF-8

-Listeners:

View Results Tree

Aggregate Report

3.Kết quả kiểm tra:
