# Minimalist Bir Linux Dağıtımı Geliştirilmesi (MyOS)

Bu proje, minimalist, yüksek performanslı, yalnızca gerekli bileşenleri içeren ve sunucu odaklı bir Linux dağıtımı geliştirmek amacıyla yapılmıştır. MyOS, düşük donanım gereksinimlerine sahip sistemler için optimize edilmiş bir çözüm sunar.

## 🔍 Proje Hakkında

- **Proje Adı:** MyOS
- **Tür:** Tezsiz Yüksek Lisans Proje Tezi
- **Danışman:** Prof. Dr. Erkan ÜLKER
- **Sayfa Sayısı:** 48
- **Yıl:** 2025
- **Üniversite:** Konya Teknik Üniversitesi

### 🎯 Amaç
1. **Performans Artışı:** Sistem açılış sürelerini ve bellek kullanımını minimize etmek.
2. **Küçük Ayak İzi:** Disk alanı kullanımını 500 MB altında tutmak.
3. **Esneklik:** Kullanıcıların sistemlerini özelleştirebileceği bir altyapı sağlamak.

### 🚀 Özellikler
- Minimal bileşenler
- Sunucu odaklı tasarım
- 10 saniye altında başlatma süreleri
- Ortalama 100 MB bellek kullanımı
- 400 MB disk alanı

### 🛠️ Kullanılan Teknolojiler
- **Linux Kernel:** Minimalist yapılandırma
- **QEMU:** Sanal makine test ortamı
- **Bash Scripting:** Kullanıcı betikleri ve sistem başlangıcı

## 📄 Detaylı Rapor
Projenin tüm teknik detaylarına ve geliştirme sürecine [tam rapordan](./Minimalist_Bir_Linux_Dagitimi_Gelistirilmesi.pdf) ulaşabilirsiniz.

## 📊 Performans Karşılaştırması
| **Özellik**           | **MyOS** | **Debian** | **Alpine** | **Tiny Core** | **Arch Linux** |
|------------------------|----------|------------|------------|---------------|----------------|
| **Bellek Kullanımı**   | 100 MB   | 260 MB     | 100 MB     | 64 MB         | 512 MB         |
| **Başlatma Süresi**    | 10 sn    | 20 sn      | 10 sn      | 5 sn          | 15-20 sn       |
| **Disk Alanı Kullanımı** | 400 MB  | 1.2 GB     | 130 MB     | 16 MB         | 800 MB         |

## 📝 Lisans
Bu proje [MIT Lisansı](./LICENSE) altında lisanslanmıştır.
