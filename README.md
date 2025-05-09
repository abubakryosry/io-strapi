# 🌐 IO TECH Strapi CMS  

The **Al Safar Strapi CMS** serves as the backend for the **Al Safar multilingual website**, built with **Strapi**. It features a flexible content management system supporting both **Arabic** and **English** content.  

## 🚀 Technologies Used  
- **Strapi (Node.js)**: Headless CMS for managing and delivering content.  
- **PostgreSQL**: Database for storing multilingual content.  
- **Cloudinary**: Efficient image and video management.  
- **JWT Authentication**: Secure user access and content management.  

---

## 🌟 Features  
- **Multilingual Content Management (Arabic/English)**  
  - Create and update content seamlessly for both languages.  
- **Media Library**  
  - Upload and manage images and videos with **Cloudinary**.  
- **Custom Content Types**  
  - **Hero Section**: Supports both image and video slides.  
  - **Team Members**: Profiles with names, positions, and photos.  
  - **Client Showcase**: Logos and testimonials.  
- **API Integration**  
  - RESTful API endpoints for the Next.js frontend.  
- **Role-Based Access**  
  - Admin and Editor roles for secure content updates.  

---

## 🛠️ Installation  

### 1. Clone the repository:  
```bash
git clone https://github.com/abubakryosry/iotech-strapi.git
cd iotech-strapi
```

### 2. Install dependencies:
```bash
npm install
```

### 3. Create a `.env` file and configure environment variables:
```ini
DATABASE_CLIENT=postgres
DATABASE_HOST=localhost
DATABASE_PORT=5432
DATABASE_NAME=iotech-db
DATABASE_USERNAME=your-username
DATABASE_PASSWORD=your-password
CLOUDINARY_NAME=your-cloudinary-name
CLOUDINARY_KEY=your-cloudinary-key
CLOUDINARY_SECRET=your-cloudinary-secret
```

### 4. Start the development server:
```bash
npm run develop
```

### 5. Access the Strapi admin panel:
Visit: [http://localhost:1337/admin](http://localhost:1337/admin)