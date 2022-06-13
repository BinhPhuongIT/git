<!-- Cài đặt Git -->
### Trên Linux
### Chạy lệnh ở terminal với Ubuntu
```sh
sudo apt install git-all
```

###Với CentOS
```sh
sudo yum install git
```

### Với macOS
```sh
brew install git
```

### Trên Windows
https://git-scm.com/download/win


###Lệnh đầu tiên là hãy kiểm tra Version của Git đang dùng:
```sh
git --version
```
### Hiện thị các lệnh Git bằng cách gõ
```sh
git --help
```

### Cấu hình Git
# /etc/gitconfig : tham số khai báo trong file này có hiệu lực cho mọi user, dự án. Lệnh tương tác thiết lập với tham số --system
# ~/.gitconfig hoặc ~/.config/git/config (Windows: C:\Users\$USER\.gitconfig) - thiết lập có hiệu lực với User hiện tại của hệ thống, thực hiện với tham số --global
# .git/config cấu hình lưu ở chính thư mục .Git của dự án (repository), chỉ có tác dụng cho Repository này.

### Danh sách các thiết lập cấu hình
```sh
git config --list
```
### Thiết lập tên
```sh
git config --global user.name "Tên của Bạn"
```
### Thiết lập email
```sh
git config --global user.email emailcuaban@domain.com
```