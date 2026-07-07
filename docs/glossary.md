<!--
---
title: Sözlük
hide: [navigation]
---
-->

# Sözlük

FastAPI dokümantasyonu artık [otomatik olarak Türkçeye çevriliyor](https://fastapi.tiangolo.com/tr/); çeviri koordinasyonu artık topluluğumuzun işi değil. Yine de tutarlı bir terminoloji, Türkçe içerik (blog yazıları, rehberler, sunumlar, projeler) üretirken değerini koruyor. Bu sayfa, topluluk olarak benimsediğimiz Türkçe terimleri ve yazım kurallarını bir arada tutan bir mirastır.

## Terimler

Bir metin genelinde aynı kavram için aynı çeviri kullanılmalı; örneğin `request` için hem `istek` hem `talep` kullanmak tutarsızlık yaratır. Aşağıdaki teknik terimler için önerilen karşılıklar:

| İngilizce | Türkçe |
| --- | --- |
| `HTTP Request` | HTTP İsteği |
| `HTTP Response` | HTTP Yanıtı |
| `Body Parameter` | Gövde Parametresi |
| `Query Parameter` | Sorgu Parametresi |
| `Cookie` | Çerez |
| `Header` | Header |
| `Function` | Fonksiyon |
| `Method` | Metod |
| `Type Hint` | Tip Belirteci |
| `Type Annotation` | Tip Belirteci |
| `Editor` | Editör |
| `Data` | Veri |
| `Database` | Veritabanı |
| `Validation` | Doğrulama |
| `Dependency Injection` | Bağımlılık Enjeksiyonu |

## Yazım Kuralları

* **Samimi bir dil:** `edit it` gibi bir ifadeyi `düzenle` yerine `düzenleyelim` şeklinde çevirmek daha sıcak bir üslup sağlar.
* **Yazım ve noktalama:** Yazım hatalarına ve noktalama işaretlerine dikkat edelim.
* **Başlıklarda büyük/küçük harf:** Başlıklarda her kelimenin baş harfi büyük yazılır; `## Sıkça yapılan hatalar` yerine `## Sıkça Yapılan Hatalar`. Ancak `ile`, `ve`, `veya`, `de`, `da`, `değil`, `dahi`, `ki`, `ise`, `ya da`, `yani` gibi bağlaçlar küçük harfle başlar.
* **Art arda boşluk:** `Bu benim  cümlem` hatalıdır; fazladan boşluk kaldırılmalı: `Bu benim cümlem`.
* **Art arda boş satır:** Markdown'da alt alta iki boş satır, stili bozabilir; tekli boş satır kullanın.
* **İngilizce karşılığı verme:** Bir kavramın Türkçe çevirisiyle birlikte İngilizce halini de erişilebilir kılmak için `abbr` etiketini kullanabilirsiniz. Detaylar için [MkDocs rehberine](tutorials/mkdocs.md#abbreviations) bakabilirsiniz.

## Kaynaklar

* Bilişim kavramları:
  * [Bilkent Bilişim Terimleri Sözlüğü](http://cayfer.bilkent.edu.tr/~cayfer/bilisim-sozlugu/tbd-ing-trk-sozluk.htm)
  * [Bilişim Sözlüğü](https://eski.tbd.org.tr/index.php?sayfa=sozluk)
* Türkçe – İngilizce sözlük olarak [Tureng](https://tureng.com/en/turkish-english) kullanıyoruz.
* İmla kuralları ve Türkçe anlamları için [Türk Dil Kurumu Sözlükleri](https://sozluk.gov.tr/) sayfasını kullanıyoruz.
