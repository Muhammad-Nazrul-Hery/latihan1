# Summary Section 2 Version Control and Branch Management (Git)

### Disection 2 ini terdapat beberapa point penting, yaitu :

<hr> 

1. Versioning adalah untuk mengatur versi dari source code program, dimana ini dilakukan agar seseorang tidak perlu melakukan perubahan dengan mengunakan banyak file. Terdapat 3 version control system,  Single User terdiri dari SCCS dan RCS, Centralized terdiri CVS, Perforce, dll, dan terakhir Distributed terdiri dari git, Mercurial, dan Bazaar. <br> Salah satu bentuk version control system yang popular digunakan para developer untuk mengenmbangkan software secara bersama-sama adalah git.

2. Untuk bisa melakukan setting up pertama pada Git, kita perlu melalukan (git config) untuk memasukkan username dan email dari akun github kita. <br> Ada beberapa syntax dasar untuk melakukan operasi memasukkan file ke github, Seperti :     
    - Untuk membuat file
        ```
        $ git add <nama directory>
        ```
    - Untuk memasukkan semua file ke staging area
        ```
        $ git add .
        ``` 
    - Untuk memasukkan file ke repository github
        ```
        $ git commit -m "add config file"
        ```
    - Untuk mengetahui perubahan di file yang telah di edit
        ```
        $ git diff 
        ```
    - Untuk menyimpan perubahan serta perubahan tersebut bisa dikembalikan
        ```
        $ git stash
        ```
    - Untuk menampilkan setiap commit yang kita lakukan
        ```
        $ git log --oneline
        ```
    - Untuk berpindah repository
        ```
        $ git checkout <nama repository>
        ```
3. Branch adalah turunan dalam suatu repository untuk memudahkan proses pengeditan source code. Untuk membuat branch dapat dilakukan dengan syntax “$ git branch . Selain itu github juga memiliki suatu fitur yang bisa memberikan akses untuk kita mengubah source code program orang lain yang salah, atas persetujuan pemilik source code tersebut. Fitur ini adalah fitur pull and request.

