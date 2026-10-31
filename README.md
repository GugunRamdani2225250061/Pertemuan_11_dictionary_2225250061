# Pertemuan 11_Dictionary/Map

- Nama: Gugun Ramdani  
- NIM: 2225250061
- Kelas: 3A 
- Program Studi: S1 Pendidikan Matematika

## 1. Tujuan
Mempelajari dan menerapkan struktur data dictionary dalam Python untuk memodelkan data pendidikan menggunakan pasangan key-value, melakukan pencarian, penambahan, perubahan, penghapusan, dan menampilkan data.

## 2. Struktur Data
Program menggunakan dictionary dengan NIM sebagai key utama.
Setiap value berupa dictionary yang memiliki tiga atribut:
- Nama mahasiswa.
- Kelas mahasiswa.
- Nilai mahasiswa.

Contoh:
```python
"A001": {
    "nama": "Ayu",
    "kelas": "A",
    "nilai": 85
}
```
## 3. Daftar File
- Folder latihan berisi:
1. 01_dasar_dictionary.py
2. 02_akses_get.py
3. 03_manipulasi_dictionary.py
4. 04_iterasi_dictionary.py
5. 05_dictionary_bersarang.py
6. 06_fungsi_dictionary.py
   
- Folder praktik berisi:
  data_mahasiswa.py
- kuis formatif_pertemuan 11.docx
- .gitignore

## 4. Cara Menjalankan
Pastikan Python 3 sudah terpasang.
Jalankan melalui terminal VS Code:
```bash
python praktik/data_mahasiswa.py
```
## 5. Test Case
| Pengujian | Hasil |
|---|---|
| Pencarian A003 | Data Citra ditemukan |
| Pencarian A999 | Data tidak ditemukan |
| Perubahan nilai A002 | Nilai menjadi 82 |
| Penambahan A006 | Data Fajar berhasil ditambahkan |
| Rekap data | Seluruh data mahasiswa tampil |
| Rata-rata nilai | 83,50 |

## 6. Refleksi
Kesalahan yang dapat terjadi dalam penggunaan dictionary adalah KeyError, yaitu ketika program mengakses key yang tidak tersedia.

Kesalahan tersebut dapat diperbaiki dengan menggunakan method get() atau memeriksa keberadaan key menggunakan operator in sebelum mengakses data.

Melalui praktikum ini, saya memahami bahwa dictionary lebih tepat digunakan untuk menyimpan data yang memiliki identitas tertentu, seperti NIM mahasiswa. Saya juga memahami penggunaan dictionary bersarang, iterasi items(), serta fungsi untuk mempermudah pengolahan data.

## 7. Kesimpulan
Dictionary merupakan struktur data Python yang menyimpan pasangan key-value. Dengan dictionary, pencarian dan pengelolaan data mahasiswa dapat dilakukan secara lebih terstruktur, efektif, dan mudah dipahami.
