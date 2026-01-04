# Online Tutor Matching System

Dự án này là một nền tảng website toàn diện nhằm hiện đại hóa quy trình dạy và học cá nhân hóa tại Việt Nam].
Hệ thống giúp tự động hóa việc kết nối giữa học viên và gia sư, mang lại trải nghiệm học tập minh bạch, hiệu quả và có thể theo dõi được tiến độ.

## Công Nghệ Sử Dụng
Dự án được xây dựng dựa trên kiến trúc **Microservices** để đảm bảo tính linh hoạt, dễ mở rộng và bảo trì.

* **Frontend:** React (JSX) kết hợp CSS (Responsive Design) giúp tối ưu trải nghiệm trên mọi thiết bị.
* **Backend:** Python kết hợp **FastAPI** cung cấp các API REST hiệu suất cao.
* **Cơ sở dữ liệu:** **Supabase (PostgreSQL)** hỗ trợ lưu trữ dữ liệu quan hệ và truy vấn thời gian thực.
* **Triển khai:** **Docker** giúp đảm bảo tính nhất quán và ổn định giữa các môi trường.

## Cách cài đặt và chạy thử
Để chạy dự án này ở máy cục bộ, bạn làm theo các bước:

1. Clone dự án:
   `git clone https://github.com/thuygiangxd/Source-code.git`

**FE**
2. Di chuyển vào thư mục dự án:
   `cd frontend`

3. Cài đặt thư viện:
   `npm install`
   'npm install react react-dom react-router-dom'
   'npm install axios'
   
5. Chạy dự án:
   `npm run dev`

**BE**
   Git Bash
6. Di chuyển vào thư mục dự án:
   cd backend
   
7. Chạy dự án:
  ./start_all.sh
