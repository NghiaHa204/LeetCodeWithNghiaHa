📘 HƯỚNG DẪN QUY TRÌNH UP BÀI LÊN REPO
1️⃣ Kiểm tra bài tập hàng ngày
Thời gian giao task: Mỗi ngày, admin sẽ cập nhật bài tập mới vào file TASKS.md trước 22:00.
Nơi xem bài tập: File TASKS.md trong repo GitHub (thường nằm ở thư mục gốc của repo).
Công việc của bạn:
Vào repo lúc 22:00 để xem bài tập cho ngày hôm sau.
Nếu sau 22:00 mà TASKS.md chưa được cập nhật, vui lòng báo ngay cho Admin (Nghĩa Hà) vì tôi có thể quên =))))) .
2️⃣ Làm bài tập theo yêu cầu
Lấy bài tập: Vào file TASKS.md, xem danh sách bài tập cần làm.

Phân chia bài tập: Mỗi bài tập sẽ có tên, deadline và file yêu cầu. Ví dụ:

Bài tập: Two Sum
Nộp file: arrays/two_sum.py
Làm bài tập trên máy của bạn:

Giải bài tập trên máy cá nhân.
Đặt tên file và lưu bài tập vào thư mục phù hợp (ví dụ arrays/, linked_lists/, binary_trees/).

3️⃣ Cách nộp bài tập lên GitHub
Kiểm tra repo có thay đổi gì không:

git pull origin main

Tạo file bài tập và viết code của bạn:

Tạo file bài tập theo đúng cấu trúc thư mục (ví dụ: arrays/two_sum.py).
Viết code cho bài tập.

Thêm bài tập vào repo:
vd: git add arrays/two_sum.py

Commit bài tập với nội dung rõ ràng:
vd: git commit -m "Add solution for Two Sum"

Đẩy bài tập lên GitHub:
git push origin main

5️⃣ Cách cập nhật trạng thái bài tập trong TASKS.md
Mở file TASKS.md trong repo.
Tìm đến phần Trạng thái của từng thành viên.
Đổi trạng thái bài tập của bạn từ 🔲 Chưa nộp thành ✅ Hoàn thành.

Lưu và đẩy file TASKS.md lên GitHub:
vd:
git add TASKS.md
git commit -m "Update status for Two Sum - [Tên của bạn]"
git push origin main
