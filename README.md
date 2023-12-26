# AWS-SaaS-Sales-Data-Analysis
## **Latar Belakang**

Perusahaan AWS (Amazon Web Services) adalah layanan berbasis cloud yang di sediakan oleh amazon sejak tahun 2002. Amazon yang di kenal perusahaan yang besar untuk membeli buku dan lagu , tetapi sekarang amazon telah menambah layanan dalah hal infrastruktur cloud komputing. 

Salah satu produk milik AWS SaaS (Software as a Service) adalah model perangkat lunak yang berbasis cloud yang mengirimkan aplikasi ke pengguna melalui internet. Dengan Saas tidak perlu lagi memikirkan cara memelihara layanan atau cara mengelola infrastruktur. Pengguna hanya perlu memikirkan cara menggunakan perangkat lunak tersebut. Harga yang diberikan menyesuaikan dengan layanan yang di gunakan.

## **Pernyataan Masalah**

Untuk meningkatkan penjualan produk SaaS, terlampir data penjualan dari perusahaan amazon selama tahun 2020 hingga 2023. Data tersebut perlu di analisa berdasarkan performa penjualan, agar dapat menentukan strategi marketing yang sesuai untuk meningkatan sales. Divisi Data pada perusahaan tersebut akan membuatkan analisa untuk memudahkan divisi marketing dalam membuat strategi yang efektif. **Bagaimana performa penjualan meningkat dengan analisa dari tim data?**

### Data


dfset ini berisi df transaksi dari perusahaan SaaS fiktif yang menjual perangkat lunak penjualan dan pemasaran kepada perusahaan lain (B2B). Dalam dfset ini, setiap baris mewakili satu produk dalam suatu transaksi, dan kolom-kolom mencakup:

Berikut adalah dfset Asli: [Sumber](https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales)

| No. | Column Name    | Description                                                |
|----|----------------|------------------------------------------------------------|
| 1  | Row ID         | Identifikasi unik untuk setiap transaksi.                  |
| 2  | Order ID       | Identifikasi unik untuk setiap pesanan.                    |
| 3  | Order Date     | Tanggal ketika pesanan ditempatkan.                         |
| 4  | Date Key       | Representasi numerik dari tanggal pesanan (YYYYMMDD).       |
| 5  | Contact Name   | Nama orang yang menempatkan pesanan.                       |
| 6  | Country        | Negara tempat pesanan ditempatkan.                         |
| 7  | City           | Kota tempat pesanan ditempatkan.                            |
| 8  | Region         | Wilayah tempat pesanan ditempatkan.                         |
| 9  | Subregion      | Subwilayah tempat pesanan ditempatkan.                      |
| 10 | Customer       | Nama perusahaan yang menempatkan pesanan.                  |
| 11 | Customer ID    | Identifikasi unik untuk setiap pelanggan.                   |
| 12 | Industry       | Industri yang dimiliki oleh pelanggan.                      |
| 13 | Segment        | Segmen pelanggan (SMB, Strategis, Enterprise, dll.).       |
| 14 | Product        | Produk yang dipesan.                                       |
| 15 | License        | Kunci lisensi untuk produk.                                |
| 16 | Sales          | Jumlah penjualan total untuk transaksi.                    |
| 17 | Quantity       | Jumlah total barang dalam transaksi.                       |
| 18 | Discount       | Diskon yang diterapkan pada transaksi.                     |
| 19 | Profit         | Keuntungan dari transaksi.                                  |

**Kesimpulan dan Rekomendasi**

Untuk meningkatkan performa penjualan perusahaan AWS dengan cara?

1. Meningkatkan frekuensi pembelian dari customer, karena dari analisa cross tab jumlah frequensi transaksi memliki hubungan positif terhadap penjualan.

2. Meningkatkan jumlah per order dari customer, karena dari analisa yang sudah di lakukan. Quantity pada penjualan memiliki hubungan positif.

3. Pada industri finance memiliki penjualan tinggi, dan industri misc memiliki penjualan yang rendah.

4. Terdapat peluang peningkat penjualan pada industri energi, manufaktur, tech dan healthcare.

5. Top Customers in Each Industry:

    - Finance: Allianz, Bank of America Corp., BNP Paribas, Allstate
    - Manufacturing: Ford Motor, Siemens, Volkswagen
    - Consumer Products: Tyson Foods
    - Healthcare: AmerisourceBergen, UnitedHealth Group
6. Produk "ContactMatcher" merupakan kontributor terbesar terhadap penjualan dengan total penjualan sebesar 379,087.86.

7. Produk "FinanceHub" menempati peringkat kedua dengan total penjualan sebesar 340,935.42, diikuti oleh "Site Analytics" dengan total penjualan 330,007.05.

8. Produk dengan penjualan rendah dapat dievaluasi untuk menentukan apakah perlu ditingkatkan, dihentikan, atau mendapatkan perhatian lebih lanjut dalam strategi pemasaran.

9. Pola pada grafik penjualan berdasarkan quartal, bahwa penjualan mulai kuartal 1 terendah akan mulai meningkat setelah kuartal selanjutnya puncaknya pada quartal 4 dan tren nya akan naik di setiap tahunnya. 

Rekomendasi:

1. Dorong program loyalitas pelanggan atau promosi khusus untuk mendorong pembelian berulang dari pelanggan.

2. Pertimbangkan untuk memberikan insentif kepada pelanggan yang sering berbelanja, seperti diskon khusus atau hadiah.

3. Manfaatkan peningkatan penjualan yang dapat terjadi pada kuartal tertentu, seperti memperkuat persiapan promosi menjelang kuartal puncak.

4. Pertimbangkan untuk meningkatkan strategi pemasaran produk "ContactMatcher" yang merupakan kontributor terbesar terhadap penjualan.

5. Tinjau dan pertahankan strategi produk "FinanceHub" dan "Site Analytics" yang juga memiliki kontribusi penjualan yang signifikan.

6. Terus pantau dan analisis tren penjualan tahunan untuk memahami perubahan perilaku pelanggan.


* **Perkasa Muhammad** - *Initial work* - [PurpleBooth](https://github.com/PerkasaM/AWS-SaaS-Sales-performance/blob/main/AWS%20Saas%20Perkasa%20Muhammad..ipynb)



