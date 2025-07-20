📚 Book Nest

**Book Nest** is a platform designed to facilitate the buying, selling, and exchange of books among students, readers, and sellers. It aims to create a digital ecosystem for managing books efficiently and affordably.

🚀 Project Overview

Book Nest addresses the problem of inaccessible or expensive books by connecting users who wish to sell, donate, or exchange their books. The platform simplifies book discovery and fosters a reading culture by promoting reuse.

🧩 Features

- 📖 Book listing with search and filters  
- 👤 Role-based access for Admin, Seller, and User  
- 🛒 Wishlist and Order management  
- 🧾 User authentication and profile management  
- 📦 File/image upload for book cover photos  
- 📊 Dashboard with analytics for sellers and admin

🏗️ Solution Architecture

The platform is built using the MERN stack:

- **Frontend:** React + Tailwind + Axios  
- **Backend:** Express.js + Node.js  
- **Database:** MongoDB with Mongoose  
- **Authentication:** JWT-based authentication  
- **File Handling:** Multer for image uploads
- 
📐 Data Flow

1. **User Registration/Login →** JWT token issued → Frontend stores token  
2. **Book Listing/Fetching →** API call to backend → MongoDB query → Response to frontend  
3. **Image Upload →** Multer handles multipart form → Stores in `uploads/`  
4. **Wishlist/Order →** User action → API call → DB update

📋 Installation & Setup
