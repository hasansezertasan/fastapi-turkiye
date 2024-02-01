---
hide:
  - navigation
---
# Çeviri Notları

## Başlamadan Önce

Herhangi bir çalışmadan önce, mümkünse [Development - Contributing - FastAPI](https://fastapi.tiangolo.com/contributing/) sayfasının tamamını, değilse `Translations` başlığını kesinlikle okumanızı tavsiye ederim.

### Katkı  Düzeni - Contribution Convention

Bir doküman üzerinde ekleme, düzenleme veya güncelleme yapıldığında, sadece o doküman `commit`lenmeli ve `pull request` içerisinde sadece o doküman yer almalı.

`Pull Request` açarken isimlendirmeye dikkat etmeliyiz.

!!! example "Eklemeler için"

    ```markdown
    🌐 Add {{language}} translation for `{{file_path}}`
    ```


    🌐 Add Turkish translation for `docs/tr/docs/learn/index.md`

!!! example "Güncellemeler için"

    ```markdown
    🌐 Update {{language}} translation for `{{file_path}}`
    ```

    🌐 Update Turkish translation for `docs/tr/docs/learn/index.md`

## Kurallar

- Çeviride tutarlılık:
  - Mesela doküman genelinde `request` çevirisi olarak `istek` kullanılmışsa, `talep` kullanılmamalı. Burada bahsi geçen kelimeler teknik kelimelerdir.
    - `HTTP Request`: `HTTP İsteği`
    - `HTTP Response`: `HTTP Yanıtı`
    - `Body Parameter`: `Gövde Parametresi`
    - `Query Parameter`: `Sorgu Parametresi`
    - `Cookie`: `Çerez`
    - `Header`: `Header`
    - `Function`: `Fonksiyon`
    - `Method`: `Metod`
    - `Type Hint`: `Tip Belirteci`
    - `Type Annotation`: `Tip Belirteci`
    - `Editor`: `Editör`
    - `Data`: `Veri`
    - `Database`: `Veritabanı`
    - `Validation`: `Doğrulama`
    - `Dependency Injection`: `Bağımlılık Enjeksiyonu`
- Samimi bir dil:
  - Mesela `edit it` çevirisini `düzenle` gibi çevirmek yerine `düzenleyelim` diyebiliriz.
- Yazım hatası ve noktalama işaretlerine dikkat etmeliyiz.

## Öneriler

Kullanılan kavramın Türkçe çevirisiyle birlikte İngilizce halini de kullanıcı için erişilebilir hale getirmek çok kolay, bunu `abbr` etiketini kullanarak yapabilirsiniz. [Detaylar için](./tutorials/mkdocs.md#abbreviations) `MkDocs` dokümanına bakabilirsiniz.

## Sıkça Yapılan Hatalar

- Türkçe karakterlerin kullanımı.
- Başlıklarda sadece ilk kelimenin büyük harfle başlaması: örnek bir başlık olarak `## Sıkça yapılan hatalar` hatalı bir kullanımdır, bunun yerine `## Sıkça Yapılan Hatalar` kullanılmalıdır. Aynı şekilde, `ile`, `ve`, `veya`, `de`, `da`, `değil`, `dahi`, `ki`, `ise`, `ya da`, `yani` gibi bağlaçlar da küçük harfle başlamalıdır.
- Art arda boşluk: `Bu benim  cümlem` yazımı hatalıdır çünkü aradaki boşluklar gereksizdir. `Bu benim cümlem` şeklinde yazılmalıdır. Bu hata İngilizce dokümanda da sıkça yapılmıştır, çeviri yaparken bu hataya dikkat edelim.
- Art arda boş satır: Markdown yapısında art arda boş satır, alt alta iki boş satır stili bozabiliyor.
- Hizalamalı çeviri: İngilizce dokümanda bir yapıyı anlatmak için 10 satır kullanılmış olabilir ve bu yapı Türkçeye çevirilirken 2 satırda, özet bir paragrafla anlatılabilir. Doğru ancak bunu yapmak bu tarz çevirilerde yanlış olacaktır. Çevirilerimizi gerçekleştirirken satır satır çeviri yaparsak eğer inceleme yapan kişi veya ileride çeviriyi güncelleyecek kişi satır numaralarını referans alarak çalışabilir.

## Kaynaklar

- Bilişim kavramları:
  - [Bilkent Bilişim Terimleri Sözlüğü](http://cayfer.bilkent.edu.tr/~cayfer/bilisim-sozlugu/tbd-ing-trk-sozluk.htm)
  - [Bilişim Sözlüğü](https://eski.tbd.org.tr/index.php?sayfa=sozluk)
- Türkçe - İngilizce sözlük olarak [Tureng - Turkish English Dictionary](https://tureng.com/en/turkish-english) sayfasını kullanıyoruz.
- İmla kuralları ve Türkçe anlamları için [Türk Dil Kurumu Sözlükleri](https://sozluk.gov.tr/) sayfasını kullanıyoruz.
