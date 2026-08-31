# analisis-sentimen-jasa-pengiriman-naive-bayes
Dataset penelitian analisis sentimen jasa pengiriman e - commerce menggunakan metode naive bayes
Repository ini berisi dataset penelitian untuk analisis sentimen terhadap jasa pengiriman e-commerce menggunakan metode Naive Bayes.

## Deskripsi

Penelitian ini menganalisis sentimen pengguna terhadap tiga jasa pengiriman, yaitu:

* SPX Express
* SiCepat
* Ninja Xpress

Data yang digunakan berupa komentar pengguna yang kemudian diberi label sentimen menjadi dua kategori, yaitu *Positif* dan *Negatif*.

## Dataset

Dataset penelitian terdiri dari tiga file berdasarkan jasa pengiriman:

| File                        | Jasa Pengiriman |
| --------------------------- | --------------- |
| dataset_spx_express.xlsx  | SPX Express     |
| dataset_sicepat.xlsx      | SiCepat         |
| dataset_ninja_xpress.xlsx | Ninja Xpress    |

Seluruh dataset telah melalui proses pelabelan sentimen dan digunakan dalam penelitian.

## Sumber Data

Data komentar diperoleh dari *Lacako.com* dan digunakan sebagai data penelitian untuk analisis sentimen.

## Metode

Metode klasifikasi yang digunakan adalah *Naive Bayes*.

Tahapan pengolahan data meliputi:

1. Pengumpulan data
2. Pelabelan sentimen
3. Transform Case
4. Tokenisasi
5. Stopword Removal
6. Filter Token by Length
7. Pembobotan TF-IDF
8. Klasifikasi menggunakan Naive Bayes
9. Evaluasi menggunakan Cross Validation

## Kategori Sentimen

Dataset menggunakan dua kategori sentimen:

* *Positif* — komentar yang menunjukkan kepuasan atau penilaian positif terhadap jasa pengiriman.
* *Negatif* — komentar yang menunjukkan ketidakpuasan atau penilaian negatif terhadap jasa pengiriman.

## Tools

Penelitian ini menggunakan:

* Microsoft Excel
* RapidMiner / Altair AI Studio
* Microsoft Word

## Tujuan Repository

Repository ini dibuat sebagai dokumentasi dan penyimpanan dataset yang digunakan dalam penelitian analisis sentimen jasa pengiriman e-commerce menggunakan metode Naive Bayes.
