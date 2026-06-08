FinChain Secure Ledger adalah aplikasi sistem manajemen keuangan pribadi berbasis terminal (TUI) yang mengintegrasikan prinsip integritas data ala blockchain sederhana. 
Program ini dirancang untuk memberikan transparansi dan keamanan catatan keuangan pengguna dengan memanfaatkan struktur data in-memory yang efisien.
Sistem ini memastikan setiap transaksi yang terjadi tidak dapat dimanipulasi tanpa meninggalkan jejak, karena setiap entry transaksi terhubung satu sama lain melalui mekanisme hashing berbasis algoritma permutasi dan karakter unik.

Fitur Utama:
1. Secure Authentication: Sistem login dengan proteksi 3 kali percobaan untuk mencegah akses tidak sah, memastikan keamanan data sesi pengguna.
2. Financial Control Center: Manajemen aset yang komprehensif mencakup pemantauan saldo, alokasi anggaran (50/30/20), dan pelacakan target keuangan (Goal Tracker).
3. Cryptographic Transaction Ledger: Implementasi Transaction ID (TXID) unik yang dihasilkan melalui algoritma permutasi karakter, dilengkapi dengan mekanisme Previous Hash dan Current Hash untuk validasi rantai transaksi.
4. Automated Audit Log: Pencatatan otomatis (Audit Log) untuk setiap aktivitas pengguna, mulai dari manajemen dompet hingga perubahan status transaksi, memberikan transparansi penuh atas riwayat data.
5. TUI Visualization: Visualisasi kesehatan keuangan menggunakan representasi grafis progress bar berbasis matriks ANSI, memberikan insight real-time mengenai status anggaran (sehat/kurang sehat).

Spesifikasi Teknis:
1. Bahasa Pemrograman: C++ (Standard Template Library/STL).
2. Paradigma: Prosedural (menghindari penggunaan OOP, struct digunakan sebagai wadah data dasar).
3. Struktur Data: Penggunaan std::vector untuk penyimpanan dinamis dan ledger transaksi.
4. Keamanan: Algoritma hashing internal untuk validasi integritas data antar transaksi.
5. Antarmuka: Terminal User Interface (TUI) berbasis console dengan skema warna ANSI untuk keterbacaan data.
