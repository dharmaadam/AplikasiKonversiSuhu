# Aplikasi Konversi Suhu

## Deskripsi Program
Aplikasi ini memungkinkan pengguna untuk:
- Memasukkan nilai suhu dalam suatu skala (misalnya Celcius).
- Memilih jenis konversi yang diinginkan (misalnya ke Fahrenheit, Kelvin, atau Reamur).
- Menampilkan hasil konversi setelah tombol diklik.

## Logika Program
1. **Konversi Suhu**:
   - Menggunakan rumus untuk mengonversi antara Celcius, Fahrenheit, Kelvin, dan Reamur.
2. **Validasi Input**:
   - Memastikan input berupa angka.
   - Menampilkan pesan error dengan `JOptionPane` jika input tidak valid.
3. **Pengelolaan Event**:
   - `ActionListener` untuk tombol Konversi.
   - `KeyAdapter` untuk membatasi input hanya angka.
   - `ItemListener` pada `JRadioButton` untuk memilih arah konversi.
