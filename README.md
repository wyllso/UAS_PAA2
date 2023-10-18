# UAS_PAA2
# Analisis Buble Sort Dan Insertion Sort
a. Worst Case:

Bubble Sort: Pada kondisi terburuk, yaitu ketika daftar tidak terurut dan memerlukan pertukaran elemen secara berulang, Bubble Sort memiliki kompleksitas waktu O(n^2), di mana n adalah jumlah elemen dalam daftar.
Insertion Sort: Pada kondisi terburuk, yaitu ketika daftar tidak terurut dan setiap elemen harus dimasukkan ke posisi yang benar, Insertion Sort juga memiliki kompleksitas waktu O(n^2).

b. Best Case:

Bubble Sort: Pada kondisi terbaik, yaitu ketika daftar sudah terurut secara menaik, Bubble Sort memiliki kompleksitas waktu O(n), karena tidak perlu dilakukan pertukaran elemen.
Insertion Sort: Pada kondisi terbaik, yaitu ketika daftar sudah terurut secara menaik, Insertion Sort memiliki kompleksitas waktu O(n), karena tidak perlu dilakukan pergeseran elemen.

c. Average Case:

Bubble Sort: Pada kasus rata-rata, Bubble Sort memiliki kompleksitas waktu O(n^2), karena rata-rata memerlukan pertukaran elemen sebanyak (n^2)/2 kali.
Insertion Sort: Pada kasus rata-rata, Insertion Sort memiliki kompleksitas waktu O(n^2), karena rata-rata memerlukan pergeseran elemen sebanyak (n^2)/4 kali.


# Analisis algoritma untuk evaluasi perhitungan Shortest Path menggunakan TSP (Travelling Salesman Problem) dan Dijkstra:

a. Worst Case:

TSP: Dalam worst case, ketika semua node terhubung dan harus mencari rute terpendek yang melalui semua node, TSP memiliki kompleksitas waktu yang tinggi. Pada TSP dengan n node, kompleksitas waktu dapat mencapai O(n!), yang sangat mahal dan tidak efisien.
Dijkstra: Dalam worst case, ketika semua node terhubung dan harus mencari rute terpendek dari satu node ke semua node lainnya, Dijkstra memiliki kompleksitas waktu O((V + E) log V), di mana V adalah jumlah node dan E adalah jumlah edge. Kompleksitas ini muncul karena Dijkstra menggunakan struktur data heap untuk mencari node dengan jarak terpendek.

b. Best Case:

TSP: Dalam best case, jika ada hubungan langsung antara dua node dan tidak ada simpul tambahan yang harus dikunjungi, TSP memiliki kompleksitas waktu O(1), karena hanya memerlukan satu rute.
Dijkstra: Dalam best case, jika simpul tujuan terhubung secara langsung dengan simpul awal dan tidak ada simpul tambahan yang harus dikunjungi, Dijkstra memiliki kompleksitas waktu O(1), karena hanya memerlukan satu jalur terpendek.

c. Average Case:

TSP: TSP tidak memiliki kasus rata-rata yang jelas, karena kompleksitasnya tergantung pada banyak faktor, termasuk jumlah simpul, topologi graf, dan bobot edge. Namun, secara umum, TSP memiliki kompleksitas waktu yang tinggi dan rumit, dengan kompleksitas rata-rata yang diperkirakan sekitar O(n^2 2^n).

Dijkstra: Dalam kasus rata-rata, kompleksitas waktu Dijkstra adalah O((V + E) log V), di mana V adalah jumlah node dan E adalah jumlah edge. Namun, pada graf dengan bobot non-negatif, Dijkstra dapat mencapai kompleksitas waktu O(V^2), karena pencarian jalur terpendek dapat dilakukan langsung tanpa menggunakan heap.
 
# Kelas B
