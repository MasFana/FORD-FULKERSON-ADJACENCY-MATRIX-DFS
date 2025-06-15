# Visualisasi dan Implementasi Algoritma Ford-Fulkerson

Repositori ini berisi implementasi dan visualisasi algoritma *Ford-Fulkerson* untuk menyelesaikan masalah *Maximum Flow* pada graf. Proyek ini merupakan bagian dari Tugas Akhir Mata Kuliah **Desain dan Analisis of Algoritma**.

## Deskripsi Proyek

Ford-Fulkerson adalah algoritma klasik yang digunakan untuk mencari aliran maksimum (*maximum flow*) dari sumber (*source*) ke tujuan (*sink*) pada sebuah jaringan aliran (*flow network*). Dalam proyek ini, algoritma tersebut tidak hanya diimplementasikan secara fungsional, tetapi juga divisualisasikan secara interaktif menggunakan library `networkx` dan `matplotlib`.

## Anggota Kelompok

| Nama                          | NIM          |
| ----------------------------- | ------------ |
| Adrian Fathan Imama           | 232410103047 |
| Koniedo Tri Novendar Ramadhan | 232410103087 |
| Muhammad Rafi Kurniawan       | 232410103098 |

### Fitur Utama
- Implementasi algoritma Ford-Fulkerson dengan pencarian jalur augmentasi menggunakan DFS.
- Visualisasi interaktif dari setiap langkah augmentasi (penambahan aliran).
- Representasi graf menggunakan adjacency matrix.
- Dukungan tampilan label kapasitas dan aliran pada setiap sisi graf.
- Versi dengan dan tanpa visualisasi disediakan.


## Teknologi yang Digunakan

- Python 3.x
- [NetworkX](https://networkx.org/)
- [Matplotlib](https://matplotlib.org/)


## Struktur Berkas

- `VisualGraph`: Kelas dengan visualisasi graf dan pelacakan setiap augmenting path.
- `Graph`: Kelas implementasi algoritma tanpa visualisasi, untuk perbandingan atau pengujian cepat.
- `main`: Bagian yang menjalankan contoh penggunaan graf dan menghitung *maximum flow*.

## Contoh Visualisasi

Setiap langkah algoritma divisualisasikan sebagai berikut:
- Node biru menunjukkan simpul dalam graf.
- Panah merah menunjukkan jalur augmentasi saat ini.
- Label pada sisi menunjukkan `flow/capacity` saat ini.
- Flow akhir ditampilkan setelah semua augmenting path ditemukan.

## Cara Menjalankan

Pastikan telah menginstal dependensi berikut:

```bash
pip install networkx matplotlib
````

Kemudian buka file IPYNB:

## Referensi
* [Ford-Fulkerson Algorithm - GeeksForGeeks](https://www.geeksforgeeks.org/ford-fulkerson-algorithm-for-maximum-flow-problem/)
* [NetworkX Documentation](https://networkx.org/documentation/stable/)

