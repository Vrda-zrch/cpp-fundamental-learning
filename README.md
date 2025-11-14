# cpp-fundamental-learning
Sebuah repository pembelajaran C++ yang berisi materi fundamental, penjelasan visual, contoh implementasi, dan catatan teori yang tersusun rapi. Dibangun untuk membantu proses memahami dasar pemrograman secara bertahap, mendalam, dan terstruktur, sekaligus menjadi dokumentasi progres belajar yang bisa dikembangkan terus.
<div align="center">

# 🚀 C++ FUNDAMENTAL LEARNING  
**Basic to Intermediate C++ — Notes, Examples, and Visual Guides**

<img src="https://raw.githubusercontent.com/github/explore/main/topics/cpp/cpp.png" width="120">

![Language](https://img.shields.io/badge/language-C++-blue)
![Status](https://img.shields.io/badge/progress-learning-green)
![Platform](https://img.shields.io/badge/platform-GitHub-black)
![Level](https://img.shields.io/badge/level-beginner-lightgrey)

---

</div>

## 📌 Tentang Repository
Repository ini adalah dokumentasi pembelajaran **C++ Fundamental**, berisi teori dasar, visualisasi konsep, penjelasan singkat, contoh kode, dan latihan yang dirapikan secara terstruktur.  
Tujuannya adalah menjadi catatan belajar pribadi yang jelas, mudah dipahami, dan cocok digunakan sebagai referensi jangka panjang.

---

## 📚 Daftar Isi
- [Pendahuluan](#pendahuluan)
- [Instalasi & Persiapan](#instalasi--persiapan)
- [Dasar C++](#dasar-c)
- [Variabel & Tipe Data](#variabel--tipe-data)
- [Operator](#operator)
- [Percabangan](#percabangan)
- [Perulangan](#perulangan)
- [Fungsi](#fungsi)
- [Array](#array)
- [Latihan](#latihan)
- [Cara Compile](#cara-compile)

---

## 📖 Pendahuluan
C++ adalah bahasa pemrograman tingkat menengah yang digunakan untuk:
- Game Development  
- Sistem Operasi  
- Competitive Programming  
- Aplikasi performa tinggi  

Bahasa ini cocok dipelajari karena fleksibel, cepat, dan powerful.

---

## 🛠 Instalasi & Persiapan

### Windows  
Gunakan **MinGW** atau **MSYS2**  
```bash
g++ --version
---

## 🧠 Dasar C++: Penjelasan Lengkap

### 🔹 Struktur Dasar Program C++
Setiap program C++ minimal memiliki struktur:

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello World!";
    return 0; 
}
int umur = 15;
double tinggi = 155.5;
bool hidup = true;
string nama = "Verda";
a + b
a - b
a * b
a / b
a % b
&&   // AND
||   // OR
!    // NOT
int umur = 17;

if (umur >= 18) {
    cout << "Dewasa";
} else {
    cout << "Belum dewasa";
}
==  !=  >  <  >=  <=
int angka = 2;

switch(angka){
    case 1: cout << "Satu"; break;
    case 2: cout << "Dua"; break;
    default: cout << "Tidak diketahui";
}
for (int i = 1; i <= 5; i++) {
    cout << i << endl;
}
