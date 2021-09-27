# Examination

# Exam 01: single API 
Sử dụng cucumber để tạo tất cả các test case cho 1 API: `POST /team/{pattern}`

# Exam 02: flow APIs
Sử dụng cucumber để tạo test case cho kịch bản sau

| No    | Step                      | Expected result                                           |
| ----- | ------------------------- | --------------------------------------------------------- | 
| 1     | Get danh sách các cầu thủ | Response trả về kết quả 22 cầu thủ                        |
| 2     | Tạo team                  | Response trả về 11 cầu thủ với đội hình DEFAULT là 442    | 
| 3     | Thay người hợp lệ 5 lần   | Kết quả trả về đội hình hiện tại và lịch sử thay người    | 
| 4     | Kết thúc trận đấu         | Không có cầu thủ nào đang chơi                            |

Yêu cầu:
- Cần xác định rõ các thông tin nào có thể fix và có thể thay đổi. 
- Các thông tin data có thể thay đổi không được hardcode trong file java.