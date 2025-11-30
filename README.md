# Maulana Futsal Booking

Sistem booking lapangan futsal online yang memudahkan pengguna untuk memesan lapangan futsal dengan mudah dan cepat. Aplikasi ini dibangun menggunakan Laravel dan Tailwind CSS untuk memberikan pengalaman pengguna yang optimal.

## 🎯 Fitur Utama

- **User Authentication**: Sistem login dan registrasi untuk pengguna
- **Booking Management**: Pesan lapangan futsal dengan jadwal yang fleksibel
- **Payment System**: Integrasi pembayaran untuk transaksi booking
- **Field Management**: Admin dapat mengelola lapangan dan jadwal
- **Schedule Management**: Sistem penjadwalan yang terstruktur
- **Responsive Design**: Desain yang responsif untuk semua perangkat

## 🛠️ Teknologi yang Digunakan

### Backend
- **Laravel 11**: PHP Framework untuk backend development
- **MySQL/MariaDB**: Database management system
- **Composer**: PHP package manager

### Frontend
- **Tailwind CSS**: Utility-first CSS framework
- **Vite**: Frontend build tool
- **JavaScript**: Untuk interaksi dinamis

### Development Tools
- **PHPUnit**: Testing framework
- **Git**: Version control

## 📋 Requirements

- PHP 8.2 atau lebih tinggi
- MySQL 10.4 atau MariaDB 10.4
- Composer
- Node.js & npm
- XAMPP (untuk development)

## ⚙️ Instalasi

1. **Clone Repository**
   ```bash
   git clone https://github.com/lana-techn/Laravel-Web-Futsal-Booking.git
   cd "Maulana Futsal Booking"
   ```

2. **Install Dependencies PHP**
   ```bash
   composer install
   ```

3. **Install Dependencies Node.js**
   ```bash
   npm install
   ```

4. **Setup Environment**
   ```bash
   cp .env.example .env
   ```

5. **Generate Application Key**
   ```bash
   php artisan key:generate
   ```

6. **Database Migration & Seeding**
   ```bash
   php artisan migrate
   php artisan db:seed
   ```

7. **Build Frontend Assets**
   ```bash
   npm run build
   ```

8. **Start Development Server**
   ```bash
   php artisan serve
   ```

## 📊 Struktur Database

### Tabel Utama
- **users**: Data pengguna (admin dan regular user)
- **fields**: Data lapangan futsal
- **schedules**: Jadwal ketersediaan lapangan
- **bookings**: Data pemesanan lapangan
- **payments**: Data pembayaran

## 👤 Default Credentials

Setelah seeding, Anda dapat login dengan:
- **Email**: `admin@gmail.com`
- **Password**: *(Reset dengan password baru)*
- **Role**: Admin

## 📸 Screenshot Aplikasi

### Dashboard Admin
![Dashboard](assets/Screenshot%202025-11-30%20at%2018.48.38.png)

### Halaman Lapangan
![Lapangan List](assets/Screenshot%202025-11-30%20at%2018.48.48.png)

### Detail Lapangan
![Lapangan Detail](assets/Screenshot%202025-11-30%20at%2018.48.56.png)

### Form Booking
![Form Booking](assets/Screenshot%202025-11-30%20at%2019.00.14.png)

### Konfirmasi Booking
![Konfirmasi Booking](assets/Screenshot%202025-11-30%20at%2019.01.00.png)

### Halaman Payment
![Payment Page](assets/Screenshot%202025-11-30%20at%2019.01.12.png)

### Invoice/Receipt
![Invoice](assets/Screenshot%202025-11-30%20at%2019.01.22.png)

### Booking History
![History](assets/Screenshot%202025-11-30%20at%2019.01.29.png)

## 🚀 Deployment

### Production Build
```bash
npm run build
```

### Run Tests
```bash
php artisan test
```

## 📁 Struktur Project

```
├── app/
│   ├── Console/
│   ├── Exceptions/
│   ├── Http/
│   │   ├── Controllers/
│   │   ├── Middleware/
│   │   └── Requests/
│   ├── Models/
│   ├── Providers/
│   └── Services/
├── config/
├── database/
│   ├── factories/
│   ├── migrations/
│   └── seeders/
├── public/
├── resources/
│   ├── css/
│   ├── js/
│   └── views/
├── routes/
├── storage/
├── tests/
├── vendor/
└── ...
```

## 🔐 Keamanan

- Password di-hash menggunakan bcrypt
- CSRF protection untuk semua form
- Middleware authentication untuk protected routes
- Input validation pada semua endpoint

## 📝 API Routes

Aplikasi ini menggunakan RESTful API dengan route management di:
- `routes/web.php` - Web routes
- `routes/api.php` - API routes
- `routes/console.php` - Artisan commands

## 🤝 Contributing

Silakan buat pull request untuk berkontribusi pada project ini.

## 📄 License

Project ini adalah project pribadi/pembelajaran.

## 👨‍💻 Author

- **Nama**: [Your Name]
- **GitHub**: [@lana-techn](https://github.com/lana-techn)
- **Email**: admin@gmail.com

## 📞 Support

Jika Anda menemukan bug atau memiliki pertanyaan, silakan buat issue di GitHub repository.

---

**Last Updated**: November 30, 2025
