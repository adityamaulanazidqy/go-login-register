# Go Session Auth

Go Session Auth adalah aplikasi autentikasi sederhana yang dibangun menggunakan bahasa pemrograman Go. Aplikasi ini memungkinkan pengguna untuk mendaftar, masuk, dan mengelola sesi mereka dengan aman.

## Fitur

- Pendaftaran pengguna baru
- Autentikasi pengguna dengan username dan password
- Manajemen sesi pengguna
- Validasi input dengan pesan kesalahan yang jelas
- Menggunakan bcrypt untuk hashing password

## Teknologi yang Digunakan

- Go (Golang)
- Gorilla Sessions
- Bootstrap (untuk tampilan)
- Validator (untuk validasi input)

## Instalasi

1. **Clone repositori ini:**

   ```bash
   git clone https://github.com/username/go-auth.git
   cd go-auth
   ```

2. **Instal dependensi:**

   ```bash
   go mod tidy
   ```

3. **Jalankan aplikasi:**

   ```bash
   go run main.go
   ```

## Penggunaan

1. **Registrasi:**

- Akses halaman pendaftaran di `http://localhost:8080/register`.
- Isi formulir pendaftaran dan klik "SIGN UP".

2. **Login:**

- Akses halaman login di `http://localhost:8080/login`.
- Isi formulir pendaftaran dan klik "SIGN IN".

3. **Logout:**

- Setelah masuk, Anda dapat keluar dengan mengakses endpoint logout.

## Kontak

Jika Anda memiliki pertanyaan atau saran, silakan hubungi saya di adityamaullana234@gmail.com.
