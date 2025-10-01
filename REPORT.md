#  REPORT – Thực hành Git nhóm 8

##  Repo nhóm  
- Link repo: [https://github.com/vanhoa66482-lgtm/nhom-8](https://github.com/vanhoa66482-lgtm/nhom-8)  

##  Pull Requests đã merge  
- [PR #1](link_PR_1) – Thêm file cá nhân MSSV 25139058  
- [PR #2](link_PR_2) – Thêm file cá nhân MSSV 25139001  
- [PR #3](link_PR_3) – Thêm file cá nhân MSSV 25139053  

*(Bạn cần thay `link_PR_x` bằng link thật của PR trong repo nhóm)*  

##  Thành viên và nhiệm vụ  
| Họ tên                 | MSSV     | Nhiệm vụ                                                |
|------------------------|----------|----------------------------------------------------------|
| Lê Trọng Tuấn          | 25139058 | Tạo nhánh `feature-25139058`, file cá nhân, PR           |
| Lê Nguyễn Văn Hòa      | 25139013 | Quản lý README, review PR, hỗ trợ merge                 |
| Thành viên khác         | xxxxxxxx | Tạo file cá nhân, commit, review                         |
| Thành viên khác         | xxxxxxxx | …                                                        |

##  Lệnh Git dùng nhiều nhất  
- `git clone <repo>`  
- `git checkout -b feature-[MSSV]`  
- `git add <file>`  
- `git commit -m "…”`  
- `git push origin feature-[MSSV]`  
- `git pull origin main`  
- `git merge feature-[MSSV]`  
- (Có thể dùng thêm) `git log --oneline --graph`, `git revert <commit>`  

##  Khó khăn gặp phải & cách giải quyết  
- Khi nhiều người sửa chung README.md → xung đột (conflict).  
  → Giải pháp: mỗi người tạo file cá nhân riêng, tránh sửa chung file README.  
- Có lúc push bị lỗi vì repo main đã thay đổi trước đó.  
  → Giải pháp: trước khi push, dùng `git pull origin main`, xem xét merge / rebase.  
- Chưa quen quy trình review PR → phải trao đổi nhóm, làm test cá nhân trước rồi submit PR nhỏ.  

##  Điều mới học được ngoài slide  
- Kỹ năng tạo nhánh và làm việc nhóm qua Pull Request & Review.  
- Cách xử lý conflict khi merge giữa các nhánh.  
- Sử dụng commit message chuẩn (feat, docs, fix) để dễ đọc lịch sử.  
- Hiểu cách tag phiên bản & release trên GitHub.  
- (Nếu nhóm bạn làm) Quản lý công việc qua Issues.  
