[AKILLI TELEFONLAR İLE NESNE TAKİBİ PROJESİ]

**********PROJE ÖZETİ**********

->Bu projede react-native kod ile yazdığımız android uygulamasıyla resim çekip veya resmi galeriden seçebilirsiniz, 
çekilen veya seçilen resmi backend'teki kendi yazdığımız server'a atar server üzerinde Darknet Yolov3 algoritmasıyla nesne takibini gerçekleştirir
nesne takibi gerçekleştikten sonra output.jpg şeklinde resim geri dönderilir ve ekranda resimde kaç tane nesne olduğu yazar  

**********PROJEYİ İNDİRMEK**********

-> kaynakKod.zip kodunun içerisinde mevcuttur. (resimleriyle beraber)
-> Veya https://webapp.diawi.com/install/Ac7Wzw bu link üzerinden apk olarak indirebilirsiniz
NOT : >.zip dosyasını açmak için 
>Windows'ta çeşitli programlar kullanabilirsiniz. 
>Linux'ta ise eğer .zip dosyasında şifre yoksa unzip dosyaadı.zip / eğer .zip dosyasında şifre var ise unzip -P şifre dosyaadı.zip ile açabilirsiniz.

**********PROJEYİ ÇALIŞTIRMAK VE TEST ETMEK**********

-> Yeni bir react-native projesi oluşturun, App.js içerisindeki kodu kendi kodunuzu kopyalayın
-> npm i react-native-image-crop-picker --save, komut satırını kullanarak kütüphaneyi koda ekleyin
-> buid.gradle altındaki repositories'i https://github.com/ivpusic/react-native-image-crop-picker sitedeki yöntemleri izleyerek düzeltiniz
-> daha sonra android 9 ve üstü cihazlarda proje çalışabilir
-> uygulamayı ilk açtığınıza karşınıza 3 buton ve resim yeri çıkacaktır, ilk buton ile kameradan fotoğraf çekersiniz, ikinci buton ile galeriden
fotoğraf seçersiniz, üçüncü buton ile mevcut gösterilen fotoğrafı temizlersiniz
-> herhangi bir fotoğraf çektikten veya seçtikten sonra fotoğraf server'a gönderiler ve geriye nesne takibi yapılmış fotoğraf geriye döner
ayrıca fotoğraf üzerindeki toplam nesne sayısı ekrana yazılır

**********PROJEYİ GELİŞTİRİRKEN YARARLANILAN TEKNOLOJİLER**********
-> react-native, react-native-image-crop-picker ,python, python flask api, fetch api, darknet yolov3 
**********PROJEYİ HAZIRLAYAN**********
Abdussamed KILIÇ (180201011)
Orhun Mert BOZKURT (180201159)