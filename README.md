# 🍅 Tomoto - Food Delivery Platform

Tomoto is a full-stack **food delivery web application** that connects users with nearby restaurants and enables them to browse menus, place online orders, and make secure payments — all from one platform.  
It’s built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)** and provides a smooth and intuitive experience for both users and restaurant owners.

---

## 🚀 Features

### 👨‍🍳 For Users
- 🍽️ Browse and search for restaurants and food items  
- 🛒 Add items to the cart and place orders  
- 💳 Secure online payment integration (Stripe/Razorpay ready)  
- 🚚 Track your order status in real-time  
- ⭐ Rate and review restaurants  

### 🏪 For Restaurant Owners
- 🏗️ Register and manage your restaurant profile  
- 📦 Add, edit, or delete food items  
- 📊 View and manage all incoming orders  

### 🛠️ For Admin
- 🧾 Manage users, restaurants, and orders  
- 🧹 Maintain overall platform integrity and security  

---

## 🧰 Tech Stack

**Frontend:**  
- React.js  
- Redux Toolkit  
- Axios  
- Tailwind CSS / Bootstrap  

**Backend:**  
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- JWT Authentication  

**Other Tools:**  
- Cloudinary for image uploads  
- Stripe / Razorpay for payment gateway  
- Bcrypt.js for password encryption  

---

Tomoto/
├── client/ # React frontend
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Home, Cart, Orders, etc.
│ │ ├── redux/ # Redux store and slices
│ │ └── App.js
│ └── package.json
│
├── server/ # Express backend
│ ├── models/ # Mongoose schemas
│ ├── routes/ # API endpoints
│ ├── controllers/ # Logic for each route
│ ├── middleware/ # Auth & error handling
│ ├── server.js
│ └── package.json
│
└── README.md


---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Tomoto.git


Navigate to the project

cd Tomoto


Install dependencies

Backend:

cd server
npm install


Frontend:

cd ../client
npm install


Create a .env file inside the server folder and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
STRIPE_SECRET=your_stripe_secret


Run the application

Start backend:

npm start


Start frontend:

npm run dev

--- 

### 🔒 Authentication Flow

- Users can sign up using email and password.
- JWT tokens ensure secure session management.
- Clerk/Auth0 integration can be added for advanced authentication.

### 🧩 Future Enhancements

- 📱 Mobile app version using React Native
- 🗺️ Real-time delivery tracking via Google Maps API
- 🧾 Order history analytics for restaurants

### 🤝 Contributing
- Contributions are welcome!
- Feel free to fork this repository and submit a pull request with your improvements.

---

### 🧑‍💻 Author
Ridhi Bhatia

---

### 📝 License
This project is licensed under the MIT License.


