# IntelliBuy - AI-Driven Smart Shopping Assistant for Informed Buying
This project envisions a next-generation shopping website that integrates AI to guide users through product purchases based on their familiarity and experience levels. When a user searches for a product, the system intelligently determines their knowledge—asking tailored, dynamically generated questions using LLMs (large language models). For naive users unfamiliar with a product (e.g., protein powder), it offers contextual education and queries like usage goals, past experience, preferences, etc., to recommend the most suitable item—ensuring they don’t make the wrong choice even by 1%. Intermediate users are asked 3–4 focused questions, while advanced users are left to explore freely. The goal is to eliminate confusion, enrich product understanding, and personalize the purchase journey through adaptive AI.

#file structure 
IntelliBuy/
│
├── backend/
│   ├── controllers/
│   │   └── productController.js
│   ├── models/
│   │   └── Product.js
│   ├── routes/
│   │   └── productRoutes.js
│   ├── uploads/
│   ├── .env
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── Navbar.jsx
│   │   │   └── ProductCard.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── ProductPage.jsx
│   │   │   ├── Login.jsx
│   │   │   └── Signup.jsx
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
└── README.md
