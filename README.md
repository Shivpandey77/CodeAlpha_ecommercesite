express-ecommerce/
│
├── public/                  # Frontend Static Files
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── main.js
│   │   └── cart.js
│   ├── index.html           # Product Catalog
│   ├── product.html         # Product Details Page
│   ├── cart.html            # Shopping Cart Page
│   ├── login.html           # Login / Register Page
│   └── checkout.html        # Order Processing
│
├── src/                     # Backend Logic
│   ├── config/
│   │   └── db.js            # SQLite Connection
│   ├── routes/
│   │   ├── auth.js          # User Registration & Login
│   │   ├── products.js      # Product Catalog API
│   │   └── orders.js        # Cart & Order Processing
│   └── middleware/
│       └── auth.js          # JWT Verification
│
├── database.sqlite          # Local SQLite DB (Auto-generated)
├── .env.example             # Template for Environment Variables
├── .gitignore               # Exclude node_modules & secrets
├── server.js                # Express Server Entry Point
├── package.json
└── README.md
