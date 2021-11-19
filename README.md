# PYTHON_191121


1. PROGRAM MENGHITUNG LUAS

```y
print("PROGRAM MENGHITUNG LUAS")
print("="*40)
#MENU
def menu():
    print ("Menu Pilihan")
    print("\n")
    print("1. Persegi Panjang")
    print("2. Segitiga")
    print("3. Lingkaran")

def persegipanjang ():
    print ("Menghitung Luas Persegi Panjang")
    p = int(input("Masukkan Panjang : "))
    l = int(input("Masukkan Lebar : "))
    luas = p*l
    print(f"Luas Persegi Panjang : {luas}")
    print("\n")
    print("Mau coba lagi [Y/N] ? ")
    back =input().upper()
    if back == "Y":
        menu()
    else:
        exit()

def segitiga ():
    print ("Menghitung Luas Segitiga")
    a = int(input("Masukkan Alas : "))
    t = int(input("Masukkan Tinggi : "))
    luas = a*t
    print(f"Luas Segitiga : {luas}")
    print("\n")
    print("Mau coba lagi [Y/N] ? ")
    back =input().upper()
    if back == "Y":
        menu()
    else:
        exit()

def Lingkaran ():
    print ("Menghitung Luas Lingkaran")
    r = int(input("Masukkan Jari jari : ")) 
    luas = 3.14*(r*r) 
    print(f"Luas Lingkaran : {luas}")
    print("\n")
    print("Mau coba lagi [Y/N] ? ")
    back =input().upper()
    if back == "Y":
        menu()
    else:
        exit()

menu() 
while True:
    pilih = int(input("Masukkan Pilihan : "))
    if pilih != 1 and pilih != 2 and pilih != 3:
        print("Tak ada dalam Menu")
        continue

    if pilih == 1:
        persegipanjang()
    elif pilih == 2:
        segitiga()
    elif pilih == 3:
        Lingkaran()
        print("="*50)
        break

 ```
 ![image](https://user-images.githubusercontent.com/93015185/142630760-0f5ea9d0-ee7a-41f4-8f54-a08ae6294fb2.png)
 
2. 
