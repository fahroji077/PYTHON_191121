# PYTHON_191121


1. PROGRAM MENGHITUNG LUAS

```y
print("PROGRAM MENGHITUNG LUAS")
print("="*40)

def program() :
    print("a. persegi panjang")
    print("b. segituga")
    print("c. lingkaran")
    print("\n")
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
![image](https://user-images.githubusercontent.com/93015185/142637239-1a97ea77-76ef-46e8-b5ee-18823931d2eb.png)

2. MODIF NOMOR 1/PENYIMPANAN DALAM SATU FILE

a. persegi panjang
```y
print("PROGRAM MENGHITUNG LUAS PERSEGI PANJANG")
print("="*40)

def persegi_panjang() :
    p=int(input("Masukan Panjang  : "))
    l=int(input("Masukan Lebar    : "))
    luas=p*l
    print(f"Maka Luas Persegi Panjang : {luas}")

persegi_panjang()
```
![image](https://user-images.githubusercontent.com/93015185/142637580-3034bb21-1d78-4fa3-933d-434a717904de.png)

b. segitiga
```y
print("PROGRAM MENGHITUNG LUAS SEGITIGA")
print("="*40)

def segitiga():
    a=int(input("Masukan alas segitiga   : "))
    t=int(input("Masukan tinggi segitiga : "))
    luas=0.5*a*t
    print(f"Maka Luas Segitiga : {luas}")
    
segitiga()
```
![image](https://user-images.githubusercontent.com/93015185/142637797-fe879706-eeae-4773-8498-591c28a5191d.png)

c. lingkaran
```y
print("PROGRAM MENGHITUNG LUAS LINGKARAN")
print("="*40)

def lingkaran():
    r=int(input("Masukan Jari Jari Lingkaran : "))
    phi=22/7
    luas=phi*r*r
    print(f"Maka Luas Lingkaran : {luas}")
    
lingkaran()
```
![image](https://user-images.githubusercontent.com/93015185/142637958-8213f293-7e2c-4164-b2bb-e0d69f62296b.png)

3. MENGHITUNG LUAS SEGITIGA MENGGUNAKAN FUNGSI LUAS_SEGITIGA(ALAS,TINGGI)

```y
print("PROGRAM MENGHITUNG LUAS DENGAN FUNGSI")
print("="*40)

def segitiga(alas,tinggi) :
    luas_segitiga = alas*tinggi 
    print("="*25)
    print(f"Maka luas segitiga : {luas_segitiga} ")
    print("="*25)
segitiga(7,20)
```
![image](https://user-images.githubusercontent.com/93015185/142638331-2ef37013-6426-4c47-a356-bfc8df5f0337.png)
