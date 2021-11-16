# Tugas Python7
## 1. Membaca CSV
### Source Code

```py
from os import system
system('cls')
try:
    level = input("Level kamu : ")
    level = int(level)
    level = level / 0
    print (level)
except TypeError:
    print("Error")
except ZeroDivisionError:
    print(f"Error {level} tidak bisa dibagi 0")
except ValueError:
    print("Tolong masukkan huruf saja")
```
### VS Code & Output
![C1](https://user-images.githubusercontent.com/93004722/141304775-971f2c11-1b10-4c6d-8953-9bbe1de20bb5.PNG)

## 2. With Block
### Source Code

```py
from os import system
system('cls')
try:
    level = input("Level kamu : ")
    level = int(level)
    level = level / 0
    print(level)
except:
    print("Telah terjadi error")
```
### VS Code & Output
![C2](https://user-images.githubusercontent.com/93004722/141305244-f976aa94-29ca-48cb-9b94-a31ef1dfee80.PNG)

## 3. Module
### Source Code

```py
from os import system
system('cls')
text = open("abel.txt", "r")
print(text.read()) #Membaca file keseluruhan 
print("\n")
print(text.readline()) #membaca perbaris

#==============================

list =  text.readlines() #list string pada file
index = 1
for text in list:
    print(f"{index} - {text}") # Menampilkan string dari list 
    index += 1 # nomor urut baris
    
text.close()
```
### VS Code & Output
![C3](https://user-images.githubusercontent.com/93004722/141309454-8d28b0d3-7d2e-4b37-ad1c-e532844cb8b1.PNG)
![C4](https://user-images.githubusercontent.com/93004722/141310089-65a9d5ef-07db-41df-a4b3-2b6b0573bac6.PNG)
![C5](https://user-images.githubusercontent.com/93004722/141310564-6717d918-1e25-424f-9806-b9e97bd7f164.PNG)

## 4. Package
### Source Code

```py
from os import system
system('cls')
text = open("abel.txt", "w") # menulis kedalam file
# text = open("abel.txt", "a") # akan menambahkan text kedalam file
text.write("Nama : Abigail Perkasa")
text.close
print("File text berhasil ditulis")
```
### VS Code & Output
![C6](https://user-images.githubusercontent.com/93004722/141311148-92bba854-4447-4053-9035-4d4f8d193140.PNG)
![C7](https://user-images.githubusercontent.com/93004722/141311315-e159d1b8-7994-41fb-b9e0-58d648936825.PNG)

## 5. Random
### Source Code

```py
from os import system
system('cls')
text = open("abel.txt", "w") # menulis kedalam file
# text = open("abel.txt", "a") # akan menambahkan text kedalam file
text.write("Nama : Abigail Perkasa")
text.close
print("File text berhasil ditulis")
```
### VS Code & Output
![C6](https://user-images.githubusercontent.com/93004722/141311148-92bba854-4447-4053-9035-4d4f8d193140.PNG)

## 6. PIP dan Virtualenv
### Source Code

```py
from os import system
system('cls')
text = open("abel.txt", "w") # menulis kedalam file
# text = open("abel.txt", "a") # akan menambahkan text kedalam file
text.write("Nama : Abigail Perkasa")
text.close
print("File text berhasil ditulis")
```
### VS Code & Output
![C6](https://user-images.githubusercontent.com/93004722/141311148-92bba854-4447-4053-9035-4d4f8d193140.PNG)
