# E-commerce statistical analysis

***Permasalahan*** : ```Mengetahui kondisi sales & operational di Toko Online The Look```

Berdasarkan hasil pengamatan data dan kekhawatiran dari CEO, maka focus dari persoalan biasanya datang dari ***keluhan customer*** (complain, warranty, waktu, dll). Pada case in, tools 8 Waste DOWN TIME akan digunakan (instead of 5W 1H) untuk menjabarkan possible cause persoalan. ***DOWN TIME*** sendiri element-nya adalah,<br>

1. Defect (berapa byk barang yg defect dan return? berapa kerugiannya? apakah signifikan atau tidak?)
2. Overproduction (berapa banyak supply product bagi customer? apa saja product-nya)
3. Waiting (berapa lama rentan waktu yang dibutuhkan untuk setiap proses?)
4. Unused Talent/customer (seperti apa demografi dari pembeli? melalui apa pembeli akses produk toko?)
5. Transportation (dimana saja lokasi distribution center dan negara pembeli?)
6. Inventory (apakah semua inventory terkirim sampai deliver done kepada customer?)
7. Motion (unproductive distribution center?)
8. dan Extraprocessing (too much to give)<br>

Dari breakdown tersebut, maka problem paling relefan vs ketersediaan dataset (BigQuery) salah satunya adalah data return product, date, number of item, sales proces per item, cost of delivery, product category, all data related to buyers/users (age, gender, negara, trafic resource), lokasi distribusi center, proses dari business (status) dll.

---

## Deployment Link

See more my depployment app [here](https://handoko-pramulyo-ftds-014-p0m1.herokuapp.com)