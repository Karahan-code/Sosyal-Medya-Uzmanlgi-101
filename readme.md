<div align="center">

# 📱 Sosyal Medya İçerik Üretimi & Tasarım Rehberi

Bu repo, sosyal medya uzmanlığı yolunda görsel tasarım süreçlerini, teknik detayları ve ipuçlarını içerir.

<img src="https://img.shields.io/badge/Adobe%20Photoshop-31A8FF?style=for-the-badge&logo=Adobe%20Photoshop&logoColor=black" />
<img src="https://img.shields.io/badge/Adobe%20Illustrator-FF9A00?style=for-the-badge&logo=Adobe%20Illustrator&logoColor=black" />
<img src="https://img.shields.io/badge/Adobe%20After%20Effects-9999FF?style=for-the-badge&logo=Adobe%20After%20Effects&logoColor=black" />

</div>

---

## 🛠️ İhtiyacımız Olan Araçlar

| Program | Kullanım Amacı |
| :--- | :--- |
| **Photoshop** | Fotoğraf düzenleme işlemleri için. |
| **Illustrator** | Vektörel çizimler ve Yapay Zeka desteği için. |
| **After Effects** | Hareketli grafikler ve video kurgu işleri için. |

---

## 📂 Örnek Çalışmalar
Aşağıda bu rehber kullanılarak oluşturulmuş bazı şablon örneklerini görebilirsiniz:

<div align="center">
  <img src="bitmiş-tasarımlar/şablondeneme4 kopya.jpg" width="200" />
  <img src="bitmiş-tasarımlar/şablondeneme3 kopya.jpg" width="200" />
  <img src="bitmiş-tasarımlar/şablondeneme2 kopya.jpg" width="200" />
  <img src="bitmiş-tasarımlar/şablondeneme1 kopya.png" width="200" />
</div>

---

## 📸 Bölüm 1: İlgili Görselleri Temin Etmek

Ürünlerin stok fotoğraflarını indirmek için iki temel yöntem vardır:

1.  **Doğrudan Kayıt:** İlgili fotoğraflara sağ tıklayıp `Resmi Farklı Kaydet` diyerek indirebilirsiniz.
2.  **Kaynak Kod İle (Inspect):** Sağ tıklayıp `İncele (Inspect)` diyerek sitenin kaynak kodlarından görsel linkini bulabilirsiniz.

> [!WARNING]
> Bazı web sitelerinin logoları veya görselleri tamamen kodlarla (CSS) yapılmış olabilir. Bu durumda görsel olarak indirme yapılamaz, ekran görüntüsü veya SVG export gerekebilir.

<div align="center">
  <img src="readme-foto/1.png" width="600" alt="Resim indirme örneği">
</div>

---

## 🎨 Bölüm 2: Photoshop Hazırlığı ve Kurulum

Standart bir Instagram gönderisi için tuval ayarları kritik önem taşır.

* **Genişlik:** 1080px
* **Yükseklik:** 1080px (Kare form)
* **Çözünürlük (DPI):** 150 (Web için 72 yeterlidir ama 150 daha net sonuç verir)
* **Renk Modu:** RGB (Dijital ekranlar için)

<div align="center">
  <img src="readme-foto/2.png" width="600" alt="Photoshop ayarları">
</div>

---

## ⚠️ Bölüm 3: Sık Karşılaşılan Hatalar ve Çözümleri

### 1. Arka Plan Temizleme (Dekupe)
İndirdiğiniz fotoğraflar genellikle şeffaf (PNG) değildir.
* **Çözüm:** Photoshop'ta görseli açın > **Sihirli Silgi Aracı (Magic Eraser Tool)** seçin > Arka plana bir kez tıklayın.

<div align="center">
  <img src="readme-foto/3.png" width="600" alt="Arka plan silme">
</div>

### 2. Kaydetme Formatı Sorunu (RGB vs CMYK)
Arka planı silseniz bile bazen PNG olarak kaydedemezsiniz. Bunun sebebi renk modudur.

> [!TIP]
> **CMYK**, baskı içindir ve şeffaflığı desteklemez. Dosyanızı **RGB** moduna çevirmeden PNG (şeffaf) çıktı alamazsınız.

<div align="center">
  <img src="readme-foto/4.png" width="600" alt="Renk modu hatası">
</div>

### 3. Doğru Kaydetme (Export)
Dosyalarınızı yönetmek için kısayolları kullanın:
* `Dosya > Farklı Kaydet`
* Kısayol: `CTRL + Shift + S`

<div align="center">
  <img src="readme-foto/5.png" width="600" alt="Farklı kaydet ekranı">
</div>