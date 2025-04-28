## Nama: Muhammad Naufal Zaki
## Kelas: SKU2B

![Symmetric Multiprocessing drawio](https://github.com/user-attachments/assets/cb9eac92-b6f4-4350-803c-2eecb0595af2)

- Sisi kiri
  
Multiple Processor Architecture yang menerapkan model Master-Slave Multiprocessing. Dalam model ini, terdapat satu Master Processor yang bertugas mengatur dan mendistribusikan tugas ke beberapa Slave Processor. Setiap Slave Processor memiliki memori sendiri dan semua unit terhubung melalui System Bus yang juga mengakses perangkat I/O. Model ini memiliki karakteristik terpusat, di mana kontrol penuh ada pada Master Processor. Meskipun implementasinya sederhana, arsitektur ini berisiko mengalami bottleneck karena semua perintah dan data harus melalui Master, sehingga performanya sangat bergantung pada kinerja Master tersebut. Model ini banyak ditemukan pada superkomputer lama dan beberapa sistem server awal.

- Sisi kanan

Di sisi kanan, diperlihatkan arsitektur Multiprocessor Architecture dengan pendekatan Symmetric Multiprocessing (SMP). Dalam model ini, semua CPU memiliki kedudukan yang setara tanpa adanya Master. Setiap CPU dilengkapi dengan L1 Cache pribadi dan berkomunikasi dengan L2 Cache melalui System Bus. Selanjutnya, sistem terhubung ke System Controller yang mengatur akses ke Main Memory dan perangkat I/O. Arsitektur ini mendukung distribusi beban kerja secara merata karena semua CPU dapat mengambil alih tugas apa pun sesuai kebutuhan. Dengan load balancing yang baik, SMP cocok untuk sistem server modern, komputer multi-core, dan aplikasi yang membutuhkan pemrosesan paralel yang intensif. Meskipun kompleksitasnya lebih tinggi dibanding Master-Slave, SMP menawarkan skalabilitas dan kinerja yang jauh lebih baik.

