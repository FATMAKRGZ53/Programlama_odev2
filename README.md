sabit_sayi = 25  # Tahmin edilmesi gereken sayı
tahmin = None    # Başlangıçta boş

while tahmin != sabit_sayi:
    tahmin = int(input("Bir sayi tahmin edin: "))

    if tahmin < sabit_sayi:
        print("Tahmininiz sabit sayidan küçüktür.")
    elif tahmin > sabit_sayi:
        print("Tahmininiz sabit sayidan büyüktür.")
    else:
        print("Doğru tahmin ettiniz!")
