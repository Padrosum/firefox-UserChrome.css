# Padros Minimalist Firefox (Floating Sidebar) 🦊

![Banner](https://github.com/Padrosum/firefox-UserChrome.css/banner.png)

Bu depo, Firefox'u hantal ve kalabalık arayüzünden kurtarıp, tam odaklı bir "iş istasyonuna" dönüştüren özel bir `userChrome.css` yapılandırmasıdır. Sidebery eklentisiyle tam uyumlu çalışır.

Sürekli sayfa genişliğini bozan, siteleri sağa sola kaydıran geleneksel yan panellerin aksine; bu yapılandırma **sayfanın üzerine binen (floating/overlay) ve sadece üzerine gelindiğinde açılan (hover-to-expand)** akıcı bir mekanizma kullanır.

## 🚀 Özellikler

- **Görünmez Yerleşik Sekmeler:** Üstteki kalabalık sekme çubuğu tamamen gizlendi.
- **Yüzen Yan Panel (Floating Sidebar):** Panel açıldığında web sitelerini itmez, sohbet uygulamalarında genişlik daralmasına (jitter) sebep olmaz.
- **Hover-to-Expand:** Sadece ekranın en soluna (5px'lik tetikleyici alana) fareyi götürdüğünüzde pürüzsüzce açılır. Kapalıyken tamamen gizlenir.
- **Merkezi Adres Çubuğu:** URL çubuğundaki metin, odaklanmayı artırmak için ortalandı.
- **Minimalist Arayüz:** Dikey ayırıcı çizgiler (splitter) ve gereksiz başlıklar tamamen temizlendi.

## 🛠️ Kurulum (Arch Linux / Genel Linux)

### 1. CSS Desteğini Açın
1. Firefox adres çubuğuna `about:config` yazın.
2. `toolkit.legacyUserProfileCustomizations.stylesheets` değerini aratıp **true** yapın.

### 2. Dosyaları Yerleştirin
Terminali açın ve Firefox profilinizin bulunduğu `chrome` klasörüne gidin (Eğer klasör yoksa oluşturun):

```bash
cd ~/.mozilla/firefox/*.default-release/
mkdir -p chrome
cd chrome
git clone https://github.com/Padrosum/firefox-UserChrome.css

```

### Gereksinimler

- **Firefox tabanlı browser**
 - **Sidebery eklentisi**
