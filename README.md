# Laravel 11 RESTful API

A Petition RESTful API built with Laravel 11.



## Installation

Follow these steps to set up the project:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Install Dependencies:**
   ```bash
   composer install
   ```

3. **Install Frontend Dependencies (Optional):**
   ```bash
   npm install
   npm run dev
   ```

4. **Set Up Environment:**
   - Copy `.env.example` to `.env`:
     ```bash
     cp .env.example .env
     ```
   - Update `.env` with your database and other environment configurations.

5. **Generate Application Key:**
   ```bash
   php artisan key:generate
   ```

6. **Run Migrations:**
   ```bash
   php artisan migrate
   ```

7. **Seed the Database (Optional):**
   ```bash
   php artisan db:seed
   ```

---

## Setup

1. **API Base URL:**
   Set the `APP_URL` in your `.env` file to match your API base URL:
   ```env
   APP_URL=http://localhost:8000
   ```

2. **Run the Application:**
   ```bash
   php artisan serve
   ```

3. **Access the API:**
   Visit `http://localhost:8000/api` for your API routes.

---
