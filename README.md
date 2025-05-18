# Retrotech-tycoon
 “Garajdan başlayan, gerçek zamanlı kaynak yönetimli teknoloji simülasyonu”
# RetroTech Tycoon

**RetroTech Tycoon**, 1970’lerin sonunda geçen, oyuncunun garajında teknoloji üretmeye çalıştığı bir strateji-simülasyon oyunudur. Amacın; donanım, yazılım ve oyun geliştirme alanlarında kariyer yaparak, sıfırdan kendi teknoloji imparatorluğunu kurmak!

![banner-placeholder](https://via.placeholder.com/800x200.png?text=RetroTech+Tycoon)

## Özellikler

- **Karakter Yaratma:** Oyuncular 7 puanla karakterlerini özelleştirir (3 teknik, 3 aktif özellik).
- **Gerçek Zamanlı Proje Yönetimi:** Projeler başlatıldığında gerçek dünyadaki süre kadar beklenmesi gerekir.
- **Yıldız Tabanlı Kabiliyet Sistemi:** Renkli ve bölünebilir yıldızlar oyuncunun hangi projeleri yapabileceğini etkiler.
- **Modüler Ana Ekran:** Karakter, projeler, teknoloji ağacı ve ekip yönetimi gibi bölümler ayrı modüller halinde görüntülenir.
- **Tarihsel Teknoloji Ağacı:** Gerçek bilgisayar tarihine dayalı donanım ve yazılım gelişim yolları.
- **Gelecekte:** Ekip üyeleri, yatırımcılar, rakip firmalar ve pazar dinamikleri gibi özelliklerle genişletilebilir.

## Kurulum

### Gerekli Kurulumlar

- Python 3.8+
- pip
- virtualenv (önerilir)

### Başlatmak İçin

```bash
git clone https://github.com/kullaniciadi/retrotech-tycoon.git
cd retrotech-tycoon

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

pip install -r requirements.txt
python run.py
