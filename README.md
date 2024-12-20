# Fashion Store E-commerce Project

## 📋 Project Overview
An e-commerce website built with WordPress and WooCommerce, specializing in fashion and accessories. This project was developed as part of the CMS course at Ibn zohr AGADIR.

## 🛠️ Technologies Used
- WordPress 6.x
- WooCommerce 8.x
- PHP 8.x
- MySQL 5.7+
- Theme: StoreFront.

## 🚀 Installation Instructions

### Prerequisites
- XAMPP, WAMP, or MAMP installed
- Git installed
- Web browser
- FTP Client (FileZilla recommended)

### Local Installation Steps

.gitignore Configuration
We exclude certain files and directories from version control for security and practical reasons:

# WordPress Configuration
wp-config.php               # Contains database credentials and security keys

# Content Directories
wp-content/uploads/         # User uploaded files
wp-content/cache/          # Cache files
wp-content/               # Main content directory

# Development
node_modules/             # NPM packages
vendor/

1. **Clone the Repository**
```
git clone https://github.com/Nouredine119/Fashion-Flow.git
cd Fashion Flow

```

2. **Database Setup**
```
- Open phpMyAdmin (http://localhost/phpmyadmin)
- Create a new database named 'myShop'
- Import the database file from /database/myShop.sql
```

3. **WordPress Configuration**
```
- Copy wp-config-sample.php to wp-config.php
- Update database credentials in wp-config.php:
  DB_NAME: myShop
  DB_USER: root
  DB_PASSWORD: 
  DB_HOST: localhost
```

4. **Move to Server Directory**
```
- Move all files to your local server directory
  (e.g., xampp/htdocs/fashion-store)
```

5. **Access the Site**
```
Local URL: http://localhost/fashion-store
Admin URL: http://localhost/fashion-store/wp-admin
```

## 👤 Administrator Credentials
```
Admin Panel Login:
URL: http://localhost/fashion-store/wp-admin
Username: admin
Password: [your-admin-password]
```

## 📁 Project Structure
```
fashion-store/
├── wp-admin/
├── wp-content/
│   ├── themes/
│   ├── plugins/
│   └── uploads/
├── wp-includes/
├── database/
│   └── fashion_store.sql
└── README.md
```

## 🔌 Installed Plugins
- WooCommerce
- variation
- Wpforms Lite
- Elementor
- Site Mailer
- YITH WooCommerce Wishlist
- GTranslate
- Google for WooCommerce

## 👥 User Roles
1. **Administrator**
   - Full access to all features

2. **Editor**
   - Can publish and manage posts/pages
   - Can manage other users' posts

3. **Contributor**
   - Can write and manage own posts
   - Cannot publish posts


## 📱 Features
- Responsive design
- Product categories
- Shopping cart
- User registration
- Order management
- Payment integration
- Contact form

## 💳 Payment Methods
- Cash on Delivery


## 📧 Contact Form Setup
- Plugin used: WPForms
- Form location: http://localhost/myshop/wordpress/index.php/contact/

## 🔒 Security Measures
- Limited login attempts
- Security plugins installed
- Regular backup system

## 🔄 Updates and Maintenance
```
To update the site:
1. Backup database and files
2. Update WordPress core
3. Update plugins
4. Update theme
5. Test functionality
```

## 📝 Additional Notes
- Custom post types: [list if any]
- Custom taxonomies: [list if any]
- Special configurations: [list if any]

## 🤝 Contributors
- ACHLAFTA Nouredine
- MAJID Ichraq

## 📄 License
This project is part of an academic assignment at ibn zohr AGADIR.

## ❗ Important Notes
- Remember to change all passwords after installation
- Keep WordPress and all plugins updated
- Regular backups are recommended
