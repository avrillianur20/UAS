# UAS
## Nama  : Avrillia Nur Hidayah
## NIM   : 312210309
## Kelas : TI.22.A3
### Package dan module

![Screenshot (718)](https://user-images.githubusercontent.com/115686359/210766307-7c0963ba-ea6b-4a3c-8e6c-36b0a571366c.png)

Sudah dibuat Package dan Module seperti diatas

![Screenshot (705)](https://user-images.githubusercontent.com/115686359/210766516-ec0a6c72-4384-4cc1-ac3a-e1c6393f7aa9.png)

```daftar_nilai.py``` Berisi Modul Untuk:

*tambah_data

*ubah_data

*hapus_data

*cari_data

```view_nilai.py``` Berisi Modul Untuk:

*cetak_daftar_nilai

*cetak_hasil_pencarian

```input_nilai.py``` Berisi Modul Untuk:

*input_data(yang meminta pengguna masukkan data)

``main.py``` Berisi Program Utama

*Memanggil semua menu yang yang ada

1. Kemudian saya tlah menyamtukan syntax yang nanti akan menghasilkan semua modul dari ```daftar_nilai``` yang diantaranya adalah (tambah data,ubah data,lihat data,hapus data,dan cari data)

```

from view.input_nilai import *
data={}
class daftarnilai():
    def tambah_data(self):
        tambah_nama = nama()
        tambah_nim = nim()
        tambah_tugas = tugas()
        tambah_uts = uts()
        tambah_uas = uas()
        tambah_akhir = akhir()
        data[tambah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir

    def ubah_data(self):
        ubah_nama = nama()
        if ubah_nama in data.keys():
           
            tambah_nim = nim()
            tambah_tugas = tugas()
            tambah_uts = uts()
            tambah_uas = uas()
            tambah_akhir = akhir()
            data[ubah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir
        else:
            print('data tidak ditemukan !!!')

    def hapus_data(self):
        hapus_nama = nama()
        if hapus_nama in data.keys():
            del data[hapus_nama]
            print('data berhasil di hapus')
        else:
            print('data tidak ditemukan !!!')

    def keluar(self):
    
```     

### Output Tambah_data:

![Screenshot (706)](https://user-images.githubusercontent.com/115686359/210776507-a2474e79-a293-4c78-a662-166614c8d320.png)

### Output Daftar_nilai:

![Screenshot (707)](https://user-images.githubusercontent.com/115686359/210777076-24c583e9-5e0a-46b9-98f7-b88555ae1aaa.png)

### Output Ubah_data:

![Screenshot (708)](https://user-images.githubusercontent.com/115686359/210777388-5d29d18b-c37f-41f8-ac47-0636d7a374fa.png)

### Output Cari_data:

![Screenshot (709)](https://user-images.githubusercontent.com/115686359/210777567-e21e00f0-4457-4d7d-ab64-2922054bb941.png)

### Output Hapus_data:

![Screenshot (710)](https://user-images.githubusercontent.com/115686359/210777699-a356b089-4086-4ac3-82db-74a8024e8465.png)

## Done!
