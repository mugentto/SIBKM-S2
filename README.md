Fast-Forward 
1. Membuat Branch
![Membuat branch](images/1.png)
pembuatan branch ParentAgus dan Child Agus
2. Memindahkan isi branch
![Memindahan branch](images/2.png)
Memindahkan seluruh isi master ke ParentAgus seolah olah ParentAgus menjadi main atau master saat ini
3. Memodifikasi file di ChildAgus
![Memodifikasi file](images/3.png)
setelah berpindah ke branach childagus kita memodifikasi file dan kira add dan commit 
4. Push file dari ChildAgus
![...](images/4.png)
Dikarenakan belum ada branch di remote maka kita tambahkan dlu dengan cara 
git push --set-upstream origin ChildAgus
5. Melakukan merge
![...](images/5.png)
Setelah berpindah ke ParentAgus maka kira melakukan merge dengan ChildAgus dan Fast Forward telah berhasil
6. Push ke remote
![...](images/6.png)
dikarenakan belum ada ParenAgus di remote github maka kita tambahkan dengan cara git push --set-upstream origin ParentAgus
7. hasil
![...](images/7.1.png)
![...](images/7.2.png)

THREE WAY MERGING
1. Memodifikasi file

