This project is just a demo how to use git

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