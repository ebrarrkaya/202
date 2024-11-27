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
