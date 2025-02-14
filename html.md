İşte en çok kullanılan **30 HTML etiketi**, sıralı bir şekilde açıklamalarıyla birlikte:

---

### 1. **`<!DOCTYPE html>`**  
**Bilgi:** HTML belgesinin türünü ve sürümünü belirtir.  
**Amaç:** Tarayıcıya belgenin HTML5 standardında olduğunu bildirmek.  
**Kullanım Şekli:**  
```html
<!DOCTYPE html>
<html>
  ...
</html>
```

---

### 2. **`<html>`**  
**Bilgi:** Tüm HTML belgesini kapsayan kök etiket.  
**Amaç:** Belgenin başlangıç ve bitişini belirlemek.  
**Kullanım Şekli:**  
```html
<html lang="en">
  ...
</html>
```

---

### 3. **`<head>`**  
**Bilgi:** Belgeyle ilgili meta verileri (başlık, stil, script) içerir.  
**Amaç:** Tarayıcıya ve arama motorlarına bilgi sağlamak.  
**Kullanım Şekli:**  
```html
<head>
  <title>Sayfa Başlığı</title>
</head>
```

---

### 4. **`<title>`**  
**Bilgi:** Sayfanın tarayıcı sekmesinde görünen başlığı.  
**Amaç:** SEO ve kullanıcı deneyimi için kritik.  
**Kullanım Şekli:**  
```html
<title>Örnek Web Sitesi</title>
```

---

### 5. **`<body>`**  
**Bilgi:** Sayfanın görünen tüm içeriğini kapsar.  
**Amaç:** Kullanıcıya gösterilen metin, resim, video vb. içerikleri barındırmak.  
**Kullanım Şekli:**  
```html
<body>
  <h1>Merhaba Dünya!</h1>
</body>
```

---

### 6. **`<h1>` - `<h6>`**  
**Bilgi:** Başlık etiketleri (h1 en büyük, h6 en küçük).  
**Amaç:** İçerik hiyerarşisini oluşturmak ve SEO'yu desteklemek.  
**Kullanım Şekli:**  
```html
<h1>Ana Başlık</h1>
<h2>Alt Başlık</h2>
```

---

### 7. **`<p>`**  
**Bilgi:** Paragraf etiketi.  
**Amaç:** Metin bloklarını düzenlemek.  
**Kullanım Şekli:**  
```html
<p>Bu bir paragraf örneğidir.</p>
```

---

### 8. **`<a>`**  
**Bilgi:** Bağlantı (hyperlink) oluşturur.  
**Amaç:** Sayfalar veya kaynaklar arası geçiş sağlamak.  
**Kullanım Şekli:**  
```html
<a href="https://ornek.com">Tıkla</a>
```

---

### 9. **`<img>`**  
**Bilgi:** Resim eklemek için kullanılır.  
**Amaç:** Görsel içerik göstermek.  
**Kullanım Şekli:**  
```html
<img src="resim.jpg" alt="Açıklama">
```

---

### 10. **`<div>`**  
**Bilgi:** Blok düzeyinde bir konteynır.  
**Amaç:** HTML öğelerini gruplamak ve stil vermek.  
**Kullanım Şekli:**  
```html
<div class="container">...</div>
```

---

### 11. **`<span>`**  
**Bilgi:** Satır içi bir konteynır.  
**Amaç:** Metin içinde belirli bölümleri vurgulamak.  
**Kullanım Şekli:**  
```html
<span style="color:red">Kırmızı Metin</span>
```

---

### 12. **`<ul>` / `<ol>` / `<li>`**  
**Bilgi:** Sırasız (ul), sıralı (ol) liste ve liste öğesi (li).  
**Amaç:** Liste yapıları oluşturmak.  
**Kullanım Şekli:**  
```html
<ul>
  <li>Madde 1</li>
  <li>Madde 2</li>
</ul>
```

---

### 13. **`<table>` / `<tr>` / `<td>`**  
**Bilgi:** Tablo (table), satır (tr), sütun (td).  
**Amaç:** Verileri tablo formatında göstermek.  
**Kullanım Şekli:**  
```html
<table>
  <tr>
    <td>Hücre 1</td>
    <td>Hücre 2</td>
  </tr>
</table>
```

---

### 14. **`<form>`**  
**Bilgi:** Kullanıcı girişi almak için form oluşturur.  
**Amaç:** Veri toplamak (örneğin, iletişim formu).  
**Kullanım Şekli:**  
```html
<form action="/submit" method="POST">
  <input type="text" name="ad">
</form>
```

---

### 15. **`<input>`**  
**Bilgi:** Kullanıcıdan veri almak için giriş alanı.  
**Amaç:** Metin, şifre, tarih vb. veri türlerini toplamak.  
**Kullanım Şekli:**  
```html
<input type="email" placeholder="E-posta">
```

---

### 16. **`<button>`**  
**Bilgi:** Tıklanabilir düğme.  
**Amaç:** Kullanıcı etkileşimi sağlamak.  
**Kullanım Şekli:**  
```html
<button onclick="alert('Merhaba')">Tıkla</button>
```

---

### 17. **`<meta>`**  
**Bilgi:** Sayfa hakkında meta veri sağlar (örneğin, karakter seti).  
**Amaç:** SEO ve tarayıcı uyumluluğu için önemli.  
**Kullanım Şekli:**  
```html
<meta charset="UTF-8">
```

---

### 18. **`<link>`**  
**Bilgi:** Harici kaynakları (CSS) bağlamak için kullanılır.  
**Amaç:** Stil dosyalarını entegre etmek.  
**Kullanım Şekli:**  
```html
<link rel="stylesheet" href="style.css">
```

---

### 19. **`<style>`**  
**Bilgi:** Dahili CSS yazmak için kullanılır.  
**Amaç:** Sayfaya özel stiller eklemek.  
**Kullanım Şekli:**  
```html
<style>
  body { background: #fff; }
</style>
```

---

### 20. **`<script>`**  
**Bilgi:** JavaScript kodu ekler veya harici JS dosyası bağlar.  
**Amaç:** Sayfaya dinamik özellikler eklemek.  
**Kullanım Şekli:**  
```html
<script>
  console.log("Merhaba!");
</script>
```

---

### 21. **`<strong>`**  
**Bilgi:** Metni kalın yapar ve semantik olarak önemini vurgular.  
**Amaç:** Önemli kelimeleri belirtmek.  
**Kullanım Şekli:**  
```html
<strong>Dikkat!</strong>
```

---

### 22. **`<em>`**  
**Bilgi:** Metni italik yapar ve vurgular.  
**Amaç:** Kelimeleri tonlama ile işaretlemek.  
**Kullanım Şekli:**  
```html
<em>Bu vurgulu bir metin.</em>
```

---

### 23. **`<br>`**  
**Bilgi:** Satır sonu oluşturur.  
**Amaç:** Metin içinde boşluk bırakmak.  
**Kullanım Şekli:**  
```html
Merhaba<br>Dünya!
```

---

### 24. **`<hr>`**  
**Bilgi:** Yatay çizgi ekler.  
**Amaç:** İçerik bölümlerini ayırmak.  
**Kullanım Şekli:**  
```html
<hr>
```

---

### 25. **`<header>`**  
**Bilgi:** Sayfanın veya bölümün üst kısmını temsil eder.  
**Amaç:** Semantik yapıyı geliştirmek.  
**Kullanım Şekli:**  
```html
<header>Logo ve Menü</header>
```

---

### 26. **`<footer>`**  
**Bilgi:** Sayfanın veya bölümün alt kısmını temsil eder.  
**Amaç:** Telif hakkı, iletişim bilgileri eklemek.  
**Kullanım Şekli:**  
```html
<footer>© 2023 Örnek Şirket</footer>
```

---

### 27. **`<nav>`**  
**Bilgi:** Navigasyon bağlantılarını gruplar.  
**Amaç:** Menüleri semantik olarak işaretlemek.  
**Kullanım Şekli:**  
```html
<nav>
  <a href="/">Ana Sayfa</a>
</nav>
```

---

### 28. **`<section>`**  
**Bilgi:** İçerik bölümlerini belirtir.  
**Amaç:** Sayfayı mantıksal parçalara ayırmak.  
**Kullanım Şekli:**  
```html
<section>
  <h2>Hakkımızda</h2>
</section>
```

---

### 29. **`<iframe>`**  
**Bilgi:** Harici bir kaynağı (video, harita) gömme.  
**Amaç:** Üçüncü taraf içerikleri entegre etmek.  
**Kullanım Şekli:**  
```html
<iframe src="https://www.youtube.com/embed/..."></iframe>
```

---

### 30. **`<textarea>`**  
**Bilgi:** Çok satırlı metin giriş alanı.  
**Amaç:** Kullanıcıdan uzun metin almak.  
**Kullanım Şekli:**  
```html
<textarea rows="4" cols="50"></textarea>
```

---

Bu liste, HTML5 etiketlerini ve temel kullanımlarını kapsar. Her etiketin daha detaylı özellikleri (örneğin, `input`'un `type` attribute'ü) mevcuttur.
