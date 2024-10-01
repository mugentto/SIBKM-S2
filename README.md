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
1. Memodifikasi file di dalam ChildAgus
![...](images/1a.png)
melakukan modifikasi file pada ChildAgus melakukan add,commit dan push
![...](images/2a.png)
log nya
2. melakukan pull
![...](images/3a.png)
kita mencoba melakukan pull dari ParentAgus ke ChildAgus dan menemukan konflik
3. tampilan vs code
akan menunjukan tindakan yang kita pilih atas perubahan tersebut
4. Menambahkan setelah merging
![...](images/4a.png)
setelah memilih tindakan yang ada sekarang kita add, dan comit serta push
5. Hasil log
![...](images/5a.png)
6. Membuat pull request
![...](images/6a.png)
![...](images/7a.png)
7. git pull diterminal

