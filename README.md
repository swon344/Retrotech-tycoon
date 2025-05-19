# RetroTech Tycoon

**RetroTech Tycoon**, 1970'lerin sonunda geçen, oyuncunun garajında teknoloji üretmeye çalıştığı bir strateji-simülasyon oyunudur. Oyuncu donanım, yazılım ve oyun geliştirme alanlarında kariyer yaparak, gerçek zamanlı bir sistem içinde kendi teknoloji imparatorluğunu kurmaya çalışır.

---

## Özellikler

### Karakter Sistemi
- 3 Teknik Özellik: Hardware, Software, UI/UX
- 3 Aktif Özellik: Yaratıcılık, Verimlilik, Problem Çözme
- Karakter yaratma sırasında 7 puan verilir (4 teknik + 3 aktif)
- Özellikler renkli yıldız sistemiyle tanımlanır (beyaz < sarı < turuncu < kırmızı < mor < mavi)
- Her yıldız 5 kola bölünebilir (örnek: 2.6 yıldız)

### Gerçek Zamanlı Proje Sistemi
- Projeler gerçek zamanla işler (örnek: 15 dakikalık proje gerçekten 15 dakika sürer)
- Oyuncu oyunda olmasa da süre işlemeye devam eder

### Dinamik Zaman Akışı
- Oyun yılı zamanla yavaşlar:
  - Başta hızlı ilerler (örneğin 1 yıl = 2 saat)
  - İlerledikçe teknolojik karmaşıklığa göre yavaşlar

### Kaynaklar
- Temel: Para (USD), Süre (dakika)
- Her teknoloji ve proje bu iki kaynakla gerçekleştirilir
- İleride ikincil kaynaklar eklenebilir

---

## Teknoloji Ağaçları

### Ortak Teknoloji Ağı
- Oyuncu herhangi bir alanda ilerleyebilir (yazılım, donanım, oyun)
- Her teknoloji:
  - Gerekli yıldız seviyesi
  - Gerçekçi dolar maliyeti (döneme uygun)
  - Belirli bir geliştirme süresi (gerçek zaman)

### Örnek: Hardware Ağacı (1977–1985)
- **Apple II Klavye Tasarımı**: $45, 15 dakika, ≥ 6 beyaz Hardware
- **RS-232 Arabirimi**: $80, 25 dakika, ≥ 1.4 sarı Hardware
- **Floppy Disk Denetleyici**: $150, 45 dakika, ≥ 2.0 sarı Hardware
> Tüm teknolojiler gerçek tarihlere ve bileşenlere dayanır.

---

## Ana Ekran – Modüler Yapı

### Modüller
- Karakter Durumu
- Projeler Modülü
- Teknoloji Ağacı
- Zaman Takvimi
- Çalışma Ortamı (ekip üyeleri)
- Kaynak ve Rapor Paneli
- Popup Bilgi Kutuları

### Çalışma Ortamı
- Başlangıçta oyuncu yalnızdır
- İleride ekip üyeleri işe alınabilir
- Her üyenin kendi yıldız özellikleri olur
- Büyük projelerde ekip üyeleri kullanılabilir

---

## Teknik Altyapı

- **Backend:** Flask
- **Arayüz:** HTML, CSS, JS (Bootstrap destekli)
- **Veri Yapısı:** Beyaz yıldız sayısına dayalı hesaplama
- **Gerçek Zamanlı Süre Takibi:** Flask + zaman damgası ile yapılır

### Proje Yapısı

retrotech_tycoon/
├── app/
│ ├── templates/
│ ├── static/
│ ├── routes.py
│ ├── models.py
│ └── utils.py
├── run.py
├── requirements.txt
└── README.md


---

## Geliştirme Durumu

- [x] Tema ve kurgu belirlendi
- [x] Karakter sistemi ve yıldız yapısı kurgulandı
- [x] Gerçek zamanlı süre ve kaynak sistemi tasarlandı
- [x] Hardware teknoloji ağacı (1977–1985) oluşturuldu
- [x] Replit uyumlu starter template (.zip) hazırlandı
- [ ] Karakter yaratma arayüzü (yakında)
- [ ] Dashboard (ana ekran) modülleri (yakında)
- [ ] Proje başlatma-tamamlama döngüsü (yakında)

---

## Lisans

MIT License – Açık kaynaklı geliştirilmekte

---

RetroTech Tycoon ile dijital devrimi kendi ellerinle başlat!
