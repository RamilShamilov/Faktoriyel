# Faktoriyel
faktoriyel = 1

while True:
    sayi = int(input("Lütfen negatif olmayan bir sayı giriniz"))
    if (sayi <= 0):
        print("Lütfen tekrar dedneyiniz")
    else:
        for i in range(1,sayi+1):
            faktoriyel *=i
        print("faktoriyel", faktoriyel)
        break
