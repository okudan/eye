# Göz

**4. Ders**



  -	Başlamak için bilgisayarınıza **Aruino IDE**’yi yükleyin.
	- ***[Arduino IDE](https://www.arduino.cc/en/Main/Software)***
  -	Eğer Arduino’nuz klon ise ekstradan bir driver daha yüklemeniz gerekmektedir. Eğer gerekiyorsa bu driverı da yükleyin.
  -	Arduino IDE’yi açın ve Arduino’yu boş bir şekilde bilgisayarınıza bağlayın. Açılan kodu **‘Kontrol Et’** ve **‘Yükle’** butonları ile Arduino’ya atarak doğru bir şekilde atıldığından ve Arduino’nun ışıklarının düzgün gözüktüğünden emin olun.
  
  -	Bu derste Arduino kullanarak etrafı tarayan ve en yakınındaki cisme dönen bir robotçuk yapılacaktır. Bu amaçla servonun ve sensörün doğru şekilde kullanılabilmesi gerekmektedir. Bunun için öncelikle servoyu kullanan ardından sensörü kullanan birer kod yazıp daha sonra ikisi birleştirilecektir. Projenin amacı bu işlemi **en hızlı** ve **en doğru** şekilde yapan sistemi oluşturmaktır. 
  -	**Servoyu** Arduino’ya bağlayın ve servoyu sırasıyla **“0”, “120” ve “180”** derecelere getirecek bir kod yazarak Arduino’ya atın.
	- Google’da bu işe yarayan bir kod aramanız gerekmektedir. Geliştirdiğimiz alan olan **“Arduino Uno”** ve aradığımız şey olan **“Servo”** yu yazmanız yeterli olacaktır.
  -	Servoyu çıkararak **Uzaklık Sensörünü** Arduino’ya bağlayın ve sensörün ölçtüğü uzaklığı sağ üstte bulunan **‘Seri Port’** ekranından okumanızı sağlayacak bir kod yazın. Doğru şekilde ölçüm yapabiliyorsanız kodunuzu **‘Araçlar’** da bulunan **‘Seri Çizici’** yi kullanarak etrafı haritalandıracak hale getirin.
	- Sensör için hazırlanmış kütüphanelerden birini kullanmanız işinizi kolaylaştıracaktır. Farklı bir kütüphane kullanmak için kütüphane klasörünü bilgisayarınızda yer alan Arduino klasörünün içerisindeki **‘libraries’** klasörünün içerisine atmanız ve kodunuzun başında bu kütüphaneyi ```#include <kütüphaneadı.h>``` kodu ile derlemeye dahil etmeniz gerekmektedir.
  
  -	Servo ve sensörü; servo döndükçe o açının uzaklığını ölçecek şekilde birbirine monte edin. Ardından servo **“0”** dereceden **“180”** dereceye giderken uzaklık ölçümlerini alacak bir kod yazın. Ölçümün sonunda servoyu ölçülen en küçük dereceye getirin.
	- For döngüsü içerisinde ölçülen değeri bir minimum değerine atayarak; sonraki ölçümlerde ölçülen değer daha küçükse minimumu değiştirip o andaki indise denk gelen açıyı başka bir değişkene eşitleyip en sonunda bu değişkeni kullanarak bu işlemi yapabilirsiniz.
  -	GitHub masaüstü uygulamasını kullanarak bu proje için yeni bir Repository oluşturun. Deponuzun public olduğundan emin olun. README.md dosyasını oluşturun veya diğer deponuzdakini kopyalayın. Bu dosyayı text editor programınızla açarak projeniz için GitHub’da aşağıda gözükecek bir açıklama yazın. Arduino kodunuzu bu depoya atarak depo linkini mail atın.
