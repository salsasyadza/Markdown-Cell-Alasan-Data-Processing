## Evaluasi Hasil Model Clustering

### Elbow Method:

Metode Elbow digunakan untuk menentukan jumlah optimal dari cluster dengan mengamati inersia (within-cluster sum of squares) pada berbagai nilai k (jumlah cluster). Dalam visualisasi Elbow Method, titik di mana penurunan inersia mulai melambat sering dianggap sebagai jumlah optimal dari cluster. Dalam grafik ini, kita mencari siku (elbow) di mana penurunan inersia tidak lagi signifikan. Pada gambar ini, titik di sekitar k=4 mungkin merupakan pilihan yang baik untuk jumlah cluster.

### Silhouette Coefficient:

Silhouette Coefficient mengukur seberapa baik setiap titik data ditempatkan dalam cluster mereka sendiri dibandingkan dengan cluster tetangga terdekat. Nilai Silhouette Coefficient berkisar dari -1 hingga 1, di mana nilai yang lebih tinggi menunjukkan hasil clustering yang lebih baik. Pada grafik tersebut, kita mencari nilai k yang memberikan Silhouette Coefficient tertinggi. Pada contoh ini, nilai tertinggi terlihat pada k=4, yang mendukung hasil dari Elbow Method.

### Connectivity (untuk Hierarchical Clustering):

Metode Hierarchical Clustering dengan menggunakan koneksi (connectivity) dapat mempertimbangkan informasi struktural tambahan dalam data. Kita menghitung matriks koneksi menggunakan neighbors graph, dan model kemudian diberikan informasi konektivitas ini saat melakukan clustering. Hasil clustering ini dapat diinterpretasikan dengan mempertimbangkan struktur hubungan antar data. Analisis lebih lanjut, seperti visualisasi dendrogram, dapat memberikan wawasan tambahan terhadap pengelompokan yang dihasilkan.

Melalui kombinasi metode-metode evaluasi ini, kita dapat mendapatkan pemahaman yang lebih baik tentang kualitas hasil dari proses clustering pada dataset yang digunakan.
