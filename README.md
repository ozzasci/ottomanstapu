# 📜 Osmanlıca Tapu Terimleri Sözlüğü

Tapu ve Kadastro Genel Müdürlüğü Arşiv Dairesi Başkanlığı kaynaklarından derlenen Osmanlıca tapu, kadastro, hukuk ve ölçü terimlerini içeren interaktif ve modern bir web sözlüğü uygulamasıdır. 

Tek sayfalık (Single Page Application - SPA) yapıda geliştirilen bu proje, araştırmacıların ve meraklıların terimleri kolayca bulmasını, favorilerine eklemesini ve "Bilgi Testi" modülü ile kendini sınamasını sağlar.

## ✨ Özellikler

*   🔍 **Gelişmiş Arama:** Türkçe karakterlere (ı, İ, vb.) tam uyumlu, başlığa ve anlama göre anlık arama yapabilme.
*   📂 **Dinamik Kategoriler:** Veri setinden otomatik çekilen kategorilerle (Arazi, Hukuk, Matematik, Takvim vb.) terimleri filtreleme.
*   ⭐ **Favoriler Sistemi:** Sık kullanılan terimleri tarayıcı hafızasına (LocalStorage) kaydederek oturumlar arası kalıcılık sağlama.
*   🧠 **İnteraktif Bilgi Testi (Quiz):** 
    *   Öğrenilen terimleri pekiştirmek için 10 soruluk rastgele testler.
    *   Doğru/yanlış cevaplarda anında renkli görsel geri bildirim.
    *   Test sonu başarı derecesine göre özel mesajlar.
*   📊 **İstatistik Takibi:** Çözülen test sayısını, en yüksek puanı ve son test geçmişini kaydetme.
*   📱 **Tam Uyumlu (Responsive) Tasarım:** Mobil, tablet ve masaüstü cihazlarda kusursuz kullanım deneyimi (yatay kaydırılabilir menüler, dokunmatik dostu butonlar).

## 🛠️ Kullanılan Teknolojiler

*   **HTML5** (Semantik yapı)
*   **CSS3** (Flexbox, CSS Grid, Custom Variables, Medya Sorguları)
*   **Vanilla JavaScript (ES6+)** (DOM Manipülasyonu, Array Methodları, Set, LocalStorage API)
*   **FontAwesome 6.4.0** (Vektörel İkonlar)

## 🚀 Kurulum ve Çalıştırma

Bu proje herhangi bir paket yöneticisi, sunucu veya derleyici gerektirmez. Sadece tarayıcıda çalışacak şekilde tasarlanmıştır.

1.  Projeyi bilgisayarınıza klonlayın:
    ```bash
    git clone [https://github.com/kullanici-adiniz/osmanlica-tapu-sozlugu.git](https://github.com/kullanici-adiniz/osmanlica-tapu-sozlugu.git)
    ```
2.  Klasöre gidin ve dosyayı açın:
    ```bash
    cd osmanlica-tapu-sozlugu
    ```
3.  `osmanlica-tapu-sozlugu.html` (veya adını `index.html` olarak değiştirdiğiniz) dosyasına çift tıklayarak modern bir web tarayıcısında (Chrome, Safari, Firefox vb.) çalıştırın.

## 📚 Veri Kaynağı

Bu sözlükte yer alan terimler ve anlamları **Tapu ve Kadastro Genel Müdürlüğü Arşiv Dairesi Başkanlığı** kaynaklarından elde edilmiş ve aslına sadık kalınarak dijital ortama aktarılmıştır. Ek olarak projeye dönüştürme ve takvim (Miladi/Rumi) eşleştirmeleri dahil edilmiştir.

## 👨‍💻 Geliştirici

**Oğuz Bulut**

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır. Dilediğiniz gibi kullanabilir, değiştirebilir ve dağıtabilirsiniz.
