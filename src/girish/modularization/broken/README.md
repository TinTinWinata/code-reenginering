# Broken Modularization

Smell ini terdapat 2 kondisi yaitu : 
- Class hanya memegang data saja tanpa operasi apapun (mirip dengan **data class** martin fowler)
- Metode dalam class lebih suka memakai data / fungsi dari class lain (mirip dengan **Feature envy** martin fowler)

# Penyebab Smell

**Lack of knowledge of existing design** developer yang baru memasuki perusahaan biasanya mendapatkan codingan yang sudah complex, sehingga developer tersebut hanya melihat bagian kecil dari code tersebut tanpa melihat dari design codingan yang dibuat.