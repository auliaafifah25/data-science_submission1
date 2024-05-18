# Submission Pertama: Menyelesaikan Permasalahan Human Resources

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Perusahaan ini memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. Walaupun telah menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih mengalami kesulitan dalam mengelola karyawan, yang berdampak pada tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

Diketahui bahwa Jaya Jaya Maju memiliki 1470 karyawan, dan lebih dari 10% dari mereka keluar. Berdasarkan analisis data, terdapat beberapa faktor yang mempengaruhi tingginya attrition rate tersebut.

### Permasalahan Bisnis

Permasalahan bisnis yang sedang dihadapi oleh perusahaan Jaya Jaya Maju adalah tingginya tingkat attrition rate. Attrition rate adalah rasio jumlah karyawan yang keluar dari perusahaan dibandingkan dengan total karyawan keseluruhan. Pada kasus ini, attrition rate telah melebihi ambang batas yang dianggap tinggi, yaitu lebih dari 10%. Tingkat attrition yang tinggi ini menimbulkan tantangan signifikan bagi perusahaan dalam mempertahankan tenaga kerja yang kompeten.

Analisis terhadap faktor-faktor yang mempengaruhi tingginya attrition rate mengungkap beberapa pola yang menarik. Misalnya, ditemukan bahwa tingkat attrition yang tinggi terjadi terutama pada karyawan dengan karakteristik tertentu, seperti gender laki-laki, sering melakukan perjalanan bisnis yang tinggi, tingkat kepuasan lingkungan kerja yang rendah, tingkat pendidikan bachelor, dan lain sebagainya. Selain itu, tingkat attrition juga dipengaruhi oleh faktor-faktor seperti status pernikahan, departemen tempat bekerja, dan pola kerja lembur.

Dari analisis ini, dapat disimpulkan bahwa ada beberapa masalah di tempat kerja atau kebijakan perusahaan yang mungkin menjadi penyebab tingginya attrition rate. Mungkin ada masalah dengan kepuasan kerja, keseimbangan kerja, atau kebijakan manajemen sumber daya manusia yang tidak efektif.

### Cakupan Proyek

1. Persiapan
   - Menyiapkan library yang dibutuhkan
   - Menyiapkan data yang akan digunakan
2. Data Understanding: Mengumpulkan informasi tentang data yang dimiliki, untuk memahami struktur, kualitas, dan karakteristik data secara keseluruhan.
   - Data preparation/preprocessing: Menyiapkan data untuk analisis dengan membersihkan, merapihkan, dan mengubah format data agar sesuai dengan kebutuhan analisis.
   - Exploratory Data Analysis: Melakukan eksplorasi data secara visual dan deskriptif untuk memahami karakteristik dan pola dalam data.
3. RFM Analysis: Digunakan untuk memahami perilaku karyawan berdasarkan Recency, Frequency, dan Monetary.
4. Dashboard visualisasi data: Membuat dashboard menggunakan Metabase, memvisualisasikan informasi penting seperti jumlah karyawan, distribusi gender, dan faktor-faktor yang mempengaruhi tingginya atttrition rate.

Output akhir dari proyek adalah dashboard visualisasi data yang memberikan pandangan menyeluruh tentang kondisi tenaga kerja di perusahaan Jaya Jaya Maju. Dashboard ini akan membantu pemangku kepentingan dalam memahami faktor-faktor yang mempengaruhi tingginya tingkat attrition dan menyusun strategi yang tepat untuk mengatasi masalah tersebut.

### Persiapan

Sumber data: [https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee]

Setup environment - Anaconda

```
conda create --name employee-data python=3.9
conda activate employee-data
pip install numpy pandas scipy matplotlib seaborn jupyter sqlalchemy scikit-learn==1.0.2 joblib==1.1.0
jupyter-notebook .
```

## Business Dashboard

Dashboard yang dibuat menggunakan aplikasi Metabase berfungsi sebagai alat visualisasi untuk memantau berbagai aspek terkait karyawan di perusahaan Jaya Jaya Maju. Dashboard ini menyajikan informasi penting seperti jumlah karyawan, distribusi gender, dan faktor-faktor yang menyebabkan tingginya attrition rate (rasio jumlah karyawan yang keluar dari perusahaan).

## Conclusion

Diketahui bahwa Jaya Jaya Maju memiliki 1470 karyawan, dan lebih dari 10% dari mereka keluar. Berdasarkan analisis data, terdapat beberapa faktor yang mempengaruhi tingginya attrition rate tersebut, antara lain:

1. Gender: Sebagian besar karyawan yang keluar adalah laki-laki.
2. BusinessTravel: Karyawan dengan tugas perjalanan yang sering (Frequent business travel) cenderung memiliki attrition rate yang lebih tinggi.
3. EnvironmentSatisfaction: Karyawan dengan tingkat kepuasan lingkungan kerja yang rendah (environment satisfaction low) lebih mungkin untuk keluar.
4. JobLevel: Karyawan yang masih berada di level pekerjaan 1 (job level 1) menunjukkan kecenderungan lebih tinggi untuk keluar.
5. MaritalStatus: Karyawan yang masih single memiliki attrition rate yang lebih tinggi.
6. Department: Department research and development memiliki angka keluarnya karyawan yang tinggi.
7. Overtime: Karyawan yang sering bekerja lembur cenderung lebih cepat keluar.
8. Education: Karyawan dengan pendidikan bachelor lebih banyak yang keluar.
9. Age: Karyawan berusia antara 26-34 tahun, menunjukkan kecenderungan lebih tinggi untuk keluar.

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- Meningkatkan kepuasan lingkungan kerja (Melakukan survei rutin untuk mengukur kepuasan karyawan terhadap lingkungan kerja)
- Fleksibilitas dan kebijakan perjalanan (Meninjau kembali kebijakan perjalanan bisnis untuk mengurangi frekuensi perjalanan yang tidak perlu dan mempertimbangkan opsi kerja jarak jauh atau fleksibel bagi karyawan yang sering melakukan perjalanan)
- Program pengembangan karir (Membuat program pengembangan karir untuk karyawan di level 1 agar mereka melihat jalur karir yang jelas di perusahaan)
- Kebijakan kerja lembur (Mengevaluasi kembali kebijakan kerja lembur untuk memastikan keseimbangan kerja-hidup yang lebih baik bagi karyawan dan mempertimbangkan untuk memberikan kompensasi tambahan bagi karyawan yang sering bekerja lembur)

