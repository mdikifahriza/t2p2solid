# T2P2Solid

## Deskripsi

Proyek **T2P2Solid** adalah aplikasi berbasis Next.js yang terintegrasi dengan Supabase sebagai backend untuk autentikasi, database, dan penyimpanan file.

## Persyaratan

* Node.js (minimal versi 15)
* npm atau yarn
* Akun Supabase (jika ingin menggunakan database sendiri)

## Instalasi

1. Clone repository ini ke komputer lokal Anda:

   ```bash
   git clone https://github.com/mdikifahriza/t2p2solid.git
   ```

2. Masuk ke folder proyek:

   ```bash
   cd t2p2solid
   ```

3. Instal semua dependensi:

   ```bash
   npm install
   ```

4. **Jika menggunakan Supabase sendiri:**

   * Buat project baru di [Supabase](https://supabase.com/).
   * Salin **Project URL** dan **anon key** dari dashboard Supabase.
   * Sesuaikan isi `.env.local` dengan kredensial Supabase Anda.
   * Sesuaikan struktur database sesuai dengan file `skema database.txt` yang ada di root project.

6. **Jika tidak disesuaikan:**

   * Secara default, aplikasi akan menggunakan Supabase milik saya, baik database maupun storage.

## Menjalankan Proyek

Untuk menjalankan proyek di mode pengembangan:

```bash
npm run dev
```

Aplikasi akan berjalan di `http://localhost:3000`

## Deployment

Proyek ini dapat dengan mudah di-deploy ke [Vercel](https://vercel.com/) karena berbasis Next.js dan sudah sesuai standar EsLint.

