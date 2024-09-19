## Langka 1
- buat Layer baru
- pertama masukan data (**Add Data**) modis berformat **csv**
- selanjutnya **klik kanan** pada file modis csv tadi yang berada pada layer arcgis
- lalu pilih **Display XY Data...**
- kemudian tentukan tipe **Coordinat System** dengan cara pilih edit lalu pilih **WGS 1984** untuk **coordinat system**
- tekan oke
- lalu nama file csv tadi dibelakangnya bertambah nama berupa tulisan Events

## Langkah 2
- lalu klik kanan pada csv **Events**
- kemudian pilih **Data** dan pilih **Export Data..**
- lakukan **save data** menajdi file dgn eksetensi .shp (agar berubah menjadi format map dan dapat dilakukan seleksi)

## Langkah 3
- siapkan data **map boundries** (batas wilayah) dari sebuah wilayah yg dijadikan sebagai map selection untuk mengambil koordinat (lat dan long) dari csv Events
- silakan mendownload batas wilayah kalimantan tengah di link berikut yg berkekstensi .shp (https://gisdata.mapog.com/indonesia/Province%20level%201/Central%20Kalimantan)
- masukan batas wilayah berkestensi .shp tadi ke dalam aplikasi arcgis dgn cara **Add Data**
- setelah dimasukan kemudian **klik kanan** pada file map boundries tadi
- lalu pilih **Open Attribute Table**
- kemudia klik atau seleksi row wilayah yg akan di seleksi yakni kalimantan tengah

## Langkah 4
- setelah itu tambahkan data yang telah disimpan pada Langkah 2 ke dalam layer

## Langkah 5
- selanjutnya arahakan kursor ke menu **Selection** pada bagian top bar
- lalu pilih **Selection By Location**
- kemudian checklist file pada Langkah 2 tadi sebagai Target Layers dan sebelumnya pilih "select featuress from" sebagai aksi yang dilakukan terhadap target layers
- kemudia checkllist "only show selectables layer in this list"
- selanjutnya jadikan map boundries pada langkah 3 tadi sebagai **Source Layers** yg digunakan untuk batasan seleksi data
- kemudian **checklist use selected features**
- lalu pilih intersect **the source layer feature** pada bagian spatial selection method for...
- langkah terakh klik Apply lalu OK





