<!-- markdownlint-disable MD046 -->
# MkDocs

## Admonitions

[Admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/) `!!! {type}` şeklinde olan yapılarda `{type}` kısmını Türkçe'ye çevirirsek MkDocs düzgün derleme almıyor. Bu yapıları çevirmek için `admonition_map` üzerinde olan karşılıkları birebir kullanılabilir.

```python
admonition_map = {
  '!!! note': '!!! note "Not"',
  '!!! abstract': '!!! abstract "Soyut"',
  '!!! info': '!!! info "Bilgi"',
  '!!! tip': '!!! tip "İpucu"',
  '!!! success': '!!! success "Başarı"',
  '!!! question': '!!! question "Soru"',
  '!!! warning': '!!! warning "Uyarı"',
  '!!! failure': '!!! failure "Başarısızlık"',
  '!!! danger': '!!! danger "Tehlike"',
  '!!! bug': '!!! bug "Hata"',
  '!!! example': '!!! example "Örnek"',
  '!!! quote': '!!! quote "Alıntı"',
  '!!! important': '!!! important "Önemli"',
  '!!! usage': '!!! usage "Kullanım"',
}
```

```markdown
!!! example "Örnek"
    Bu bir örnektir.
```

## Abbreviations

Abbreviations ile kelimeleri vurgulayabiliriz. Örneğin `Python` kelimesini `Python, bir programlama dilidir.` şeklinde çevirebiliriz. Bu durumda `Python` kelimesini vurgulamak için `abbr` etiketini kullanabiliriz.

!!! example "Örnek"

    ```markdown
    [Python], bir programlama dilidir. [^1]

    *[Python]: Python, a programming language.
    ```

    [Python], bir programlama dilidir. [^1]

    *[Python]: Python, a programming language.

veya

!!! example "Örnek"

    ```markdown
    <abbr title="a programming language">Python</abbr>, bir programlama dilidir.
    ```

    <abbr title="a programming language">Python</abbr>, bir programlama dilidir.

## Bağlantılar

- [MkDocs](https://www.mkdocs.org/)
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
