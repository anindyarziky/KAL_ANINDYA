---
title: Penyelesaian sistem persamaan linear

---
## PENYELESAIAN SISTEM PERSAMAAN LINEAR
### Operasi Baris Elementer
1. Menukar baris pertama dengan baris kedua 
2. Perkalian satu baris dengan konstanta non-Nol
3. Penjumlahan satu baris dengan konstanta non-Nol dengan baris yang lain.
### Eleminasi Gauss
Eliminasi gauss ini dapat dimanfaatkan untuk memecahkan sistem persamaan linear dengan merepresentasikan mengubah menjadi bentuk matriks, matriks tersebut lalu diubah kebentuk Eselon Baris melalui Operasi Baris Elementer. Kemudian sistem diselesaikan dengan substitusi balik.

Contoh soal:

Selesaikan dengan menggunakan Eliminasi Gauss.

$$
\begin{array}{cc}
x_1+2x_2+3x_3z&=6\\
2x_1+4_2+6x_12&=4\\
x_3-x_24&=2
\end{array}
$$

### Soal 1
Selesaikan dengan menggunakan eliminasi Gauss


$$
\begin{array}{cc}
x_1+2x_2+3x_3&=6\\
2x_1+4x_2+6x_3&=12\\
x_2+x_3&=2
\end{array}
$$

jawab:


$$
\begin{bmatrix}
1 & 2 & 3 & | &6\\
2 & 4 & 6 & | &12\\
0 & 1 & 1 & | &2\\
\end{bmatrix}
\quad
$$

$$
\begin{bmatrix}
1 & 2 & 3 & | &6\\
0 & 0 & 0 & | &0\\
0 & 1 & 1 & | &2\\
\end{bmatrix}
\quad
$$

$$
\begin{bmatrix}
1 & 2 & 3 & | &6\\
0 & 1 & 1 & | &2\\
\end{bmatrix}
\quad
$$

$$
\begin{array}{cc}
x_2+x_3 = 2\\
x_2 = 2 - x_3\\
\end{array}
$$

$$
\begin{array}{cc}
x_1+2x_2+3x_3 = 6\\
x_2 = 2 - x_3 \\
\end{array}
$$

$$
\begin{array}{cc}
x_1 + 2(2-x_3)+3x_3 = 6\\
x_1 + 4-2x_3+3x_3 = 6\\
x_1+4+x_3\\
x_1=2-x_3
\end{array}
$$

$$
\begin{array}{cc}
x_1 = 2-x_3\\
x_2=2-x_3\\
x_3=x_3
\end{array}
$$

jadi hanya ada satu variabel maka sistem memiliki *tak hingga banyak solusi*.

### Soal 2
Selesaikan dengan menggunakan eliminasi Gauss.

$$
\begin{array}{cc}
x_1+x_2+x_3&=3\\
2x_1+2x_3&=5\\
x_1+2x_2&=3
\end{array}
$$

jawab: 

$$
\begin{bmatrix}
1 & 1 & 1 & | &3\\
2 & 0 & 2 & | &5\\
1 & 2 & 0 & | &3\\
\end{bmatrix}
\quad
$$

$$
\begin{bmatrix}
1 & 1 & 1 & | &3\\
0 & -2 & 0 & | &-1\\
0 & 1 & -1& | &0\\
\end{bmatrix}
\quad
$$

$$
\begin{bmatrix}
1 & 1 & 1 & | &3\\
0 & -2 & 0 & | &-1\\
0 & 0 & -1 & | &-1/2\\
\end{bmatrix}
\quad
$$

$$
\begin{array}{cc}
-x_3=-1/2\\
x_3=1/2
\end{array}
$$

$$
\begin{array}{cc}
-2x_2=-1\\
x_2=1/2
\end{array}
$$

$$
\begin{array}{cc}
x_1+x_2+x_3=3\\
x_1+1/2+1/2=3\\
x_1+1=3\\
x_1=2
\end{array}
$$

hasil akhirnya adalah:

$$
\begin{array}{cc}
(x_1+x_2+x_3)=(2,1/2,1/2)
\end{array}
$$

jadi, sistem ini memiliki *solusi tunggal*.

### Soal 3
Selesaikan dengan menggunakan eliminasi Gauss.

$$
\begin{array}{cc}
2x_1+2x_2&=4\\
x_1+x_2&=2
\end{array}
$$

jawab:

$$
\begin{bmatrix}
2 & 2 &  | &4\\
1 & 1 &  | &2\\
\end{bmatrix}
\quad
$$

$$
\begin{bmatrix}
1 & 1 &  | &2\\
1 & 1 &  | &2\\
\end{bmatrix}
\quad
$$

$$
\begin{array}{cc}
x_1+x_2=2\\
x_1=2-x_2\\
x_2=x_2
\end{array}
$$

$$
\begin{array}{cc}
(x_1,x_2)=(2-x_2,x_2)
\end{array}
$$

$$
\begin{array}{cc}
jika(x_2=0),maka((x_1,x_2)=(2,0))\\
jika(x_2=1),maka((x_1,x_2)=(1,1))\\
jika(x_2=2),maka((x_1,x_2)=(0,2))
\end{array}
$$

maka sistem ini memiliki *tak hingga banyak solusi*.

### Soal 4
Selesaikan dengan menggunakan eliminasi Gauss.

$$
\begin{array}{cc}
x_1+x_2&=5\\
x_1+2x_3&=6
\end{array}
$$

jawab:

$$
\begin{bmatrix}
1 & 1 &| &5\\
0 & 2 &| &6\\
\end{bmatrix}
\quad
$$

$$
\begin{bmatrix}
1 & 1 &| &5\\
0 & 1 &| &1\\
\end{bmatrix}
\quad
$$

$$
\begin{array}{cc}
x_2=1\\
x_1+1=5\\
x_1=4
\end{array}
$$

jadi:

$$
\begin{array}{cc}
(x_1,x_2)=(4,1)
\end{array}
$$

maka, sistem ini memiliki *solusi tunggal*.