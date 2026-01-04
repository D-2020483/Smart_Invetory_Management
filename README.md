# Smart Inventory Manager

A full-stack web application for managing inventory with real-time tracking, user authentication, and comprehensive dashboard analytics. Built with modern web technologies for efficient and scalable inventory management.

## 🚀 Features

- **User Authentication**: Secure sign-in and sign-up with JWT-based authentication
- **Dashboard Analytics**: Real-time inventory statistics, stock alerts, and trend analysis
- **Inventory Management**:
  - Add, edit, and delete inventory items
  - Bulk operations for multiple items
  - Stock level monitoring (in-stock, low-stock, out-of-stock)
  - Image upload support
  - PDF export functionality
- **Responsive Design**: Mobile-friendly interface with dark/light theme support
- **Real-time Updates**: Live data synchronization with the backend
- **Search & Filtering**: Advanced search and sorting capabilities
- **Settings Management**: User profile and application preferences

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern JavaScript library for building user interfaces
- **Vite** - Fast build tool and development server
- **Redux Toolkit** - State management for complex application state
- **React Router** - Declarative routing for React applications
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Accessible UI components
- **Axios** - HTTP client for API requests
- **Lucide React** - Beautiful & consistent icon toolkit

### Backend
- **Node.js** - JavaScript runtime for server-side development
- **Express.js** - Web application framework for Node.js
- **MongoDB** - NoSQL database for data storage
- **Mongoose** - MongoDB object modeling for Node.js
- **JWT** - JSON Web Tokens for authentication
- **bcryptjs** - Password hashing
- **Multer** - Middleware for handling file uploads
- **Nodemailer** - Email sending functionality

## 📁 Project Structure

```
smart-inventory-manager/
├── client/                 # React frontend application
│   ├── public/            # Static assets
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Application pages/routes
│   │   ├── state/         # Redux API slices
│   │   ├── store/         # Redux store configuration
│   │   └── lib/           # Utility functions
│   ├── package.json
│   └── vite.config.js
├── server/                 # Node.js backend application
│   ├── config/            # Database configuration
│   ├── controllers/       # Route controllers
│   ├── middleware/        # Custom middleware
│   ├── models/            # MongoDB schemas
│   ├── routes/            # API routes
│   ├── utils/             # Utility functions
│   ├── package.json
│   └── server.js          # Main server file
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js
- MongoDB (local installation or MongoDB Atlas)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd smart-inventory-manager
   ```
- Frontend Repo:[Frontend](https://github.com/D-2020483/Smart_Invetory_Management_FND)
- Backend Repo:[Backend](https://github.com/D-2020483/Smart_Invetory_Management_BND)

2. **Install server dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install client dependencies**
   ```bash
   cd ../client
   npm install
   ```

4. **Start MongoDB**
   Make sure MongoDB is running on your system.

5. **Start the development servers**

   **Terminal 1 - Backend:**
   ```bash
   cd server
   npm run dev
   ```

   **Terminal 2 - Frontend:**
   ```bash
   cd client
   npm run dev
   ```

7. **Access the application**
   - Frontend: http://localhost:5173
   - Backend API: http://localhost:5000

## 📖 Usage

### User Authentication
1. Visit the application and sign up for a new account
2. Sign in with your credentials
3. Access the dashboard and inventory management features

### Managing Inventory
1. Navigate to the "Inventory" section from the sidebar
2. Click "Add New Item" to create inventory items
3. Fill in item details: name, SKU, quantity, price, minimum stock level
4. Upload product images if available
5. Use bulk actions to manage multiple items simultaneously
6. Monitor stock levels and receive alerts for low stock items

### Dashboard Analytics
- View real-time statistics on total products, stock value, and alerts
- Monitor recent products and low stock items
- Track inventory trends and performance metrics

## 🔧 Available Scripts

### Client Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Server Scripts
- `npm start` - Start production server
- `npm run dev` - Start development server with nodemon

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📸 Interface Screenshots

<img width="450" height="280" alt="Home page" src="https://github.com/user-attachments/assets/3f8e49f7-1f37-4de1-be89-acb348fd79ab" />
<img width="450" height="280" alt="Inventory page" src="https://github.com/user-attachments/assets/fc77998c-f81d-401c-aea5-4a77eabf4c38" />
<img width="450" height="280" alt="Settings page" src="https://github.com/user-attachments/assets/e1a95b3e-0944-44aa-aa9b-0876a2fa761c" />

## 🔄 Future Enhancements

- [ ] Barcode scanning integration
- [ ] Multi-warehouse support
- [ ] Advanced reporting and analytics
- [ ] Mobile application
- [ ] API rate limiting and caching
- [ ] Automated stock replenishment alerts
- [ ] Integration with e-commerce platforms
