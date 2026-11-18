# hesap_bolme
arkadaşsayisi=int( input("arkadaş sayısı girin:"))
urunfiyat=float(input("ürün fiyatı:"))
toplam=0
while urunfiyat!=0:
    toplam+=urunfiyat
    urunfiyat=float(input("ürün fiyatı:"))
if toplam>=500:
    toplam=toplam*0.9
    print("tutar:",toplam)
    print("kişi başına düşen tutar", toplam/arkadaşsayisi)
elif 200<=toplam<500:
    toplam=toplam*0.95
    print("tutar:",toplam)
    print("kişi başına düşen tutar", toplam/arkadaşsayisi)
elif toplam<200:
    print("tutar:",toplam)
    print("kişi başına düşen tutar", toplam/arkadaşsayisi)
