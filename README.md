## Implementasi Integrasi Numerik untuk Menghitung Estimasi nilai Pi

### Deskripsi
Proyek ini bertujuan untuk menggunakan metode integral Riemann dalam memperkirakan nilai dari konstanta matematika pi ($\pi$). Metode ini membagi area di bawah kurva fungsi tertentu menjadi subinterval kecil dan menghitung jumlah total area subinterval tersebut. Dalam proyek ini, fungsi yang digunakan adalah $f(x) = \frac{4}{1 + x^2}$, yang merupakan fungsi integral dari lingkaran dengan jari-jari 1. Dengan meningkatkan jumlah subinterval ($N$), estimasi nilai pi akan semakin akurat.

### Metode
Metode yang digunakan dalam proyek ini adalah sebagai berikut:
1. **Metode Integral Riemann**: Proyek ini menggunakan pendekatan integral Riemann untuk mengestimasi nilai pi. Area di bawah kurva fungsi $f(x)$ antara batas $a$ dan $b$ diperkirakan dengan membagi interval $[a, b]$ menjadi $N$ subinterval yang sama lebar.

2. **Fungsi**: Fungsi yang digunakan dalam perhitungan adalah $f(x) = \frac{4}{1 + x^2}$. Fungsi ini dipilih karena merupakan fungsi integral dari lingkaran dengan jari-jari 1 dan memberikan nilai pi saat $x = 1$.

### Variasi Nilai $N$
Variasi nilai $N$ digunakan untuk mengamati perubahan estimasi pi seiring peningkatan jumlah subinterval. Nilai $N$ yang digunakan adalah [10, 100, 1000, 10000].

### Evaluasi
Evaluasi dilakukan dengan membandingkan estimasi pi yang dihasilkan dengan nilai pi referensi ($\pi_{reference} = 3.14159265358979323846$). RMS error digunakan sebagai metrik evaluasi untuk mengevaluasi seberapa akurat estimasi pi yang dihasilkan.

### Output
Output dari proyek ini mencakup:
- Estimasi pi untuk setiap nilai $N$.
- RMS error, yang menunjukkan seberapa jauh estimasi pi dari nilai pi referensi.
- Waktu eksekusi untuk setiap iterasi, yang memberikan gambaran tentang efisiensi komputasi metode integral Riemann.

### Kesimpulan
Proyek ini memberikan pemahaman tentang penggunaan metode integral Riemann untuk memperkirakan nilai pi. Dengan mengamati variasi nilai $N$, proyek ini menunjukkan bagaimana peningkatan jumlah subinterval dapat meningkatkan akurasi estimasi pi. Evaluasi menggunakan RMS error memberikan informasi tentang seberapa baik estimasi tersebut.
