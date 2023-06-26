# FINALPROJECTPAA2
Putri Innayah F55121045

ALGORITMA BUBBLE SORT DAN INSERTION SORT

A. BUBBLE SORT

Best case: Best case pada bubble sort terjadi ketika data yang diurutkan sudah dalam urutan yang benar atau hampir benar sebelum pengurutan dilakukan. Dalam kondisi ini, algoritma bubble sort hanya perlu melakukan sedikit atau tanpa pertukaran elemen. Jumlah perbandingan yang dibutuhkan adalah O(n), di mana n adalah jumlah elemen yang diurutkan. Namun, meskipun best case terjadi, bubble sort tetap memiliki kompleksitas waktu O(n^2) karena tetap memerlukan perulangan ganda untuk memastikan bahwa semua elemen telah terurut.

Worst case: Worst case pada bubble sort terjadi ketika data yang diurutkan berada dalam urutan terbalik atau dalam urutan yang terbalik secara terbalik. Dalam kondisi ini, algoritma bubble sort harus membandingkan dan menukar setiap pasangan elemen secara berulang hingga data terurut. Jumlah perbandingan yang dibutuhkan adalah O(n^2), dan jumlah pertukaran elemen juga sama dengan O(n^2). Dengan demikian, kompleksitas waktu worst case dari bubble sort adalah O(n^2).

Average case: Average case pada bubble sort mengacu pada kinerja algoritma ketika data yang diurutkan tidak terlalu berurutan atau terlalu terbalik. Dalam kasus rata-rata, bubble sort masih memerlukan jumlah perbandingan dan pertukaran yang sama dengan worst case, yaitu O(n^2).

B. INSERTION SORT

Best case: Best case pada insertion sort terjadi ketika data yang diurutkan sudah dalam urutan yang benar atau hampir benar sebelum pengurutan dilakukan. Dalam kondisi ini, algoritma insertion sort hanya perlu memeriksa sedikit atau tanpa perbandingan dan pertukaran elemen. Jumlah perbandingan yang dibutuhkan adalah O(n), di mana n adalah jumlah elemen yang diurutkan. Jumlah pertukaran elemen juga sama dengan O(1), yaitu tidak ada pertukaran yang dilakukan. Oleh karena itu, dalam best case, kompleksitas waktu insertion sort adalah O(n).

Worst case: Worst case pada insertion sort terjadi ketika data yang diurutkan berada dalam urutan terbalik secara terbalik. Dalam kondisi ini, algoritma insertion sort harus membandingkan dan memindahkan setiap elemen yang belum terurut ke posisi yang benar dalam bagian terurut. Jumlah perbandingan yang dibutuhkan adalah O(n^2), dan jumlah pertukaran elemen juga sama dengan O(n^2). Oleh karena itu, kompleksitas waktu worst case dari insertion sort adalah O(n^2).

Average case: Average case pada insertion sort mengacu pada kinerja algoritma ketika data yang diurutkan tidak terlalu berurutan atau terlalu terbalik. Dalam kasus rata-rata, insertion sort memiliki kompleksitas waktu yang lebih baik daripada worst case, namun masih memiliki kompleksitas waktu O(n^2) karena masih memerlukan perbandingan dan pertukaran elemen dalam jumlah yang signifikan.


ALGORITMA TSP DAN DJIKSTRA

A. TSP

Best case: Best case pada algoritma TSP terjadi ketika graf yang merepresentasikan kota-kota memiliki struktur yang sangat teratur, seperti graf yang membentuk lintasan spiral atau linear. Dalam kasus ini, algoritma TSP dapat menemukan solusi optimal dengan cepat karena hanya memerlukan sedikit perbandingan dan perhitungan. 

Worst case: Worst case pada algoritma TSP terjadi ketika graf yang merepresentasikan kota-kota memiliki struktur yang sangat kompleks dan tidak beraturan, seperti graf penuh atau graf dengan banyak siklus dan hubungan yang rumit antara kota-kota. Dalam kasus ini, algoritma TSP akan membutuhkan waktu yang sangat lama untuk menemukan solusi optimal karena harus memeriksa semua kemungkinan perjalanan yang membutuhkan waktu eksponensial. Oleh karena itu, kompleksitas waktu dalam worst case pada algoritma TSP adalah O(n!), di mana n adalah jumlah kota yang harus dikunjungi.

Average case: Average case pada algoritma TSP mengacu pada kinerja algoritma ketika graf yang merepresentasikan kota-kota memiliki struktur yang acak atau hampir acak. Dalam kasus rata-rata, algoritma TSP cenderung memiliki kompleksitas waktu yang tinggi karena harus mengeksplorasi banyak kemungkinan perjalanan. Kompleksitas waktu dalam kasus rata-rata pada algoritma TSP dapat bervariasi tergantung pada teknik atau algoritma khusus yang digunakan untuk memecahkan masalah tersebut, seperti algoritma Branch and Bound atau Dynamic Programming.

B. DJIKSTRA

Best case: Best case pada algoritma Dijkstra terjadi ketika simpul awal adalah simpul tujuan atau terhubung langsung dengan simpul tujuan. Dalam kasus ini, algoritma Dijkstra dapat menemukan jalur terpendek dengan cepat karena hanya perlu melakukan sedikit iterasi dan perbandingan. Kompleksitas waktu pada best case adalah O(1) atau konstan.

Worst case: Worst case pada algoritma Dijkstra terjadi ketika ada banyak simpul dan tepi dalam graf, dan tidak ada jalur langsung dari simpul awal ke simpul tujuan. Dalam kasus ini, algoritma Dijkstra harus memeriksa semua simpul dan tepi yang ada untuk mencari jalur terpendek. Kompleksitas waktu dalam worst case pada algoritma Dijkstra adalah O((V + E) log V), di mana V adalah jumlah simpul dan E adalah jumlah tepi dalam graf.

Average case: Average case pada algoritma Dijkstra mengacu pada kinerja algoritma ketika graf memiliki struktur yang acak atau hampir acak. Dalam kasus rata-rata, algoritma Dijkstra cenderung memiliki kompleksitas waktu yang tinggi karena harus mengeksplorasi banyak simpul dan tepi dalam graf. Kompleksitas waktu dalam kasus rata-rata pada algoritma Dijkstra dapat bervariasi tergantung pada ukuran dan kepadatan graf.
