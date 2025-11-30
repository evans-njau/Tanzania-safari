# Tanzania Safari

**Tanzania Safari** is a web application built with **Laravel** to provide tourists and travelers with a comprehensive guide to exploring the natural beauty and cultural attractions of Tanzania. The platform highlights national parks, safaris, and tourist services, helping users plan unforgettable trips.

---

## Table of Contents

1. [About the Project](#about-the-project)  
2. [Features](#features)  
3. [Tourism Highlights](#tourism-highlights)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Technologies](#technologies)  
7. [Contributing](#contributing)  
8. [License](#license)  

---

## About the Project

Tanzania Safari provides a user-friendly interface for exploring Tanzania’s **wildlife, national parks, cultural experiences, and travel packages**. Users can:

- Browse top safari destinations  
- View wildlife information and park details  
- Access travel tips and recommended itineraries  

---

## Features

- Search and filter national parks and wildlife  
- Interactive maps of safari destinations  
- User accounts to save favorite trips  
- Travel package booking interface (optional/future)  
- Responsive design for mobile and desktop  

---

## Tourism Highlights

Content related to Tanzanian tourism includes:  

- **National Parks & Reserves:** Serengeti, Ngorongoro Crater, Tarangire, Lake Manyara, Selous Game Reserve  
- **Wildlife:** Lions, elephants, giraffes, zebras, wildebeests (Great Migration)  
- **Beaches & Islands:** Zanzibar, Pemba, Mafia Island  
- **Cultural Experiences:** Maasai villages, local markets, traditional festivals  
- **Adventure Activities:** Mount Kilimanjaro trekking, hot air balloon rides, safari tours  
- **Travel Tips:** Best visiting seasons, park fees, safety guidelines  

---

## Installation

Clone the repository:

```bash
git clone https://github.com/evans-njau/Tanzania-safari.git
cd tanzania-safari
```
## Install PHP dependencies:
```bash
composer install
```

## Install frontend dependencies (if using Vite/NPM):
```bash
npm install
npm run dev
```

## Set up your environment variables:
```bash
cp .env.example .env
php artisan key:generate
```

## Run database migrations:
```bash
php artisan migrate
```

## Start the local server:
```bash
php artisan serve
```

## Access the app at: http://localhost:8000

# Usage

Browse national parks and wildlife information

Filter safaris by location, activity, or price

Save favorite destinations to your account

# Technologies

Backend: PHP 8.x, Laravel

Frontend: Blade templates, HTML, CSS, JS, optionally Vue.js/React

Database: MySQL / SQLite / PostgreSQL

Version Control: Git & GitHub

# Contributing

Fork the repository

Create a feature branch: git checkout -b feature/your-feature

Commit your changes: git commit -m "Add feature"

Push to the branch: git push origin feature/your-feature

Open a Pull Request

