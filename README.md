<img width="500" height="500" alt="Ankora Güncel Logo" src="https://github.com/user-attachments/assets/4645e22e-59e6-4afe-85c7-4f8bd8144067" />
<div align="center">
  <img src="Ankora%20G%C3%BCncel%20Logo.jpg" alt="Ankora OS Logo" width="220" style="border-radius: 50%;">
  
  <h1>Ankora OS</h1>
  <p><b>Eski donanımları canlandıran, yazılımcı ve oyuncu dostu, yüksek performanslı Linux dağıtımı.</b></p>

  ![Sürüm](https://img.shields.io/badge/Sürüm-1.0_(Zümrüt)-0ea5e9?style=for-the-badge)
  ![Taban](https://img.shields.io/badge/Taban-Debian_12-A81D33?style=for-the-badge&logo=debian)
  ![Masaüstü](https://img.shields.io/badge/Masaüstü-XFCE_|_KDE-2284F2?style=for-the-badge&logo=xfce)
  ![Lisans](https://img.shields.io/badge/Lisans-Açık_Kaynak-success?style=for-the-badge)
</div>

---

## 📌 Ankora OS Nedir?
Ankora OS, Debian'ın kaya gibi sağlam temelini alıp, modern kullanıcıların ihtiyaç duyduğu hız ve sadelikle yeniden inşa eden bağımsız bir Linux dağıtımıdır. "Bloatware" (sistemi şişiren gereksiz yazılımlar) kavramına karşı sıfır tolerans politikasıyla geliştirilmiştir. 

Amacımız, donanımı ne kadar eski olursa olsun her kullanıcıya akıcı bir deneyim sunarken, profesyonel geliştiricilerin ve oyuncuların ihtiyaç duyduğu altyapıyı "Out-of-the-box" (Kutudan çıktığı gibi) hazır etmektir.

---

## 🎯 Kime Hitap Ediyor?

### Yeni Başlayanlar İçin: "Kur ve Kullan"
Linux dünyasına yeni adım atıyorsanız, Ankora OS sizi terminal ekranlarına veya karmaşık ayarlara mahkum etmez.
* **Tanıdık Arayüz:** Windows kullanıcılarının yabancılık çekmeyeceği, sol altta yer alan akıllı başlat menüsü (Whisker).
* **Günlük Araçlar Hazır:** Brave Browser ile reklamsız internet, LibreOffice ile belge yönetimi ve VLC/MPV ile tüm medya formatları kurulumla birlikte gelir.
* **Tek Merkezden Yönetim:** XFCE ve KDE'nin uygulama çöplüğü temizlenmiş, sistemin tek dosya yöneticisi olarak güçlü ve kullanıcı dostu **Dolphin** belirlenmiştir.

### Profesyoneller ve Geliştiriciler İçin: "Saf Performans"
Sistemin altında yatan mimari, kaynak tüketimini minimize etmek için özel olarak yapılandırıldı.
* **Akıllı Bellek Yönetimi:** `zram-tools` ile bellek sıkıştırma aktiftir, Swap (Takas) alanı optimizasyonu standart olarak gelir.
* **Preload Entegrasyonu:** Makine öğrenimi tabanlı `preload` arka planda çalışarak, en sık kullandığınız uygulamaları RAM'de hazır bekletir ve açılış sürelerini dramatik ölçüde düşürür.
* **Geliştirici Cephaneliği:** `build-essential`, `git`, `python3`, `pip`, `curl` ve `wget` sisteme gömülüdür. VS Code hafifliğindeki **Geany** varsayılan IDE/Editör olarak ayarlanmıştır.
* **Global Mimeapps:** Sistemdeki tüm dosya ilişkilendirmeleri (`/etc/xdg/mimeapps.list`) manuel olarak yapılandırılmış, masaüstü ortamları arası çakışmalar engellenmiştir.

---

## 🎮 Oyun ve Multimedya
Ankora OS, bir iş istasyonu olduğu kadar bir eğlence merkezidir.
* **GameMode:** Oyuna girdiğiniz anda CPU Governor'ı performans moduna çeker, I/O önceliğini oyuna verir ve arka plan süreçlerini dondurur.
* **Wine ve Flatpak Altyapısı:** Windows uygulamalarını (`.exe`) doğrudan çalıştırmanız için Wine mimarisi sisteme entegredir. Lutris ve Steam gibi platformlar için modern Flatpak mağaza altyapısı tercih edilmiştir.

---

## 💻 Sistem Gereksinimleri

| Donanım | Minimum (Günlük Kullanım) | Önerilen (Oyun & Geliştirme) |
| :--- | :--- | :--- |
| **İşlemci** | 64-bit Çift Çekirdekli CPU | Intel Core i3 / AMD Ryzen 3 |
| **RAM** | 2 GB (ZRAM Destekli) | 4 GB veya Üzeri |
| **Depolama** | 15 GB Boş Alan | 30 GB SSD |

---

## 🚀 Kurulum Rehberi

1. **İndirin:** Sağ üst köşedeki **[Releases](#)** bölümünden `Ankora-OS-Zumrut.iso` dosyasının en güncel halini indirin.
2. **USB'ye Yazdırın:** İndirdiğiniz ISO dosyasını boş bir USB belleğe yazdırmak için [Rufus](https://rufus.ie/tr/) (Windows) veya [BalenaEtcher](https://balena.io/etcher/) kullanın.
3. **Boot Edin:** Bilgisayarınızı yeniden başlatın, BIOS/Boot menüsüne girerek USB belleğinizi ilk sıraya alın.
4. **Kurulumu Tamamlayın:** Karşınıza çıkan Calamares grafiksel kurulum sihirbazını takip ederek bölge, klavye ve kullanıcı ayarlarınızı saniyeler içinde tamamlayın.

---

## 🌐 Topluluk ve İletişim
Bu proje tamamen açık kaynaklıdır ve topluluğun geri bildirimleriyle büyümektedir. Karşılaştığınız sorunlar, yeni özellik talepleri veya sadece selam vermek için bize katılın:

* 💬 **Topluluk Forumu:** [Ankalab Flarum Cloud](https://ankalab.flarum.cloud)
* 🌍 **Resmi Web Sitesi:** [ankora.xo.je](http://ankora.xo.je) 
* 🐞 **Hata Bildirimi:** GitHub üzerindeki [Issues](../../issues) sekmesini veya forumdan konu açarak kullanabilirsiniz.

