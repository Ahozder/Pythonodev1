# kodlama.io

Programlamada kullanacağımız verinin tipi çok önemlidir ve yanlış girilen bir veri tipi kodlarımızın düzgün çalışmamasına sebep olabilir. Bazı veri tiplerine örnek vermek gerekirse:


Metin tipleri: str

Sayısal tipler: int , float , complex

Dizi tipleri:  list , tuple , range

Adresleme tipleri: dict

Küme tipleri: set , frozenset

Mantıksal tipler: bool

Binary tipler: bytes , bytearray , memoryview

# Kodlama.io sitesinde kullanılan bazı veri tipleri

Sitedeki tüm yazılar için String(str) kullanılmıştır

Sayısal Tipler: int, float, complex int komutu derslerdeki ilerlememizi gösterir

Boolean komutu da genelikle bitir ve devam et tuşuna bastığımızda diğer sayfanın açılmasını sağlar

# Kodlama.io sitesinde şart bloklarına örnek

sayı1 = 15
sayı2 = 16

if sayı1 < sayı2:
    print("sayı1 sayı2'den küçüktür")
    

#eğer if bloğuna girmez ise
elif sayı1 == sayı2:
    print("iki sayı eşittir")

else:
    print("sayı1 sayı2'den büyüktür")



print("burası if bloğunun dışıdır.")

