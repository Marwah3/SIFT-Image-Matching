SIFT Image Matching

Final Project Mata Kuliah Visi Komputer
Implementasi Scale-Invariant Feature Transform (SIFT) untuk pencocokan dua citra.

📌 Deskripsi

Project ini mengimplementasikan algoritma SIFT menggunakan Python dan OpenCV untuk melakukan:

- Deteksi keypoints
- Ekstraksi descriptor
- Feature matching
- Lowe’s Ratio Test
-Visualisasi hasil

📂 Dataset

Dataset menggunakan dua citra objek yang sama dengan variasi sudut pengambilan dan pencahayaan.
Gambar diambil secara mandiri menggunakan kamera smartphone.

⚙️ Library yang Digunakan
- OpenCV
- NumPy
- Matplotlib
- 
▶️ Cara Menjalankan

1. Clone repository:
git clone https://github.com/USERNAME/SIFT-Image-Matching.git

2. Masuk ke folder project:
cd SIFT-Image-Matching

3. Install dependencies:
pip install -r requirements.txt

4. Jalankan program:
python main.py

📊 Output

Program akan menampilkan:

- Jumlah keypoints pada masing-masing citra
- Jumlah total matches
- Jumlah good matches setelah Lowe’s Ratio Test
- Visualisasi keypoints
- Visualisasi feature matching
