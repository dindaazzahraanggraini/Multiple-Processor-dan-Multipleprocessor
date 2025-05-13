# Multiple Processor dan Multipleprocessor Symmetric

![multiple procesor dan multiprosesor symmetric drawio (1)](https://github.com/user-attachments/assets/19293777-ed63-4b1e-9164-d326f41f696a)

* Gambar sebelah kiri (multiple processor) menunjukkan arsitektur multiple processor yang mendukung pemrosesan paralel, dimana setiap CPU bisa bekerja mandiri maupun kolaboratif, dengan akses ke memori pribadi dan bersama. Sistem ini meningkatkan performa, terutama pada tugas-tugas komputasi berat dan multitasking.

* Gambar di sebelah kanan (multiprocessor symmetric) menunjukkan bahwa dalam multiprosesor symmetric, beberapa prosesor dapat bekerja secara paralel dan seimbang, karena semua berbagi memori dari sumber data yang sama, sehingga sistem lebih efisien untuk pemrosesan multitugas dan komputasi berat.

### Pengertian Multiple Processor
Multiple processor adalah arsitektur komputer dimana dua atau lebih processor berbagi satu memori utama dan perangkat input/output, dan bekerja secara paralel.

### Jenis-jenis Multiple Processor
* Multiprocessor Symmetric: arsitektur komputer dimana semua prosesor memiliki hak yang sama dalam mengakses memori, perangkat I/O, dan menjalankan tugas dari sistem operasi. Semua processor berbagi sistem operasi yang sama dan dapat menjalankan proses atau thread apapun secara independen.
* Multiprocessor Asymmetric: arsitektur dimana satu processor bertindak sebagai master dan mengontrol sistem, sedangkan processor lain (slave) hanya menjalankan tugas-tugas tertentu yang ditetapkan oleh master.

### Kesimpulan
Multiple processor adalah sistem komputer yang menggunakan lebih dari satu processor untuk mempercepat kerja dan meningkatkan efisiensi. Terdapat dua jenis utama, yaitu multiprocessor symmetric dan multiprocessor asymmetric. Pada multiprocessor symmetric, semua processor memiliki peran yang sama dan bekerja bersama dalam satu sistem operasi, sehingga cocok untuk komputer modern dan server. Sedangkan multiprocessor asymmetric, satu processor menjadi pusat pengendali (master), dan processor lainnya hanya menjalankan tugas tertentu, biasanya diguanakan pada sistem sederhana seperti perangkat elektronik atau mesin industri. Pemilihan jenisnya tergantung pada kebutuhan sistem, apakah butuh kinerja tinggi atau cukup dengan sistem yang lebih sederhana.

### Source/Sumber
* https://www.tutorialspoint.com/operating_system/os_multiprocessing.htm
* https://www.geeksforgeeks.org/symmetric-vs-asymmetric-multiprocessing/
* https://www.studytonight.com/operating-system/multiprocessing.php
* https://www.intel.com/content/www/us/en/developer/topic-technology/multi-core/overview.html
