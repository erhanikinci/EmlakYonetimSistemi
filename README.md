
# Masaüstü Uygulaması(Desktop Application) Çevrimiçi Emlak Yönetimi Sistemi

## Emlak Yönetim Sistemi
Emlak Yönetim Sistemi sayesinde belirlenen bölgelerdeki Satılık/Kiralık Emlakları tek bir platform altında toplayarak, çeşitli filtreler ve emlak sorgulama parametreleri ile potansiyel müşterilere kolay ve kullanışlı bir ara yüz sunarak çaba harcamadan o bölgedeki Emlaklar arasından en avantajlı fiyatları garanti eder. Bu bağlamda Emlak Yönetim Sistemi (EYS) müşteri odaklı bir uygulamadır.


## Gereksinimler
  - MySQL Server
  - Eclipse IDE
  - JDK 1.8
## Kurulum
  - Öncelikle yerel mysql sunucusu kurulumu yapılır.
  - Kaynak kodun yanında paylaşılan SQL dosyası(EstateMS.sql) mysql sunucusuna aktarılır.
  - Kaynak kod Eclipse IDE'ye aktarılır.
  - Proje Eclipse IDE ile açılıp, Model paketi altındaki Model sınıfında bulanan mysql sunucusu bilgileri (mysql sunucusu adresi, portu, kullanıcı adı ve şifresi) düzenlenir.
  - Eclipse IDE üzerinde proje Maven build yapılıp çalıştırılır.
## Bağımlılık Yönetimi
  - Maven ile swing, mysql connector gibi bağımlılık paketleri maven depolarından temin edilir. Build işlemi haricinde ek bir işlem yapmanız gerekmemektedir.
## Kullanıcı Giriş Ekranı
![KullaniciGirisEkrani](https://user-images.githubusercontent.com/81168263/154951901-64639ba0-9e09-4410-8956-4e509ec4e3fe.jpg)
## Kayıt Ekranı
![KayitEkrani](https://user-images.githubusercontent.com/81168263/154951935-f1923754-56d1-4a54-985c-b15935ce2d7b.jpg)
## Kullanıcı Düzenleme
![KullaniciDuzenleme](https://user-images.githubusercontent.com/81168263/154951943-33f83e83-5c94-47b0-836a-68368b6b0f0a.jpg)
## Emlak Düzenleme
![EmlakDuzenleme](https://user-images.githubusercontent.com/81168263/154951966-c3ff515c-6779-4d95-a6a2-8963334fea11.jpg)
## Lisans Düzenleme
![LisansDuzenleme](https://user-images.githubusercontent.com/81168263/154951970-6f9ea5e3-b494-4189-ab19-6ac30c5e8ecd.jpg)
## Tüm Kullanıcılar
![TumKullanicilar](https://user-images.githubusercontent.com/81168263/154952038-df8ea00e-b47f-454c-979c-312c64e9fb43.jpg)
## Yetkili Kullanıcılar
![YetkiliKullanicilar](https://user-images.githubusercontent.com/81168263/154952041-1d247055-2efc-4be3-94d6-d243c16a132d.jpg)
## Yönetici İşlemleri
![Yoneticiİslemleri](https://user-images.githubusercontent.com/81168263/154952048-9a267c24-0ba3-42d5-b5cf-54543ac0593d.jpg)


## Dipnot

- Kısıtlı zamana sahip olan bir Proje olduğu için kod kalitesi çok düşüktür.
- Uygulamanın server side tarafı, API katmanı, dolaylı olarak input validation kontrolleri mevcut değildir. Uzak bir mysql sunucusuna doğrudan client side bir uygulama ile bağlantı sağlanıldığı bir senaryo olarak baz alınmıştır. Güvenli yazılım geliştirme metodları hakgetiredir.
