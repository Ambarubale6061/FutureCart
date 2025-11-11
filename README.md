# 🛒 QuickCart — Modern E-Commerce Website

**QuickCart** is a full-stack e-commerce platform built using **Next.js**, **Tailwind CSS**, and **MongoDB**.  
It offers a clean, fast, and responsive shopping experience — including user authentication, product browsing, cart management, and secure checkout.

![QuickCart Preview](./public/quickcart-preview.png)

---

## 🚀 Features

✅ **Modern UI/UX** — built with Tailwind CSS and Framer Motion animations  
✅ **Responsive Design** — mobile-first layout for all screen sizes  
✅ **User Authentication** — login/register using JWT or NextAuth  
✅ **Add to Cart / Remove from Cart** — real-time cart management  
✅ **Product Search & Filtering**  
✅ **Order Summary & Checkout Flow**  
✅ **Secure Payments Integration (Stripe or Razorpay)**  
✅ **Admin Dashboard** _(optional)_ — manage products, categories, and orders  
✅ **SEO-friendly** — optimized for performance and fast load times

---

## 🧩 Tech Stack

| Layer           | Technology                       |
| :-------------- | :------------------------------- |
| Frontend        | Next.js 14, React 18, TypeScript |
| Styling         | Tailwind CSS, Framer Motion      |
| Backend         | Next.js API Routes               |
| Database        | MongoDB / Mongoose               |
| Authentication  | NextAuth.js / JWT                |
| Deployment      | Vercel                           |
| Package Manager | npm / yarn                       |

---

## 📂 Folder Structure

QuickCart-E-Commerce-Website/
│
├── app/ # Next.js App Router pages
├── components/ # Reusable UI components
├── context/ # React Context (Cart, Auth)
├── lib/ # Utility functions, DB connection
├── models/ # Mongoose models (User, Product, Order)
├── public/ # Static assets (images, icons)
├── styles/ # Global CSS or Tailwind styles
├── middleware.ts # Next.js Middleware for auth/redirects
├── next.config.mjs # Next.js configuration
├── tailwind.config.mjs # Tailwind setup
├── .env.example # Environment variables template
└── README.md

yaml
Copy code

---

## ⚙️ Environment Variables

Create a `.env.local` file in the root directory and add:

```bash
# MongoDB Connection
MONGODB_URI=your_mongodb_connection_string

# JWT Secret (for NextAuth or custom auth)
JWT_SECRET=your_jwt_secret

# Stripe or Razorpay Keys (optional)
STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_public_key

# NextAuth Config (if used)
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret
⚠️ Never commit .env.local to GitHub.

🧠 Installation & Setup
1️⃣ Clone the repository
bash
Copy code
git clone https://github.com/Ambarubale6061/QuickCart-E-Commerce-Website.git
cd QuickCart-E-Commerce-Website
2️⃣ Install dependencies
bash
Copy code
npm install
# or
yarn install
3️⃣ Set up environment variables
Copy .env.example to .env.local and fill in your own values.

4️⃣ Run the development server
bash
Copy code
npm run dev
# or
yarn dev
The app will be available at http://localhost:3000

🚢 Deployment (Vercel)
Push your project to GitHub

Go to vercel.com

Import your repository

Add all environment variables under “Settings → Environment Variables”

Click Deploy

Vercel will automatically build and host your app.

🧾 Scripts
Command	Description
npm run dev	Run development server
npm run build	Build the project for production
npm start	Start production server
npm run lint	Run ESLint checks

📦 Future Improvements
🧑‍💻 Admin Panel for product/order management

🛍️ Wishlist functionality

📦 Product categories and sorting

🔍 Advanced search and filters

💳 Payment integration (Stripe / Razorpay)

📱 PWA support (installable app)

🤝 Contributing
Contributions are welcome!

Fork the repo

Create a new branch (feature/your-feature)

Commit your changes

Push to the branch

Open a Pull Request 🎉

🪪 License
This project is licensed under the MIT License.
Feel free to use, modify, and distribute this project with attribution.

👨‍💻 Author
Developed by Ambar Ubale
💼 Portfolio: https://ambarportfolio.vercel.app/

⭐ If you like this project, give it a star on GitHub! ⭐


```
