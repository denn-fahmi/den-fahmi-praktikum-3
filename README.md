# den-fahmi-praktikum-3
FLOWCHART YANG DI JADIKAN PROGRAM PYTHON, BESERTA PENJELASAN

        def cari_bilangan_terbesar():
    angka = []
    
    while True:
    
        n = float(input("Masukkan bilangan (atau 0 untuk menghentikan): "))
        if n == 0:
        
            break
            
        angka.append(n)
    if angka:
    
        terbesar = max(angka)
        
        print("Bilangan terbesar adalah:", terbesar)
        
    else:
    
        print("Tidak ada bilangan yang diinputkan.")

        cari_bilangan_terbesar()

Penjelasan=
def disini mendefinisikan sebuah fungsi bernama cari_bilangan_terbesar, 

Array Ini membuat daftar kosong bernama angka untuk menyimpan bilangan yang diinputkan, 

Ini adalah loop yang berjalan tanpa henti (while True). Di dalam loop: 

n = float(input("Masukkan bilangan (atau 0 untuk menghentikan): ")) meminta pengguna untuk memasukkan bilangan dan mengubahnya menjadi tipe data float.

if n == 0: break memeriksa apakah bilangan yang dimasukkan adalah 0. Jika ya, loop dihentikan (break).

angka.append(n) menambahkan bilangan yang dimasukkan ke daftar angka
