# Site Kapalıdır - GitHub Pages Yayınlama Kılavuzu

Bu proje, sitenizin geçici olarak kapalı olduğunu belirten, modern, şık ve mobil uyumlu bir statik web sayfasıdır.

## Proje İçeriği
- `index.html` - Sayfa yapısı ve SEO uyumlu HTML5 kodları
- `style.css` - Gelişmiş karanlık mod tasarımı, cam efekti (glassmorphism) ve yumuşak animasyonlar

## GitHub'da Nasıl Yayınlanır?

Bu siteyi GitHub Pages kullanarak tamamen ücretsiz olarak yayına almak için aşağıdaki adımları takip edebilirsiniz:

### 1. Yöntem: GitHub Masaüstü veya Git ile Gönderme (Önerilen)

Bu dizin sizin için bir Git deposu (`git repository`) olarak ilklendirilmiştir. Sadece aşağıdaki komutları kullanarak GitHub'a gönderebilirsiniz:

1. Tarayıcınızda [GitHub](https://github.com) hesabınıza giriş yapın.
2. Sağ üstteki **+** simgesine tıklayıp **New repository** (Yeni Depo) seçeneğini seçin.
3. Depo adını girin (örneğin: `kapali-site`) ve **Public** (Açık) olarak işaretleyin. Başka hiçbir dosya (README, .gitignore vb.) eklemeden **Create repository** butonuna basın.
4. Karşınıza çıkan sayfadaki komutları terminalinizde bu klasörün içindeyken sırasıyla çalıştırın:

```bash
git remote add origin <sizin-depo-linkiniz>
git branch -M main
git push -u origin main
```

### 2. Yöntem: Tarayıcı Üzerinden Sürükle-Bırak

1. GitHub'da yeni bir public depo oluşturun.
2. Deponuzu oluşturduktan sonra çıkan ekrandaki **"uploading an existing file"** (mevcut bir dosyayı yükle) linkine tıklayın.
3. Bu klasördeki `index.html` ve `style.css` dosyalarını sürükleyip tarayıcıya bırakın.
4. Sayfanın altındaki **Commit changes** (Değişiklikleri kaydet) butonuna tıklayın.

---

### GitHub Pages ile Yayına Alma

Dosyalarınızı GitHub'a yükledikten sonra siteyi aktif etmek için:

1. GitHub deponuzun üst menüsündeki **Settings** (Ayarlar) sekmesine gidin.
2. Sol menüden **Pages** seçeneğine tıklayın.
3. **Build and deployment** başlığı altındaki **Source** kısmında **"Deploy from a branch"** seçili olduğundan emin olun.
4. **Branch** kısmını `None` yerine `main` (veya `master`) yapıp yanındaki klasörün `/ (root)` olmasını sağlayın, ardından **Save** (Kaydet) butonuna tıklayın.
5. Birkaç dakika içinde sayfanın üst kısmında sitenizin canlı yayın adresi görünecektir (örn: `https://kullanici-adiniz.github.io/kapali-site/`).
