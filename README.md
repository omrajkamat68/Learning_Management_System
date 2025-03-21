Here's a README for your Git repository:  

---

# 🎓 Learning Management System (LMS)  

A full-featured Learning Management System (LMS) built using the **MERN stack** and **React + Vite**. This platform allows students to create profiles, purchase courses, and watch them. Additionally, users can become educators and publish their own courses.  

## 🚀 Features  

### For Students:  
✅ Create a profile and manage enrolled courses  
✅ Purchase courses securely  
✅ Watch course videos and track progress  

### For Educators:  
✅ Apply to become an educator  
✅ Create and publish courses  
✅ Manage course content and students  

### General Features:  
✅ Secure authentication with Clerk/Auth  
✅ Payment integration for course purchases  
✅ Responsive UI with a modern design  
✅ User-friendly course browsing and filtering  

## 🛠 Tech Stack  

- **Frontend:** React + Vite, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB with Mongoose  
- **Authentication:** Clerk/Auth  
- **Payments:** (Stripe)  
- **State Management:** React Context API  
- **Deployment:** (Vercel)  

## 🏗 Setup & Installation  

### Prerequisites:  
- Node.js (Latest LTS)  
- MongoDB (Local/Cloud)  

### Steps:  

1️⃣ Clone the repository:  
```bash
git clone https://github.com/omrajkamat68/Learning_Management_System.git
cd Learning_Management_System
```

2️⃣ Install dependencies:  
```bash
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

3️⃣ Set up environment variables:  
Create `.env` files in both `client` and `server` directories.  

#### Example for **server/.env**:  
```env
CURRENCY=USD
MONGODB_URI=your_mongodb_connection_string
CLERK_WEBHOOK_SECRET=your_clerk_webhook_secret
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
```

#### Example for **client/.env**:  
```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_CURRENCY='$'
VITE_BACKEND_URL=http://localhost:5000
```

4️⃣ Start the development servers:  
```bash
# Run the backend
cd server
nodemon server.js

# Run the frontend
cd ../client
npm run dev
```
