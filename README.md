TUGAS SISTEM OPERASI
Nama Kelompok	: Thomas Dalton  –  203400001
                Yulius Dani Eko – 203400012
Prodi			: Teknik informatika

Chapter 5.42
The decrease count() function in the previous exercise currently returns 0 if sufﬁcient resources are available and −1 otherwise. This leads to awkward programming for a process that wishes to obtain a number of resources:
while (decrease count(count) == -1) ;
Rewrite the resource-manager code segment using a monitor and condition variables so that the decrease count() function suspends
the process until sufﬁcient resources are available. This will allow a process to invoke decrease count() by simplycalling
decrease count(count);
The process will return from this function call only when sufﬁcient resources are available.

Soal dan jawaban 
1.	Untuk apakah tujuan program ini?
Tujuan program ini adalah sebagai bentuk komunikasi yang dilakukan oleh manusia terhadap mesin komputer untuk melaksanakan tugas tertentu atau memecahkan suatu masalah 
2.	Section berapa yang menjelaskan program ini?
Chapter 5.40 dan Chapter 5.41
3.	Jelaskan logika program ini?
Logika program ini count untuk menampilkan teks ke layar, printf() untuk menampilkan output,  %s adalah simbol untuk menampilkan nilai string, %d adalah simbol untuk menampilkan nilai angka atau bilangan decimal,  \n adalah simbol untuk membuat baris baru dan return untuk kembalikan nilai yang tersimpan di dalam variabel luas kepada kode yang akan memanggil function tersebut jika nanti dirun maka akan keluar //available resources = 5 pertama kali
4.	Apa guna source code ini?
Kegunaan program ini untuk mengurangi pengulangan penulisan aktivitas yang berulangan atau sama. Program menjadi lebih terstuktur, sehingga gampang dipahami dan sanggup lebih dikembangkan. Fungsi-fungsi yang sudah kita kenal sebelumnya yakni fungsi cout() yang memiliki kiprah untuk menampilkan informasi atau data kelayar dan masih banyak lainnya.
