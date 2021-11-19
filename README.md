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

def segitiga(alas,tinggi):
    return (0.5 * (alas * tinggi))

alas = int(input("masukan alas :"))
tinggi = int(input("masuk tinggi :"))
luas = segitiga(alas,tinggi)
print("Luas Segitiga adalah :",luas)
```
![image](https://user-images.githubusercontent.com/93015185/142649670-4cae6b32-5093-4e31-a238-e6e6a2f39c4e.png)

4. MENGHITUNG SEKELOMPOK DATA YG DITAMPUNG DALAM SEBUAH LIST UNTUK MENCARI NILAI TERTINGGI

```y
print("""MENGHITUNG SEKELOMPOK DATA YG DITAMPUNG 
DALAM SEBUAH LIST UNTUK MENCARI NILAI TERTINGGI""")
print("="*40)

def proses(deret_bilangan):
    nilai_terbesar = deret_bilangan[0]

    for nilai in deret_bilangan:
        if nilai > nilai_terbesar:
            nilai_terbesar = nilai

    return nilai_terbesar
 
def cetakhasil(hasil):
    print("bilangan terbesar adalah :",proses(hasil))       

def inputdata():
    bilangan = []
    n = int(input("masukan banyak data :"))
    for i in range(n):
        masukandata = float(input("masukan bilangan :"))
        bilangan.append(masukandata)
    cetakhasil(bilangan)
    
inputdata()
```
![image](https://user-images.githubusercontent.com/93015185/142651362-870f468b-37ba-4e03-9104-076bc400d886.png)

5. 

6. MENGHITUNG FAKTORIAL DENGAN BILANGAN(INPUT) MENGGUNAKAN FUNGSI

```y
def faktorial(n):
    if n > 2:
        return n * faktorial(n - 1)
    
    return 2

bilangan = int(input("bilangan :"))
faktor = faktorial(bilangan)
print(f'{bilangan}! = {faktor}')
```
![image](https://user-images.githubusercontent.com/93015185/142656990-09f54213-a30d-4a43-b2a7-8b7606c497d5.png)
