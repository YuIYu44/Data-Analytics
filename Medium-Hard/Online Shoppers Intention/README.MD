# Online Shoppers Purchasing Intention

Dataset yang berisi kumpulan data mengenai pola pembelian dan perilaku konsumen saat berbelanja online.

### Variabel:

- Administrative : Jumlah halaman yang berhubungan dengan administratif dikunjungi
- Administrative_Duration : Total waktu berkunjung pada halaman administratif
- Informational : Jumlah halaman yang berhubungan dengan informasi dikunjungi
- Informational_Duration : Total waktu berkunjung pada halaman informasi
- ProductRelated : Jumlah halaman yang berhubungan dengan produk dikunjungi
- ProductRelated_Duration : Total waktu berkunjung pada halaman produk
- BounceRates : Persentasi pengunjung hanya melihat satu halaman website
- ExitRates : Persentasi pengunjung website keluar dari halaman tertentu
- PageValues : Rata-rata jumlah halaman yang dikunjungi sebelum pengunjung melakukan transaksi
- SpecialDay : Skala kedekatan tanggal kunjungan terhadap hari spesial
- Month : Bulan kunjungan
- Spesifikasi dari pengunjung:
  - OperatingSystems (Sistem Operasi Komputer)
  - Browser (Web Browser yang dipakai)
  - Region (Daerah pengunjung)
  - TrafficType : Sumber lalu lintas yang membawa pengujung ke website
- VisitorType (Jenis Pengujung) : Returning visitor atau New visitor
- Weekend (Apakah diakses saat akhir pekan) : True atau False
- Revenue (Apakah pengujung akhirnya membeli) : True atau False

### Pertanyaan

1. How does a visitor's closeness to key dates (special day) impact conversion rates (revenue =true) across different visitor cohorts (visitor type) over various months?
2. At what page-count threshold does the probability of conversion diminish for distinct user behavioral clusters derived from the joint distribution of different page types?
3. After accounting for right-skewed session lengths, what specific duration window optimizes time efficiency per page to maximize revenue?
4. When controlling for exit rates alongside page values, what is the independent predictive power of bounce rates on conversion given the interaction effect of different traffic sources?
5. Which specific combinations of operating systems, browsers, plus regional settings point to cross-platform technical friction causing anomalously low conversion rates despite high page values?

## Dashboard

![Dashboard Menjawab Dari 5 Pertanyaan](Dashboard.png)

1.  - Terhadap Bulan: ![Jawab Pertanyaan 1](image.png)
    - Terhadap Jenis Pengujung: ![Jawab Pertanyaan 1](image-1.png)
2.  - Halaman 0-49 ![Halaman 0-50](image-2.png)
    - Halaman 50-99 ![Halaman 50-99](image-3.png)
    - Halaman 100-149 ![Halaman 100-149](image-4.png)
    - Halaman 150-199 ![Halaman 150-199](image-5.png)
    - Halaman 200-249 ![Halaman 200-249](image-6.png)
    - Halaman 250-299 ![Halaman 250-299](image-7.png)
    - Halaman >=300 ![Halaman >=300](image-8.png)
3.  - Halaman administratif![Halaman Administratif](image-9.png)
    - Halaman informasi![Halaman informasi](image-10.png)
    - Halaman produk![Halaman produk](image-11.png)
4.  ![Jawab Pertanyaan 4](image-12.png)
5.  ![Jawab Pertanyaan 5](image-13.png)
