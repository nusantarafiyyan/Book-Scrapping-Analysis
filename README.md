📚 Books Data Scraping & Exploratory Data Analysis
📌 Project Overview

Project ini bertujuan untuk melakukan web scraping pada website Books to Scrape dan menganalisis hubungan antara harga buku dan rating.

Fokus utama analisis:

Mengumpulkan data buku dari seluruh halaman website

Melakukan data cleaning dan preprocessing

Melakukan Exploratory Data Analysis (EDA)

Menguji distribusi data

Menganalisis apakah harga memengaruhi rating buku

Menarik insight bisnis dari hasil analisis

🌐 Data Source

Website: http://books.toscrape.com/

Dataset hasil scraping berisi 1000 buku dengan fitur berikut:

title → Judul buku

price → Harga buku

rating → Rating buku (1–5)

stock_text → Status ketersediaan

url → Link detail buku

🛠 Tools & Libraries

Python

Requests

BeautifulSoup

Pandas

Matplotlib

Seaborn

SciPy

🔄 Project Workflow
1️⃣ Web Scraping

Scraping multi-page hingga seluruh katalog terkumpul

Mengambil informasi: title, price, rating, stock, dan url

Mengubah rating berbasis teks menjadi numerik

2️⃣ Data Cleaning

Konversi tipe data

Pengecekan missing value

Penghapusan kolom yang tidak digunakan

3️⃣ Exploratory Data Analysis (EDA)

Distribusi rating buku

Distribusi harga (histogram)

Boxplot harga (outlier detection)

Korelasi harga dan rating

Top 5 buku dengan rating tertinggi

Distribusi stok buku

4️⃣ Statistical Testing

Skewness & Kurtosis

Shapiro-Wilk Test

Kolmogorov-Smirnov Test

Hasil menunjukkan bahwa distribusi harga tidak sepenuhnya normal, namun mendekati simetris.

📊 Key Findings

Tidak ditemukan korelasi signifikan antara harga dan rating.

Buku dengan harga tinggi tidak selalu memiliki rating tinggi.

Distribusi harga relatif merata.

Sebagian besar buku tersedia dalam kondisi "In Stock".

🎯 Business Insight

Harga bukan indikator utama kualitas berdasarkan rating.

Strategi penetapan harga dapat difokuskan pada positioning pasar, bukan asumsi kualitas.

Promosi dapat dilakukan tanpa harus selalu menaikkan harga sebagai simbol premium quality.
