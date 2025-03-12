# Proses Normalisasi Database
Normalisasi database adalah proses pengorganisasian data dalam suatu basis data untuk mengurangi `redundansi` dan meningkatkan `integritas data`.

## Tujuan Normalisasi database adalah

- Menghilangkan Redudansi Data
- Mengurangi Kompleksitas Data
- Mempermudah proses analis dan pengornasisasian data

## Unnormal
`Unnormalized Form (UNF)` atau bentuk yang tidak dinormalisasi adalah tahap awal di mana data belum terstruktur dengan baik, mengandung duplikasi dan inkonsistensi, sehingga menyebabkan masalah saat melakukan manipulasi data. 

![Screenshot 2025-03-12 at 23 28 16](https://github.com/user-attachments/assets/8579ee0f-a492-47b6-9df7-8ad2390974cf)

## 1NF
`First Normal Form (1NF)` Sebuah tabel dikatakan berada pada bentuk normal pertama atau INF bila menuhi beberapa syarat berikut

- Tidak memiliki atribut multi-value (tidak ada kelompok-kelompok data yang berulang)
- Setiap sel hanya memiliki satu nilai tunggal yang unik

Pada tingkatan ini, tabel yang mengandung elemen-elemen berulang dipecah menjadi tabel-tabel yang lebih kecil.

![Screenshot 2025-03-12 at 23 31 42](https://github.com/user-attachments/assets/837a5fd4-a63e-43ef-bffe-df8da2a44ee1)

## 2NF
`Second Normal Form (2NF)` Tabel berada pada bentuk normal kedua jika sudah memenuhi aturan 1NF dan semua atribut non-kunci bergantung pada primary key. Pada tingkatan ini, semua atribut yang tidak terkait langsung dengan primary key dipindahkan ke tabel lain. Berikut beberapa syarat yang wajib dipenuhi tahapan 2NF dalam normalisasi database

- Seluruh atribut harus bergantung pada Primary Key
- Bila ditemuai adanya ketergantungan parsial, maka atribut tersebut harus di pisah di table lain dan harus dibantu dengan foreign key

![Screenshot 2025-03-12 at 23 33 02](https://github.com/user-attachments/assets/d2b7c104-58bd-4fcf-bc2f-9cac408b5b50)

## 3NF
`Third Normal Form (3NF)` Tabel berada pada bentuk normal ketiga semua atribut non-kunci yang bergantung pada atribut non-kunci lainnya dipindahkan ke tabel lain, sehingga semua atribut non-kunci bergantung langsung pada kunci utama. Berikut beberapa syarat yang wajib dipenuhi tahapan 3NF dalam normalisasi database

- Tidak ada ketergantungan transitif (atrubut bukan kunci bergantung pada atribut kunci lainnya)

![Screenshot 2025-03-12 at 23 33 58](https://github.com/user-attachments/assets/8043ba9e-f7b1-4ae4-9d36-e7c75e839bb5)

## ERD
Setelah proses Normalisasi tersebut kita dapat simpulkan Entity Relation Diagram adalah sebagai berikut

<img src="https://raw.githubusercontent.com/asepseptiyadi/learning-repo/refs/heads/master/analisis-sistem/proyek-absensi-siswa/ERD/ERD%20-%20Absensi%20Siswa.png" />
