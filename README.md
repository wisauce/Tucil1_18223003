# Queens Solver — Brute Force

## Deskripsi Program

Program ini merupakan implementasi algoritma brute force untuk menyelesaikan permainan Queens pada papan berwarna. Program akan membaca konfigurasi papan dari file `.txt`, kemudian mencoba seluruh kemungkinan penempatan queen dengan memilih satu petak dari setiap region warna.

Setiap konfigurasi yang dihasilkan akan divalidasi berdasarkan aturan permainan:

* satu queen pada setiap baris
* satu queen pada setiap kolom
* satu queen pada setiap region warna
* tidak ada queen yang bersebelahan secara diagonal

Program dilengkapi dengan Graphical User Interface (GUI) untuk memuat papan, menampilkan proses pencarian solusi, serta menyimpan hasil dalam bentuk file teks atau gambar.

## Requirement Program

Program dibuat menggunakan Python.

Requirement:

* Python 3.x
* tkinter
* Pillow

Instalasi Library Pillow:

```
pip install pillow
```

atau jika menggunakan UV

```
uv add pillow
```


## Cara Kompilasi

Program tidak memerlukan proses kompilasi karena menggunakan Python.

## Cara Menjalankan Program

Jalankan file utama dengan perintah berikut:

```
python main.py
```

atau jika menggunakan uv

```
uv run main.py
```

Langkah penggunaan:

1. Klik tombol **Load File** untuk memilih file papan `.txt`.
2. Klik **Solve** untuk menjalankan algoritma brute force.
3. Gunakan **Save as Text** untuk menyimpan solusi dalam file `.txt`.
4. Gunakan **Save as Image** untuk menyimpan solusi dalam bentuk gambar (memerlukan Pillow).

Format input papan:

* File `.txt` berisi papan persegi.
* Setiap karakter merepresentasikan warna region.

Contoh:

```
AABB
AABB
CCDD
CCDD
```

## Author

Nama: Wisa Ahmaduta Dinutama
NIM: 18223003