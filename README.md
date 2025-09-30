#  Pratikum 2 - CSS Dasar
### NAMA : Grayven c.w
### NIM : 312410435
### KELAS : TI.24.A3

## LANGKAH - LANGKAH PENGERJAAN

### 1. MEMBUAT FILE DASAR HTML.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Lab 1 – HTML Dasar</title>
  </head>
  <body>
    <!-- Konten HTML akan ditambahkan di sini -->
  </body>
</html>
```

📸 **SCREENSHOOT VSCODE & BROWSER**

<img width="1138" height="909" alt="Program1" src="https://github.com/user-attachments/assets/739c5fe6-825d-42c1-aa87-ffe62d0d69b2" />
>

<br>

<img width="1333" height="455" alt="Screenshot 2025-10-01 002957" src="https://github.com/user-attachments/assets/0fcdf495-e487-4541-9c0d-9d10256bc62e" />


 **MENDEKLARASIKAN CSS INTERNAL**
 
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.

<img <img width="668" height="437" alt="program2" src="https://github.com/user-attachments/assets/a17cc4fa-0297-4622-b876-14b0d1492f04" />
>

<br>

<img width="1275" height="713" alt="Screenshot 2025-10-01 003151" src="https://github.com/user-attachments/assets/2f24cb96-c4c5-4251-b3a1-7d35d254ebd8" />
>

  **MENAMBAHKAN INLINE CSS**
  
Kemudian tambahkan deklarasi inline CSS

<img width="1024" height="79" alt="program5" src="https://github.com/user-attachments/assets/4bcf35f4-3f2e-4849-8d9e-7a83afdaceb8" />
>

Simpan kembali dan refresh kembali browser untuk melihat perubahannya.

<img width="1919" height="1079" alt="web5" src="https://github.com/user-attachments/assets/6798b272-fe58-45ea-9ec7-b8a56f66d647" />
>

 **MEMBUAT CSS EKSTERNAL**

 Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.

 <img width="361" height="273" alt="Program3" src="https://github.com/user-attachments/assets/e89edeec-6c84-4dbc-8937-1f0382c59f89" />
>

 Kemudian tambahkan tag link untuk merujuk file css yang sudah dibuat pada bagian head

 <img width="596" height="80" alt="program6" src="https://github.com/user-attachments/assets/2b64577a-6fec-4353-95fa-6133c11173e1" />
>

Selanjutnya refresh kembali browser untuk melihat perubahannya.

 <img width="1037" height="552" alt="Screenshot 2025-10-01 004134" src="https://github.com/user-attachments/assets/287d2047-1711-4d4a-b33e-d8aaddef1ed6" />
>

**MENAMBAHKAN CSS SELECTOR**

Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kode berikut.

<img width="377" height="443" alt="program4" src="https://github.com/user-attachments/assets/c6755932-fb88-4329-b30b-98c0d2c6101f" />
>

Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.

<img width="1040" height="556" alt="Screenshot 2025-10-01 004505" src="https://github.com/user-attachments/assets/2452dfc3-1016-4ead-b16e-5edb3cea98a7" />
>

**JAWABAN UNTUK PERTANYANNYA**

1. Untuk soal pertama, kita bisa melakukan eksperimen dengan menambahkan properti CSS baik secara internal, eksternal, maupun inline. Misalnya dengan menambahkan warna teks, ukuran font, latar belakang, atau perataan teks. Dengan begitu, tampilan elemen HTML akan berubah sesuai properti yang kita tambahkan.

2. Pada soal kedua, perbedaan antara deklarasi h1 {…} dengan #intro h1 {…} ada pada cakupan selektornya. Selektor h1 berlaku untuk semua elemen heading h1 yang ada di halaman web, sedangkan #intro h1 hanya berlaku khusus untuk elemen h1 yang berada di dalam elemen dengan id="intro". Dengan kata lain, #intro h1 lebih spesifik dibandingkan h1.

3. Untuk soal ketiga, apabila terdapat deklarasi CSS yang sama dalam internal, eksternal, dan inline, maka yang ditampilkan oleh browser adalah CSS dengan prioritas tertinggi. Urutannya adalah inline CSS yang memiliki prioritas tertinggi, diikuti oleh internal CSS, dan terakhir eksternal CSS. Jadi meskipun pada internal atau eksternal sudah diatur warna teks biru, jika inline CSS menetapkan warna merah, maka teks akan tetap berwarna merah.

4. Sedangkan pada soal keempat, jika sebuah elemen HTML memiliki deklarasi CSS melalui ID dan class sekaligus, maka yang akan ditampilkan adalah deklarasi dengan spesifisitas yang lebih tinggi, yaitu ID. Dengan demikian, jika sebuah paragraf diberi ID dan class lalu keduanya memiliki aturan CSS yang berbeda, maka aturan CSS dari ID yang akan diterapkan oleh browser.
