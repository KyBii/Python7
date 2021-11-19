# Tugas Python7
## 1. Membaca CSV
### Source Code

```py
from os import system
system('cls')
import csv

tulis = open("abel.csv", "r")

csvTulis = csv.reader(tulis, delimiter = ',')

for i in csvTulis:
    print(i)
    print(f"\nFirst : {i[0]}\nLast : {i[1]}\nNumber : {i[2]}")
tulis.close()
```
### VS Code & Output
![N1](https://user-images.githubusercontent.com/93004722/142545794-3f449f63-8cb8-4d3a-bb17-c44f1a6d1a2a.PNG)

## 2. With Block
### Source Code

```py
from os import system
system('cls')
import csv

# tulis = open("abel.csv", "r")
with open("abel.csv", "r") as tulis:
    csvTulis = csv.reader(tulis, delimiter=',')

    for i in csvTulis:
        print(i)
        print(f"\nFirst : {i[0]}\nLast : {i[1]}\nNumber : {i[2]}")
   # tulis.close()
```
### VS Code & Output
![N2](https://user-images.githubusercontent.com/93004722/142551664-a15d6c2b-bb34-49ed-9f82-9be1e545fc1e.PNG)

## 3. Module
### Source Code

```py
from os import system
system('cls')
import nama
from nama import hello #import fungsi hello secara langsung


result = nama.hello("Abigail Perkasa", 19)
print(result)
print("===============================================================")
result = hello("Game", 0)
print(result)
```
### nama
```py
def hello(nama , level):
   return (f"Hello {nama} - {level}")
```
### VS Code & Output
![N3](https://user-images.githubusercontent.com/93004722/142552598-a92cb9dd-a830-4c1f-b0d1-b9f113ff99ce.PNG)

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
