# vucut_kitle_indeksi
#Vücüt kitle indeksi hesaplaması için aşağıdaki kodlama sistemi kullanılmıştır.

isim = input ("adınız: ") 
kilo = float(input("Kilonuzu kg cinsinden girin: "))
boy = float(input("Boyunuzu metre cinsinden girin (lütfen nokta kullanın, örn 1.79): "))

indeks = (kilo/(boy*boy))
print("vücut kitle indeksiniz", indeks)

if indeks < 18.5:
    print("zayıf")
elif indeks >= 18.5 and indeks <= 24.9:
    print("Normal")
elif indeks >= 25 and indeks <= 29.9:
    print("kilolu")
elif indeks >= 30 and indeks <= 34.9:
    print("1.derece obez")
elif indeks >= 35 and indeks <= 39.9:
    print("2.derece obez")
else:
    print("3.derece obez")
