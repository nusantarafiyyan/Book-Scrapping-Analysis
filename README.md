**📚 Books Data Scraping & Exploratory Data Analysis**

Project ini bertujuan untuk melakukan web scraping pada website Books to Scrape dan menganalisis hubungan antara harga buku dan rating.
Fokus utama analisis:
1. Mengumpulkan data buku dari seluruh halaman website
2. Melakukan data cleaning dan preprocessing
3. Melakukan Exploratory Data Analysis (EDA)
4. Menguji distribusi data
5. Menganalisis apakah harga memengaruhi rating buku
6. Menarik insight bisnis dari hasil analisis

**🌐 Data Source**

Website: http://books.toscrape.com/
Dataset hasil scraping berisi 1000 buku dengan fitur berikut:
1. title → Judul buku
2. price → Harga buku
3. rating → Rating buku (1–5)
4. stock_text → Status ketersediaan


url → https://books.toscrape.com/
🛠 Tools & Libraries
1. Python
2. Requests
3. BeautifulSoup
4. Pandas
5. Matplotlib
6. Seaborn
7. SciPy

**🔄 Project Workflow**

A. Web Scraping
1. Scraping multi-page hingga seluruh katalog terkumpul
2. Mengambil informasi: title, price, rating, stock, dan url
3. Mengubah rating berbasis teks menjadi numerik

B. Data Cleaning
1. Konversi tipe data
2. Pengecekan missing value
3. Penghapusan kolom yang tidak digunakan

C. Exploratory Data Analysis (EDA)
1. Distribusi rating buku
2. Distribusi harga (histogram)
3. Boxplot harga (outlier detection)
4. Korelasi harga dan rating

**Top 5 buku dengan rating tertinggi**
Distribusi stok buku
4️⃣ Statistical Testing
1. Skewness & Kurtosis
2. Shapiro-Wilk Test
3. Kolmogorov-Smirnov Test
Hasil menunjukkan bahwa distribusi harga tidak sepenuhnya normal, namun mendekati simetris.

**📊 Key Findings**
1. Tidak ditemukan korelasi signifikan antara harga dan rating.
2. Buku dengan harga tinggi tidak selalu memiliki rating tinggi.
3. Distribusi harga relatif merata.
4. Sebagian besar buku tersedia dalam kondisi "In Stock".

**🎯 Business Insight**
1. Harga bukan indikator utama kualitas berdasarkan rating.
2. Strategi penetapan harga dapat difokuskan pada positioning pasar, bukan asumsi kualitas.
3. Promosi dapat dilakukan tanpa harus selalu menaikkan harga sebagai simbol premium quality.
