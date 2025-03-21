# Simple Blogging System

## 📌 Description
A basic blog where users can create, read, and comment on posts. This project is built using **PHP & MySQL** and covers essential web development concepts such as authentication, CRUD operations, and security measures.

## 🔹 Features
- 🔑 **User Authentication** (Register/Login/Logout)
- ✍ **Create, Edit, and Delete Blog Posts**
- 💬 **Comment System** (Users can comment on posts)
- 📄 **Pagination** for better post navigation
- 🔐 **Security Features** (SQL Injection Prevention, Password Hashing)

## 📚 Concepts Covered
✅ User authentication & sessions (PHP)  
✅ Database design for posts and comments  
✅ CRUD operations  
✅ Security measures (prepared statements, hashing)  

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** PHP
- **Database:** MySQL

## 📂 Project Structure
```
blogging-system/
│── index.php          # Homepage displaying all blog posts
│── login.php          # User login page
│── register.php       # User registration page
│── dashboard.php      # User dashboard for managing posts
│── create_post.php    # Create a new blog post
│── edit_post.php      # Edit an existing blog post
│── delete_post.php    # Delete a blog post
│── post.php           # View a single blog post with comments
│── comment.php        # Handle comments on posts
│── logout.php         # Logout user
│── db.php             # Database connection
│── styles.css         # Stylesheet
│── README.md          # Project documentation
└── assets/            # Images, CSS, JS files
```

## 🚀 Installation
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/blogging-system.git
cd blogging-system
```
### 2️⃣ Setup the Database
- Create a new MySQL database
- Import the `database.sql` file (provided in the project) using phpMyAdmin or MySQL CLI

### 3️⃣ Configure Database Connection
Edit `db.php` and update the database credentials:
```php
$host = "localhost";
$user = "root";
$password = "";
$database = "blog_db";
$conn = new mysqli($host, $user, $password, $database);
```

### 4️⃣ Start the Server
If using **XAMPP** or **WAMP**, place the project in the `htdocs` folder and start Apache & MySQL.

If using **PHP built-in server**, run:
```sh
php -S localhost:8000
```
Then, open **http://localhost:8000** in your browser.

## 📜 License
This project is open-source under the **MIT License**.

## 🙌 Contributions
Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

💡 **Need help?** Feel free to reach out!

