# Tahap Awal
1. Gunakan Scraping Google Play.ipynb untuk melakukan scraping komentar-komentar dari halaman game yang dipilih pada website google play store.
2. Setelah sudah selesai melakukan scraping lanjutkan ke dalam proses pembersihan pada data-data yang sudah diambil dari website google play store. Pada proses pembersihan gunakan Cleaning_Labelling_modelDatathon.ipynb.

# Tahap Kedua
1. Data yang sudah dibersihkan akan dilakukan proses pelabelan otomatis pada Cleaning_Labelling_modelDatathon.ipynb juga.
2. Setelah selesai melakukan pelabelan, data yang sudah diberi label akan diklasifikasi dengan Zero-Shot Classification.
3. Agar data menjadi lebih baik lagi lakukan koreksi dan validasi manual.

# Tahap Ketiga
1. Output dari tahap kedua kita akan lakukan pelatihan dengan IndoBERT.
2. Kita lakukan split data terlebih dahulu menjadi data training dan data test untuk melatih model IndoBERT.
3. Model IndoBERT yang sudah dilatih mampu memberikan label secara otomatis terhadap review atau umpan balik pemain.
4. Data yang sudah diberi label oleh model IndoBERT akan di periksa dan dikoreksi secara manual.
5. Data yang sudah dikoreksi akan digunakan lagi untuk melatiih kembali model IndoBERT serta menambah data atau menambah umpan balik pemain yang belum diberi label untuk melihat kinerja dari model IndoBERT.
6. Proses ini dilakukan berulang kali hingga tingkat akurasinya mencapai 90%.
7. Setelah model mencapai akurasi 90% maka model akan divalidasi.

