# HomeLink - Home Rental Platform

HomeLink is a comprehensive home rental platform built with the MERN stack (MongoDB, Express, React, Node.js) and Redux for state management. The platform offers a seamless experience for both property owners and renters, allowing users to browse, search, and manage rental properties efficiently.

---

## 🚀 Features

### Frontend
- Browse available rental properties
- Advanced search by location, price, and property type
- View detailed property information and images
- User authentication and profile management
- Responsive design for both mobile and desktop

### Backend
- User registration and authentication using JWT
- CRUD operations for property listings
- Booking and rental management
- Secure API endpoints for frontend integration

---

## 🛠️ Tech Stack

### Frontend
- **React.js**
- **Redux Toolkit** for state management
- **Axios** for API communication
- **React Router** for navigation
- **Bootstrap** for UI styling

### Backend
- **Node.js** with **Express.js**
- **MongoDB** with **Mongoose** for database management
- **JWT** for authentication
- **Cloudinary** for image uploads (optional)

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js & npm installed
- MongoDB setup
- Git installed

### 1. Clone the Repositories
```sh
# Frontend
git clone https://github.com/DeshanNanayakkara/HomeLink-FrontEnd.git
cd HomeLink-FrontEnd

# Backend
git clone https://github.com/DeshanNanayakkara/HomeLink-BackEnd.git
cd HomeLink-BackEnd
```

### 2. Install Dependencies
```sh
# Frontend
npm install

# Backend
npm install
```

### 3. Configure Environment Variables

#### Frontend (`.env`)
```env
REACT_APP_API_URL=http://localhost:5000
```

#### Backend (`.env`)
```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 4. Run the Application
```sh
# Frontend
npm start

# Backend
npm run dev
```

---

## 📄 API Endpoints

### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login a user

### Properties
- `GET /api/properties` - Get all properties
- `POST /api/properties` - Create a new property (Admin only)
- `PUT /api/properties/:id` - Update a property (Admin only)
- `DELETE /api/properties/:id` - Delete a property (Admin only)

---

## 📂 Folder Structure

```
HomeLink
├── frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── redux
│   │   └── App.js
│   └── package.json
└── backend
    ├── controllers
    ├── models
    ├── routes
    ├── middleware
    ├── server.js
    └── package.json
```

---

## 💡 Contributing
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

---

## 📝 License
This project is licensed under the MIT License.

---

## 👨‍💻 Author
**Deshan Nanayakkara**  
Passionate Software Engineering Student | MERN Stack Developer

Feel free to contribute or reach out if you have any questions!
