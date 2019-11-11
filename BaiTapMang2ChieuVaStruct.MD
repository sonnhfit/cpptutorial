Bài tập mảng 2 chiều

Bài 1: Viết CT nhập vào một ma trận vuông, tính và in ra màn hình tổng của đường chéo chính của ma trận đó.
Ví dụ
```
1	2	3	4
2	8	6	4
-1	4	-9	1
5	3	2	0
```
Tổng là 1+8+(-9)+0 = 0

Bài 2: Viết CT nhập vào một ma trận, tìm và in ra số lớn nhất trên mỗi dòng của ma trận.

Bài 3: Viết CT nhập vào 1 mảng 2 chiều, sau đó xóa 1 dòng và 1 cột của mảng 2 chiều đó theo yêu cầu của người dùng.

Bài 4: Viết CT nhập vào 2 ma trận A và B. Tính và tin ra ma trận C=A + B

Bài 5: Viết CT nhập vào 2 ma trận A và B. Tính và in ra ma trận C=A x B. Nếu A và B không thể nhân với nhau thì hãy thông báo ra màn hình.
 

Bài tập struct
Bài 1 : Tạo struct về 1 tài khoản bao gồm tên đăng nhập và mật khẩu. Viết CT tạo ra 1 tài khoản từ struct đó (tên đăng nhập và mật khẩu do bạn định sẵn) sau đó yêu cầu người dùng nhập tên đăng nhập và mật khẩu rồi so sánh với thông tin tài khoản bạn tạo ra rồi thông bao kết quả cho người dùng.

Bài 2 : Tạo struct về 1 con người, bao gồm họ tên, tuổi, chiều cao, cân nặng. Nhập thông tin cho một người như vậy rồi in ra họ tên và tuổi của họ ra màn hình. Nếu chiều cao dưới 120 (tính theo centimet) và trên 17 tuổi thì in ra họ là người lùn.

Bài 3 : Viết CT nhập vào 1 danh sách các mẫu điện thoại, mỗi mẫu bao gồm : tên hãng (VD : nokia, samsung, LG, …), đời máy, ngày tháng sản xuất (có thể dùng kiểu xâu), giá bán (tính theo USD). In ra màn hình thông tin về điện thoại đắt giá nhất và rẻ nhất.

Bài 4 : Nhập vào một danh sách hóa của một của hàng. Mỗi loại hàng hóa bao gốm : tên, hãng sản xuất, giá. In ra danh sách đó và tổng giá trị của tất cả các mặt hàng.

Bài 5 : Tạo 1 struct về hình chữ nhật bao gồm chiều rộng, chiều cao, chu vi, diện tích. Viết CT nhập vào chiều rộng và chiều cao của nhiều hình chữ nhật, tính chu vi và diện tích cho các hình chữ nhật đó sau đó in ra màn hình.

Bài 6 : Tạo 1 struct về phân số bao gồm tử số và mẫu số, viết CT nhập vào 2 phân số a và b, tính và in ra màn hình 2 phân số (tối giản 2 phân số này nếu có thể):
	C = a + b; D = a x b ;

Từ bài 7-11 : Nhập vào một danh sách sinh viên, mỗi sinh viên bao gồm mã sinh viên, họ tên, giới tính, năm sinh, điểm trung bình các môn.
Bài 7 : Sắp xếp và in ra danh sách sinh viên theo năm sinh tăng dần. 

Bài 8 : Thêm 1 sinh viên vào danh sách sao cho vẫn đảm bảo tính tăng dần của năm sinh như ở bài 7.

Bài 9 : Nhập vào 1 điểm số, in ra danh sách sinh viên có điểm thấp hơn điểm vừa nhập vào.

Bài 10 : Tạo ra 2 danh sách gồm sinh viên nam riêng và nữ riêng từ danh sách đã cho (2 mảng mới).

Bài 11 (*) : Ghép đôi cho các sinh viên nam và nữ, yêu cầu là trong mỗi cặp thì sinh viên nam phải nhiều tuổi hơn hoặc bằng tuối sinh viên nữ (không cho lái máy bay :D). In ra danh sách các đôi (các sinh viên còn lại không có đôi có thể bỏ qua).


Bài 12 (*): Tạo ra 2 struct là điểm thi và sinh viên, điểm thi bao gồm điểm trên lớp, điểm thi kết thúc học phần, điểm trung bình theo số và theo chữ. Struct sinh viên bao gồm mã sv, họ tên, và điểm thi (là cái struct điểm thi kia). Viết CT nhập thông tin và điểm thi của nhiều sinh viên, tính điểm trung bình cho họ và in ra màn hình.

Bài 13 (*): Tạo ra 3 struct về các thành phần của một chiếc máy tính bao gồm :
Màn hình :
-	Bật hay tắt
-	Độ sáng màn hình
CPU :
-	Tên CPU
-	Dung lượng cache (tính theo MB)
Mainboard :
-	Tên main
-	CPU được sử dụng (chính là struct của CPU kia)
Sau đó tạo 1 struct về máy tính bao gồm màn hình, và mainboard. Viết CT nhập thông tin cho chiếc máy tính đo (yêu cầu nhập thông tin cho cả CPU). Sau đó in các thông tin đó ra màn hình sao cho đẹp mắt nhất :x

Bài 14 (*): Viết CT nhập vào 1 danh sách các phim đang chiếu rạp, bao gồm : tên phim, tên đạo diễn, thời gian của phim (tính theo phút), giờ chiếu phim (tính theo giờ). In ra danh sách dài nhất trong đó các phim  có thể xem liền nhau (không bị trùng giờ chiếu, xem phim này xong chạy sang phòng khác xem tiếp :D).
Ví dụ : Phim A dài 90 phút chiều lúc 12h, phim B dài 120 phút chiếu lúc 1h, phim C dài 100 phút chiếu lúc 2h. Như vậy bạn có thể xem xong phim A đến 1h30 rùi chờ đến 2h xem phim C (vì xem phim A xong thì phim B chiếu được 30p rùi còn xem làm gì nữa)

Bài 15 (*): Nhập vào 1 danh sách n thí sinh thi tuyển vào ngành VIP của Haui, mỗi thí sinh bao gồm tên, mã dự thi và điểm thi. Nhập tiếp chỉ tiêu của ngành này và in ra điểm chuẩn của ngành đó. Điểm chuẩn phải đảm bảo sao cho có ít nhất 1 thí sinh đạt điểm đó và số lượng thí sinh đỗ vào ngành VIP này phải bằng hoặc nhỏ hơn càng gần càng tốt chỉ tiêu của ngành.
Chẳng hạn có 10 thí sinh dự thi bao gồm các điểm :
29, 25, 25, 27, 28, 28.5, 29, 20, 21, 22 
Mà chỉ tiêu là 5 người thì điểm chuẩn sẽ là 27 vì sẽ có đúng 5 người trúng tuyển.
Còn nếu chỉ tiêu là 6 người thì điểm chuẩn vẫn sẽ là 27 vì có 1 thí sinh đạt 27 điểm và sẽ có 5 người trúng tuyển (nhỏ hơn chỉ tiêu).
