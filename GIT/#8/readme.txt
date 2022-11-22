22/11/2022

Mempelajari Git Remote

-$ git clone , untuk mengambil repo dari github ke local
    ^ $ git clone (link clonenya)
-$ git remote , untuk menyambungkan local dan github agar bisa pull dan push
    ^ setiap remote akan memiliki nama,jika kita clone dari github maka nama default nya dalah origin 
      -$ git remote -v , untuk melihat detail link remote 
      -$ git remote add (nama(origin defautl)) origin (link)
        ^ berfungsi untuk menjadi repo dari github menjadi remote
-$ git push , mengirimkan commit dari repo local ke repo remote
    ^ -jika tidak terjadi conflict maka akan otomatis terpull 
      -$ git push -u (upstream agar selanjutnya tinggal git push saja agar langusng terpush ke repo yg telah menjadi remote 
-$ git pull , mengambil commit dari remote ke local
    ^ jika terjadi merge conflict maka harus kita edit dulu dan pilih mau menggunakan line yang mana.
-$ git fetch , untuk mencheck commit repo di remote
    ^ jika muncul have diverged artinya repo di remote dan local terjadi percabangan ( branch ) karena terjadi perubahan
      dibaris yang sama,maka dari itu muncul commit baru yang terjadi remote.
      
      
      
-$ git config --global (akan mensave config untuk semua file/repo saat membuka bash) user.name "(masukan user name)"
-$ git config --global (akan mensave config untuk semua file/repo saat membuka bash) user.email "(masukan email)"

