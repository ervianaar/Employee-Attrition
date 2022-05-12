# Klasifikasi Employee-Attrition
Project ini dibuat dalam memenuhi tugas dibimbing. Pada project ini, saya akan menjadi pegawai di departemen SDM perusahaan XYZ. 
Saat ini, perusahaan tidak memiliki anggaran untuk merekrut karyawan baru. Bos saya ingin menyelidiki dan mendeteksi karyawan yang paling mungkin untuk berhenti, sehingga manajemen dapat membujuk orang tersebut agar tetap di perusahaan sebelum karyawan tersebut berhenti.

Dataset: https://www.kaggle.com/datasets/patelprashant/employee-attrition?resource=download

Tujuan utama project ini mengembangkan model klasifikasi untuk mengetahui pegawai yang kemungkinan besar akan berhenti dan juga mengetahui siapa dan faktor apa saja yang mempengaruhi pegawai untuk berhenti. Dalam `employee_attrition.ipnb` terdapat proses Exploratory Data Analysis dan Data Modeling. 

EDA:
* employee dengan usia 20an dan 30an lebih banyak resign
* bagi employee dengan kelompok usia antara 20 dan 30, kerja lembur merupakan salah satu faktor yang mempengaruhi mereka untuk resign
* Lama pegawai bekerja dalam perusahaan dan kerja lembur tidak mempengaruhi promosi jabatan
* pegawai dengan job level dan gaji rendah cenderung untuk resign 
* Pegawai yang resign kebanyakan dari pegawai dengan posisi baru (beberpa bulan dan 2 tahun) diposisi tersebut.
* Pegawai resign terbanyak dari departement Research & Development.

Model dengan nilai recall tertinggi yaitu model random forest dengan undersampling yang mempunyai recall 0.76 dan akurasi 0,72
