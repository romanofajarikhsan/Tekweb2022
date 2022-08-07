
a.Menampilkan data user

GET: /users
respon:
[
    {
        "id": "",
        "nama": "",
        "motto": "",
        "ig": "",
        "fb": "",
        "yt": "",
    },
]


b. Menampilkan user dengan ID

GET: /users/[id]
repon:
{
        "nama": "",
        "motto": "",
        "ig": "",
        "fb": "",
        "yt": "",
}


c. Menambahkan data user Secara oomatis

POST: /user
data:
{
        "nama": "",
        "motto": "",
        "ig": "",
        "fb": "",
        "yt": "",
}

respon:
true    // jika sukses
false   // jika salah


d. Mengedit data user dengan ID

PUT: /user/[id]
data:
{
        "nama": "",
        "motto": "",
        "ig": "",
        "fb": "",
        "yt": "",
}

respon:
true    // jika sukses
false   // jika salah



e. Menghapus data user dengan ID

DELETE: /user/[id]
respon:
true    // jika sukses
false   // jika salah
