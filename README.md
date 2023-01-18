color_cycle = cycle(["light blue", "light green", "light pink", "light yellow", "light cyan"]) -->digunakan untuk memberikan warna pada telur
egg_width = 45 --> ukuran lebar pada telur
egg_height = 55 --> ukuran tinggi pada telur
egg_score = 10 --> nilai/skor pertelur jika berhasil didapat
c = Canvas(root, width=canvas_width, height=canvas_height, background="deep skyblue") -->memberikan warna pada background
difficulty = 0.95 --> waktu/kecepatan telur yang bergerak
catcher_color = "blue"--> untuk memberi warna pada tempat telur 
messagebox.showinfo("Game Over!", "Final Score: "+ str(score)) --> menampilkan kalah atau berakhirnya permainan
def move_eggs():--> agar telur bisa berpindah pindah
def lose_a_life():--> menampilkan kesempatan telur jika tidak berhasil didapatkan
def increase_score(points):--> menampilkan meningkatnya skor pada telur yang didapat
def move_left(event):--> agar telur bisa bergerak ke arah kiri
def move_right(event):--> agar telur bisa bergerak ke arah kanan
text="Nilai: "+ str(score))--> menampilkan skor yang didapat
