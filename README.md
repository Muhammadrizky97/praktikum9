# praktikum9
sslatihan1,sslatihan2,sslatihan3 dan sslatihan4
![sslatihan1](https://user-images.githubusercontent.com/43899133/49681661-5a51f280-fad8-11e8-8927-870883a8db30.png)
![sslatihan2](https://user-images.githubusercontent.com/43899133/49681662-61790080-fad8-11e8-9dca-1234c047ecf7.png)
![sslatihan3](https://user-images.githubusercontent.com/43899133/49681666-6938a500-fad8-11e8-8cb9-6b663c34950b.png)
![sslatihan4](https://user-images.githubusercontent.com/43899133/49681667-6dfd5900-fad8-11e8-86e9-3e0a3bcdd9f6.png)
contoh flowchart latihan1

![1flowchartp9](https://user-images.githubusercontent.com/43899133/49681695-d8ae9480-fad8-11e8-86d9-d26054302745.jpg)
![2flowchartp9](https://user-images.githubusercontent.com/43899133/49681696-dba98500-fad8-11e8-8e97-5d8bbbf4c030.jpg)
![3flowchartp9](https://user-images.githubusercontent.com/43899133/49681700-dfd5a280-fad8-11e8-9c3b-2fcec9b3db03.jpg)

contoh algoritma latihan1

![ahlgoritmap9](https://user-images.githubusercontent.com/43899133/49681703-e49a5680-fad8-11e8-8d41-4e28c29d4298.jpg)

#Latihan3

Misalkan A merupakan matriks berordo m x p dan B merupakan matriks berordo p x n, maka hasil kali dari A dan B, kita tulis AB merupakan matriks berordo m x n.
Ingat : banyaknya kolom matriks A sama dengan banyaknya baris matriks B, yaitu : p.
Contoh 1 :
S =  merupakan matriks berordo 1 x 3 dan T = merupakan matriks berordo 3 x 1.
Hasil kali dari S dan T adalah 
ST = 
⇔ ST = ((-3)(-6) + (4)(10) + (5)(14))
⇔ ST = (18 + 40 + 70)
⇔ ST = (128)
Jadi, hasil kali dari kedua matriks S dan T adalah (128) dan merupakan matriks berordo 1 x 1.
Contoh 2 :
P =  merupakan matriks berordo 2 x 2 dan Q = merupakan matriks berordo 3 x 2.
Matriks P dan Q tidak dapat dikalikan, karena banyaknya kolom matriks P tidak sama dengan banyaknya baris matriks Q.
Jadi, hasil kali dari kedua matriks P dan Q tidak didefinisikan.

Matriks transpose yaitu matriks yang diperoleh dari memindahkan elemen-elemen baris menjadi elemen pada kolom atau sebaliknya.
Transpose matriks A dilambangkan dengan AT
Contoh: A3×2 =, maka AT  =, perhatikan bahwa ordo dari AT  adalah 2 x 3.
Algoritma Transpose Matrik
1.	Masukkan ordo matrik(n)
2.	Input matrik di dalam array [0][0] sampai dengan array[n][n]
3.	ditampilkan matrik tersebut
4.	menukar matrik[i][j] menjadi matrik[j][i]
5.	ditampilkan hasil matrik tranpose

Deklarasi :
a[10][10] : int
m,n,i,j   : int
Deskripsi :
Baca (m)
Baca (n)
for(i=0;i<m;i++)
{
for(j=0;j<n;j++)
{
Tulis a[i][j]
Transpose :
for(i=0;i<m;i++)
{
for(j=0;j<n;j++)
{
Transpose a[j][i]
}
