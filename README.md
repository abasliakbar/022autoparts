# 🚗 022 Avto Ehtiyat Hissələri

[![GitHub Pages](https://img.shields.io/badge/Status-Live%20on%20GitHub%20Pages-brightgreen)](https://022auto.github.io)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Dark Mode](https://img.shields.io/badge/Theme-Dark%20%2F%20Light-orange)](#-əsas-özəlliklər)
[![Language](https://img.shields.io/badge/Language-AZ%20%7C%20EN-red)](#-əsas-özəlliklər)

**022 Avto** — Bakı şəhərində fəaliyyət göstərən, premium və orijinal avtomobil ehtiyat hissələrinin satışı üzrə ixtisaslaşmış mağazanın rəsmi müasir veb-saytıdır. 

Müştərilərə avtomobillərinin VIN kodu və ya hissə adları vasitəsilə birbaşa **WhatsApp** üzərindən sürətli sifariş göndərmək, mağazanın canlı iş saatlarını və dəqiq məkanını görmək imkanı yaradır.

---

## ✨ Əsas Özəlliklər

- **⚡ Express WhatsApp Sifariş Sistemi**: 
  - Müştərinin daxil etdiyi məlumatlar (ad, telefon, avtomobil markası, VIN kod və tələb olunan hissələr) avtomatik olaraq strukturlaşdırılmış peşəkar mesaja çevrilir və birbaşa WhatsApp çatına ötürülür.
  - **Avtomatik Prefiks**: Telefon nömrəsi üçün avtomatik `+994` formatı və yalnız rəqəm filtrləməsi.
  - **VIN Kod Doğrulaması**: Dəqiq 17 simvolluq hərf və rəqəm validasiyası, avtomatik böyük hərflərə (uppercase) çevrilmə.

- **🕒 Timezone Dəstəkli Canlı İş Saatları (Açıq / Bağlı)**:
  - Hər gün **09:00 – 19:00** (Bakı vaxtı, UTC+4) rejimində fəaliyyət göstərir.
  - Mağaza açıq olduqda yaşıl nəfəs alan (pulsing) indikatorla **"İndi Açıqdır"**, iş saatından sonra isə qırmızı indikatorla **"Hazırda Bağlıdır"** göstərilir.
  - Xaricdən (fərqli saat qurşağından) daxil olan istifadəçilər üçün mağazanın açılış və bağlanış vaxtı onların **yerli saatına** avtomatik konvertasiya olunur.

- **🎨 Premium Dark & Light UI/UX Dizayn**:
  - Müasir avtomobil sənayesinə uyğun qara (#0D0D0D), tünd səthlər və elektrik qırmızı (#FF1E27) vurğularla zənginləşdirilmiş minimalist dizayn.
  - Bir toxunuşla qaranlıq və işıqlı mövzu arasında keçid.

- **🌐 İkidilli İnterfeys (AZ / EN)**:
  - Sayt Azərbaycan və İngilis dillərini tam dəstəkləyir; dil dəyişdirildikdə bütün mətnlər və dinamik iş saatları statusu anında yenilənir.

- **📍 İnteraktiv Google Maps və Əlaqə Paneli**:
  - Mağazanın Babək prospektindəki ("Qədim Qəbələ" restoranı ilə üzbəüz) dəqiq koordinatları ilə interaktiv xəritə inteqrasiyası.
  - Tək kliklə birbaşa zəng etmə və Instagram səhifəsinə keçid imkanı.

- **📱 100% Mobil və Planşet Uyğunluğu (Responsive)**:
  - İstənilən ekran ölçüsündə (iPhone, Android, Planşet, Noutbuk və Desktop) ideal vizual və performans təcrübəsi.

---

## 🛠️ İstifadə Olunan Texnologiyalar

| Sahə | Texnologiya |
|---|---|
| **Struktur** | HTML5 (Semantik və SEO optimizasiyalı) |
| **Dizayn & Stillər** | Vanilla CSS3 (Custom Properties, Glassmorphism, Responsive Grid/Flexbox) + Tailwind CSS (Utility classes) |
| **Məntiq & İnteqrasiya** | Vanilla JavaScript ES6+ (DOM API, IntersectionObserver, Intl DateTimeFormat) |
| **Xəritə** | Google Maps Embed API |
| **Fontlar** | Google Fonts (`Plus Jakarta Sans`, `Inter`) |

---

## 📁 Fayl Strukturu

```text
022auto.github.io/
├── index.html       # Əsas veb-səhifə (bütün bölmələr, formalar və xəritə)
├── style.css        # Bütün xüsusi dizayn stilləri, dəyişənlər və animasiyalar
├── script.js        # Validasiya, WhatsApp sifarişi, dil, tema və timezone məntiqi
└── README.md        # Layihə haqqında ətraflı sənədləşmə
```

---

## 🚀 Quraşdırma və İşə Salma

Layihə tamamilə **serverless (statik)** arxitekturaya malikdir və heç bir build prosesinə ehtiyac duymur.

### 1. Kompüterdə yerli açmaq:
Faylları klonlayın və ya yükləyin:
```bash
git clone https://github.com/022auto/022auto.github.io.git
cd 022auto.github.io
```
Və sadəcə `index.html` faylını istənilən veb-brauzerdə iki dəfə klikləyərək açın.

### 2. GitHub Pages ilə yayımlamaq:
1. Repozitoriyanı GitHub-a göndərin (push edin).
2. Repozitoriyanın **Settings > Pages** bölməsinə keçin.
3. Branch olaraq `main` (və ya `master`) və `/root` seçib **Save** edin.
4. Sayt avtomatik olaraq `https://022auto.github.io` ünvanında canlı rejimə keçəcəkdir.

---

## 📞 Əlaqə və Mağaza Məlumatları

- **Ünvan**: Bakı şəhəri, Babək prospekti (Qədim Qəbələ restoranı ilə üzbəüz)
- **Telefon / WhatsApp**: [+994 50 800 54 33](https://wa.me/994508005433)
- **İş Saatları**: Hər gün 09:00 – 19:00 (Bakı vaxtı ilə)
- **Instagram**: [@avto_ehtiyat_hisseleri_022](https://instagram.com/avto_ehtiyat_hisseleri_022)

---

## 📄 Lisenziya

Bu layihə [MIT Lisenziyası](LICENSE) altında qorunur. Bütün hüquqlar **O22 Avto Ehtiyat Hissələri** tərəfindən qorunur.
