Nama        : Nurmaida Intan Permadani  

NRP         : 5025251040  

Mata Kuliah : Struktur Data  

Materi      : Tree


# Tree

Tree (pohon) adalah struktur data non-linear yang berbentuk hierarki dan terdiri dari kumpulan elemen yang disebut node (simpul). Setiap node dalam tree dihubungkan oleh garis yang disebut edge(sisi), yang bisa bersifat terarah (directed) maupun tidak terarah (undirected).

Struktur data seperti:
1. array
2. linked list
3. stack
4. queue
merupakan struktur data linear yang memiliki kelemahan :
- operasi seperti insert dan delete semakin lambat ketika data besar 
- kompleksitas waktu meningkat (kurang efisien untuk data besar)


# Keunggulan Tree

1. Struktur non-linear lebih fleksibel
2. Proses penyimpanan data lebih efisien, akses data lebih cepat, dan manipulasi data lebih optimal
3. Mendukung teknik tranversal seperti preorder, inorder, postorder


# Terminologi I : Hierarki dan Hubungan Keluarga 

![alt text](image.png)
1. Root (Akar) : Node pertama dan titik awal dari seluruh struktur tree.
2. Parent (Induk) : Node pendahulu yang memiliki cabang ke node lain di bawahnya
3. Child (Anak) : Node turunan langsung dari sebuah parent 
4. Siblings (Saudara) : Node - node sejajar yang memiliki parent yang sama


# Terminologi II : Klasifikasi Komponen Struktur

![alt text](image-1.png)
1. Leaf Node (Daun) : Terminal node / external node yang sama sekali tidak memiliki child 
2. Subtree : Tree baru yang terbentuk secara rekursif dari setiap child
3. Internal Node : Node yang memiliki minimal satu child
4. Edge (Sisi) : Garis penghubung antar dua node


# Terminologi III : Mengukur Posisi Vertikal

![alt text](image-2.png)
1. Level : Posisi horizontal sebuah node dalam tree, perhitungan selalu dimulai dari atas (root = level 0, anak root = level 1, dst) 
2. Depth (Kedalaman) : Jumlah edge yang dihitung dari root turun ke node tertentu


# Terminologi IV : Menghitung Jarak, Jalur, dan Kapasistas

![alt text](image-3.png)
1. Height (Tinggi) : Jumlah edge dari sebuah node turun ke leaf terjauh
2. Path (Jalur) : Urutan langkah berkesinambungan dari satu node ke node lain, panjang path dihitung dari jumlah node dalam jumlah tersebut
3. Degree (Derajat) : Jumlah child yang dimiliki sebuah node, degree tree adalah derajat  terbesar dari semua node yang ada di dalam tree tersebut


# Implementasi Tree dalam Ekosistem Teknologi

- Sistem File (OS) : Memetakan hierarki direktori dan folder pada komputer
- Database Indexing : Mengoptimalkan struktur penyimpanan untuk pencarian data berkecepatan tinggi 
- HTML DOM : Menyusun hierarki tag HTML yang dirender oleh web browser
- AI & Machine Learning : Membentuk fondasi Decision Trees untuk algoritma prediktif


# Traversal

Traversal adalah proses mengunjungi setiap node dalam tree secara sistematis

Traversal penting digunakan untuk 
- Pencarian data
- Pengolahan Ekspresi
- Penyimpanan dan pengambilan 

Dua Kategori Utama Traversal
1. Depth First Search (DFS)
2. Breadth First Search (BFS)


