
# Assigment 1 - Searching Siswa By Id

Repository ini berisi tugas untuk project search siswa berdasarkan id.

Dimana data yang telah disediakan seperti dibawah ini:

```
{
		No:           1,
		Nama:         "Fajri Muhammad Tio",
		Alamat:       "Jl. Merdeka No. 1",
		Pekerjaan:    "Mahasiswa",
		AlasanGolang: "Ingin belajar bahasa pemrograman baru yang powerful",
	},
	{
		No:           2,
		Nama:         "Hikma Nelda",
		Alamat:       "Jl. Merdeka No. 2",
		Pekerjaan:    "Tidak Bekerja",
		AlasanGolang: "Katanya over power untuk backend",
	},
	{
		No:           3,
		Nama:         "Kemku",
		Alamat:       "Jl. Merdeka No. 3",
		Pekerjaan:    "Freelance",
		AlasanGolang: "Iseng aja sih pengen nyoba hal baru aja sih",
	},
	{
		No:           4,
		Nama:         "Asuna",
		Alamat:       "Jl. Merdeka No. 5",
		Pekerjaan:    "Freelance",
		AlasanGolang: "Iseng aja sih pengen nyoba hal baru aja sih",
	},
	{
		No:           5,
		Nama:         "Kirigaya Kazuto",
		Alamat:       "Jl. Merdeka No. 4",
		Pekerjaan:    "Freelance",
		AlasanGolang: "Iseng aja sih pengen nyoba hal baru aja sih",
	},
```

Cara Penggunaan:

misalkan user menjalankan command di bawah ini

```
go run main.go 1
```

akan menampilkan data siswa dengan id 1:

```
No:           1,
Nama:         "Fajri Muhammad Tio",
Alamat:       "Jl. Merdeka No. 1",
Pekerjaan:    "Mahasiswa",
AlasanGolang: "Ingin belajar bahasa pemrograman baru yang powerful"
```

jika id yang diinputkan tidak terdapat pada data di atas, seperti:

```
go run main.go 7
```

maka akan menampilkan pesan

```
Data dengan no absen 8 tidak ditemukan
```

dan jika user tidak menginputkan id siswa,

```
go run main.go
```

akan menampilkan pesan:
```
Silahkan masukkan id absen siswa
```

@Fajri Muhammad Tio - hikio-17

