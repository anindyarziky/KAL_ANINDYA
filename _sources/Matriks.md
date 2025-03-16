---
title: Matriks

---

## Matriks
### Definisi Matriks
Matriks adalah susunan bilangan atau objek matematika lainnya yang diatur dalam baris dan kolom. Dalam materi matriks terdapat istilah baris dan kolom yang membentuk persegi atau persegi panjang.

Contoh bentuk matriks 3 kali 3:

$$
\begin{bmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
0 & 1 & 1 \\
\end{bmatrix}
\quad
$$

### Operasi Aritmatika Matriks
### Operasi Penjumlahan dalam Matriks
Penjumlahan Operasi Aritmatika pada matriks memiliki syarat-syarat yang harus dipenuhi agar dapat menjumlahkan dua buah matriks. Caranya dapat dilakukan penambahan lebih dari satu suku matriks jika memiliki ukuran yang sama.

contoh:
$$
A =
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
$$

$$
B =
\begin{bmatrix}
5 & 6 \\
7 & 8
\end{bmatrix}
$$

$$
C = A + B =
\begin{bmatrix}
1+5 & 2+6 \\
3+7 & 4+8
\end{bmatrix}
=
\begin{bmatrix}
6 & 8 \\
10 & 12
\end{bmatrix}
$$

### Operasi Pengurangan dalam Matriks
Sama dengan operasi penjumlahan, operasi pengurangan dalam matriks juga harus memiliki ukuran yang sama agar dapat bisa di kurangkan.
contoh:

$$
A =
\begin{bmatrix}
7 & 8 \\
9 & 10
\end{bmatrix}
$$

$$
B =
\begin{bmatrix}
3 & 5 \\
2 & 1
\end{bmatrix}
$$

$$
C = A - B =
\begin{bmatrix}
7 - 3 & 8 - 2 \\
9 - 5 & 10 - 1
\end{bmatrix}
=
\begin{bmatrix}
4 & 6 \\
4 & 9
\end{bmatrix}
$$

### Operasi Perkalian dalam Matriks
Perkalian matriks adalah operasi aritmatika yang dilakukan antara dua matriks untuk menghasilkan matriks baru. Tidak seperti penjumlahan atau pengurangan, perkalian matriks memiliki aturan khusus.Dua matriks dapat dikalian jika jumlah kolom matriks pertama harus sama dengan jumlah baris matriks kedua.

contoh:

$$
A =
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
$$

$$
B =
\begin{bmatrix}
5 & 6 \\
7 & 8
\end{bmatrix}
$$


$$
C = A \times B =
\begin{bmatrix}
(1 \times 5 + 2 \times 7) & (1 \times 6 + 2 \times 8) \\
(3 \times 5 + 4 \times 7) & (3 \times 6 + 4 \times 8)
\end{bmatrix}
=
\begin{bmatrix}
(5 + 14) & (6 + 16) \\
(15 + 28) & (18 + 32)
\end{bmatrix}
=
\begin{bmatrix}
19 & 22 \\
43 & 50
\end{bmatrix}
$$
### Perkalian Matriks dengan Skalar
Operasi skalar pada matriks dilakukan dengan cara mengalikan semua elemen matriks dengan skalar tersebut.

contoh:

$$
A =
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
$$

$$
C = 3 \times A =
\begin{bmatrix}
3 \times 1 & 3 \times 2 \\
3 \times 3 & 3 \times 4
\end{bmatrix}
=
\begin{bmatrix}
3 & 6 \\
9 & 12
\end{bmatrix}
$$

## SOAL 
#### Selesaikan dengan menggunakan invers matriks, kemudian invers dicari menggunakan OBE

\begin{aligned}
    -7x_1 - 6x_2 - 12x_3 &= -33 \\
    5x_1 + 5x_2 + 7x_3 &= 24 \\
    x_1 + 4x_3 &= 5
\end{aligned}

### Penyelesaian:
1. Tuliskan dalam bentuk matriks

$$
Ax = b
$$

$
A =
$

$$
\begin{bmatrix}
    -7 & -6 & -12 \\
    5 & 5 & 7 \\
    1 & 0 & 4
\end{bmatrix}
$$

$
b =
$

\begin{bmatrix}
    -33 \\
    24 \\
    5
\end{bmatrix}

2. Menyusun matriks argumen, merubah bagian kiri menjadi matriks I sehingga bagian kanan berubah menjadi A invers.

$$
[A | I] 
$$

$$
\begin{bmatrix}
    -7 & -6 & -12 & | 1 & 0 & 0 \\
    5 & 5 & 7 & | 0 & 1 & 0 \\
    1 & 0 & 4 & | 0 & 0 & 1
\end{bmatrix}
$$

3.  Bagi baris pertama dengan -7, agar elemen (1,1) menjadi 1

\begin{bmatrix}
    1 & \frac{6}{7} & -\frac{12}{7} & \big| & -\frac{1}{7} & 0 & 0 \\
    5 & 5 & 7 & \big| & 0 & 1 & 0 \\
    1 & 0 & 4 & \big| & 0 & 0 & 1
\end{bmatrix}

4. Nol kan elemen di bawahnya menggunakan operasi:

$$
R_2 \leftarrow R_2 - 5R_1
$$ 

$$
R_3 \leftarrow R_3 - R_1
$$

\begin{bmatrix}
    1 & \frac{6}{7} & -\frac{12}{7} & \big| & -\frac{1}{7} & 0 & 0 \\
    0 & \frac{5}{7} & -\frac{13}{7} & \big| & \frac{5}{7} & 1 & 0 \\
    0 & -\frac{6}{7} & \frac{16}{7} & \big| & \frac{1}{7} & 0 & 1
\end{bmatrix}

5. Ubah elemen (2,2) menjadi 1, dengan cara baris kedua di bagi 5/7

$$
R_2 \leftarrow R_2 \times \frac{7}{5}
$$

\begin{bmatrix}
    1 & \frac{6}{7} & -\frac{12}{7} & \big| & -\frac{1}{7} & 0 & 0 \\
    0 & 1 & -\frac{13}{5} & \big| & 1 & \frac{7}{5} & 0 \\
    0 & -\frac{6}{7} & \frac{16}{7} & \big| & \frac{1}{7} & 0 & 1
\end{bmatrix}

6. Nol kan elemen di atas dan bawah (2,2) menggunakan operasi:

$$
R_1 \leftarrow R_1 - \frac{6}{7} R_2
$$

$$
R_3 \leftarrow R_3 - \frac{6}{7} R_2
$$

\begin{bmatrix}
    1 & 0 & \frac{102}{35} & -\frac{13}{35} & \big| & -\frac{6}{5} & 0 \\
    0 & 1 & -\frac{13}{5} & \frac{1}{5} & \big| & 1 & \frac{7}{5} & 0 \\
    0 & 0 & \frac{26}{35} & \frac{13}{26} & \big| & \frac{42}{26} & 0 & 1
\end{bmatrix}

7. Ubah elemen (3,3) menjadi 1, dengan cara baris ketiga dibagi dengan 26/35

$$
R_3 \leftarrow R_3 \times \frac{35}{26}
$$

\begin{bmatrix}
    1 & 0 & \frac{102}{35} & -\frac{13}{35} & \big| & -\frac{6}{5} & 0 \\
    0 & 1 & -\frac{13}{5} & \frac{1}{5} & \big| & 1 & \frac{7}{5} & 0 \\
    0 & 0 & 1 & \frac{13}{26} & \big| & \frac{42}{26} & \frac{35}{26} & 1
\end{bmatrix}

8. Nol kan elemen diatas (3,3)

$$
R_1 \leftarrow R_1 - \frac{102}{35} R_3
$$

diperoleh inversnya yaitu:

$
A^{-1} =
$

\begin{bmatrix}
    \frac{26}{35} & \frac{102}{65} & \frac{102}{91} \\
    -\frac{7}{5} & \frac{13}{5} & -\frac{35}{26} \\
    -\frac{13}{26} & -\frac{42}{26} & \frac{35}{26}
\end{bmatrix}

9. Kalikan A invers dengan b

$$
x = A^{-1} b
$$

$$
\begin{equation*}
\begin{bmatrix}
x_1\\
x_2\\
x_3
\end{bmatrix}=
\begin{bmatrix}
\frac{26}{35} & \frac{102}{65} & \frac{102}{91} \\
-\frac{7}{5} & \frac{13}{5} & -\frac{35}{26} \\
-\frac{13}{26} & -\frac{42}{26} & \frac{35}{26}
\end{bmatrix}
\begin{bmatrix}
-33\\
24\\
5
\end{bmatrix}
\end{equation*}
$$

Hasil akhirnya adalah

$$
x_1 = -1, \quad x_2 = 4, \quad x_3 = 2
$$