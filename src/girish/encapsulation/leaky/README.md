# Leaky Encapsulation

Smell ini terjadi ketika terdapat suatu public modifier yang menyebarkan data private modifier, yang seharusnya tidak boleh disebarkan.

### Penyebab Smell

- **Lack of awareness of what should be "hidden"** developer yang kurang berpengalaman dan kurang berhati-hati dapat mengakibatkan data yang bocor.
- **Viscosity** karna tekanan projek atau deadline sehingga tidak memperhatikan deficient abstraction
- **Use of fine-grained interface** interface terlalu lengkap yang bisa melakukan banyak tujuan (get terlalu banyak data sehingga data bocor)
