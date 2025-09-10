# 💍 Wedding Website Generator

A modern **Laravel-powered application** that allows couples to create their own personalized wedding website.  
The platform provides event management, interactive features, and customizable themes, enabling couples to beautifully showcase their wedding details in a sleek, elegant format.  

---

## ✨ Features

- **Dynamic Event Management**  
  - Add, edit, and delete wedding events with date and time.  
  - Built-in **Add to Calendar** feature so guests can save events directly.  

- **Location Details**  
  - Add multiple event locations.  
  - **Google Maps integration** for easy navigation.  

- **Bride & Groom Profiles**  
  - Customize with photos, names, and family details.  

- **Image Gallery**  
  - Upload and display wedding photos.  
  - Share memories and build excitement before the event.  

- **Customizable Themes**  
  - Choose from multiple elegant designs.  
  - Preview themes instantly.  
  - Styled with **Tailwind CSS** for flexibility.  

- **Countdown Timer**  
  - Display a live countdown to the wedding day.  

- **Extra Details**  
  - Add personalized messages or descriptions for guests.  

---

## 🛠 Technology Stack

- [Laravel](https://laravel.com/) – Backend & routing  
- [Tailwind CSS](https://tailwindcss.com/) – Styling & themes  
- [AJAX](https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX) – Seamless interactivity  
- [MySQL](https://www.mysql.com/) – Database storage  

---

## 📋 Prerequisites

Make sure you have the following installed:

- PHP >= 8.0  
- Composer  
- Node.js & NPM  
- MySQL (or compatible database)  

---

## 🚀 Installation & Setup

1. **Clone the repository**  
git clone https://github.com/mistrydarshan222/WeddingInvite-Laravel/
cd Wedding-Website-Generator 

2. Install PHP dependencies
composer install

# 3. Install Node.js dependencies
npm install

# 4. Configure environment
cp .env.example .env   # copy example env file
# Open .env in your editor and update database credentials & other settings

# Generate application key
php artisan key:generate

# 5. Run migrations
php artisan migrate

# 6. Compile frontend assets
# For development
npm run dev

# For production
npm run production

# 7. Start the development server
php artisan serve



