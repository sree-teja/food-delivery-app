# Tomato: Online Food Ordering Application

Tomato is a full-stack web application for seamless online food ordering, built using the MERN (MongoDB, Express, React, Node.js) stack. It offers a user-friendly interface for customers and an efficient management system for administrators.

## Features

### User Interface
- **Browse & Search**: Users can explore food items, view details, and add items to their cart.
- **Sliding Navigation**: Intuitive sliding mechanism for browsing food categories.
- **Shop Section**: Dedicated section for additional item discovery.
- **User Authentication**: Secure login and registration system.

### Admin Interface
- **Dashboard Access**: Admins must log in to manage the platform.
- **Food Item Management**:
  - Add, edit, and delete food items with name, description, price, and image.
- **Logout Functionality**: Easy sign-out option for security.

## Tech Stack

### **Frontend: React (Vite)**
- Component-based UI for dynamic and responsive design.
- Seamless navigation and interaction with food items.
- Vite for fast development and optimized builds.

### **Backend: Node.js & Express**
- Handles authentication, data processing, and API endpoints.
- Efficient route handling for user requests.

### **Database: MongoDB**
- NoSQL database for flexible storage of food items and user data.
- Schema-less structure for adaptability.

## Installation & Setup

### **Backend Setup**
1. Navigate to the backend directory:
   ```sh
   cd Backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the backend server:
   ```sh
   npm run server  # Uses nodemon for automatic restarts
   ```

### **Frontend Setup** (User and Admin Panels)
1. Navigate to the frontend directory:
   ```sh
   cd Frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend:
   ```sh
   npm run dev
   ```
4. Navigate to the admin directory:
   ```sh
   cd ../admin
   ```
5. Install dependencies:
   ```sh
   npm install
   ```
6. Start the admin panel:
   ```sh
   npm run dev
   ```

## Contributing
Pull requests are welcome. For major changes, please open an issue to discuss improvements.

## License
This project is open-source under the [MIT License](LICENSE).

