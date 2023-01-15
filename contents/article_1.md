# Analisis Sentimen Tweet Mixue

_Oleh Hahan Nur Rizky_

Nama : Hahan Nur Rizky Nim : 2000016038
Responsi Crawling data pada twitter

Mengambil data dari twitter menggunakan menggunakan snscrape lalu membuat function untuk memanggil data twiter

Function yang dibuat yaitu untuk menggambil username dan content tweet dari library snscrape lalu membuat data frame nya menggunakan pandas

lalu pada gambar diatas saya merubah data format dataframe tadi menjadi string agar dapat di tokenize dan di stemming, karna sebelum nya terdapat eror karna datatype ‘object’

dengan menggunakan library NLTK disini saya mencoba untuk mentokenize kan data yang sebelumnya terdapat dari dataframe yang telah dirubah menjadi string

setelah ditokenization pada gambar diatas saya menstemming menggunakan library sastrawi

setelah stemming, saya melakukan stop word removal dengan sama menggunakan library
NLTK dan memfilter tokens

’membuat function sentimental disini saya menaruh kata-kata positif seperti enak,terbaik,suka,keren,HAHAN,ganteng,manis,banyak,like untuk mendapatkan sentimen dari tweeet yang dibuat lalu memasukan kata-kata negatif nya seperti benci gaenak dll. function diatas saya dapatkan pada modul prak 10 textprocessing

membuat chart analisis nya menggunakan matplotlib yaitu dengan memasukan function res untuk mengklasifikasikan text dari data crawling yang sebelumnya dataframe menjadi string disini saya menginport library matplotlib

codingan diatas juga didaptkan dari modul prak 10 yaitu textprocessing

kesimpulan yang didapat dalam analisis sentimen tweet mengenai mixue yaitu mengarah ke netral karna pengembangan data yang saya pilih untuk memfilter kata positif dan negatif terlalu sedikit dan berbanding terbalik dengan 100 data yang telah saya ambil.
Sekian
Terima kasih
