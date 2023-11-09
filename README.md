![Disini menampilkan tampilan microfrontend sederhana Toko Buku] (<screenshot (4).png>)(<screenshot (5).png>)
Ketika menekan button lihat perubahan akan muncul perubahan gambar bukunya (<screenshot (6).png>)

```
function img() {
  document.getElementById("gantiGambar").src = "images/cantik.jpg";
  document.getElementById("gantiLatar").src = "images/download.jpg";
  document.getElementById("gantiFoto").src = "images/pulang.jpg";
  document.getElementById("gantiNovel").src = "images/rinai.jpg";
}
```
