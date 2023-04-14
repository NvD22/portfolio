# portfolio
# Đưa website lên mạng với Git + Github page

# Chuẩn bị 
1. Cài đặt Git
2. Tạo tài khoản Github (Nếu chưa có)

# Up dự án lên mạng
1. Đưa dự án vào VScode

2. chạy terminal terminal khởi tạo một local repo (Có thể bị lỗi)
-> git init 

 - khắc phục lỗi: Vào Edit system environment variable -> environment  variable -> path (User variable ...) -> New -> Copy (C:\Program Files\Git\bin)\
 - Sau khi khắc phục lỗi thì thực hiện các bước tiếp theo 

3. lưu code dự án vào local repo tại git
-> git add .
-> git commit -m 'first commit'

4. Tạo Repository trên Github
-> Truy cập link : https://github.com/New
-> đặt tên cho Repository : portfolio 
-> Create repository
-> coppy link của repository (https://github.com/NvD22/portfolio.git)

5. Đẩy dự án từ Git lên Github
-> git remote add portfolio https://github.com/NvD22/portfolio.git
-> git push portfolio master

6. Vào Github Pages
- Source -> master -> /(root) -> save 
