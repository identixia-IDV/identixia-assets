<div align="center">

# Identixia assets

</div>


Shared **brand files** and **README screenshots** for Identixia product repositories.


---

## Brand


Wordmark and mark. Colors are unchanged; only size changes when an app needs another pixel size. App icons (Android, iOS) are copied into each product repository. README headers link here:


```html
<img alt="Identixia" src="https://raw.githubusercontent.com/identixia-IDV/identixia-assets/main/brand/logo.png" width="320"/>
```


| File | Use |
| --- | --- |
| `brand/logo.png` | Wordmark for README headers |
| `brand/mark.png` | Mark for favicons and app icons |


Example pictures (`assets/examples/` in each product repo) are **not** stored here so a normal product clone still includes demo samples.


---

## Use in a product README


```html
<img src="https://raw.githubusercontent.com/identixia-IDV/identixia-assets/main/screenshots/face-recognition/android/home.png" alt="Home" width="240"/>
```


Layout:


```
screenshots/
  document-reader/{desktop,docker}/
  face-recognition/{desktop,android,ios,flutter}/
  face-liveness/{desktop,mobile}/
```


See [MANIFEST.md](MANIFEST.md) for hashes and which repos consume each file. Do not merge files that share a name across families — Android `home.png` is not iOS `home.png`.


---

## License


Screenshots are Identixia product documentation. All rights reserved.
