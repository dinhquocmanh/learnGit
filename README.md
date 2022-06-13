This project is just a demo how to use git

from youtube link: https://www.youtube.com/playlist?list=PLkY6Xj8Sg8-viFVtaVps_h_Emi2wQyE7q

git init : Khởi tạo project mới sử dụng git
git status: Kiểm tra các thay đổi trong thư mục hiện tại
git add: add file  changed vao commit
git commit -m 'message' : commit

git log: hien len danh sach cac commit gan day
git show {logid}: show len xem commit nay thay doi chi tiet nhung gi
git diff: xem thay doi cua file da duoc modified (different)

Thuật ngữ:
- Working directory: thư mục đang làm việc 
- Staging area: file màu xanh khi gõ git status được gọi là 
đang nằm trong staging area. Tức là file nào được git add vào
để commit mà chưa commit thì đang nằm trong staging area
- Git repository: nơi chứa một loạt các thay đổi của commit
khi gõ git log sẽ hiện ra

gitk: hien cua so gui de xem 
git checkout: giong nhu undo
git reset: gỡ file khỏi staging area (sau khi sử dụng git add)

Lam viec voi branch: todo 
git branch
git checkout -b <branch>
git checkout <branch>
git merge

git reset :todo
git revert: todo

// .gitignore
khong commit cac files trong git ignore

// git config --global credential.helper "cache --timeout=1800"
Sau 1800s (5h) se khong hoi thong tin dang nhap nua 