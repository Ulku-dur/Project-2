#Patika Turizm Acentesi Turizm Acente Sistemi
Bu proje, Patika Turizm Acentesi'nin günlük operasyonlarını dijital bir platforma taşımak için geliştirilmiş bir 
yazılım çözümüdür. Bu yazılım, otel yönetimi, oda yönetimi, dönem yönetimi, fiyat yönetimi, oda arama ve rezervasyon 
işlemleri gibi bir dizi özelliği içermektedir.

**Kullanılan Teknolojiler**
- Java
- Java Swing (GUI)
- MySQL

**Kurulum **
- Bu projeyi klonlayın.
- MySQL veritabanında patika_turizm adında bir veritabanı oluşturun.
- trsm.sql dosyasını kullanarak veritabanı tablolarını oluşturun.
Veritabanı bağlantısını yapılandırmak için DatabaseConnection.java dosyasını düzenleyin.

**Proje Yapısı**
src dizini altında Java kaynak kodları bulunmaktadır.
entity: Veritabanı tablolarını temsil eden model sınıfları
dao: Veritabanı işlemlerini gerçekleştiren DAO (Data Access Object) sınıfları
business: İş mantığını gerçekleştiren servis sınıfları
views: Kullanıcı arayüzünü oluşturan Swing GUI sınıfları
core: dizini altında veritabanı oluşturma dosyası, bulunmaktadır.
Kullanıcı Roller ve Yetkileri

**Admin**
Acente çalışanı ekleme, silme, güncelleme

**Acente Çalışanı (Personel)**
Otel ekleme, listeleme
Oda ekleme, listeleme
Sezon ekleme, listeleme
Fiyat yönetimi
Oda arama
Rezervasyon işlemleri
projenin çalıştırıldığı videoya aşağıdaki linkten ulaşabilirsiniz:
https://www.loom.com/share/0556ce38b2554c3d9650eec2f402cef7?sid=2802128d-d1b0-4e4d-8985-3ded7dc561de
