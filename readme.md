### Tugas Softdev
membuat todolist api menggunakan express js
menggunakan database mysql


Untuk mengambil data dengan method GET
http://localhost:4000/

response :
```
{
    activitas: [
        {
            id:1,
            activity:"belajar html"
        }
    ]
}
```

untuk menambah data dengan method POST
http://localhost:4000/tambah

key yang diperlukan :
```
activity : value
```

response :
```
{
    message: "Data berhasil ditambahkan"
}
```

untuk menambah data dengan method PUT
http://localhost:4000/edit/:id

key yang diperlukan :
```
activity : value
```

response :
```
{
    message: "Data berhasil diperbarui"
}
```

untuk menghapus data dengan method DELETE
http://localhost:4000/delete/:id

response :
```
{
    message: "Data berhasil dihapus"
}
```
