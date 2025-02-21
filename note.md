# Terms

Repository (Repo)
Branch
Conflict
Local
Remote

# Commands

- git init : tạo một kho lưu trữ Git
- git status : cho thấy đc trạng thái của dự án 
- git add (. || tên file) :  Chuẩn bị các thay đổi để commit.
- git reset : Hủy các thay đổi hoặc hủy commit
- git commit :  Tạo một commit mới với các thay đổi
"git commit -m 'first commit'"
- git log :Hiển thị lịch sử commit của kho lưu trữ.
- git log --oneline :Hiển thị lịch sử commit một cách ngắn gọn
- git checkout "branch name":sang một nhánh đã tồn tại.
- git checkout -b "branch name": Tạo nhánh mới 
- git merge "branch name": Kết hợp
- git branch -d "branch name": Xóa nhánh đã được hợp nhất.

- git push:Đẩy các commit từ nhánh hiện tại lên kho lưu trữ
- git remote add origin "repo url":Thêm một remote repository với tên origin
- git push origin "branch name" : Đẩy các commit từ một nhánh cụ thể lên remote repository.
- git clone "repo url":Sao chép một remote repository về máy local.
- git fetch origin: Tải về các thay đổi từ remote repository nhưng không hợp nhất vào nhánh hiện tại.
- git checkout -b "branch name'  origin/"branch name": ạo một nhánh mới từ một nhánh trên remote repository và chuyển sang nhánh đó.