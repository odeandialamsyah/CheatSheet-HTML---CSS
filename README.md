
# 📄 HTML & CSS Cheat Sheet Lengkap

## 🔰 Struktur Dasar HTML
```html
<!DOCTYPE html>
<html>
<head>
  <title>Judul Halaman</title>
</head>
<body>
  <!-- Konten di sini -->
</body>
</html>
```

## 🧱 Elemen Teks
- `<h1>` sampai `<h6>` — Heading/judul  
- `<p>` — Paragraf  
- `<br>` — Ganti baris  
- `<hr>` — Garis horizontal  
- `<strong>` / `<b>` — Teks tebal  
- `<em>` / `<i>` — Teks miring  
- `<u>` — Garis bawah  
- `<blockquote>` — Kutipan panjang  

## 🔗 Link & Gambar
```html
<a href="https://example.com">Kunjungi</a>
<img src="gambar.jpg" alt="Deskripsi">
```

## 📃 Daftar
```html
<ul>
  <li>Item 1</li>
</ul>

<ol>
  <li>Item 1</li>
</ol>
```

## 🔲 Tabel
```html
<table>
  <tr>
    <th>Nama</th>
    <th>Usia</th>
  </tr>
  <tr>
    <td>Ali</td>
    <td>20</td>
  </tr>
</table>
```

## 🔘 Formulir
```html
<form action="/submit" method="post">
  <input type="text" name="nama">
  <input type="email" name="email">
  <textarea></textarea>
  <select>
    <option>Opsi 1</option>
  </select>
  <button type="submit">Kirim</button>
</form>
```

---

# 🎨 CSS Cheat Sheet

## 🔧 Selektor Dasar
- `*` — Semua elemen  
- `p` — Semua paragraf  
- `.class` — Elemen dengan class  
- `#id` — Elemen dengan ID  
- `div > p` — Paragraf langsung di dalam div  

## 🖌 Properti Umum
```css
color: red;
background-color: #f0f0f0;
font-size: 16px;
font-family: Arial;
text-align: center;
margin: 10px;
padding: 10px;
border: 1px solid black;
width: 300px;
height: auto;
```

## 🧱 Box Model
```
+-------------+
|  margin     |
| +---------+ |
| | padding | |
| | +-----+ | |
| | |content| |
| | +-----+ | |
| +---------+ |
+-------------+
```

## 🎯 Display & Positioning
```css
display: block;
display: inline;
display: flex;
display: none;

position: static;
position: relative;
position: absolute;
position: fixed;

z-index: 1;

top: 0;
left: 0;
right: 0;
bottom: 0;
```

## 🧭 Flexbox Singkat
```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

## 📱 Responsive CSS
```css
@media (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
```
