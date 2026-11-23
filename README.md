# Hourly Production Tracker & Dashboard

ระบบบันทึกผลผลิตรายชั่วโมง (Good / NG) รองรับการเพิ่ม ดู แก้ไข ลบ ข้อมูล และแสดงสรุปผลบน Dashboard

## Tech Stack
- **Database:** MySQL (`production_tracker`)
- **Backend:** Node.js, Express, `mysql2`
- **Frontend:** React (Vite), Axios, Recharts

## How to Run Locally

### 1. Database (MySQL)
- สร้างฐานข้อมูล `production_tracker` และรันสคริปต์สร้างตาราง (`users`, `master_lines`, `master_products`, `hourly_logs`)

### 2. Backend
```bash
cd backend
cp .env.example .env   # แล้วกรอกรหัสผ่าน MySQL ในไฟล์ .env
npm install
npm run dev
