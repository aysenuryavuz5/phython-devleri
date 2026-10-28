# phython-ödevleri

print("HESAP MAKİNESİ")

sayi1 = float(input("Birinci sayıyı gir: "))
sayi2 = float(input("İkinci sayıyı gir: "))

print("Toplama (+):", sayi1 + sayi2)
print("Çıkarma (-):", sayi1 - sayi2)
print("Çarpma (*):", sayi1 * sayi2)

if sayi2 != 0:
    print("Bölme (/):", sayi1 / sayi2)
    print("Tam bölme (//):", sayi1 // sayi2)
else:
    print("Sıfıra bölme yapılamaz!")

print("Üs alma (**):", sayi1 ** sayi2)