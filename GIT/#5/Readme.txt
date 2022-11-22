19-11-2022

GIT
  Menggunakan vcs namun secara local.
  Git dapat difungskikan menggunakan console dan git client (GUI).
  
  Menggunakan git menggunakan console : 
    Git Command ( Local ) : 
      -$ git init,untuk menjadikan sebuah folder di local menjadi repo 
      -$ git add <file(s)> , untuk menambahkan file yang telah dirubah agar tersimpan di staging area ( gunakan add . agar menambahkan semua file yang beruabh)
      -$ git status, untuk melihat status file apa saja yang berubah dan belum masuk ke staging area serta belum commit
      -$ git commit, untuk commit sebuah file yang sudah kita ubah agar tersipan di git
      -$ git config, untuk menambahkan user yang melakukan commit
      -$ git branch, untuk melihat ada branch apa saja dan sedang di branch mana kita, bisa menggunakan branch nama untuk menambah branch baru,dan branch -d nama untuk 
                     menghapus branch yyg ada.
      -$ git help, untuk melihat help pada git
      -$ pwd , untuk melihat kita sedang di directory mana
      -$ cd , untuk masuk ke directory,gunakan cd .. untuk mundur 1 direcoru
      -$ ls , untuk melihat list director yg ada.
   
    3 area pada repo git : 
      -Working tree, folder tempat kita berkerja/folder yang berisi project kita.
      -Staging area, Memberitahu git kalau kita sudah melakukan perubahan,
      -History,Rekaman sejarah yang agar disimpan dan bisa di panggil/checkout kapan saja
      
      setelah mengubah suatu folder/repo maka harus melakukan git add-git commit
      
      Staging area dan history atau ketika folder kita telah kita inisiai menjadi repo maka
      akan muncul sebuah file/folder dengan extension .git.
      ( file .git ini tersembunyi )
       
      notes : 
        -file dengan akhir / berarti itu folder/directory.
