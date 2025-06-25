# Food Donation Platform

## Description  
A web-based platform that connects food donors with individuals and organizations in need. The goal is to reduce food waste and fight hunger by facilitating food redistribution through a simple and accessible interface.

## Tech Stack  
- **Backend** : Laravel (PHP)  
- **Frontend** : Vue.js  
- **Database** : MySQL  
- **Payment** : N/A (planned for future donor partnerships)  
- **Other** : Postman (API testing), GitHub Actions (CI/CD), Jira (project management)

## Features  
- User authentication for Donors, Recipients, and Admins  
- Donor listing of available food donations  
- Recipient browsing, filtering, and claiming of donations  
- Admin dashboard for managing users and monitoring activity  
- Search and filter donations by location, food type, or expiry date  
- Reporting system for statistics and platform metrics  

## Installation & Setup  
1. Clone this repository  
2. Copy `.env.example` to `.env` and configure your database credentials  
3. Run `composer install` (for Laravel dependencies)  
4. Run `npm install && npm run dev` (for Vue build)  
5. Run `php artisan key:generate`  
6. Run `php artisan migrate`  
7. Launch local server with `php artisan serve`

## API Documentation  
[Postman Collection – Food Donation API]([https://www.postman.com/your-workspace-link](https://www.postman.com/lucbanze/workspace/food-donation-platform))

## Live Demo  
_Coming soon_ (deployment planned on Render/DigitalOcean)

## Screenshots  
<!-- Replace with actual image links -->
![Home Page](screenshots/homepage.png)  
![Donation Listing](screenshots/listing.png)  
![Admin Dashboard](screenshots/admin.png)

## Contributing  
1. Fork the repository  
2. Create a new branch: `git checkout -b feature/your-feature-name`  
3. Make your changes and commit them: `git commit -m 'Add new feature'`  
4. Push to the branch: `git push origin feature/your-feature-name`  
5. Open a pull request

## License  
This project is licensed under the MIT License.
