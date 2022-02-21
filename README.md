# EmlakYonetimSistemi
Emlak Yönetim Sistemi sayesinde belirlenen bölgelerdeki Satılık/Kiralık Emlakları tek bir platform altında toplayarak, çeşitli filtreler ve emlak sorgulama parametreleri ile potansiyel müşterilere kolay ve kullanışlı bir ara yüz sunarak çaba harcamadan o bölgedeki Emlaklar arasından en avantajlı fiyatları garanti eder. Bu bağlamda Emlak Yönetim Sistemi (EYS) müşteri odaklı bir uygulamadır.
# Masaüstü Uygulaması(Desktop Application) Çevrimiçi Emlak Yönetimi Sistemi

## Dipnot

- Kısıtlı zamana sahip olan bir Proje olduğu için kod kalitesi çok düşüktür.
- Uygulamanın server side tarafı, API katmanı, dolaylı olarak input validation kontrolleri mevcut değildir. Uzak bir mysql sunucusuna doğrudan client side bir uygulama ile bağlantı sağlanıldığı bir senaryo olarak baz alınmıştır. Güvenli yazılım geliştirme metodları hakgetiredir.

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
## Demo
![alt text](./assets/img/KullaniciGirisEkrani.jpg)
![alt text](./assets/img/4.jpg)
![alt text](./assets/img/5.jpg)
![alt text](./assets/img/6.jpg)
![alt text](./assets/img/2.jpg)
![alt text](./assets/img/3.jpg)
![alt text](./assets/img/7.jpg)
