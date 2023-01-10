# -LT-16_Undefined

`Undefined` adalah nilai yang diberikan kepada variabel di JavaScript jika variabel tersebut tidak memiliki nilai apa pun. Ini juga merupakan tipe data di JavaScript. Jika Anda mencoba mengakses properti dari objek yang tidak ada atau mencoba menggunakan variabel yang tidak dideklarasikan, maka akan menghasilkan nilai `undefined`. Misalnya:

    let x;
    console.log(x); // Output: undefined

    const y = {};
    console.log(y.prop); // Output: undefined

    const z;
    console.log(z); // Output: Uncaught SyntaxError: Missing initializer in const declaration

Pada contoh di atas, variabel `x` tidak memiliki nilai apa pun, sehingga saat kita coba untuk menampilkan nilainya, maka akan menghasilkan `undefined`. Kita juga mencoba untuk mengakses properti `prop` dari objek `y`, tetapi objek `y` tidak memiliki properti tersebut, sehingga saat kita coba untuk menampilkan nilainya, maka akan menghasilkan "undefined". Dan pada variabel `z`, kita tidak memberikan nilai apa pun saat mendeklarasikannya, sehingga akan menghasilkan error.

jadi `undefined` adalah nilai yang diberikan kepada variabel di JavaScript jika variabel tersebut tidak memiliki nilai apa pun. Ini juga merupakan tipe data di JavaScript. Anda dapat mengecek apakah suatu variabel bernilai `undefined` dengan menggunakan operator pembandingan `===` atau `!==`. Misalnya:

    let x;
    if (x === undefined) {
      console.log('x is undefined');
    }

    if (x !== undefined) {
      console.log('x is defined');
    }

Anda juga dapat menggunakan fungsi `typeof` untuk mengecek tipe data dari suatu variabel. Jika variabel bernilai `undefined`, maka fungsi `typeof` akan mengembalikan string `undefined`. Misalnya:

    let x;
    console.log(typeof x); // Output: undefined




