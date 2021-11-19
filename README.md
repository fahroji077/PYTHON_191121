# PYTHON_191121


1. PROGRAM MENGHITUNG LUAS

```y
def program() :
    print(f"""
           a.persegi panjang
           b.segitiga
           c.lingkaran
          """)
    pilihan=str(input("Masukan Bangun Datar Yang Dipilih : "))

    if pilihan == "persegi panjang" :
        p=int(input("Masukan Panjang : "))
        l=int(input("Masukan Lebar : "))
        hasil=p*l
        print(f"Maka luas persegi panjang : {hasil}")
    elif pilihan == "segitiga" :
        a=int(input("Masukan alas segitiga : "))
        t=int(input("Masukan tinggi segitiga : "))
        hasil=0.5*a*t
        print(f"Maka luas segitia: {hasil}")
    elif pilihan=="lingkaran":
        r=int(input("Masukan jari jari lingkaran : "))
        phi=22/7
        hasil= phi*r*r
        print(f"Maka luas lingkaran : {hasil}")
    else :
        print("Masukan bangun datar sesuai data ")
program()

 ```
