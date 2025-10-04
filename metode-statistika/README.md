# Metode Statistika - Learning Path

## Deskripsi
Project pembelajaran metode statistika dari level beginner hingga advanced menggunakan Jupyter notebooks dengan konten lengkap, istilah bahasa Inggris populer, dan visualisasi interaktif.

## Fitur Utama
- ✅ **Konten Lengkap**: Penjelasan teoritis yang komprehensif dengan rumus matematis
- ✅ **Istilah Bahasa Inggris**: Setiap konsep dilengkapi dengan istilah bahasa Inggris yang populer
- ✅ **Kode Python Interaktif**: Contoh implementasi dengan pandas, numpy, matplotlib, seaborn, scipy
- ✅ **Visualisasi Menarik**: Grafik dan diagram yang informatif untuk memahami konsep
- ✅ **Simulasi Data**: Contoh data dan simulasi untuk demonstrasi konsep
- ✅ **Pembelajaran Bertahap**: Dari konsep dasar hingga aplikasi lanjutan

## Struktur Pembelajaran

### Level Beginner
1. **01_pengenalan_statistika_deskriptif.ipynb** - Pengenalan konsep dasar statistika (Statistics)
   - Jenis-jenis data (Types of Data): Kualitatif/Quantitative, Nominal/Ordinal, Discrete/Continuous
   - Data primer/sekunder, internal/eksternal
   - Contoh kode Python untuk demonstrasi

2. **02_ukuran_pemusatan.ipynb** - Mean (Arithmetic Mean), Median, Mode
   - Sifat-sifat mean (sensitive to outliers, unique, mathematical properties)
   - Perhitungan manual dan menggunakan library
   - Visualisasi perbandingan ukuran pemusatan

3. **03_ukuran_penyebaran.ipynb** - Range, Variance, Standard Deviation, IQR, CV
   - Kelebihan dan kelemahan setiap ukuran
   - Aturan empiris (Empirical Rule) untuk standard deviation
   - Visualisasi dengan histogram, box plot, scatter plot

4. **04_distribusi_frekuensi.ipynb** - Tabel dan grafik frekuensi (Frequency Distribution)
   - Distribusi frekuensi absolut, relatif, dan kumulatif
   - Data kategorik dan numerik
   - Visualisasi dengan bar chart, pie chart, histogram

5. **05_probabilitas_dasar.ipynb** - Konsep dasar probabilitas (Basic Probability)
   - Ruang sampel dan kejadian (Sample Space and Events)
   - Pendekatan probabilitas (Classical, Empirical, Subjective)
   - Simulasi dengan dadu dan visualisasi

6. **06_distribusi_normal.ipynb** - Distribusi normal (Normal Distribution/Gaussian Distribution)
   - PDF dengan rumus matematis
   - Pengaruh mean dan standard deviation
   - Simulasi data normal

### Level Intermediate
7. **07_sampling_dan_estimasi.ipynb** - Teknik sampling dan estimasi parameter
   - Probability dan non-probability sampling
   - Point estimation dan interval estimation
   - Confidence interval dengan simulasi

8. **08_uji_hipotesis.ipynb** - Pengujian hipotesis statistik (Hypothesis Testing)
   - Null dan alternative hypothesis
   - Type I dan Type II error
   - Tingkat signifikansi dan p-value

9. **09_uji_t.ipynb** - Uji t (t-test): One-sample, Two-sample, Paired
   - Asumsi uji t
   - Interpretasi hasil
   - Visualisasi dengan t-distribution

10. **10_uji_chi_square.ipynb** - Uji chi-square (Chi-Square Test)
    - Goodness of fit dan test of independence
    - Tabel kontingensi
    - Visualisasi dengan heatmap

11. **11_anova.ipynb** - Analysis of Variance (ANOVA)
    - One-way dan two-way ANOVA
    - F-test dan F-distribution
    - Post-hoc analysis

12. **12_korelasi_dan_regresi.ipynb** - Korelasi (Correlation) dan regresi linear
    - Pearson dan Spearman correlation
    - Simple linear regression
    - Residuals analysis dan model validation

### Level Advanced
13. **13_regresi_multiple.ipynb** - Regresi Linear Berganda (Multiple Linear Regression)
    - Model regresi dengan beberapa variabel independen
    - Multikolinearitas dan VIF analysis
    - Model evaluation dan cross-validation
    - Outlier detection dan residual analysis

14. **14_analisis_varians_multivariat.ipynb** - MANOVA (Multivariate Analysis of Variance)
    - One-way dan two-way MANOVA
    - Multivariate F-test
    - Post-hoc analysis untuk MANOVA

15. **15_distribusi_sampling.ipynb** - Teorema Limit Pusat (Central Limit Theorem)
    - Sampling distribution
    - Central Limit Theorem
    - Law of Large Numbers
    - Bootstrap sampling

16. **16_interval_kepercayaan.ipynb** - Interval Kepercayaan (Confidence Intervals)
    - Confidence interval untuk mean dan proportion
    - t-distribution dan normal distribution
    - Margin of error dan sample size

17. **17_uji_non_parametrik.ipynb** - Uji Non-Parametrik (Non-Parametric Tests)
    - Mann-Whitney U test
    - Wilcoxon signed-rank test
    - Kruskal-Wallis test
    - Friedman test

18. **18_time_series_analysis.ipynb** - Analisis Deret Waktu (Time Series Analysis)
    - Komponen deret waktu (trend, seasonal, cyclical)
    - Stasionaritas dan differencing
    - Dekomposisi deret waktu
    - ARIMA modeling dan forecasting

19. **19_machine_learning_statistik.ipynb** - Machine Learning Statistik (Statistical ML)
    - Bias-variance tradeoff
    - Cross-validation dan bootstrap
    - Regularization (Ridge, Lasso, Elastic Net)
    - Model selection dan evaluation

## Prerequisites
- Python 3.7+
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scipy, scikit-learn, statsmodels

## Cara Menggunakan
1. Install dependencies: `pip install -r requirements.txt`
2. Buka Jupyter Notebook: `jupyter notebook`
3. Mulai dari notebook 01 dan ikuti urutan pembelajaran
4. Jalankan setiap cell untuk melihat output dan visualisasi
5. Modifikasi parameter untuk eksperimen dengan data berbeda

## Tips Belajar
- **Jalankan semua cell**: Setiap notebook dirancang untuk dijalankan secara berurutan
- **Eksperimen dengan data**: Ubah parameter dalam simulasi untuk memahami konsep
- **Perhatikan visualisasi**: Grafik membantu memahami konsep abstrak
- **Baca penjelasan teoritis**: Setiap konsep dilengkapi dengan penjelasan mendalam
- **Gunakan istilah bahasa Inggris**: Familiar dengan terminologi internasional

## Fitur Khusus
- **Simulasi Interaktif**: Data dihasilkan secara random untuk demonstrasi
- **Visualisasi Komprehensif**: Multiple plots untuk setiap konsep
- **Perhitungan Manual**: Langkah-langkah perhitungan yang jelas
- **Verifikasi Hasil**: Perbandingan antara perhitungan manual dan library
- **Interpretasi Hasil**: Penjelasan makna statistik dari setiap analisis

## Struktur Kode
Setiap notebook memiliki struktur yang konsisten:
1. **Import Libraries**: Library yang diperlukan
2. **Data Preparation**: Persiapan data contoh
3. **Theoretical Explanation**: Penjelasan konsep teoritis
4. **Manual Calculation**: Perhitungan step-by-step
5. **Library Implementation**: Implementasi menggunakan library
6. **Visualization**: Grafik dan diagram informatif
7. **Interpretation**: Interpretasi hasil analisis

## Kontribusi
Silakan buat issue atau pull request untuk perbaikan atau penambahan materi.

## Status Project
- ✅ **19 Notebook Lengkap**: Semua notebook telah dilengkapi dengan konten detail
- ✅ **3 Level Pembelajaran**: Beginner, Intermediate, dan Advanced
- ✅ **Istilah Bahasa Inggris**: Setiap konsep memiliki terminologi internasional
- ✅ **Kode Python Interaktif**: Implementasi lengkap dengan visualisasi
- ✅ **Simulasi Data**: Contoh data dan simulasi untuk demonstrasi
- ✅ **Pembelajaran Bertahap**: Progresi dari konsep dasar hingga lanjutan
- ✅ **Requirements.txt**: Daftar dependency yang lengkap
- ✅ **Advanced Topics**: Regresi multiple, time series, non-parametrik, ML statistik


