# Portfolyo Web Sitesi

Modern ve responsive bir portfolyo web sitesi. HTML, CSS ve JavaScript kullanılarak geliştirilmiştir.

## Özellikler

- ✨ Modern ve temiz tasarım
- 📱 Tam responsive (mobil uyumlu)
- 🎨 Smooth animasyonlar ve geçişler
- 🚀 Hızlı yükleme
- 📧 Çalışan iletişim formu
- 🎯 Proje filtreleme sistemi
- 🌟 Interaktif kullanıcı arayüzü

## Bölümler

1. **Ana Sayfa (Hero)** - Kişisel tanıtım ve sosyal medya linkleri
2. **Hakkımda** - Kişisel bilgiler ve istatistikler
3. **Yetenekler** - Teknik beceriler ve araçlar
4. **Projeler** - Portfolyo projeleri ve filtreleme
5. **İletişim** - İletişim formu ve bilgileri

## Teknolojiler

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

## Kurulum

1. Bu dosyaları bir web sunucusuna yükleyin
2. `index.html` dosyasını tarayıcınızda açın
3. Kişisel bilgilerinizi düzenleyin

## Özelleştirme

### Kişisel Bilgileri Değiştirme

1. `index.html` dosyasında aşağıdaki alanları düzenleyin:
   - Ad ve soyad
   - Meslek tanımı
   - Hakkımda metni
   - İletişim bilgileri
   - Sosyal medya linkleri

### Renkler ve Tema

`style.css` dosyasının `:root` bölümünde renk değişkenlerini düzenleyebilirsiniz:

```css
:root {
    --primary-color: #4f46e5;
    --secondary-color: #06b6d4;
    --accent-color: #f59e0b;
    /* ... diğer renkler */
}
```

### Projeler Ekleme

`index.html` dosyasında projeler bölümüne yeni proje kartları ekleyebilirsiniz:

```html
<div class="project-card" data-category="web">
    <div class="project-image">
        <img src="proje-resmi.jpg" alt="Proje Adı">
        <div class="project-overlay">
            <div class="project-links">
                <a href="#" class="project-link"><i class="fas fa-eye"></i></a>
                <a href="#" class="project-link"><i class="fab fa-github"></i></a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Proje Adı</h3>
        <p>Proje açıklaması...</p>
        <div class="project-tech">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
        </div>
    </div>
</div>
```

### Yetenekler Ekleme

Yeni yetenekler eklemek için `skill-items` div'ine yeni öğeler ekleyin:

```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React</span>
</div>
```

## Resim Optimizasyonu

- Profil fotoğrafı: 350x350px
- Proje resimleri: 400x300px
- Hakkımda bölümü resmi: 400x500px

Resimleri optimize etmek için:
1. WebP formatını kullanın
2. Responsive resimler için farklı boyutlar hazırlayın
3. Lazy loading kullanın

## Browser Desteği

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## SEO Optimizasyonu

### Meta Etiketleri Ekleme

`<head>` bölümüne şu etiketleri ekleyin:

```html
<meta name="description" content="Profesyonel web developer portfolyosu">
<meta name="keywords" content="web developer, frontend, backend, portfolio">
<meta name="author" content="Adınız Soyadınız">

<!-- Open Graph -->
<meta property="og:title" content="Adınız Soyadınız - Portfolyo">
<meta property="og:description" content="Profesyonel web developer portfolyosu">
<meta property="og:image" content="og-image.jpg">
<meta property="og:url" content="https://yourwebsite.com">

<!-- Twitter Cards -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Adınız Soyadınız - Portfolyo">
<meta name="twitter:description" content="Profesyonel web developer portfolyosu">
<meta name="twitter:image" content="twitter-image.jpg">
```

## Performance Tips

1. **Resim Optimizasyonu**: WebP formatı kullanın
2. **Minification**: CSS ve JS dosyalarını minify edin
3. **CDN**: Font Awesome ve Google Fonts için CDN kullanın
4. **Lazy Loading**: Resimler için lazy loading aktif
5. **Compression**: Gzip sıkıştırma kullanın

## İletişim Formu Entegrasyonu

Formun çalışması için backend servis entegrasyonu gereklidir. Öneriler:

1. **Formspree**: Basit form servisi
2. **Netlify Forms**: Netlify üzerinde barındırıyorsanız
3. **EmailJS**: JavaScript ile e-posta gönderimi
4. **Custom Backend**: Node.js, PHP vb. ile kendi backend'iniz

### EmailJS Entegrasyonu Örneği

```javascript
// EmailJS ile form gönderimi
emailjs.send('service_id', 'template_id', {
    from_name: name,
    from_email: email,
    subject: subject,
    message: message
}).then(() => {
    showNotification('Mesajınız gönderildi!', 'success');
}).catch(() => {
    showNotification('Bir hata oluştu!', 'error');
});
```

## Güvenlik

1. Form validasyonu hem frontend hem backend'de yapılmalı
2. HTTPS kullanın
3. CSRF koruması ekleyin
4. Rate limiting uygulayın

## Deployed Link

Web sitenizi yayınlamak için:

1. **Netlify**: Drag & drop ile kolay deploy
2. **Vercel**: Git entegrasyonu ile otomatik deploy
3. **GitHub Pages**: Ücretsiz statik site hosting
4. **Firebase Hosting**: Google'ın hosting servisi

## Lisans

MIT License - Kişisel ve ticari projelerinizde özgürce kullanabilirsiniz.

## Yardım ve Destek

Herhangi bir sorunuz varsa:
- Issues bölümünde soru sorabilirsiniz
- Dokumentasyonu detaylıca okuyun
- Community'den yardım alabilirsiniz

---

💡 **İpucu**: Bu portfolyoyu kendi ihtiyaçlarınıza göre özelleştirmekten çekinmeyin! Yaratıcı olun ve kişiliğinizi yansıtın.
