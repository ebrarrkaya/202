#  ELSE KOŞULU

Else ifadesi bizim için "Girilen hiçbir koşul sağlanmıyorsa" anlamına gelmektedir, else ifadesinden sonra herhangi bir kontrol durumu girmemize gerek yoktur çünkü zaten kendi başına bir koşul belirtmektedir. Bu yüzden else koşulunda da girinti oluşturulması gereklidir.

Örnek Kod: (Ehliyet Kontrolü)

yas=int(input("Lutfen yasinizi giriniz: "))

if(yas>=18):

    print("Araba ve motor ehliyeti alabilirsiniz!")
elif(yas>=15):

    print("Motor ehliyeti alabilirsiniz!")
else:

    print("Ehliyet alamazsiniz!")

<a href="https://github.com/ebrarrkaya/202/blob/65c7e1781650893acc67ef7c5e75921f4efbc245/eee.png">ÇIKTI 1</a>

<a href="https://github.com/ebrarrkaya/202/blob/60c3b007a744658fa7a3e0155e8ec51814e2adb6/AAAAA.png">ÇIKTI 2</a>
