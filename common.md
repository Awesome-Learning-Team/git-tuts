#10 CÂU LỆNH GIT THÔNG DỤNG
###1. Config:
-Sử dụng để config username, email
-Các tùy chọn: --global, --system, --local
-Command:
``` 
$ git config --global user.name (config user name)
$ git config --global user.email (config email)
$ git config --list (kiểm tra thông tin đã config)
```
###2. Clone:
-Dùng để copy 1 project từ Local Respository đến thư mục khác hoặc từ Server về máy tính
-Command:
```
$ git clone https/ssh
```
###3. Checkout:
-Dùng để checkout một nhánh
-Command: 
```
$ git checkout <name_branch> (checkout một nhánh)
$ git checkout -b <name_branch> (Tạo một nhánh mới và check out trên nhánh đó)
```
###4. Add:
- Cập nhật những thay đổi source code lên Staging Area.
- Command:
```
$ git add . (cập nhật hết các file)
$ git add .<tên đuôi> (cập nhật các file với đuôi file xác định)
$ git add <name_file_1> <name_file_2> ... <name_file_n> (cập nhật các files xác định dựa vào tên file)
```
###5. Commit:
- Sử dụng sau khi dùng git add để đẩy thay đổi lên Local Repository:
- Command: 
```
$ git commit -m <message>
```
###6. Push:
- Cập nhật những thay đổi lên Server:
```
$ git push origin <name_branch>
```
###7. Fetch:
- dùng để lấy source code từ server về Local Repository:
```
$ git fetch <name_branch>
```
###8. Pull:
- Lấy source code từ server về Local Repository và merge với code hiện tại trên máy:
- Command:
```
$ git pull <name_repo> <name_branch>
```
###9. Log:
- Confirm lịch sử update:
- Command:
```
$ git log --oneline (hiển thị trên 1 dòng)
$ git log -p <name_file_1> (hiển thị những thay đổi của 1 file)
$ git log -n <commits_number> (hạn chế số lượng commit hiển thị)
```
###10. Checkout -- (xóa thay đổi)
- Dùng để xóa thay đổi trên 1 nhánh/directory
- Command:
```
$ git checkout -- <name_file>
$ git checkout -- <name_directory>
$ git checkout -- .
```


