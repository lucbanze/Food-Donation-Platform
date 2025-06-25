# 🍽️ Food Donation Platform

A web-based platform that connects food donors with individuals and organizations in need. Our mission is to reduce food waste and fight hunger by facilitating food redistribution through a simple and accessible interface.

## 📋 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation & Setup](#installation--setup)
- [API Documentation](#api-documentation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

### 🔐 User Management
- **Multi-role Authentication**: Secure login system for Donors, Recipients, and Admins
- **Profile Management**: Users can manage their profiles and preferences

### 🎁 Donation Management
- **Donor Listings**: Easy-to-use interface for donors to list available food donations
- **Smart Browsing**: Recipients can browse, filter, and claim donations efficiently
- **Advanced Search**: Filter donations by location, food type, expiry date, and more

### 👨‍💼 Administration
- **Admin Dashboard**: Comprehensive dashboard for managing users and monitoring platform activity
- **User Management**: Admins can oversee user accounts and permissions
- **Activity Monitoring**: Real-time tracking of platform usage and donations

### 📊 Analytics & Reporting
- **Statistics Dashboard**: Detailed metrics on food donations and platform impact
- **Reporting System**: Generate reports for stakeholders and impact assessment
- **Data Visualization**: Clear charts and graphs showing platform effectiveness

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Backend** | Laravel (PHP) |
| **Frontend** | Vue.js |
| **Database** | MySQL |
| **API Testing** | Postman |
| **CI/CD** | GitHub Actions |
| **Project Management** | Jira |
| **Future Payment Integration** | TBD (planned for donor partnerships) |

## 🚀 Installation & Setup

### Prerequisites
- PHP >= 8.0
- Node.js >= 16.0
- MySQL >= 5.7
- Composer
- NPM or Yarn

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/food-donation-platform.git
   cd food-donation-platform
   ```

2. **Configure environment**
   ```bash
   cp .env.example .env
   ```
   Update your `.env` file with your database credentials and other configurations.

3. **Install dependencies**
   ```bash
   # Install PHP dependencies
   composer install
   
   # Install Node.js dependencies
   npm install
   ```

4. **Generate application key**
   ```bash
   php artisan key:generate
   ```

5. **Run database migrations**
   ```bash
   php artisan migrate
   ```

6. **Seed the database (optional)**
   ```bash
   php artisan db:seed
   ```

7. **Build frontend assets**
   ```bash
   npm run dev
   # or for production
   npm run build
   ```

8. **Start the development server**
   ```bash
   php artisan serve
   ```

Your application will be available at `http://localhost:8000`

## 📚 API Documentation

Our comprehensive API documentation is available through Postman:

**[📖 Food Donation Platform API Collection](https://www.postman.com/lucbanze/workspace/food-donation-platform)**

The API collection includes:
- Authentication endpoints
- Donation management
- User operations
- Admin functions
- Search and filtering
- Reporting endpoints

### API Base URL
```
Local: http://localhost:8000/api
Production: TBD
```

## 💡 Usage

### For Donors
1. Register as a donor
2. Log in to your account
3. Create donation listings with food details, location, and expiry dates
4. Monitor your donations and respond to recipient requests

### For Recipients
1. Register as a recipient
2. Browse available donations in your area
3. Use filters to find specific types of food
4. Claim donations and coordinate pickup

### For Admins
1. Access the admin dashboard
2. Monitor platform activity
3. Manage user accounts
4. Generate reports and analytics

## 📸 Screenshots

<!-- Replace with actual image links when available -->
| Home Page | Donation Listing | Admin Dashboard |
|-----------|------------------|-----------------|
| ![Home Page](screenshots/homepage.png) | ![Donation Listing](screenshots/listing.png) | ![Admin Dashboard](screenshots/admin.png) |

*Screenshots will be updated as the project develops*

## 🌐 Live Demo

🚧 **Coming Soon** - Deployment planned on Render/DigitalOcean

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Getting Started
1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes**
4. **Commit your changes**
   ```bash
   git commit -m 'Add: your feature description'
   ```
5. **Push to your branch**
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Open a Pull Request**

### Contribution Guidelines
- Follow PSR-12 coding standards for PHP
- Use Vue.js best practices for frontend code
- Write clear, descriptive commit messages
- Include tests for new features
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔮 Future Enhancements

- [ ] Mobile application (React Native/Flutter)
- [ ] Real-time notifications
- [ ] Integration with payment gateways for donor partnerships
- [ ] AI-powered food matching algorithm
- [ ] Multilingual support
- [ ] Advanced analytics dashboard
- [ ] API rate limiting and enhanced security

## 📞 Contact & Support

- **Project Maintainer**: [Luc Banze]
- **Email**: [lucbanze.lb@gmail.com]
- **Issues**: [GitHub Issues](https://github.com/your-username/food-donation-platform/issues)

---

### 🌟 Making a Difference
*Every donation matters. Every line of code contributes to fighting hunger and reducing food waste in our communities.*
