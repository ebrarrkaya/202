#  ELSE KOŞULU

Else ifadesi bizim için "Girilen hiçbir koşul sağlanmıyorsa" anlamına gelmektedir, else ifadesinden sonra herhangi bir kontrol durumu girmemize gerek yoktur çünkü zaten kendi başına bir koşul belirtmektedir. Bu yüzden else koşulunda da girinti oluşturulması gereklidir.

Örnek Kod 1:

yas=int(input("Lutfen yasinizi giriniz: "))

if(yas>=18):

    print("Araba ve motor ehliyeti alabilirsiniz!")
elif(yas>=15):

    print("Motor ehliyeti alabilirsiniz!")
else:

    print("Ehliyet alamazsiniz!")

<a href="https://github.com/ebrarrkaya/202/blob/65c7e1781650893acc67ef7c5e75921f4efbc245/eee.png">ÇIKTI 1</a>

<a href="https://github.com/ebrarrkaya/202/blob/60c3b007a744658fa7a3e0155e8ec51814e2adb6/AAAAA.png">ÇIKTI 2</a>

Örnek Kod 2: 

kartno=123456

cvv=110

skt="10/28"

kartnos=int(input("Kart Numarasi Giriniz: "))

cvvs=int(input("Cvv Giriniz: "))

skts=input("Son Kullanma Tarihini Giriniz(aa/yy): ")

if kartnos==kartno and cvvs==cvv and skts==skt:

    print("Sisteme hosgeldiniz!")
else:

    print("Sisteme giris yapilamiyor")

<a href="https://github.com/ebrarrkaya/202/blob/2d71ce0b63823c0db6fc56713d28be018f9e87cf/gggg.png">ÇIKTI 1</a>

<a href="https://github.com/ebrarrkaya/202/blob/d7eb3ef2caaf486f9cfcf4d7fbbfc038229ecd11/ffff.png">ÇIKTI 2</a>

