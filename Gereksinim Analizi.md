# Gereksinim Analizi

Proje Adı: **anapredai**

## Giriş
Bu gereksinim analizi, AnapredAI projesinin kapsamlı bir özeti olarak hazırlanmıştır ve projenin temel fonksiyonlarını, kullanım senaryolarını ve performans kriterlerini detaylandırmaktadır.

## Fonksiyonel Gereksinimler

### FR1: Veri Yükleme
- Kullanıcıların CSV veya Excel formatındaki veri setlerini yükleyebilmelerini sağlamak.
- Yüklenen verilerin sistem tarafından doğru bir şekilde işlenmesini garantilemek.

### FR2: Veri Temizleme
- Boş veya eksik verileri tespit edebilme ve bunları düzeltme veya kaldırma seçenekleri sunmak.
- Yanlış formatlanmış veri girişlerini düzeltebilme yeteneği.

### FR3: Veri Görselleştirme
- Çeşitli veri görselleştirme seçenekleri (örn. histogramlar, pasta grafikleri, zaman serisi grafikleri) sunmak.
- Kullanıcıların interaktif şekilde görselleştirmeler oluşturabilmeleri için araçlar sağlamak.

### FR4: Analitik Modeller
- Kullanıcıların seçebileceği çeşitli istatistiksel ve makine öğrenimi modellerini entegre etmek.
- Model seçimi ve parametre ayarları için kullanıcı dostu bir arayüz sağlamak.

### FR5: Tahmin Oluşturma
- Seçilen model temelinde veri seti için tahminler üretebilmek.
- Tahmin sonuçlarını anlaşılır ve kullanışlı bir formatta sunmak.

### FR6: Kullanıcı Hesap Yönetimi
- Kullanıcıların kendi hesaplarını oluşturabilmeleri, oturum açabilmeleri ve hesap bilgilerini yönetebilmeleri.
- Güvenlik standartlarına uygun kimlik doğrulama ve veri koruması.

## Fonksiyonel Olmayan Gereksinimler

### NFR1: Kullanılabilirlik
- Kullanıcıların sistemi minimum eğitimle kullanabilmesi.
- Intuitif ve temiz bir kullanıcı arayüzü tasarımı.

### NFR2: Performans
- Büyük veri setleri üzerinde hızlı işlem yapabilme kabiliyeti.
- Anlık kullanıcı etkileşimlerine 2 saniye içinde yanıt verebilme.

### NFR3: Güvenlik
- Tüm kullanıcı verilerinin güvenli bir şekilde saklanması.
- Veri aktarımında end-to-end şifreleme kullanımı.

### NFR4: Ölçeklenebilirlik
- Artan kullanıcı ve veri yükünü destekleyebilecek bir sistem altyapısı.
- Bulut hizmetleri ile entegrasyon.

### NFR5: Uyumluluk
- Farklı tarayıcılar ve cihazlar arasında tutarlı bir kullanıcı deneyimi sunmak.

## Kısıtlamalar

### CON1: Teknoloji Stack'ı
- Proje, Flask (Python), JavaScript, HTML ve CSS kullanılarak geliştirilecektir.

### CON2: Bütçe
- Bütçe kısıtlamaları nedeniyle, açık kaynaklı araçlar ve kütüphaneler tercih edilecektir.

### CON3: Teslim Tarihi
- Prototipin ilk sürümü YYYY-MM-DD tarihine kadar tamamlanmalı ve sunulmalıdır.

## Bağımlılıklar

### DEP1: Veri Setleri
- Modelin eğitimi ve testi için güvenilir veri setlerine erişim.

### DEP2: Harici Kütüphaneler
- Analiz ve görselleştirme için gerekli Python ve JavaScript kütüphaneleri.

## Gözden Geçirme ve Onay

Bu gereksinim analizi, projenin geliştirilmesi aşamasına geçmeden önce gözden geçirilecek ve onaylanacaktır.

