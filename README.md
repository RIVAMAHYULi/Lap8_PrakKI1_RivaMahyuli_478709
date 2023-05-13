# Lap8_PrakKI1_RivaMahyuli_478709

1. CRAFTING
Teknik Crafting UDP dan TCP Packet dengan HPING3
Perintah hping3 -c 3 192.168.246.119 adalah perintah untuk mengirimkan 3 paket ping ke alamat IP PC yang ditentukan menggunakan alat hping3. Paket ping ini berguna untuk menguji konektivitas jaringan antara host yang mengirim paket dengan host yang dituju.

Dalam hal ini, hping3 mengirimkan 3 paket ping ke alamat IP PC di Windows yang ditentukan. Jika paket ping berhasil terkirim dan diterima oleh alamat IP yang dituju, maka akan ada respons dari alamat IP tersebut yang menunjukkan bahwa koneksi jaringan antara host yang mengirim paket dan host yang dituju berfungsi dengan baik.

Pada pratikum terdapat 3 packet transmitted

Perintah hping3 --scan 1-3000 adalah perintah untuk melakukan scan port pada semua port yang tersedia dari nomor port 1 hingga nomor port 3000 menggunakan alat hping3. Dengan menggunakan perintah ini, kita dapat mendapatkan informasi tentang status port pada alamat IP atau host yang dituju, yaitu apakah port tersebut terbuka, tertutup, atau difilter oleh firewall atau alat keamanan lainnya.

Perbedaan utama antara hping3 pada protokol TCP dan UDP adalah cara mereka mengirimkan dan menerima data.

Pada protokol TCP, hping3 mengirimkan paket dengan menggunakan tiga langkah handshake untuk memastikan bahwa koneksi antara host yang mengirim paket dan host yang menerima paket telah terbentuk dengan benar. Langkah-langkah tersebut meliputi SYN (synchronize), SYN-ACK (synchronize-acknowledgement), dan ACK (acknowledge). Setelah koneksi terbentuk, data kemudian dapat dikirimkan dan diterima dalam bentuk stream data.

Sementara itu, pada protokol UDP, hping3 mengirimkan paket tanpa membangun koneksi terlebih dahulu seperti pada protokol TCP. Data yang dikirimkan melalui protokol UDP juga tidak dijamin akan sampai ke tujuan, karena tidak ada mekanisme pengiriman ulang (retransmission) pada protokol ini. Hal ini membuat protokol UDP lebih cepat, namun kurang dapat diandalkan dibandingkan dengan protokol TCP.

Dalam pengujian penetrasi jaringan, perbedaan antara protokol TCP dan UDP pada hping3 memungkinkan pengujian untuk menguji beberapa aspek koneksi jaringan seperti kecepatan, keandalan, dan stabilitas. Keduanya juga dapat digunakan untuk menguji ketersediaan layanan dan kerentanan pada aplikasi jaringan tertentu yang berjalan pada protokol TCP atau UDP.

2. DNS RECON
DNS Recon atau DNS reconnaissance adalah teknik pengumpulan informasi dalam pengujian keamanan jaringan yang bertujuan untuk mengumpulkan informasi tentang domain dan sistem yang terkait dengan domain tersebut melalui pemanfaatan protokol DNS (Domain Name System).

DNS Recon bertujuan untuk mengidentifikasi informasi seperti alamat IP yang terkait dengan sebuah domain, hostname, subdomain, dan juga informasi lain seperti MX record (Mail Exchange) yang terkait dengan domain. Teknik DNS Recon dapat digunakan sebagai tahap awal dalam pengujian penetrasi jaringan, sehingga memudahkan tester dalam memahami arsitektur dan topologi jaringan yang akan diuji.
