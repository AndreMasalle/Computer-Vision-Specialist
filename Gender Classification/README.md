# ♂️**CV Project 1 - Gender Classification with GoogleNet** ♀️

## 📌 **Overview**
Proyek ini bertujuan untuk membangun model **_gender classification_** menggunakan arsitektur yang telah ditentukan, yang memprediksi **gender** (Male atau Female) dari gambar wajah. Model ini dibangun menggunakan **PyTorch**, dengan fokus pada pemrosesan citra wajah untuk mengidentifikasi jenis kelamin berdasarkan fitur wajah.

---

## 🧑‍🤝‍🧑 **Pembagian Tugas Tim VisionPlus**

Proyek ini dikerjakan oleh tim **VisionPlus** yang terdiri dari beberapa anggota, masing-masing bertanggung jawab pada bagian tertentu:

<table>
  <tr>
    <th>Nama</th>
    <th>Tugas</th>
  </tr>
  <tr>
    <td><strong>Andre F. Masalle</strong></td>
    <td>Mengembangkan model menggunakan arsitektur <strong>GoogleNet</strong></td>
  </tr>
  <tr>
    <td><strong>Teguh Imanto</strong></td>
    <td>Mengembangkan model menggunakan arsitektur <strong>ResNet50</strong> & Pembuatan slide PPT</td>
  </tr>
  <tr>
    <td><strong>Christian B. Kuswandi</strong></td>
    <td>Mengembangkan model menggunakan arsitektur <strong>GoogleNet</strong></td>
  </tr>
  <tr>
    <td><strong>Robert Rasidy</strong></td>
    <td>Mengembangkan model menggunakan arsitektur <strong>ResNet18</strong></td>
  </tr>
</table>

---

## 🧰 **Tech Core** 🛠️
Untuk membangun dan menjalankan model ini, kami menggunakan berbagai tools dan library berikut:

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-003366?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit-learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

---

## 🧪 **Dataset** 📊

Model ini dilatih menggunakan dataset **CelebA**, yang merupakan dataset besar yang memiliki lebih dari 200K gambar selebriti dengan anotasi atribut. Berikut adalah beberapa detail dari dataset:

- **Dataset**: [CelebA Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
- **10.177** jumlah identitas selebriti
- **202.599** jumlah gambar wajah
- **5 landmark** wajah dan **40 anotasi atribut biner** per gambar

### 📄 **Disclaimer**:
- Jumlah gambar yang digunakan untuk **training** model ini hanya sekitar **5.000-an gambar**.
- Menggunakan **40 anotasi atribut biner** sebagai fitur dan **gender** sebagai target yang diprediksi.

---
