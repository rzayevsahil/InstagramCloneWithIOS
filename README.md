# InstagramCloneWithIOS

<img src="https://user-images.githubusercontent.com/58303745/186731538-5cc44294-49c7-4315-9d28-0a05d511a8c3.png" alt="drawing" width="300"/>

## **Mobil Programlama** 

### Öğrenci : ***Sahil Rzayev*** 

### Proje adı : ***Instagram Clone*** 

***04/06/2022*** 

### **Uygulama açıklaması** 

Genel görüntü olarak günümüzde popüler olan ***Instagram*** uygulamasına benzetmeye çalıştım.  

### **Giriş sayfası:** 

Kullanıcı mail ve şifresini yazmadan “Giriş Yap” butonu aktif olmuyor. Butona tıkladığında “Oturum Açılıyor” tarzında bilgilendirme mesajı alır(Hud yapısı). 

Eğer kullanıcının hesabı yoksa alt kısımda yer alan “Kayıt ol” kısmından kullanıcı hesabı oluşturabilir. 

<img src="https://user-images.githubusercontent.com/58303745/186731544-b0212734-0fee-44d5-b45e-690ec1da2cfd.png" alt="drawing" width="250"/><img src="https://user-images.githubusercontent.com/58303745/186731545-580fa39e-9c53-4c34-8f08-bde9b56c78ca.png" alt="drawing" width="250"/>
<img src="https://user-images.githubusercontent.com/58303745/186731546-f99f8c7d-ad45-4498-9046-97e59224915c.png" alt="drawing" width="250"/>

### **Kayıt Ol :** 

Burada kullanıcı kendine yeni bir hesap oluşturabilir. Mevcut alanları(kullanıcı fotoğrafı zorunlu değildir) doldurduktan sonra “Kayıt Ol” butonu aktif hale gelir ve kullanıcı botuna tıklayınca “Kaydınız gerçekleşiyor” tarzında bilgilendirme mesajı alır(Hud yapısı). 

<img src="https://user-images.githubusercontent.com/58303745/186731551-cdb2cbaa-e45c-4181-8fbc-279cb1c5d3a1.png" alt="drawing" width="250"/><img src="https://user-images.githubusercontent.com/58303745/186731555-6d08a29d-f057-44fe-89df-9f175a1b7e41.png" alt="drawing" width="250"/>
<img src="https://user-images.githubusercontent.com/58303745/186731558-883bde79-1732-41d5-9163-2dbd0bb684e2.png" alt="drawing" width="250"/>

### **Ana sayfa :** 

Burada kullanıcının zamana göre sıralanmış kendi ve takip ettiği kişilerin paylaşımları listeleniyor. Her paylaşımın içinde paylaşım yapan kullanıcının kullanıcı ismi, profil resmi, paylaşımı, yorumu, paylaşım beğenme sayısı ve ne kadar süre önce paylaştığı ile ilgili bilgiler yer alıyor. 

<img src="https://user-images.githubusercontent.com/58303745/186731561-93d5127d-3976-4dd6-9674-0f721ebbaeb9.png" alt="drawing" width="250"/><img src="https://user-images.githubusercontent.com/58303745/186731566-2af3555a-8ee8-499c-b23b-b094ab932787.png" alt="drawing" width="250"/>

### **Resim paylaşma sayfası :** 

Burada kullanıcı ilk defa paylaşım yapıyorsa telefonundaki resimleri erişmek için izin isteme ile ilgili bilgilendirme mesajı alıyor. Eğer telefonda fazla resim varsa ekranı aşağıya kaydırıp herhangi bir resme tıkladığı anda otomatik olarak kullanıcını paylaşım ekranı olan üst tarafa doğru götürür. Sonra kullanıcı “Sonraki” diyerek paylaşıma yorum yazmak için bir sonraki ekrana yönlendirilir. 

<img src="https://user-images.githubusercontent.com/58303745/186731567-85ec9715-adc1-44bd-9f02-1cbe7c8ba6b5.png" alt="drawing" width="250"/><img src="https://user-images.githubusercontent.com/58303745/186731568-13d1e44c-7d6a-409e-83c2-77235a82fed8.png" alt="drawing" width="250"/>
<img src="https://user-images.githubusercontent.com/58303745/186731569-9e458b4e-49b0-4a0f-bfff-2de825e69384.png" alt="drawing" width="250"/>

### **Kullanıcı arama sayfası :** 

Burada kullanıcı diğer takip etmek istediği profil hesaplarını arayarak takip edebilir. 

“Takip et” butonuna tıkladığında Hem buton rengi değişir, hem de buna uygun olarak “Takipten Çıkar” butonu mevcut olur ve kullanıcının takip ettiği kişinin takipçi sayısı da senkronize bir şekilde artar.   

<img src="https://user-images.githubusercontent.com/58303745/186731570-1b623ebb-fe81-44d4-9a84-845bbbfed984.png" alt="drawing" width="300"/><img src="https://user-images.githubusercontent.com/58303745/186731574-ff939cac-b597-49d6-b947-a7e85dc431a0.png" alt="drawing" width="300"/>
<img src="https://user-images.githubusercontent.com/58303745/186731577-45f0d2cb-599a-4c9d-bbaf-2641c165e58b.png" alt="drawing" width="300"/>

### **Kod Yapısı** 

- *Ara* – Kullanıcı arama kısmı  
- *AnaGorunum* – Ana Sayfa işlemleri burada yapılıyor 
- *FotografEkle* – Fotoğraf paylaşma işlemleri burada yapılıyor 
- *OturumAc* – Giriş yapma kısmı 
- *Model* – Classlar burada yer alıyor.  
- *KullanıcıProfil* – Kullanıcı profili burada yer alıyor 
- *YazdigimUzantilar* – Bazı gerekli olan extensionlar burada yer alıyor. 

<img src="https://user-images.githubusercontent.com/58303745/186731581-2e041a16-7bae-4263-b218-31849a2e67d0.png" alt="drawing" width="250"/>

Genel olarak tasarımı kod yapısı üzerinden gerçekleştirdim. 

*Not: Kod satırları çok fazla olduğu için hepsinin fotoğrafını buraya ekleyemedim. Ama birçok yerde anlaşılır olsun diye yorum satırları bıraktım.* 
