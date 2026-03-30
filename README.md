# 🐾 Pet Adoption System  
### A Full-Stack Web-Based Pet Adoption & Management Platform

---

## 📌 Project Overview

The **Adoption System** is a web-based application developed using **PHP and MySQL** that streamlines the pet adoption process.

It connects potential adopters with pet owners while also providing an integrated platform for browsing pet accessories and care resources.

This project demonstrates strong understanding of:

- Backend logic implementation  
- Database integration  
- User authentication systems  
- CRUD operations  
- Modular project structuring  
- Version control using Git  

---

## 🌟 Key Highlights

### 🐾 Find Your Perfect Companion  
Explore a wide range of pets — from adorable puppies to charming kittens — all seeking loving homes. Users can browse detailed pet listings and initiate adoption requests easily.

### 🏠 User-Friendly Interface  
Designed for smooth navigation and accessibility, the platform allows users to:

- Register and log in securely  
- Browse available pets  
- Submit adoption forms  
- Manage user profiles  
- Access pet care resources  

### 🛍️ Integrated Pet Essentials Store  
Beyond adoption services, the platform includes an integrated e-commerce section where users can shop for:

- Pet accessories  
- Toys  
- Basic care essentials  

This creates a complete pet-care ecosystem within one platform.

### 🌟 Empowering Pet Owners  
Pet owners can list pets for adoption, fostering collaboration between adopters and individuals looking to responsibly rehome their pets.

---

## 🛠️ Tech Stack

| Layer            | Technology Used |
|------------------|----------------|
| Frontend         | HTML, CSS |
| Backend          | PHP |
| Database         | MySQL |
| Server           | XAMPP (Apache) |
| Version Control  | Git & GitHub |

---

## 🔐 Core Functional Modules

### 👤 User Module
- User Registration & Login  
- Profile Management  
- Session Handling  
- Secure Authentication  

### 🐶 Pet Management Module
- Add Pet (Admin)  
- Remove Pet (Admin)  
- View Pet Listings  
- Adoption Request Workflow  

### 🛒 Accessories Module
- Browse Pet Products  
- Add to Cart Functionality  

### 📄 Informational Module
- About Page  
- Donation Page  
- Pet Care Resources  

---

## 📂 Project Structure
```

ppet-adoption-website/
│
├── admin/                  # Admin panel (manage pets, users, adoptions)
├── css/                    # Stylesheets (UI design)
├── db_img/                 # Images stored from database (uploaded pets)
├── img/                    # Static images (icons, banners, UI assets)
├── videos/                 # Video related to pets
│
├── about.php               # About page
├── accessories.php         # Pet accessories page
├── add_pet.php             # Add new pet (admin/user)
├── adoption_form.php       # Pet adoption form
├── adoption.php            # Adoption listings page
├── dbconn.php              # Database connection file
├── donate.php              # Donation page
├── footer.php              # Footer component (reusable)
├── header.php              # Header/navigation (reusable)
├── index.php               # Homepage
├── login.php               # User login
├── logout.php              # Logout functionality
├── pet-cart.php            # Cart for selected pets (if applicable)
├── profile.php             # User profile page
├── remove_pet.php          # Remove pet (admin/user)
├── resources.php           # Helpful resources page
├── signup.php              # User registration
│
└── Documentation.pdf       # Project documentation
```

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

1. Install **XAMPP** (or any PHP & MySQL server)
2. Move the project folder to:
C:/xampp/htdocs/

3. Start the following services in XAMPP:
- Apache  
- MySQL  

4. Set up the database:
- Open **phpMyAdmin**
- Create a new database
- Import the provided `.sql` file  

5. Run the project in your browser:
   http://localhost/pet-adoption-website-mini-project

   
---

## 🌟 Features

- 🐾 **Browse Pets**  
Discover pets available for adoption, including puppies and kittens.

- 📝 **Adoption Requests**  
Fill out and submit adoption forms بسهولة.

- 👤 **User Accounts**  
Sign up, log in, and manage your profile.

- 🛍️ **Pet Accessories**  
Explore products like toys, food, and other essentials.

- 📚 **Resources & Support**  
Access useful pet care and adoption information.

- 🛠️ **Admin Panel**  
Manage pets, users, and adoption listings.
