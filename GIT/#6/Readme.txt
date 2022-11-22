22/11/2022

Belajar Tentang Git branch dan git merge

$git merge, pindah dulu ke branch yg ingin menjadi tempat pindah,lalu git merge (nama branch yg ingin digabungkan)
$git branch -d,untuk delete branch
$git branch --merged,untuk melihar branch mana saja yang telah di merge jika blm di hapus


Merge : -Fast Forward
          Terjadi ketika branch yang ingin kita gabungkan dalam 1 jalur langsung/direct path
        -Three Way Merge
          ketika merge tidak tertdapat jalur langsung,maka ketia merge mereka akan membuat commit baru

NOtes : 
        -Jika sudah di add,bila kita memodifikasi file maka gunakan command $ git commit -am (a artinya add dan m untuk massage) "Contoh"
