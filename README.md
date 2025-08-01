# 🩺 Doctor Appointment Booking System – Backend (NestJS)

This project is a RESTful backend API for booking doctor appointments, built using **NestJS**, **PostgreSQL**

---

## ✅ Features

- View list of doctors
- View available time slots for a doctor
- Book appointments (with overlap prevention)
- Data validation with DTOs
- Modular structure (controllers, services, modules)
- Swagger API documentation

---

## 🚀 Tech Stack

- NestJS (TypeScript)
- PostgreSQL
- class-validator
- Swagger (OpenAPI)
- (Optional) Authentication

---

## ⚙️ Setup Instructions

```bash
# 1. Clone repo
git clone https://github.com/your-username/doctor-booking-api.git
cd doctor-booking-api

# 2. Install dependencies
npm install

# 3. Configure PostgreSQL (update .env)
cp .env.example .env

# 4. Run migrations
npm run typeorm migration:run

# 5. (Optional) Seed database
npm run seed

# 6. Start the server
npm run start:dev
