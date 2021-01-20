# MobileProgramming

//uygulama adımları/kullanılışı

1.ilk önce 'npm install' komut satırı ile bağımlılıklar yüklenir.

2.ilgili dizinde 'ionic serve' yazılarak webdeki konsolda ve arayüzde çıktılar gözlenebilmektedir.

3.Uygulama Firabase ile bağlantılıdır ve login durumları için email adresi kullanmaktadır.
  Misafir olarak da giriş yapılabilmektedir.(database and authentication)


![Screenshot from 2021-01-20 22-40-21](https://user-images.githubusercontent.com/40118057/105227200-0dbfb900-5b72-11eb-9e3e-9ae07e177be2.png)
Şekil1:Giriş sayfası



4.Kralların bilgisi(kings.information) üzerinde işlem yapılabilmektedir.(two way binding)
  
5.Navigasyon işlemleri ile ilgili sayfalara/componentlere yönlendirme yapılmaktadır.(navigation)


![Screenshot from 2021-01-20 22-40-30](https://user-images.githubusercontent.com/40118057/105227272-25973d00-5b72-11eb-91d8-cd868937cf90.png)
Şekil2:Butonlar yardımı ile navigasyon işlemi gerçekleştirilmiştir.



6.Servis yapısı ile ilgili page üzerindeki işlemler log edilebilmektedir.(servis arch)


![Screenshot from 2021-01-20 22-40-40](https://user-images.githubusercontent.com/40118057/105227303-2f20a500-5b72-11eb-9a97-3c12a21e8eef.png)
Şekil3.Ekran görüntüsü sol alt servis işleminin log edilmesini göstermektedir.



7.Uygulamanın androidde çalışması için yapılandırılması gerekmektedir.

8.Uygulamanın ilk sürümü 'npx cap open android' komutu ile emülatör üzerinde de 
  gözlemlenebilmektedir.(capacitor-cross platform app)
  

![Screenshot from 2021-01-20 22-48-15](https://user-images.githubusercontent.com/40118057/105227318-33e55900-5b72-11eb-83e5-90adce123154.png)
Şekil4:Uygulamanın capacitor üzerinde çalışması resmedilmiştir.


  


//app usage

1.By making ionic serve in the relevant directory, outputs can be observed in the console 
  and interface on the web.

2.The application is linked to Firebase and uses an e-mail address for login status. 
  You can also log in as a guest.
  
3.Operation can be done on the knowledge of the kings (two way binding).

4.Transactions on the page related to the service structure can be logged.

5.Finally, the first version of the application can be observed on the emulator with 
  the 'npx cap open android' command.
