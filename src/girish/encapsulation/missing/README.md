# Missing Encapsulation

Smell ini mempunyai 2 kondisi :

- Ketika client terikat dengan suatu service yang memiliki variasi (Contoh client.getServiceA() atau client.getServiceB()). Maka ketika variasi tersebut bertambah (contoh terdapat service C) maka akan berbahaya oleh client karna bisa saja kita perlu mengganti codingan client.
- Untuk menambah satu fitur maka ditambahkan banyak class (kasus ini mirip dengan **Parallel Inheritance Hierarcies**)
