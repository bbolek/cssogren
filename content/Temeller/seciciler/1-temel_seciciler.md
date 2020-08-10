---
title: "Temel seçiciler"
metaTitle: "Temel seçiciler"
metaDescription: "CSS'te temel seçiciler"
---

- **Eleman Seçici**

```css
p {
  text-align: left;
  color: blue;
}
```

Yukarıdaki örnekte tüm p (paragraf) elemanlarının yazısı sola dayalı olacak ve rengi de mavi olacaktır.

- **Id Seçici** 

'#' ile belirtilir. İlgili elemanın id sinin başına # koyularak css yazılır.
```css
#text1 {
  text-align: right;
  color: green;
}
```
Yukarıdaki örnekte text1 id li elemanın yazısı sağa dayalı olacak ve yazı rengi de yeşil olacak.

- **Sınıf Seçici**

'.' ile belirtilir. CSS te en çok kullanılan seçicidir. Bir sınıf css dosyasında tanımlanarak (veya html de) ardından istenilen elemanlara koyulabilir.
```css
.center {
  text-align: center;
}
```
Yukarıdaki örnekte tanımlanan sınıf hangi elemana koyulursa onun yazısını ortalayacaktır.

Örnek
```html
<p class="center">
  Bu yazı ortalanmış olmalı
</p>

```
- **Evrensel Seçici**

- **Grup Seçici**