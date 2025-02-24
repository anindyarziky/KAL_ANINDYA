---
title: Penyelesaian sistem persamaan linear

---

## Penyelesaian Sistem Persamaan Linear 
### Operasi Baris Elementer 
### Eliminasi Gauss
Soal 1:
Selesaikan dengan menggunakan Eliminasi Gauss

$$
\begin{array}{cc}
x_1+2x_2+3x_2&=6\\
2x_1+4x_2+6x_3&=12\\
x_3+x_2&= 2
\end{array}
$$

Jawaban: 

Matriks augmentasi:
$$
	\begin{bmatrix} 
	1 & 2 & 3 & | &6\\
	2 & 4 & 6 & |& 12\\
	0 & 1 & 1 & |& 2\\
	\end{bmatrix}
	\quad
	$$
Eliminasi koefisien pertama pada baris kedua
$$
	\begin{bmatrix} 
	1 & 2 & 3 & | &6\\
	0 & 0 & 0 & |& 0\\
	0 & 1 & 1 & |& 2\\
	\end{bmatrix}
	\quad
	$$
Tukar baris kedua dan ketiga 

$$
	\begin{bmatrix} 
	1 & 2 & 3 & | &6\\
	0 & 1 & 1 & |& 2\\
	0 & 0 & 0 & |& 0\\
	\end{bmatrix}
	\quad
	$$
Eliminasi koefisien pada baris pertama 
$$
	\begin{bmatrix} 
	1 & 0 & 1 & | &2\\
	0 & 1 & 1 & |& 2\\
	0 & 0 & 0 & |& 0\\
	\end{bmatrix}
	\quad
	$$
$$
\begin{array}{cc}
x_1+x_2&=2\\
x_2+x_3&=2
\end{array}
$$

$$
\begin{array}{cc}
x_1= 2-1=1\\
x_2= 2-1=1\\
x_3= 1\\
\end{array}
$$
hasilnya: 
$$
\begin{array}{cc}
x_1= 1 x_2 =1 x_3 =1
\end{array}
$$
Soal 2: 
$$
\begin{array}{cc}
x_1+x_2+x_3&= 3\\
2x_1+x_3&=3\\
x_1+2x_2&=3
\end{array}
$$
Jawaban: 

Soal 3: 
$$
\begin{array}{cc}
2x_1+2x_2&= 4\\
x_1+x_2&=2\\
\end{array}
$$

Soal 4: 
$$
\begin{array}{cc}
x_1+x_2&=5\\
x_1+2x_3&=6\\
\end{array}
$$


