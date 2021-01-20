# MobileProgramming

//uygulama adımları/kullanılışı

1.ilk önce 'npm install' komut satırı ile bağımlılıklar yüklenir.

2.ilgili dizinde ionic serve yapılarak webdeki konsolda ve arayüzde çıktılar gözlenebilmektedir.

3.Uygulama Firabase ile bağlantılıdır ve login durumları için email adresi kullanmaktadır.
  Misafir olarak da giriş yapılabilmektedir.

Şekil1:Giriş sayfası
![Screenshot from 2021-01-20 22-40-21](https://user-images.githubusercontent.com/40118057/105227200-0dbfb900-5b72-11eb-9e3e-9ae07e177be2.png)

4.Kralların bilgisi üzerinde işlem yapılabilmektedir.(two way binding)
  
5.Navigasyon işlemleri ile ilgili sayfalara/componentlere yönlendirme yapılmaktadır.

Şekil2:Butonlar yardımı ile navigasyon işlemi gerçekleştirilmiştir.
![Screenshot from 2021-01-20 22-40-30](https://user-images.githubusercontent.com/40118057/105227272-25973d00-5b72-11eb-91d8-cd868937cf90.png)

6.Servis yapısı ile ilgili page üzerindeki işlemler log edilebilmektedir.

Şekil3.Ekran görüntüsü sol alt servis işleminin log edilmesini göstermektedir.
![Screenshot from 2021-01-20 22-40-40](https://user-images.githubusercontent.com/40118057/105227303-2f20a500-5b72-11eb-9a97-3c12a21e8eef.png)

7.Uygulamanın androidde çalışması için yapılandırılması gerekmektedir.

8.Uygulamanın ilk sürümü 'npx cap open android' komutu ile emülatör üzerinde de 
  gözlemlenebilmektedir.
  
Şekil4:Uygulamanın capacitor üzerinde çalışması resmedilmiştir.
![Screenshot from 2021-01-20 22-48-15](https://user-images.githubusercontent.com/40118057/105227318-33e55900-5b72-11eb-83e5-90adce123154.png)
  


//app usage

1.By making ionic serve in the relevant directory, outputs can be observed in the console 
  and interface on the web.

2.The application is linked to Firebase and uses an e-mail address for login status. 
  You can also log in as a guest.
  
3.Operation can be done on the knowledge of the kings (two way binding).

4.Transactions on the page related to the service structure can be logged.

5.Finally, the first version of the application can be observed on the emulator with 
  the 'npx cap open android' command.
