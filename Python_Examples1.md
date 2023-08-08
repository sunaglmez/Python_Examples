# Python_Examples1

Kullanıcıdan gereken inputları(ad,soyad,sirano,beklemesüresi) alınız ve 4 farklı print metodu ile çıktıları yazıp ekranda gösteriniz.

```python
ad=(input("Adınız ve nedir?"))
soyad=(input(" Soyadınız nedir?"))
no=(input("Sıra numaranız kaç?"))
sure=(input("Bekleme süresi?"))

print(f"{ad} {soyad} , bekleyenler arasında {no} sıradasınız. Bekleme süreniz {sure}" )

print("{} {} , bekleyenler arasında {} sıradasınız. Bekleme süreniz {}".format(ad, soyad,no,sure) )

print(ad , soyad ," bekleyenler arasında", no, "sıradasınız. Bekleme süreniz" ,sure )

print(str(ad) , str(soyad) ," bekleyenler arasında", str(no), "sıradasınız. Bekleme süreniz" ,str(sure) )
```
 
