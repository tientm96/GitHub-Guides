GIT GUIDES 2
------------------------------------------------------------------------------------------------
Guides Github: https://guides.github.com/
Command line guide***: https://guides.github.com/introduction/git-handbook/

Video guide git - "Git & GitHub: GitHub Workflow": 
		    https://www.youtube.com/watch?v=47E-jcuQz5c&list=PLg7s6cbtAD17Gw5u8644bgKhgRLiJXdX4&index=0

------------------------------------------------------------------------------------------------


video tôi đi code dạo: Từ Gà Đến Pro Git và Github trong 60 phút
https://www.youtube.com/watch?v=hXM_vbEuIrE

***Dùng gitbash:
- Tạo New repository trên github. Copy đường link.

- Tại thư mục muốn chứa "thư mục lớn" của git, kích chuột phải chọn Git bash here để khởi động GitBash theo đường dẫn này.

- Code "git clone linkkkkk", Gitbash sẽ tự clone git về local. 

- "exit" để thoát của gitbash hiện tại (gitbash hiện tại đang ở uri chứa cả "thư mục lớn")

 

- Đưa dữ liệu cần up lên git vào thư mục local vừa clone về, và tiến hành push lên lại git như sau:
+ Ngay tại bên trong thư mục local đó, sau khi copied tất cả file qua, mở lại Gitbash here (uri == các file con trong thư mục lớn).
+ "git add ." để add nhiều file 1 lần.
- "git commit -m "first commit"" (dòng này copied từ trang vừa tạo xong New repository trên github)

- "git push" để push lên server (nhập pass nếu có yêu cầu)
- Lên server github, kiểm tra lại thì đã up lên đc.


--------------------------------------------------------------------------------------
- Sửa nội dung của file đã được up lên rồi:
+ Sửa xong mở gitbash tại đó (y như ở trên).
+ "git add ."
+ "git commit -m "sua lan hai""  (để xác nhận và có tiêu đề cho lần sửa)
+ "git push"
+ Lên server kiểm tra.
