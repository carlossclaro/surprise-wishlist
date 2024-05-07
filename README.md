# surprise-wishlist


#wishlist-app/
│
├── client/                     // Frontend (React)
│   ├── public/
│   ├── src/
│   │   ├── components/         // React components
│   │   ├── pages/              // React pages (e.g., landing, dashboard, wishlist view)
│   │   ├── App.js              // Main App component
│   │   ├── index.js            // React DOM rendering
│   │   ├── App.css             // Global styles
│   │   └── ...
│   ├── package.json            // Frontend dependencies and scripts
│   ├── package-lock.json
│   └── ...
│
├── config/                     // Configuration files
│   ├── keys.js                 // Secret keys (e.g., JWT secret)
│   └── passport.js             // Passport configuration
│
├── controllers/                // Backend controllers (e.g., authController, wishlistController)
│   ├── authController.js
│   └── wishlistController.js
│
├── models/                     // Backend models (e.g., User, Wishlist)
│   ├── User.js
│   └── Wishlist.js
│
├── routes/                     // Backend routes (e.g., authRoutes, wishlistRoutes)
│   ├── authRoutes.js
│   └── wishlistRoutes.js
│
├── node_modules/               // Node.js modules (created after running npm install)
│
├── server.js                   // Backend server setup
│
├── .gitignore                  // Git ignore file
├── package.json                // Backend dependencies and scripts
├── package-lock.json
└── README.md                   // Project documentation
