# 📚 Bibliotheca - Bookstore Website

**Bibliotheca** is a simple and responsive web-based bookstore built using native PHP, MySQL, JavaScript, and CSS. It features user login and registration, cart functionality, checkout system, book categories, search functionalities and an admin dashboard to manage products, orders, and users.

---

## 🚀 Features

- User authentication (Login/Logout)
- Book browsing with add-to-cart functionality
- Dynamic cart and checkout system
- Admin dashboard:
  - Manage books/products
  - Track orders
  - Manage users and contact messages

---

## 🛠️ Tech Stack

- **Backend**: PHP (No framework)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL

---

## 📁 Project Structure

```
project/
├── css/                  # Stylesheets
├── images/               # Image assets
├── js/                   # JavaScript files
├── uploaded_img/         # Uploaded book images
├── about.php             # About page
├── add_to_cart.php       # Logic to add books to cart
├── admin_contacts.php    # Admin contact message management
├── admin_header.php      # Admin dashboard header
├── admin_orders.php      # Admin order management
├── admin_page.php        # Admin dashboard main page
├── admin_products.php    # Admin product management
├── admin_users.php       # Admin user management
├── cart.php              # User cart page
├── checkout.php          # Checkout and payment processing
├── config.php            # Database connection setup
├── contact.php           # Contact form page
├── footer.php            # Website footer include
├── header.php            # Website header include
├── home.php              # Homepage with book listings
├── login.php             # Login form & logic
├── logout.php            # Logout logic
├── orders.php            # User orders and history logic
├── register.php          # Registration form & logic
├── search_page.php       # Search book by characters l
├── shop.php              # Shop page
├── shop_db.sql           # SQL database file
```

---

## ⚙️ Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/RockPockx/bookstore-website.git
cd bookstore-website
```

2. **Database Setup**

- Create a MySQL database, e.g., `shop_db`
- Import the SQL file into your database
- Update `config.php` with your database credentials:

```php
// config.php
$conn = mysqli_connect("localhost", "root", "", "shop_db");
```

3. **Run the Website**

- Use a local server like [XAMPP](https://www.apachefriends.org/) or [Laragon](https://laragon.org/)
- Place the project folder in your `htdocs` (XAMPP) or appropriate web root
- Start Apache and MySQL via XAMPP or Laragon
- Navigate to `http://localhost/bookstore-website/project/home.php`

---

## 🤝 Contributing

Contributions are welcome! Please fork this repo and submit a pull request for any enhancements or bug fixes.


