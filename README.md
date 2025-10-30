# 🍳 Recipe Sharing Platform

A modern full-stack web application for discovering and sharing recipes, built with Vue.js and Node.js.

## ✨ Features

- 🔍 Search and discover recipes from both user contributions and external API
- 👤 User authentication and personalized experience
- ⭐ Save favorite recipes and maintain viewing history
- 👨‍👩‍👧‍👦 Family recipes collection
- 📱 Responsive design for all devices

## 🛠️ Tech Stack

- **Frontend:** Vue.js
- **Backend:** Node.js, Express
- **Database:** MySQL
- **External API:** Spoonacular Recipe API
- **Authentication:** Express Sessions

## 🚀 Getting Started

1. Clone the repository
```bash
git clone https://github.com/asafzenou/recipes-website.git
```

2. Install dependencies
```bash
# Frontend
cd frontend
npm install

# Backend
cd backend
npm install
```

3. Set up environment variables
```bash
# Create .env file in backend directory
DB_HOST=your_host
DB_USER=your_user
DB_PASS=your_password
API_KEY=your_spoonacular_api_key
```

4. Run the application
```bash
# Frontend
npm run serve

# Backend
npm start
```

## 📝 API Documentation

- `/api/recipes` - Recipe management
- `/api/auth` - Authentication endpoints
- `/api/users` - User operations

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
