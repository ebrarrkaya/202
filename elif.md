# ELİF KOŞULU
Elif koşulu, ikiden fazla koşulumuz varsa ilk koşul hariç diğer koşulları oluşturmak için kullanılmaktadır. Elif ifadesini kullandıktan sonra (tıpkı if koşulunda olduğu gibi) parantez içerisinde koşul ifademizi belirtiriz ve parantezi kapattıktan sonra iki nokta üst üste sembolunu kullanırız. Yani girinti oluşturmalıyız. Şimdi bu duruma örnek algoritma oluşturup, daha sonra ise algoritmayı kodlarımıza derleyelim.

Örnek Kod:

deger1=int(input("Lutfen birinci degeri giriniz: "))

deger2=int(input("Lutfen ikinci degeri giriniz: "))

deger3=int(input("Lutfen ucuncu degeri giriniz: "))

if deger1>=deger2 and deger1>=deger3:

    print("{} degeri en buyuk sayidir.".format(deger1))
elif deger2>=deger1 and deger2>=deger3:

    print("{} degeri en buyuk sayidir.".format(deger2))
elif deger3>=deger1 and deger3>=deger2:

    print("{} degeri en buyuk sayidir.".format(deger3))

<a href="https://github.com/ebrarrkaya/202/blob/0b813e65fdfedbdac3fe98857f7cfb01412d8258/DDDD.png">ÇIKTI İÇİN TIKLAYINIZ</a>
