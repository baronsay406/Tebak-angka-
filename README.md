```
import random

angka_rahasia = random.randint(1, 100)
tebakan = 0

while tebakan != angka_rahasia:
    tebakan = int(input("Tebak angka antara 1-100: "))
    if tebakan < angka_rahasia:
        print("Angka terlalu kecil!")
    elif tebakan > angka_rahasia:
        print("Angka terlalu besar!")
