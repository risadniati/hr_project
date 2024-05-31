# Proyek Akhir: Menyelesaikan Permasalahan Human Resources

## Business Understanding dan Permasalahan Bisnis

Pada proyek ini, akan diangkat sebuah studi kasus mengenai perusahaan Jaya Jaya Maju. Perusahaan tersebut telah berdiri sejak tahun 2000 dengan karyawan lebih dari 1000 orang.

Walau demikian, Jaya Jaya Maju masih cukup kesulitan mengelola karyawan, sehingga attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) lebih dari 10%.

Oleh karena itu, perlu diidentifikasi berbagai faktor yang mempengaruhi hal tersebut, yang selanjutnya akan ditampilkan dalam business dashboard.

### Cakupan Proyek

Pada proyek ini, akan dibuat business dashboard yang berisi faktor-faktor yang berpengaruh terhadap attrition rate. Berikut beberapa pertanyaan untuk menjawab hal tersebut :
- Berapakah tingkat persentase attrition rate pada perusahaan?
- Bagaimana penilaian karyawan terhadap relasi kerja ?
- Bagaimana penilaian karyawan mengenai keseimbangan kehidupan dan pekerjaan ?
- Bagaimana attrition rate pada berbagai divisi yang ada di perusahaan ?

### Persiapan

Sumber data: "https://raw.githubusercontent.com/dicodingacademy/dicoding_dataset/main/employee/employee_data.csv"

Setup environment:

```
# Menginstal 'virtualenv'
!pip install virtualenv

# Membuat virtual environment di dalam direktori proyek
!virtualenv env

# Mengaktifkan virtual environment dan menginstal paket yang diperlukan
!source env/bin/activate && pip install numpy
```

## Business Dashboard

Link Dashboard : 
https://lookerstudio.google.com/reporting/185945bd-93f7-4579-b285-02e49f8acccb

Link video penjelasan dashboard : 
https://drive.google.com/file/d/1iKILHHexe6fpTqACBKl1uvL8JADBw8gt/view?usp=sharing


Pada perusahaan ini, terdapat total 1291 karyawan aktif, sedangkan untuk karyawan yang resign sebanyak 179 orang. Sehingga, jika dikalkulasi, tingkat attrition karyawan sebesar 12,18%.
Angka tersebut cukup besar dan perlu mendapat perhatian dari manajemen. 
Oleh karenanya, perlu diketahui pula apa faktor yang mendasari hal tersebut. 

- Pertama, tingkat attrition karyawan berdasarkan Departemen.
  Melalui grafik, Departemen Research & Development menempati urutan pertama untuk karyawan yang resign, disusul oleh Departemen Sales, dan tingkat attrition terendah adalah Departemen Human Resource. 
Dari analisa ini,  manajemen dapat lebih memperhatikan dan mengidentifikasi bagaimana sistem kerja pada Departemen RnD & Sales agar tingkat attrition dapat diminimalkan.

- Kedua, tingkat attrition dari status.
  Karyawan dengan status belum menikah adalah yang terbanyak memutus hubungan kerja.
  Sedangkan untuk karyawan dengan status menikah atau bercerai, memiliki tingkat attrition lebih rendah.
  Melalui hal ini, manajemen dapat memberikan kegiatan yang dapat mendukung karir, seperti program pengembangan karir dengan mentor. Harapannya adalah dengan adanya program tersebut, karyawan memiliki pandangan yang jelas terkait perkembangan karir dan kesempatan pengembangan diri di perusahaan, sehingga tetap dapat bekerja untuk perusahaan.

- Selanjutnya, dapat dilihat penilaian karyawan, yakni terhadap tingkat keseimbangan kehidupan dan pekerjaan serta penilaian terhadap relasi pekerjaan.
  Melalui grafik, dapat dilihat masih ada karyawan yang memberikan penilaian yang rendah terkait kedua faktor tersebut.
  Walau persentase yang ditunjukkan cukup rendah, yakni dibawah 20%, namun ini tetap menjadi catatan bagi manajemen.
  Menyikapi hal ini, dapat dilakukan diskusi dengan karyawan, sehingga pihak manajemen dapat mendengar pendapat dan saran dari karyawan.

## Conclusion

- Attrition rate pada perusahaan mencapai angka 12.18%, ini perlu menjadi perhatian manajemen untuk melakukan tindakan agar angka tersebut dapat diminimalkan. 
- Tingkat attrition tertinggi terjadi pada Departemen Research & Development. Selain itu, berdasarkan status, karyawan dengan status belum menikah memiliki tingkat attrition yang tinggi. 
- Penilaian karyawan terhadap tingkat keseimbangan kehidupan dan pekerjaan serta peniaian terhadap relasi pekerjaan cukup baik, namun masih ada karyawan yang menilai rendah kedua faktor tersebut.

### Rekomendasi Action Items 
Tindakan yang dapat dilakukan oleh manajemen untuk menyikapi hal tersebut diantaranya : 
- identifikasi sistem kerja setiap departemen
- Memberikan program yang dapat menunjang karir
- Melakukan diskusi dengan karyawan untuk mendengar pendapat dan saran 
