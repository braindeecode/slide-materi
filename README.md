# 🚀 Modul 01: NestJS Dasar

Selamat datang di modul pertama dari seri pembelajaran NestJS!

Di branch ini, kamu akan menemukan semua materi yang digunakan dalam playlist **Tutorial NestJS Dasar untuk Pemula** di channel **Brain Dee Code**. Modul ini adalah titik awal yang paling penting untuk memahami "cara berpikir" NestJS sebelum melangkah ke implementasi fitur yang lebih kompleks.

---

## 📂 Isi Branch Ini

- `slides.md`: Berisi slide presentasi dalam format Marp untuk membuat slides.
- `slides.pdf`: Merupakan slides yang digunakan untuk proses pembelajaran.

---

## 📄 Source Code

Source code pembelajaran dari modul ini dapat di akses di repository `tutorial-nestjs-01-nestjs-dasar`.
[Lihat repository](https://github.com/braindeecode/tutorial-nestjs-01-nestjs-dasar)

---

## 📚 Topik yang Dibahas

Link yang tidak bisa diakses kemungkinan karena belum di publish.

| No. | Judul Video Materi                         | Deskripsi Singkat                                                                                                                     | Link YouTube                                    |
| :-- | :----------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------ | :---------------------------------------------- |
| 1   | Pendahuluan & Pengenalan NestJS            | Pengenalan seri, serta apa itu NestJS, mengapa dibuat, dan keunggulannya dibanding framework lain.                                    | [▶️ Tonton Video](https://youtu.be/y1j7cIKiwMA) |
| 2   | Proyek Pertama: Nest CLI & Struktur Folder | Menggunakan NestJS CLI untuk membuat proyek baru dan memahami struktur folder yang dihasilkan.                                        | [▶️ Tonton Video](https://youtu.be/2wL49I1qVUA) |
| 3   | Decorator                                  | Penjelasan singkat tentang apa itu Decorator (`@`) dan mengapa ini sangat fundamental di NestJS.                                      | [▶️ Tonton Video](https://youtu.be/_4D6eEm9yxI) |
| 4   | Modules                                    | Memahami `@Module` sebagai "wadah" untuk mengelompokkan _controllers_, _providers_, dan modul lainnya.                                | [▶️ Tonton Video](https://youtu.be/wPC8phVcWI4) |
| 5   | Controllers & Routing                      | Memahami `@Controller` dan decorator method (`@Get`, `@Post`, dll.) untuk menangani routing                                           | [▶️ Tonton Video](https://youtu.be/sG3z31QjdN8) |
| 6   | HTTP Request & Response                    | Memahami cara mengakses data request dan response objek dengan menggunakan decorator `@Req`, `@Res`, `@Param`, `@Query`, dan `@Body`. | [▶️ Tonton Video](https://youtu.be/kFQrv4WTn3Y) |
| 7   | Providers & Services                       | Memahami `@Injectable` dan pentingnya memisahkan logika bisnis dari _controller_ ke dalam _service_.                                  | [▶️ Tonton Video](https://youtu.be/CkE68AJ5sOA) |
| 8   | Dependency Injection (DI)                  | Penjelasan mendalam tentang bagaimana NestJS secara otomatis mengelola dan menyediakan _instance_ (misal: Service ke Controller).     | [▶️ Tonton Video](https://youtu.be/thhyxiOZZ6I) |
| 9   | DTO (Data Transfer Object) & Request Body  | Mengenal DTO sebagai cetak biru data, dan cara menangani data yang masuk melalui _request body_ (`@Body`).                            | [▶️ Tonton Video](https://youtu.be/xeQNycP_M6Q) |
| 10  | Mengelola Cookie                           | Cara membaca dan mengatur _cookie_ serta mengontrol _response_ HTTP secara manual jika diperlukan.                                    | [▶️ Tonton Video](https://youtu.be/YJswlRgeZNo) |
| 11  | Asynchronous Programming                   | Praktik standar penggunaan `async/await` di dalam _controller_ dan _service_ untuk menangani operasi yang memakan waktu.              | [▶️ Tonton Video](https://youtu.be/k3Ky9eGQsIw) |
| 12  | Request Lifecycle                          | Visualisasi diagram urutan proses request: `Middleware` -> `Guard` -> `Interceptor` -> `Pipe` -> `Controller`.                        | [▶️ Tonton Video](https://youtu.be/Y8DlPhffrLs) |
| 13  | Middleware                                 | Cara kerja Middleware untuk intervensi paling awal pada request, dengan contoh membuat logger sederhana.                              | [▶️ Tonton Video](https://youtu.be/AcGP6JVKp0M) |
| 14  | Guards                                     | Konsep `Guard` untuk mengizinkan atau menolak akses ke sebuah _route_, dengan contoh `ApiKeyGuard`.                                   | [▶️ Tonton Video](https://youtu.be/R9BvHbzcNAc) |
| 15  | Pipes                                      | Konsep `Pipe` untuk mengubah atau memvalidasi data yang masuk sebelum sampai ke _controller_.                                         | [▶️ Tonton Video](https://youtu.be/rf4dWjCSglE) |
| 16  | Exception Filters                          | Cara menangkap semua _error_ secara terpusat dan mengirimkan _response_ error yang konsisten.                                         | [▶️ Tonton Video](https://youtu.be/sqhs0dlpf20) |
| 17  | Interceptors                               | Konsep _Aspect-Oriented Programming_ untuk memodifikasi _request/response_ atau menambahkan logika di sekeliling _handler_.           | [▶️ Tonton Video](https://youtu.be/RFvV2S54cmU) |
| 18  | Custom Decorators                          | Cara membuat decorator Anda sendiri (misal: `@User()`) untuk menyederhanakan pengambilan data dari _request_.                         | [▶️ Tonton Video](https://youtu.be/vW_dtryoyWU) |
| 19  | Reflector & Metadata                       | Cara menggunakan `Reflector` untuk membaca metadata kustom, berguna untuk membuat Guard atau Interceptor yang dinamis.                | [▶️ Tonton Video](https://youtu.be/vyy9ZHUDgIs) |
| 20  | Manajemen Configurasi                      | Menggunakan modul `@nestjs/config` untuk mengelola variabel lingkungan agar tidak ada _hardcoding_.                                   | [▶️ Tonton Video](https://youtu.be/_pMvv5MHOo8) |
| 21  | Lifecycle Events                           | Menjalankan kode pada momen-momen spesifik seperti `OnModuleInit` atau `OnApplicationBootstrap`.                                      | [▶️ Tonton Video](https://youtu.be/9m7fbXfnRgY) |
| 22  | Global Modules & Providers                 | Memahami decorator `@Global` untuk membuat sebuah modul atau provider tersedia di seluruh aplikasi.                                   | [▶️ Tonton Video](https://youtu.be/FjnrUBEPm-Q) |
| 23  | Dynamic Modules                            | Konsep `forRoot()` untuk membuat modul yang dapat dikonfigurasi, kunci untuk membuat _library_ yang _reusable_.                       | [▶️ Tonton Video](https://youtu.be/mTzffU7Q2_Q) |
| 24  | Custom Providers                           | Cara menyediakan _provider_ dengan logika yang lebih kompleks, misalnya yang memiliki dependensi lain.                                | [▶️ Tonton Video](https://youtu.be/t-wUOGwbgKI) |
| 25  | ModuleRef                                  | Fitur _advanced_ untuk mengakses _provider_ secara terprogram dari dalam _DI Container_.                                              | [▶️ Tonton Video](https://youtu.be/TzewIyWw-3c) |
| 26  | Penutup                                    | Rangkuman semua konsep fundamental yang telah dipelajari dan jembatan ke modul selanjutnya.                                           | [▶️ Tonton Video](https://youtu.be/vImQsUgCuts) |

---

## 🧭 Navigasi

Gunakan link di bawah ini untuk berpindah antar modul.

| Sebelumnya                                                                                  | Berikutnya                                                                                                                         |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------- |
| [⬅️ Kembali ke Menu Utama (main)](https://github.com/braindeecode/materi-youtube/tree/main) | [Lanjut ke Modul 02: Studi Kasus Dasar ➡️](https://github.com/braindeecode/materi-youtube/tree/nestjs/02-studi-kasus-nestjs-dasar) |
