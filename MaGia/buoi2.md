
-- Bài 1: Tìm số lớn nhất trong danh sách các số [30, 23, 3, 49,  59, 10, 22]
Begin


End
-- Bài 2
-- Bài 3
-- Bài 4
-- Bài 5
-- Bài 6
-- Bài 7
-- Bài 8
-- Bài 9
-- Bài 10


-- Bài 16: Tìm phần tử lớn thứ hai trong danh sách [3, 5, 7, 2, 8, 1]
-- Đầu vào 1 danh sách  [3, 5, 7, 2, 8, 1]
-- Đầu ra: phần từ lớn thứ 2 -> nhìn vào đầu vào thì ta sẽ có 7 là kết quả 
Begin 
    Nhập danh sách [3, 5, 7, 2, 8, 1]
    Đặt max1 = 3 (phần tử đầu tiên)
    Đặt max2 = null
    So sánh 5 với max1
        5 lớn hơn max1 thì max2 = 3 và max1 = 5
    So sánh 7 với max1 và max2
        7 lớn hơn max1 nên max2 = 5 và max1 = 7
    So sánh 2 với max1 và max2
        2 bé hơn nên giữ nguyên max1 và max2
    So sánh 8 với max1 và max2
        8 lớn hơn nên max2 = 7 và max1 = 8
    So sánh 1 với max1
        1 bé hơn nên giữ nguyên max1 và max2
    In ra max2
End
        
    
-- Bài 10: Đảo ngược danh sách [3, 5, 7, 2, 8, 1]
-- Đầu vào: [3, 5, 7, 2, 8, 1]
-- Đầu ra: [1, 8, 2, 7, 5, 3]
Begin
    Nhập 1 danh sách [3, 5, 7, 2, 8, 1]
    Đặt 1 danh sách mới là rỗng []
    (Duyệt ngược danh sách đầu vào từ điểm cuối đến điểm đầu - từ phải qua trái)
    Thêm 1 vào danh sách mới [1]
    Thêm 8 vào danh sách mới [1, 8]
    Thêm 2 vào danh sách mới [1, 8, 2]
    Thêm 7 vào danh sách mới [1, 8, 2, 7]
    Thêm 5 vào danh sách mới [1, 8, 2, 7, 5]
    Thêm 3 vào danh sách mới [1, 8, 2, 7, 5, 3]
    In ra danh sách mới [1, 8, 2, 7, 5, 3]
End

-- Bài 6: Kiểm tra xem một số có trong danh sách không [3, 5, 7, 2, 8, 1]
-- Đầu vào: [3, 5, 7, 2, 8, 1] và 10
-- Đầu ra: True
Begin
    Nhập vào danh sách [3, 5, 7, 2, 8, 1]
    Nhập vào 1 số cần kiểm tra 5
    Đặt biến tìm thấy là false (Sai)
    So sánh 3 với 5, không khớp
    So sánh 5 với 5, khới -> biến tìm thấy = true (Đúng)
    In ra biến tìm thấy (True)
End
-- rút gọn lại code
Begin
    Nhập vào danh sách [3, 5, 7, 2, 8, 1]
    Nhập vào 1 số cần kiểm tra 5
    Đặt biến tìm thấy là false (Sai)
    Duyệt qua danh sách
        So sánh giá trị trong danh sách với số cần kiểm tra
            Nếu khớp thì biến tìm thấy = true (Đúng) -> break
    In ra biến tìm thấy (True)
End


-- Bài 7: Đếm số lần xuất hiện của một số trong danh sách [3, 5, 7, 2, 8, 1, 7]
-- Đầu vào: [3, 5, 7, 2, 8, 1, 7] và 7
-- Đầu ra: 2
Begin
    Nhập vào danh sách [3, 5, 7, 2, 8, 1, 7]
    Nhập vào 1 số cần kiểm tra 7
    Đặt biến đếm là 0
    So sánh 3 với 7, không khớp
    So sánh 5 với 7, không khớp
    So sánh 7 với 7, khớp -> biến đếm = 1
    So sánh 2 với 7, không khớp
    So sánh 8 với 7, không khớp
    So sánh 1 với 7, không khớp
    So sánh 7 với 7, khớp -> biến đếm = 2
    In ra biến đếm (2)
End
-- rút gọn lại code
Begin
    Nhập vào danh sách [3, 5, 7, 2, 8, 1, 7]
    Nhập vào 1 số cần kiểm tra 7
    Đặt biến đếm là 0
    Duyệt danh sách
        So sánh giá trị trong danh sách với số cần kiểm tra
            Nếu khớp thì biến đếm = biến đếm + 1
    In ra biến đếm (2)
End
