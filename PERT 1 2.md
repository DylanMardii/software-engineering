# PERT 1-2
## Model Proses Perangkat Lunak

### Pendahuluan

> [!abstract] Definition
> Analisis sistem adalah melihat sistem dan menentukan bagian yang baik atau tidak, dan kemudian mendokumentasikan kebutuhan baru
> 

Teknik pengumpulan data dapat berupa 
+ Wawancara pihak
+ Observasi lingkungan dan sistem
+ Kuesioner

Jenis-jenis kebutuhan yang dapat adalah :
+ Development Requirement (SDK, IDE, Library, dsb)
+ Deployment Requirement (PC, Mobile phone, dsb)
+ Performance Requirement (scalability)
+ Documentation Requirement (manual)
+ Support Requirement (maintainence and training {tutorial})
+ Miscellaneous requirement (extras)

> [!info] Desain Sistem
> Adalah upaya membuat suatu sistem berdasarkan kebutuhan yang ada

### Model Proses Generik

Tindakan pekerjaan rekayasa perangkat lunak memiliki satu set tugas yang mengidentifikasikan tugas yang ada, capaian dan kualitas.

### SDLC 

SDLC (Software Development LifeCycle) adalah gambaran proses perangkat lunak. SDLC digunakan agar pengerjaan perangkat lunak agar pengembangannya jauh lebih efisien, karena mengerjakannya secara sistematis dan bersiklus

Tahapan SDLC adalah
+ Inisialisasi (pembuatan proposal)
+ Pengembangan konsep sistem (analisis mamfaat)
+ Perencanaan
+ Analisis kebutuhan (pengguna) atau REQUIREMENT
+ Desain atau DESIGN
+ Pengembangan atau CONSTRUCT atau CODING
+ Integrasi dan pengujian atau TESTING
+ Implementasi / IMPLEMENTASI
+ Pemeliharaan / MAINTAINENCE 

Model Model SDLC adalah
+ Tradisional
	+ Waterfall
	+ V 
	+ RAD 
	+ Incremental
+ Evolusioner
	+ Prototype
	+ Spiral
+ Unified
+ Agile
	+ XP
	+ SCRUM
	+ ASD
	+ DSDM
	+ FDD
	+ Crystal Light Methodology
	+ Pragmatic Programming
	+ Open Source Software Development

#### Waterfall

Dikemukakan oleh **Winston W Royce** dan dipopulerkan oleh **Ian Sommerville**. Step-stepnya adalah :
1. System Engineering
2. Analysis
3. Design
4. Code
5. Testing
6. Maintenance
>[!note]
>Hanya dapat lanjut ke step berikutnya jika step sebelumnya **benar benar lengkap**


Walau memang dimulai secara berurutan, feedback dari tiap step dapat mengulang siklus ini kembali


#### V Model

Berbeda dengan Waterfall. V model menekankan akan [[|Test Driven Development]] dalam 
+ Unit Testing
+ Component Testing
+ Systems Testing
+ Acceptance Testing
Hal tersebut menjadi feedback yang akan memperbaiki sistem waterfall
#### Incremental model

Versi waterfall yang diulang terus menerus selama projek berlangsung tiap software increment

#### RAD

Adalah versi waterfall dimana beberapa tim dapat mengerjakan bagian dari proyek secara bersamaan dengan sistem waterfall pada tiap timnya

#### Prototype Model

Model ini menggambarkan suatu suatu konsep perangkat lunak secara sederhana, kemudian diperdalam sesuai kebutuhan pengguna

#### Spiral

Pengembangan perangkat lunak besar yang kemungkinan terjadi kesalahannya lebih besar, merupakan modifikasi dari incremental model

#### Unified Process

Fase yang dapat memperbolehkan beberapa proses untuk dikerjakan secara bersamaan dan lebih cepat. Mirip dengan Spiral dan Incremental


#### Agile

Adalah metode yang lebih mudah beradaptasi dengan perubahan zaman yang cepat. Agile membutuhkan inovasi dan tanggung jawab yang baik dalam seluruh tim

## Proses Kegiatan

### Software Specification

Adalah proses REQUIREMENT ENGINEERING terhadap feasibilitas (seberapa realistis) terhadap suatu perangkat lunak. Gambaran umum akan diberikan ke pengguna dan developer akan mendapatkan spesifikasi yang rinci.

Fase fasenya adalah :
1. **Elisitasi**, yaitu proses pengumpulan [[#Pendahuluan|pengumpulan data]] untuk mendapatkan kebutuhan yang ada Contoh : Pergi ke lapangan untuk menganalisis bagaimana sistem dapat bekerja
2. **Spesifikasi**, yaitu kegiatan memproses data yang telah dikumpulkan untuk menjadi daftar kebutuhan 
3. **Validasi**, yaitu pemeriksaan atas konsistensi, realistisnya projek, dan kelengkapan persyaratan.

>[!note]
>Dalam metode agile Requirement Engineering adalah bagian dari *keseluruhan* akan pengembangan perangkat lunak

### Software Design & Implementation

4 proses dalam desain sistem informasi adalah :
1. Desain arsitektural (keseluruhan struktur dan komponen sistem)
2. Desain database (Representasi data)
3. Desain UI UX
4. Desain komponen (UML)

### Software Validation

Yaitu cara untuk menunjukkan bahwa suatu perangkat lunak sesuai dengan spesifikasi dan harapan pengguna. 

Validasi digunakan dengan menggunakan dataset simulasi, selain itu juga meninjau perangkat lunak agar sesuai dengan persyaratannya. 

Pengujuan adalah proses yang cukup lama dalam proses validasi, karena proses ini butuh pengujian dari bagian terkecil program. 

Fase testing software adalah :
1. **Component (Unit) Testing**. yaitu pengetesan suatu fungsi/kelas secara independen agar bekerja dengan semestinya
2. **System Testing**. yaitu proses pengetesan akan interaksi dari tiap komponen, apakah memenuhi persyaratan fungsional dan non fungsional, serta interaksinya dengan sistem
3. **Customer Testing** adalah pengetesan dengan dataset yang simulasi, agar dapat mememuhi kebutuhan pengguna dan dapat diterima dengan baik

### Software Evolution

Karena zaman sekarang, sedikit perangkat lunak yang orisinil, maka pengembangan perangkat lunak saat ini sifatnya adalah evolusi dimana perangkat lunak lama dimodifikasi agar memenuhi kebutuhan baru

## Mengatasi Perubahan

Perubahan sifatnya tidak dapat dipungkiri pada zaman sekarang, apalagi dengan kecepatan perkembangan teknologi sekarang. Oleh karena itu perangkat lunak harus dapat beradaptasi dengan perubahan yang ada.

Perubahan umumnya memerlukan perangkat lunak untuk dibuat ulang atau didesain ulang yang cukup boros sumber daya.

Ada 2 pendekatan untuk menghadapi ini dengan efisien

#### Prototype

>[!info]
>yaitu versi awal sistem yang digunakan untuk mendemonstrasikan bagaimana implementasinya sebagai suatu software

Bentuk ini lebih cepat dan murah sehingga mudah untuk bereksperimen

#### Incremental delivery

>[!info]
>Yaitu pendekatan pengembangan dimana peningkatan versi diberikan untuk beradaptasi dengan perubahan yang ada.

Tiap increment memberikan peningkatan fungsionalitas dari sebagian maupun seluruh sistem. Ada skala prioritas yang digunakan untuk menentukan apa yang akan diperbaharui tiap increment

## Peningkatan Proses

Pola pengembangan perangkat lunak dewasa ini banyak berputar pada increment, sehingga peningkatan proses menjadi suatu hal yang penting 

>[!abstract] Definisi
>Peningkatan proses adalah proses memahami dan mengubah proses untuk meningkatkan kualitas maupun efisiensi

Ada pendekatan kematangan dan Agile dalam memperbaiki suatu proses
+ **Kematangan Proses**, yang berfokus pada peningkatan proses yang menekankan akan kematangan suatu teknik dan manajemen praktik yang ada. (semua harus lengkap)
+ **Agile**, yaitu pengembangan iteratif yang mendeliver update dalam waktu yang cepat, dan biaya yang rendah (yang penting jadi)

Proses peningkatan suatu perangkat lunak adalah :
+ **Process Measurement**, yaitu proses mengukur atribut dari perangkat lunak dan menilai apakah peningkatan dan perbaikan sudah efektif
+ **Process Analysis**, yaitu menganalisa kelemahan dan hambatan, dan membandingkan dengan kecepatan dan ketahanan dari program baru
+ **Process Change** yaitu pengusulan untuk mengatasi kelemahan yang sudah diidentifikasi

5 Level peningkatan proses dalam suatu perangkat lunak adalah 
1. **Initial**, yaitu penetapan sasaran perbaikan
2. **Managed**, yaitu pengelolaan akan projek dan tujuannya
3. **Defined**, yaitu standarisasi organisasi dan penerapan prosesnya, apakah sudah memenuhi syarat atau tidak
4. **Quantitatively Managed**, yaitu pengukuran performa dari proses
5. **Optimizing**, yaitu menggunakan proses dan pengukuran untuk mendorong perbaikan yang lebih baik


