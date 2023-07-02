# Deficient Encapsulation

Smell ini terjadi ketika ada satu atau beberapa member class terlalu permissive dari yang seharusnya diperlukan. Contoh, ketika terdapat class yang seharusnya diberkan private, tetapi kita memberikan attribute tersebut public maka code tersebut dinamakan Deficient Abstraction.

### Penyebab Smell

- **Easier testability** developer ingin melakukan testing dengan gampang terkait variable (biasa dijadikan public semua agar mudah di akses)
- **Procedural thinking in object oriented context** developer masih berpikir prosedural sehingga mengexpose variable menjadi global variable
- **Quick-fix solutions**
