# 🍿 Pipocaflix

[![Status](https://img.shields.io/badge/status-development-green.svg)](https://github.com/yourusername/pipocaflix)
[![PHP](https://img.shields.io/badge/PHP-7.4+-blue.svg)](https://php.net)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

A Netflix-inspired streaming platform built with PHP, JavaScript, and modern web technologies.

## 📖 About

Pipocaflix is a comprehensive streaming platform that replicates the core functionality of Netflix. This project serves as an educational resource for learning web development, database management, and streaming platform architecture.

**⚠️ Educational Purpose Only**: This project is developed for educational purposes and should not be used for commercial streaming or distribution of copyrighted content.

## ✨ Features

### 🎬 Content Management
- **Movie & Series Library**: Comprehensive content management system
- **Category Organization**: Movies organized by genres (Action, Comedy, Drama, etc.)
- **Episode Management**: Complete series with episode tracking
- **Content Search**: Advanced search functionality with filters

### 👥 User Management
- **User Registration & Authentication**: Secure login system
- **Profile Management**: Multiple user profiles per account
- **Subscription Plans**: Different membership tiers
- **Payment Integration**: MercadoPago payment gateway

### 🎯 User Experience
- **Responsive Design**: Mobile-friendly interface
- **Netflix-like UI**: Familiar streaming platform interface
- **Video Player**: Integrated video streaming capabilities
- **Watchlist**: Personal content lists
- **Continue Watching**: Resume playback from where you left off

### 🔧 Admin Panel
- **Content Administration**: Add, edit, and manage movies/series
- **User Management**: Admin control over user accounts
- **Analytics Dashboard**: View platform statistics
- **Payment Management**: Handle subscriptions and payments

## 🛠️ Technology Stack

### Backend
- **PHP**: Core server-side language
- **MySQL**: Database management
- **Apache**: Web server

### Frontend
- **HTML5/CSS3**: Modern web standards
- **JavaScript/jQuery**: Interactive functionality
- **Bootstrap**: Responsive UI framework
- **React/Angular**: Advanced frontend components

### Integrations
- **MercadoPago**: Payment processing
- **PHPMailer**: Email functionality
- **Google Translate**: Multi-language support

## 🚀 Installation

### Prerequisites
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Apache/Nginx web server
- Composer (for dependency management)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/pipocaflix.git
   cd pipocaflix
   ```

2. **Install dependencies**
   ```bash
   composer install
   ```

3. **Database setup**
   - Create a MySQL database
   - Import the database schema (check `database/` folder)
   - Update database credentials in `conexao/conexao.php`

4. **Configuration**
   - Copy `env.example` to `.env` and configure your settings
   - Set up MercadoPago API credentials
   - Configure email settings for PHPMailer

5. **Web server configuration**
   - Point your web server to the project directory
   - Ensure proper permissions for file uploads

6. **Access the application**
   - Navigate to your domain in a web browser
   - Register a new account or use admin credentials

## 📁 Project Structure

```
pipocaflix/
├── admin/                 # Admin panel
│   ├── functionPHP/      # Admin functions
│   ├── includes/         # Admin includes
│   └── api/             # API endpoints
├── pages/               # Main application pages
├── functionPHP/         # Core PHP functions
├── css/                 # Stylesheets
├── js/                  # JavaScript files
├── img/                 # Images and assets
├── mercadopago/         # Payment integration
├── class/               # PHP classes
└── require/             # Required files
```

## 🔧 Configuration

### Environment Variables
Create a `.env` file with the following variables:
```env
DB_HOST=localhost
DB_NAME=pipocaflix
DB_USER=your_username
DB_PASS=your_password

MERCADOPAGO_ACCESS_TOKEN=your_access_token
MERCADOPAGO_PUBLIC_KEY=your_public_key

SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your_email@gmail.com
SMTP_PASS=your_password
```

## 🧪 Testing

Run the test suite to ensure everything is working correctly:
```bash
php test/test_suite.php
```

## 📝 API Documentation

The project includes a RESTful API for content management. See `docs/API.md` for detailed documentation.

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details on how to submit pull requests, report issues, and contribute to the project.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Developer

**Júlio César de Amorim**

- **Version**: 1.0.1
- **Status**: In Development
- **Next Version**: Coming soon

## 🙏 Acknowledgments

- Netflix for the UI/UX inspiration
- Bootstrap team for the responsive framework
- MercadoPago for payment processing
- PHPMailer for email functionality

## 📞 Support

If you have any questions or need support:
- Create an issue on GitHub
- Check the documentation in the `docs/` folder
- Review the troubleshooting guide

## ⚠️ Disclaimer

This project is created for educational purposes only. Please respect copyright laws and do not use this platform to distribute copyrighted content without proper licensing.

---

**Made with ❤️ for the developer community**
