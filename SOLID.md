# SOLID Prensipleri

**SOLID**, nesne yönelimli programlamada (OOP) daha okunabilir, genişletilebilir ve sürdürülebilir bir mimari kurmak için kullanılan beş temel prensibi ifade eder. Aşağıdaki özet, hem teknik doğruluğu korur hem de akıcı bir anlatım sunar.

---

## S — Single Responsibility Principle (Tek Sorumluluk Prensibi)

Bir sınıf **yalnızca tek bir işten sorumlu olmalıdır**.  
Bir sınıfı değiştirmek için **tek bir mantıksal sebep** bulunmalıdır.

Bu prensip, kodun daha düzenli ve yönetilebilir kalmasını sağlar.

---

## O — Open/Closed Principle (Açık/Kapalı Prensibi)

Yazılım bileşenleri **genişletmeye açık**, **değiştirmeye kapalı** olmalıdır.  
Yani yeni davranış eklerken mevcut kodu mümkün olduğunca bozmamak hedeflenir.

Bu tasarım yaklaşımı, sistemi geliştirmeyi güvenli ve öngörülebilir hale getirir.

---

## L — Liskov Substitution Principle (Yerine Geçme Prensibi)

Alt sınıflar, üst sınıfların yerine **sorunsuz bir şekilde kullanılabilmelidir**.  
Bir alt sınıf, base sınıfın beklentilerini bozuyorsa bu prensip ihlal edilmiş olur.

Doğru uygulanması, polimorfizmin sağlıklı işlemesi açısından kritiktir.

---

## I — Interface Segregation Principle (Arayüz Ayrımı Prensibi)

Bir sınıfa **ihtiyaç duymadığı metotları** zorunlu kılan geniş ve şişkin arayüzler kullanılmamalıdır.  
Arayüzler daha küçük, odaklı ve net sorumluluklara bölünmelidir.

Bu yaklaşım, bağımlılıkları azaltır ve geliştirmeyi kolaylaştırır.

---

## D — Dependency Inversion Principle (Bağımlılıkların Ters Çevrilmesi Prensibi)

Yüksek seviye bileşenler, düşük seviye bileşenlere değil; **soyutlamalara (interface/abstract class)** bağımlı olmalıdır.  
Beton (concrete) implementasyonlara doğrudan bağımlılık sistemi kırılgan hale getirir.

Soyutlamaya bağımlı olmak, modüllerin bağımsızca evrilmesini sağlar.

---

## Kısa Özet

- **S** — Tek sorumluluk  
- **O** — Genişletmeye açık, değiştirmeye kapalı  
- **L** — Alt sınıf, üst sınıfın yerine geçebilmeli  
- **I** — Küçük ve odaklı arayüzler  
- **D** — Soyutlamaya bağımlılık  

Bu prensipler bir arada kullanıldığında, büyüyen projeleri yönetmek çok daha kolay hale gelir.
