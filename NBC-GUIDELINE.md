# [NBC Guideline](https://github.com/ngalambackend/nbc-guideline/blob/master/NBC-GUIDELINE.md)
# :package: Struktur Penulisan
Dalam menuliskan `source code, terminal atau sintak khusus lainnya` gunakan `block code` untuk menyorot area tertentu.
## 1. Penulisan Source Code dan Terminal
Dalam menggunakan `block code` sertakan bahasa pemrogramman dari source code yang di tulis agar preview sesuai.

contoh dengan pemrograman PHP
````markdown
```php
$one = 55;
$two = 100;

$total = $one + $two;

echo 'Total '.$total;
```
````
contoh dengan pemrograman Javascript
````markdown
```javascript
function name(string) {
    let nbc = 1
    const ngalam = 'city'

    ...
}

console.log(name)
```
````
contoh dengan sintak terminal
````markdown
```bash
$ npm install
$ npm install name-package
```
````
## 2. Penulisan Penomoran dan Judul
```
# 1. Judul

## 1.1. Sub Judul

        * First

        * Second

## 1.2. Sub Judul

        - First

        - Second

# 2. Judul

## 2.1. Sub Judul

## 2.2. Sub Judul
```
Selain tulisan gunakan emoji untuk variasi tulisan :+1: [ referensi : [emoji-cheat-sheet](https://www.webfx.com/tools/emoji-cheat-sheet/) ]