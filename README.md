# ImageZoom.js Documentation

ImageZoom.js adalah library sederhana yang memungkinkan Anda menambahkan fitur zoom interaktif pada gambar di situs web Anda. Dengan dukungan untuk banyak gambar melalui satu query selector, library ini sangat fleksibel dan mudah digunakan.

---

## Instalasi

1. **Tambahkan Library ke Proyek Anda**
   Masukkan file `ImageZoom.js` ke dalam proyek Anda dengan menambahkan script berikut ke dalam file HTML:

```html
<script type="text/javascript" src="/ImageZoom.js"></script>
```

2. **Siapkan Elemen HTML Gambar**
   Pastikan gambar yang ingin Anda gunakan memiliki class atau selector yang sesuai.

Contoh:

```html
<img src="image1.jpg" alt="Gambar 1" class="zoomable-image">
<img src="image2.jpg" alt="Gambar 2" class="zoomable-image">
```

---

## Contoh Penggunaan

### Langkah 1: Buat Elemen Gambar yang Bisa Diperbesar
Gunakan class atau atribut unik untuk gambar-gambar yang ingin diperbesar.

Contoh HTML:

```html
<div>
    <img src="image1.jpg" alt="Produk 1" class="zoomable-image">
    <img src="image2.jpg" alt="Produk 2" class="zoomable-image">
    <img src="image3.jpg" alt="Produk 3" class="zoomable-image">
</div>
```

### Langkah 2: Inisialisasi ImageZoom.js
Panggil library `ImageZoom` dengan query selector yang sesuai.

Contoh JavaScript:

```html
<script>
    new ImageZoom(".zoomable-image");
</script>
```

Dengan menggunakan selector `.zoomable-image`, semua elemen gambar yang memiliki class tersebut akan mendapatkan fitur zoom interaktif.

### Hasil Akhir
Ketika Anda mengklik ke salah satu gambar, fitur zoom akan diaktifkan, memungkinkan pengguna untuk melihat gambar dengan lebih detail.

---

## Fitur Utama

1. **Dukungan untuk Banyak Gambar**
   - Satu query selector dapat digunakan untuk beberapa gambar.
   - Contoh:

   ```html
   <img src="image1.jpg" class="zoomable-image">
   <img src="image2.jpg" class="zoomable-image">
   ```
   
   ```javascript
   new ImageZoom(".zoomable-image");
   ```

2. **Zoom Otomatis dan Responsif**
   - Library ini dirancang untuk menyesuaikan ukuran gambar sesuai perangkat pengguna.

3. **Kemudahan Kustomisasi**
   - Anda dapat menyesuaikan parameter zoom seperti tingkat pembesaran (magnification level) dengan mudah.

---

## Tips

- **Gunakan Gambar Resolusi Tinggi**: Untuk hasil zoom yang optimal, pastikan Anda menggunakan gambar dengan resolusi tinggi.
