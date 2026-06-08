**Employee Management System**

A full-stack web application for managing employee records, built with Laravel, React.js, and MongoDB.
Tech Stack

**Backend:** Laravel (PHP), REST API
**Frontend:** React.js, Bootstrap
**Database:** MongoDB
**
Features**

CRUD operations for 100+ employee records
Role-based access control
RESTful APIs for frontend-backend communication
Responsive UI with component-level rendering
Schema-free employee profile storage via MongoDB

Getting Started
Prerequisites

PHP >= 8.0
Composer
Node.js & npm
MongoDB

Installation
# Clone the repository
git clone https://github.com/jayachandran-jayaraman/employee-management-system.git
cd employee-management-system

# Install backend dependencies
composer install

# Install frontend dependencies
npm install

# Set up environment
cp .env.example .env
php artisan key:generate

# Run the app
php artisan serve
npm run dev
