# markdown-cheatsheet
```markdown-cheatsheet``` adalah panduan ringkas dan praktis untuk mempelajari sintaks Markdown.

## 📚 Panduan Format Markdown

### 1. **Heading (Judul)**
Digunakan untuk membuat judul atau subjudul.

```markdown
# Judul Utama (H1)
## Subjudul (H2)
### Sub-subjudul (H3)
#### H4
##### H5
###### H6
```

👀 **Contoh Output:**
# Judul Utama  
## Subjudul  
### Sub-subjudul

---

### 2. **Teks Tebal, Miring, dan Coret**
```markdown
**Tebal** atau __Tebal__  
*Miring* atau _Miring_  
***Tebal dan Miring***  
~~Coret~~
```

👀 **Contoh Output:**  
**Tebal**  
*Miring*  
***Tebal dan Miring***  
~~Coret~~

---

### 3. **Daftar (List)**
#### • Daftar Tidak Berurutan:
```markdown
- Item 1
- Item 2
  - Sub-item
* Bisa juga pakai bintang
```

#### • Daftar Berurutan:
```markdown
1. Langkah pertama
2. Langkah kedua
   1. Sub-langkah
```

👀 **Contoh Output:**
- Item 1
- Item 2
  - Sub-item  
1. Langkah pertama  
2. Langkah kedua  
   1. Sub-langkah

---

### 4. **Link dan Gambar**
#### • Link:
```markdown
[Judul Link](https://www.example.com)
```

#### • Gambar:
```markdown
![Alt text](https://www.example.com/image.png)
```

👀 **Contoh Output:**  
[Klik di sini](https://www.example.com)  
![Contoh Gambar](https://www.example.com/image.png)

---

### 5. **Kode (Code)**
#### • Inline code:
```markdown
Contoh `kode` di dalam kalimat.
```

#### • Blok kode (code block):
Gunakan tiga backtick (```) atau identasi 4 spasi.

<pre>
```python
def hello():
    print("Halo, dunia!")
```
</pre>

👀 **Output:**
```python
def hello():
    print("Halo, dunia!")
```

---

### 6. **Kutipan (Blockquote)**
```markdown
> Ini adalah kutipan.
>> Bisa juga bersarang.
```

👀 **Output:**
> Ini adalah kutipan.  
>> Bisa juga bersarang.

---

### 7. **Tabel**
```markdown
| Nama | Umur | Kota      |
|------|------|-----------|
| Ali  | 25   | Jakarta   |
| Budi | 30   | Surabaya  |
```

👀 **Output:**

| Nama | Umur | Kota     |
|------|------|----------|
| Ali  | 25   | Jakarta  |
| Budi | 30   | Surabaya |

---

### 8. **Garis Horizontal**
```markdown
---
```

👀 **Output:**

---

### 9. **Checklist (Tugas)**
```markdown
- [x] Tugas selesai
- [ ] Tugas belum selesai
```

👀 **Output:**
- [x] Tugas selesai  
- [ ] Tugas belum selesai

---

### 10. **Escaping Markdown**
Gunakan `\` untuk menampilkan karakter markdown sebagai teks biasa.

```markdown
\*Teks ini tidak akan menjadi miring\*
```

👀 **Output:**  
\*Teks ini tidak akan menjadi miring\*


## 🌟 Fitur Menarik Lainnya di Markdown

### 1. **Emoji**
Markdown mendukung emoji standar (terutama di GitHub, Notion, dll):

```markdown
:sparkles: :rocket: :memo: :bulb: :x: :white_check_mark:
```

👀 **Output:**  
:rocket: :bulb: :x: :white_check_mark:

> Gunakan [Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/) untuk referensi lengkap!

---

### 2. **Badge / Lencana (GitHub style)**
Biasanya digunakan untuk menunjukkan status build, lisensi, atau versi.

```markdown
![Build Status](https://img.shields.io/badge/Status-Completed-brightgreen)
```

👀 **Output:**  
![Build Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

### 3. **Footnote (Catatan Kaki)**  
Markdown modern (seperti di Jupyter atau pandoc) mendukung footnote:

```markdown
Ini adalah teks dengan catatan kaki[^1].

[^1]: Ini catatan kaki yang akan muncul di bawah.
```

👀 **Output:**  
Ini adalah teks dengan catatan kaki[^1].

[^1]: Ini catatan kaki yang akan muncul di bawah.

---

### 4. **TOC (Table of Contents)**  
Beberapa platform seperti GitHub/GitLab/Notion mendukung pembuatan otomatis TOC dari heading:

```markdown
<!-- TOC -->
- [Judul 1](#judul-1)
- [Judul 2](#judul-2)
<!-- /TOC -->
```

> Cocok digunakan untuk dokumen panjang!

👀 **Output:**
<!-- TOC -->
- [Judul 1](#judul-1)
- [Judul 2](#judul-2)
<!-- /TOC -->
---

### 5. **HTML di Markdown**
Markdown mendukung HTML untuk hal-hal yang tidak bisa dilakukan secara native:

```markdown
<details>
  <summary>Klik untuk melihat detail</summary>
  Ini adalah konten tersembunyi.
</details>
```

👀 **Output:**  
<details>
  <summary>Klik untuk melihat detail</summary>
  Ini adalah konten tersembunyi.
</details>

---

### 6. **Anchor Link Manual**
Membuat tautan antar bagian dalam dokumen:

```markdown
[Lompat ke Bagian Bawah](#bagian-bawah)

...

## Bagian Bawah
```

👀 **Output:** 
[Lompat ke Bagian Bawah](#bagian-bawah)

---

### 7. **Mermaid.js untuk Diagram**
Jika platform mendukung, kamu bisa pakai `mermaid` untuk flowchart, UML, dll:

<pre>
```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```
</pre>

👀 **Output:**
<pre> ```mermaid graph TD; A[Mulai] --> B{Keputusan}; B -->|Ya| C[Lanjutkan]; B -->|Tidak| D[Berhenti]; C --> E[Selesai]; ``` </pre>
