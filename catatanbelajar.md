let, const, dan var adalah kata kunci yang digunakan untuk mendeklarasikan variabel di javascript. Variabel adalah tempat untuk menyimpan data atau informasi yang dapat digunakan dalam program

pemahaman tentang VAR
var adalah cara lama untuk mendeklarasikan variabel sebelum ES6 (versi baru javascript) diperkenalkan. var memiliki cakupan global atau fungsi, artinya variabel yang dideklarasikan dengan var dapat diakses dan diubah di mana saja dalam program. var juga memiliki sifat hoisting, yaitu variabel yang dideklarasikan dengan var akan dinaikkan ke bagian atas ruang lingkupnya, sehingga dapat menyebabkan kesalahan atau kebingungan. var dapat dideklarasikan ulang dengan nama yang sama tanpa error. Contoh penggunaan var

*Untuk contoh percobaan var bisa di cek di @Folder/belajar/4-pengguanan-var.html*

let adalah cara baru untuk mendeklarasikan variabel yang diperkenalkan di ES6. let memiliki cakupan blok, artinya variabel yang dideklarasikan dengan let hanya dapat diakses dan diubah dalam blok kode tempat ia dideklarasikan. Blok kode adalah bagian dari program yang dibatasi oleh kurung kurawal {}. let tidak memiliki sifat hoisting, yaitu variabel yang dideklarasikan dengan let tidak akan dinaikkan ke bagian atas ruang lingkupnya, sehingga dapat mencegah kesalahan atau kebingungan. let tidak dapat dideklarasikan ulang dengan nama yang sama dalam ruang lingkup yang sama, akan menyebabkan error. Contoh penggunaan let:

*@Folder/belajar/5-pengguanan-let.html*

Const bersifat lokal dan tetap (immutable), artinya variabel yang dideklarasikan dengan const hanya dapat diakses dalam lingkup tertentu dan tidak dapat diubah nilainya. Const juga tidak memiliki sifat hoisting, yaitu variabel yang dideklarasikan dengan const harus dideklarasikan terlebih dahulu sebelum digunakan. Const juga tidak dapat dideklarasikan ulang dengan nama yang sama dalam lingkup yang sama, karena akan menimbulkan error. Const biasa digunakan untuk menyimpan nilai yang konstan, seperti konstanta matematika, alamat URL, atau konfigurasi. Contoh:

*@Folder/belajar/6-pengguanan-const.html*
