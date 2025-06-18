# SafeDev: KOBİ Yazılım Güvenliği ve KVKK Denetim Platformu

## Genel Bakış

Ashborn, Türkiye'deki yazılım geliştiren Küçük ve Orta Ölçekli İşletmeler (KOBİ'ler) için özel olarak tasarlanmış, kullanımı kolay bir otomatik denetim platformudur. Amacımız, KOBİ'lerin yazılım projelerindeki potansiyel güvenlik açıklarını, kod kalitesi sorunlarını ve özellikle Türkiye Cumhuriyeti Kişisel Verilerin Korunması Kanunu (KVKK) uyumsuzluklarını hızlı ve etkin bir şekilde tespit etmelerini sağlamaktır.

Küresel çözümlerin karmaşıklığı ve yüksek maliyetleri karşısında, Ashborn yerel pazarın ihtiyaçlarına odaklanarak, "kur ve kullan" mantığıyla çalışan, uygun maliyetli ve güvenilir bir denetim motoru sunar.

## Temel Özellikler (MVP)

Ashborn MVP (Minimum Viable Product), ilk aşamada aşağıdaki temel yetenekleri sunmaktadır:

* **Statik Kod Analizi:** Yazılım kodundaki yaygın güvenlik zafiyetlerini (örn. SQL Injection, XSS, Path Traversal) ve potansiyel hataları otomatik olarak tespit eder.
* **KVKK ve Hassas Veri Denetimi:** Kod tabanında, kişisel verilerin (TCKN, telefon numarası, e-posta, kredi kartı bilgileri vb.) uygunsuz kullanımını veya veri sızıntısı risklerini gösteren hassas bilgileri tarar.
* **Kullanıcı Dostu Arayüz (GUI):** Kullanıcıların analiz etmek istedikleri proje klasörünü kolayca seçmelerine ve denetim sonuçlarını net bir şekilde görüntülemelerine olanak tanıyan sezgisel bir grafik arayüz sunar.

## Teknoloji Yığını

* **Çekirdek Dil:** Python
* **Kullanıcı Arayüzü (GUI):** PyQt6
* **Statik Analiz Motorları:** Semgrep, Flake8 (Python kod kalitesi için)
* **Veri Tespiti:** Regex tabanlı özelleştirilmiş kurallar


## Gelecek Planları

Ashborn'u daha da geliştirmek ve KOBİ'lere daha kapsamlı çözümler sunmak için aşağıdaki özellikler üzerinde çalışmayı planlıyoruz:

* Çeşitli programlama dilleri için destek
* Otomatik test çalıştırma ve raporlama entegrasyonu
* Gelişmiş yapay zeka (LLM) destekli analiz ve öneriler
* Detaylı GUI raporlama ve filtreleme seçenekleri
* CI/CD entegrasyonları

## İletişim

Sorularınız, geri bildirimleriniz veya potansiyel işbirlikleri için benimle iletişime geçmekten çekinmeyin:

--Ediz Savaş--

edizsavas00@gmail.com,

www.linkedin.com/in/ediz-savaş-41a96b368

---
