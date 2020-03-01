## Prediksi Bencana Alam LANDSLIDE dengan Deep Learning dan Gambar Satellite
### Quick outline of files:

Landslide_detection_main.py melatih jaringan pada CNN dan melakukan sebagian besar pekerjaan lainnya, menggunakan create_dataset.py untuk membuat dataset dari gambar dalam folder yang disebut 'earth_engine_good'.

Accuracy_plotter.py membuat plot akurasi selama pelatihan berdasarkan file teks dalam folder hasil (salin disisipkan dari apa yang dicetak file python).

image_download_script.js dapat disisipkan langsung ke https://code.earthengine.google.com konsol dan Anda hanya perlu memasukkan koordinat gempa ke dalam cropping_coordinates.py untuk mendapatkan kotak pembatas.

N.B .: Untuk menjalankan kereta validasi silang pada nilai yang berbeda untuk eval_sessions
Ubah variabel dari [i untuk i dalam rentang (0,4)] ke [i untuk i dalam kisaran (4,8)] dan seterusnya untuk 8,12 -> 12,16-> 16,20

