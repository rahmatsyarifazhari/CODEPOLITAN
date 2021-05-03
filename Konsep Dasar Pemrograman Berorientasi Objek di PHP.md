## Pengenalan OOP
1. OOP atau Object-Oriented Programming membentuk...

	A. Struktur Data yang menyimpan prosedur dan fungsi

	**B. Struktur Data yang menyimpan nilai dan fungsi**

	C. Struktur Data yang menyimpan nilai dan variabel

	D. Struktur Data yang menyimpan rekursif dan script

	E. Struktur Data yang menyimpan fungsi dan variabel

2. Kita membutuhkan OOP pada saat...

	**A. Membuat situs kompleks**

	B. Membuat situs sederhana

	C. Membuat situs berbasis non database

	D. Membuat situs non objek

	E. Membuat situs simpel

3. Contoh properties dalam object yaitu, *kecuali*...

	A. Gaun berwarna putih

	**B. Ikan berenang di air**

	C. Siswa memiliki seragam

	D. Meja memiliki tinggi 1 meter dan lebar 2 meter

	E. Dalam buku terdapat pengarang

4. Fungsi methods dalam object yang **benar** diantaranya...

	A. Hanya dapat memanggil satu method lain

	B. Tidak dapat menggunakan property

	**C. Memungkinkan object bisa melakukan suatu perintah**

	D. Tidak dapat memanggil method lainnya

	E. Tidak bisa object melakukan suatu perintah

5. Manfaat OOP adalah...

	A. Mengatur kode lebih mudah dipelihara
	
	B. Lebih jelas dan mengurangi kompleksitas

	C. Memungkinkan membuat fungsi sederhana untuk interaksi yang kompleks

	D. Modular dan *reusable code*

	**E. Benar semua**

6. Cara mendefinisikan class dalam PHP yang benar dibawah ini adalah...

	A. class Item() {
		// kode propertii dan method
		}

	B. class Item {
		// kode propertii dan method
		};

	C. class Item [
		// kode propertii dan method
		]

	**D. class Item {
		// kode propertii dan method
		}**

	E. Item {
		// kode propertii dan method
		}

7. Tips membuat class yang **tidak benar** adalah...

	A. Pendefinisian object itu sendiri

	B. Menggunakan CamelCase

	C. Diawali huruf kapital

	D. Pendefinisian class pada masing-masing file

	**E. Menggunakan bentuk kata plural**

8. Apa yang salah dari kode program dibawah ini :
   Class mobil {
   		string warna;
  		string merk;
   		int thn_produksi;
   }

   A. Kurang kurung kurawal pada bagian penutup class

   B. Penulisan class dengan huruf kecil

   **C. Penulisan huruf C yang besar pada Class**

   D. Kurang titik koma pada penulisan atribut

   E. Penulisan huruf m yang kecil pada mobil

9. Yang dimaksud dengan *instance* yang **benar** dibawah ini adalah...

	**A. Objek dari sebuah class**

	B. Subjek dari sebuah class

	C. Fungsi dari sebuah class

	D. 	Tipe struktur dari sebuah class

	E. Salah semua

10. Yang digunakan untuk membaca nilai variabel pada class, baik berupa instance maupun static disebut juga ....

	A. Abstraksi
	
	**B. Accessor Methods**
	
	C. Encapsulation
	
	D. Array
	

	E. Mutator methods
11. Variabel yang dideklarasikan didalam kelas, tetapi diluar method dan memiliki nilai default disebut...

	A. Global
	
	**B. Instances**
	
	C. Lokal
	
	D. Return
	
	E. Void

12. Code membuat instance dalam bahasa PHP dibawah ini yang **benar** adalah...

	A. Student{
		}
		$person1 = new Student
		$person2 = new Student

	B. class Student{
		$person1 = new Student;
		}
		$person2 = new Student;

	C. class Student{
		$person1 = new Student;
		$person2 = new Student;
		}

	**D. class Student{
		}
		$person1 = new Student;
		$person2 = new Student;**

	E.	$person1 = new Student;
		$person2 = new Student;
		class Student{
		}

13. Variabel yang menyimpan suatu nilai disebut juga...

	A. Property

	B. Attributes

	C. Class variables

	D. Instance variables

	**E. Benar semua**

14. class Person {
	var $name;
	var $student = false;
	var $country = 'None';
	}
	$customer = new Person;
	$customer2 = new Person;

	Property dalam code diatas ada sebanyak...

	A. 3

	B. 4

	C. 2

	D. 0

	**E. 5**

15. Mengacu pada code soal no. 14, cara yang **benar** untuk memberikan value dan menampilkannya pada variable name dalam bahasa PHP yaitu...

	**A. $customer = new Person
		 $customer->name = 'Zack'
		 echo $customer->name;**

	B. $customer->name = 'Zack'
	   echo $customer->name;

	C. $customer = new Person
	   $Person->name = 'Zack'
	   echo $customer->name;

	D. $customer = new Person
	   $customer->name = 'Zack'
       print $customer->name;

	E. $customer = new Person
	   $customer->name = 'Zack'

16. $class_vars = get_class_vars('Person');
	echo "<pre>";
	print_r($class_vars)
	echo "</pre>";

	Code diatas berfungsi untuk...

 	A. Menghapus variable dalam class

 	B. Mengeset variable dalam class

 	C. Menampilkan variable diluar class

 	**D. Mengecek variable yang dimiliki class**

 	E. Mengupdate data variable dalam class

17. Method dalam class yaitu...

 	A. Fungsi yang bekerja dalam method

 	B. Method yang bekerja dalam fungsi

 	**C. Fungsi yang bekerja dalam object**

 	D. Fungsi yang bekerja dalam instance

 	E. Method yang bekerja dalam instance

18. class Person {
		var $name;
		var country = 'None';
		function sayHello() {
			return "Hello Word!";
		}
	}

	Dari kode diatas, nama dari method tersebut ialah...

	A. Person and sayHello

	B. Person

	**C. sayHello**

	D. B dan C benar

	E. Salah semua

19. Mengacu pada code soal no. 18, cara yang **benar** untuk memanggil method yaitu...

	**A. $customer = new Person;
		 echo $customer->sayHello();**

	B. $customer = new Person;
	   echo $Person->sayHello();

	C. $customer = new Person;
	   $customer->sayHello() = 'Hello World!';
	   echo $customer->sayHello();

	D. echo $customer->sayHello();
	   $customer = new Person;

	E. $customer = new Person;
	   $Person->sayHello() = 'Hello World!';
	   echo $Person->sayHello();

20. if (method_exist('Person', 'sayHello')) {
		echo "tersedia";
	} else {
		"tidak tersedia"
	}

	Kode diatas berfungsi untuk...

	A. Menghapus method sayHello dalam class Person

	B. Mereset class Person dalam method sayHello

	C. Mengecek class Person dalam method sayHello

	**D. Mengecek method sayHello dalam class Person**

	E. Menampilkan method sayHello dalam class Person

21. Cara menggunakan instance yang **benar** dibawah ini adalah...

	A. Diluar class : $variable->

	B. Didalam class : $variable->

	C. Didalam class : $this->

	D. Diluar class : $this->

	**E. A dan C benar**

22. class Person{
		var $first_name;
		var $last_name;
		function fullName() {
			...
		}
 	}
    Contoh memanggil property atau method didalam class atau bagian blank dari kode diatas yaitu...

	A. return $first_name . ' '. $last_name

	**B. return $this->first_name . ' ' . $this->last_name** 

	C. return $fullName->first_name . ' ' . $fullName->last_name

	D. return $Person->first_name . ' ' . $Person->last_name

	E. return $this->first_name . ' ' . $last_name

23. Class yang digunakan menggunakan array dan character disebut...
	
	A. Class math
	
	B. Class wrapper
	
	C. Class string buffer

	**D. Class string**

	E. Class procces

24. Berikut ini yang termasuk tipe data wrapper adalah...

	A. Boolean
	
	B. Byte
	
	C. Character
	
	D. Double
	
	**E. Semua jawaban benar**

25. Nama lain dari istilah pewarisan adalah...

	**A. Inheritance**
	
	B. Interface

	C. Overriding

	D. Overloading

	E. Implements

26. Fungsi dari *Inheritance* yaitu...

	A. Pengulangan kode

	**B. Merapihkan kode**

	C. Memanfaatkan property dan method yang belum ada

	D. Ketidakkonsistenan dan *bugs*

	E. Semua benar

27. Pernyataan berikut yang **benar** tentang pewarisan class adalah, *kecuali*...

	A. Kemampuan suatu class akan dibagikan dengan subclassnya

	B. Memberikan kemampuan baru di parent class akan mempengaruhi subclass

	**C. Subclass tidak dapat mengubah ulang(override) kemampuan parent class**

	D. Subclass dapat memperluas fungsinya ketimbang parent class

	E. Semua salah

28. Cara mendefinisikan subclass yang **benar** yaitu...

	A. class Parent {
	   		class Parent extends Subclass{
	   		}
	   }

	B. class Parent {
	   		class Subclass extends Parent{
	   		}
	   }

	**C. class Parent {
		 }
		 class Subclass extends Parent{
		 }**

	D. class Parent {
	   }
	   class Parent extends Subclass{
	   }

	E. class Subclass extends Parent{
	   }
	   class Parent {
	   }

29. class Document{
		var $file_name;
		function downloadPath{
			return '/download' . $this->file_name;
		}
	}
	class Brochure extends Document{
	}
	class Invoice{
	}
	class Instruction extends{
	}

	Dari kode diatas, manakah yang merupakan subclass...

	**A. Brochure and Instruction**

	B. Brochure and Invoice

	C. Brochure and Document

	D. Invoice and Instruction

	E. Invoice and Document

30. class manusia{
 		var $name;	
		function setName($name) {
		$this->name=$name;
		}	
	}
	class teman extends manusia{
		var $friend;
		function setFriend($friend){
			$this->friend=$friend;
		}
	}
	// instansiasi
	$bos = new manusia;
	$bos->setName("Direktur");
	$boa->setFriend("Sekretaris");

	Dari kode diatas maka akan menampilkan...

	A. Direktur
	   Sekretaris

	B. Sekretaris
	   Direktur

	C. Direktur Sekretaris

	**D. error**

	E. Sekretaris Direktur


## Materi Lanjutan
31. Berikut syarat menggunakan setter dan getter, *kecuali*...
	
	A. Menetapkan visibilitas property menjadi private
	
	**B. Menetapkan class parent untuk menghapus nilai private property**
	
	C. Buat method untuk memanggil nilai private property
	
	D. Buat method untuk mengisi nilai private property

	E. Salah semua

32. class Product {
		private $name;
		public function setName($value) {
			$this->name = $value
		}
		punlic function getName() {
			return $this->$name;
		}
	}

	class diatas memiliki method get bernama...

	A. class producs

	B. setName($value)

	**C. getName()**

	D. setName()

	E. getName($value)

33. Fungsi setter dan getter adalah...
	
	A. Memungkinkan untuk mengakses private property
	
	B. Berguna untuk mengatur kewenangan akses
	
	C. Berguna untuk membuat property read only atau write only
	
	D. Berguna untuk membuat nilai pada pre-processing

	**E. Benar semua**

34.	Dalam pemrograman berorientasi objek terdapat 2 method, pengertian dari method yaitu....

	**A. Method adalah prosedur/fungsi yang dimiliki oleh sebuah objek**
	
	B. Method Adalah Bahasa yang tidak dapat dibaca oleh computer
	
	C. Method adalah bahasa yang yang tidak memiliki sebuah objek
	
	D. Method adalah bukan bahasa pemograman
	
	E. Method adalah bahasa pemrograman berorientasi objek

35.	Yang di maksud dengan stastic property dan method adalah...
	
	A. Tidak terikat dengan instansi tertentu
	
	B. Perilaku yang dimiliki class pada umumnya
	
	C. Bisa dipanggil secara langsung tanpa instance
	
	D. Menggunakan keywoard "static"

	**E. Benar semua**

36.	Contoh static property atau method dibawah ini yang benar adalah...
	A. static $grades = ['SD', 'SMP', 'SMA'];

	B. static function motto() {
			return "Learn PHP OOP"
		}

	C. static $number = [1,2,3,4,5]; 

	**D. static class Student {
			static $grades = ['SD', 'SMP', 'SMA'];
		}**

	E. static function Hello() {
			return "Hello World"
		}

37. Cara mengakses static property dan method yang **benar** adalah...

	A. Static bisa menggunakan $this
	
	**B. Bisa digabungkan dengan pengubah visabilitas**
	
	C. Sintak sama untuk memanggil property dan method
	
	D. Tidak bisa menggunakan self;

	E. Student:$grades, Student:motto()

38. class Student {
		public static $grades = ['SD', 'SMP', 'SMA'];
		private static $totalStudents = 0;
		public static function contStudents() {
			return self::$totalStudents;
		} 
	}
	echo Student::$grades[1];

	Keluaran dari program diatas adalah...

	A. SD

	**B. SMP**

	C. SMA

	D. 0

	E. error

39.	Apakah tatic property dan method bisa di wariskan...
	
	**A. Bisa**
	
	B. Tidak bisa
	
	C. Sebagian bisa

	D. Di sesuaikan denga kondisi

	E. Hanya pada satu class

40. Pernyataan berikut yang benar tentang pewarisan static property dan method adalah, *kecuali*...

	A. Penrubahan nilai pada subclass mempengaruhi parent class

	B. Penrubahan nilai pada parent class mempengaruhi subclass

	**C. Static property yang diwariskan tidak bersifat shared variables**

	D. Pengubah visibilitas/encapsulation berlaku

	E. Static property dan method bisa diwariskan

41. class Student {
		public static $grades = ['SD', 'SMP', 'SMA'];
	}
	class PartTimeStudent extends Student {

	}
	PartTime Student::$grades[] = 'Alumni';
	echo implode(', ', Student::$grades);

	Maka keluaran program diatas menjadi...

	A. SD, SMP, SMA

	B. Alumni

	C. Alumni, SD, SMP, SMA

	**D. SD, SMP, SMA, Alumni**

	E. error

42. Kelas konstan merupakan...
	**A. Class yang digunakan untuk nilai yang tidak bisa diubah**

	B. Class yang digunakan untuk nilai tidak tetap

	C. Class yang digunakan untuk pewarisan

	D. Class yang digunakan untuk merujuk class lain

	E. Class yang digunakan untuk property kompleks

43. Pernyataan berikut yang **salah** tentang class constant adalah...

	A. Menggunakan keywoard const

	B. Penamaan capital

	C. Dapat menyimpan nilai expression

	D. Perujukan dengan ClassName:: atau self::

	**E. Tidak support visilibilty modifier PHP 7.1**

44. Dibawah ini yang benar membuat class constant adalah...

	A. class constTime {
			public DAY = 60 * 60 * 24;
		}

	B. class Time {
			const public DAY = 60 * 60 * 24;
		}

	C. class constTime {
			public const DAY = 60 * 60 * 24;
		}

	**D. class Time {
			public const DAY = 60 * 60 * 24;
		}**

	E. class Time {
			const public const DAY = 60 * 60 * 24;
		}

45. Pernyataan yang **benar** tentang merujuk parent class adalah...
	
	A. Hanya bekerja di dalam Class bukan instance

	B. self:: dan parent:: menggantikan ClassName

	C. Tidak dibutuhkan dalam static properties

	D. Berguna pada saat memanggil static method yang telah di override

	**E. Benar semua**

46. Cara untuk merujuk parent class dibawah ini yang benar yaitu, *kecuali*...

	A. ClassName::$property / ClassName::method()

	B. self::$property / self::method()

	**C. self:$property / self:method()**

	D. parent::$property / parent::method()

	E. parent::$property / parent::method()

47. class Programmer {
		public static function System() {
			echo "Start Coding"
		}
	}
	class AmateurProgrammer extends Progammer {
		public static function System() {
			echo "Read documentation";
			parent::System();
			echo "Clean up mess";
		}
	}
	AmateurProgrammer::System();

	Berdasarkan perujukan parent diatas maka keluaran program adalah...

	A. Start Coding

	B. Read Doumentatio
	   Clean up mess

	**C. Read Documentation
		 Start Coding
		 Clean up mess**

	D. Tidak ada output

	E. error

48. Yang bukan termasuk Magic method dibawah ini adalah...

	A. __ construct()

	**B. __ const**

	C. __ destruct

	D. __ clone

	E. __ get

49. Dibawah ini yang benar membuat construct adalah...

	**A. public function __ construct() {
		 }**

	B. function __ construct() {
	   }

	C. public function construct__() {
	   }

	D. function construct__() {
	   }

	E. public __ construct() {
	   }

50. Dapat diakses dengan menggunakan metode extend dan instan pada paket yang sama, serta dapat diakses dengan metode extend maupun instan dalam paket yang berbeda adalah pengertian hak akses dari...

	A. Protected
	
	B. Default
	
	C. Private
	
	**D. Public**
	
	E. Unprotected

51. Multilevel inheritance adalah...

	A. Objek adalah anak dari class
	
	B. Hak akses yang hanya dimliki oleh user tertentu saja
	
	**C. Model inheritance ketika setiap class menjadi extend dari class yang lainnya**
	
	D. Model inheritance yang pada setiap objek menjadi extend dari class yang lainnya

	E. Model inheritance yang tidak setiap class menjadi extend dari class yang lainnya

52.  Kata kunci dari inheritance adalah...

	A. extend
	
	**B. extends**
	
	C. objek1 objek2 = new objek1
	
	D. public int getL_SG (int tinggi, int alas)
	
	E. public void int getL_SG (int tinggi, int alas)

53. Fungsi method construct Argument misalnya...
	A. Mengulangi pernyataan
	
	**B. Menambahkan value**
	
	C. Memunculkan kembali reference
	
	D. Memanggil method internal
	
	E. Benar semua

54. Karena kita memiliki argument (dalam sebuah construct) maka kita perlu dan harus menambahkan... dan kita menggunakan tipe data...
	**A. Instance object, tipe data Array**
	
	B. Class, tipe data List
	
	C. Instance objek, tipe data Character
	
	D. Class, tipe data Integer
	
	E. Instance object, tipe data Primitive 

55. Jika kita ingin menambahkan value yang tidak ada nilainya (kehabisan nilai atau memang tidak mau ada nilainya) maka kita bisa menambahkan...
	A. 0 
	B. –
	**C. NULL**
	D. NO
	E. Tidak perlu memasukkan apapun

56. Berikut ini pilihan cara untuk menjalankan destruct method, *kecuali*...
	
	A. Saat referensi terakhir dari instance object dihapus
	
	B. Script berakhir

	C. Menggunakan method unset
	
	**D. Menghapus public function __construct ()**
	
	E. Menambahkan method destruct public function __ destruct ()

57. Destruct method berfungsi untuk, *kecuali*...
	
	A. Mencatat suatu proses yang terjadi di dalam suatu object
	
	**B. Mengulangi object yang sudah ada**
	
	C. Menghapus suatu proses dari object yang kita buat
	
	D. Membersihkan ke nilai semula
	
	E. Menjalankan suatu proses atau fungsi pada suatu object berakhir kita jalankan

58. Bagaimana penulisan untuk membuat Destruct method...
	
	**A. public function __destruct () {echo} dan unset ($instance);**
	
	B. public function__construct() NO;
	
	C. public function__destruct delete ()
	
	D. public function__destruct delete () dan unset ($instance);
	
	E. public function__construct () di hapus

59. Bagaimana cara kerja dari clone method...

	**A. Duplicate dari instance object yang suda ada**

	B. Duplicate dari instance yang harus dibuat lagi
	
	C. Menambahkan nilai dari instance
	
	D. Menghapus instance
	
	E. Salah semua

60. Contoh menuliskan clone instance misalnya...
	
	**A. $shirt2 = clone $shirt1;**
	
	B. clone = $shirt2 “$shirt1”;
	
	C. $shirt2 : clone $shirt 1;
	
	D. clone = $shirt2 ()
	
	E. clone = $shirt2;

61. Clone method akan bekerja bilamana...

	A. Membuat clone instance
	
	B. Menyatakan method terlebih dahulu seperti magic method pada umumnya, yakni menggunakan visibility public dan di awali dengan double _
	
	C. Duplikasi dan dengan keyword clone
	
	D. Terdapat construct yang akan di duplicate
	
	**E. Benar semua**

62. Apa yang membedakan Autoload method dengan magic method yang lainnya di PHP adalah...
	A. Berbeda saat inisialisasi objek
	
	B. Cara *passing variable*
	
	C. Dipanggil di dalam class
	
	**D. Dipanggil di luar dari class**
	
	E. Tidak ada perbedaan

63.	Fungsi Autoload method yaitu...
	
	A. Digunakan untuk mencari kelas yang dibuat instance nya, dan kita buat di class yang sama (di dalam directory classes yang sama). 
	
	B. Digunakan untuk memanggil class dari directory classes yang lain.
	
	**C. Digunakan untuk mencari kelas yang dibuat instance nya, tetapi tidak kita buat di class yang sama (di luar dan membuat directory classes baru)**
	
	D. Digunakan untuk menduplikat class dari directory classes yang lain.
	
	E. Digunakan untuk memanggil class dari directory classes yang lain.

64.	Cara membuat instance Autoload yang **benar** adalah...
	
	A. spl_autoload();
	
	B. spl_autoload_register();
	
	C. autoload()
	
	**D. A dan B Benar**
	
	E. Benar semua

65. Penggunaan namespace dan cara pemanggilan class itu sendiri yaitu...

	A. /app/util/log.php => \App\Util\Log

	B. /vendor/framework/framework/log.php => \Fw\Fw\Log

	C. /vendor/package/package/util.log.php => \Pkg\Pkg\Util\Log

	D. Salah semua
	
	**E. A. B, dan C benar**

66. Keuntungan menggunakan namespace adalah, *kecuali*...

	A. Lebih mudah mengatur *package*

	B. Menyederhanakan penamaan method dan class

	**C. Memudahkan menentukan tipe data**
	
	D. Class aliases

	E. Composer

67. Cara baru dalam memuat file adalah...

	A. requaire '../folder/file.php'

	B. include ../../folder/file.php

	C. use App\Util\Log;

	D. $log = new Log();

	**E. C dan D benar**

68. Fungsi interface yaitu...

	A. Method signatures

	B. Membantu progammer lain untuk membedah program

	C. bukan untuk pribadi

	D. Agar mudah menjalankan suatu program

	**E. Benar semua**

69. Apa saja keterbatasan dalam interface, *kecuali*...
	
	A. Hanya mendefinisikan suatu property

	B. Tidak ada implementasi di dalamnya

	C. Hanya menggunakan visibilitas public

	D. Hanya mendefinisikan suatu method

	**E. Tidak ada perintah tersembunyi**

70. Interface sederhana dibawah ini yang benar adalah...

	**A. interface Loginterface {
			public function log(string $message);
		}**

	B. interface Loginterface() {
			public function log(string $message);
		}

	C. interface Loginterface {
			public function Loginterface(string $message);
		}

	D. interface Loginterface {
			public function interface log(string $message);
		}

	E. interface Loginterface {
			public function interface Loginterface(string $message);
		}

71. Kumpulan dari method-method yang belum terdapat operasi di dalam tubuh method tersebut disebut...
	A. Abstract class

	B. Inheritance
	
	**C. Interface**
	
	D. Method abstract
	
	E. Implements

72. interface Tableinterface {
		public function save(array $data);
	}
	interface Loginterface {
		public function log(string $message);
	}

	Dari kode interface diatas, cara mengimplementasikan 2 interface dalam satu tabel class menggunakan bahasa PHP yang **benar** yaitu...

	**A. class Table implements Tableinterface, Loginterface{
		... }** 

	B. class Table implements Tableinterface: Loginterface{
		... }

	C. class Table implements Tableinterface; Loginterface{
		... }

	D. class Table implements Tableinterface/ Loginterface{
		... }

	E. class Table implements Tableinterface$ Loginterface{
		... }

73. Dalam satu class berapa banyak kita dapat menggunakan interface yang dibutuhkan...

	A. 1 interface

	B. 2 interface

	C. 5 interface

	D. Sesuai memori

	**E. Sebanyak mungkin**

74. Peryataan yang **benar** mengenai Trait berikut, yaitu...
	
	A. Implementasi umum

	**B. Menyediakan proses**

	C. Horizontal Code Sharing

	D. Vertikal Code Sharing

	E. Tidak menyediakan proses

75. Cara membuat Trait di PHP adalah...

	**A. trait Waktu {
        public function TanggalIndonesia($tahun,$bulan,$tanggal){
            return "Sekarang tangal $tangal bulan $bulan tahun $tahun";
        }**

	B. trait Waktu() {
        public function TanggalIndonesia($tahun,$bulan,$tanggal){
            return "Sekarang tangal $tangal bulan $bulan tahun $tahun";
        }

	C. trait Waktu(Indonesia) {
        public function TanggalIndonesia($tahun,$bulan,$tanggal){
            return "Sekarang tangal $tangal bulan $bulan tahun $tahun";
        }

	D. Waktu {
        trait public function TanggalIndonesia($tahun,$bulan,$tanggal){
            return "Sekarang tangal $tangal bulan $bulan tahun $tahun";
        }

	E. Waktu {
        public function TanggalIndonesia($tahun,$bulan,$tanggal){
            return trait "Sekarang tangal $tangal bulan $bulan tahun $tahun";
        }

76. Cara memanggil Trait dari class lain di PHP adalah...

	A. class namaTrait {
        	use ClassName;
    	}

    B. use namaTrait {
        	class ClassName;
    	}

    C. use ClassName {
        	class namaTrait;
    	}

    **D. class ClassName {
        	use namaTrait;
    	}**

	E. class ClassName {
        	logging namaTrait;
    	}

77. trait Log {
		protected function log($message) {
			echo "{message}"\n;
		}
	}

	class Table {
		use log;
		public function save() {
			$this->log("created log");
		}
	}

	(new Table())->save();

	Keluaran dari program diatas adalah...

	A. error

	B. "{message}"\n

	C. tidak ada keluaran

	**D. created log**

	E. salah semua

78. Trait dapat dipanggil dalam satu class sekaligus sebanyak, *kecuali*...

	A. 1

	B. 2

	C. 3

	**D. Tak terhingga**

	E. Salah semua

79. trait Waktu {
        public function TanggalIndonesia($tahun,$bulan,$tanggal){
            return "Sekarang tanggal $tanggal bulan $bulan tahun $tahun";
        }
    }
    trait Pesan {
        public function berhasil($pesan){
            echo "Proses Berhasil -> $pesan <br/>";
        }
    }
    trait link {
        public function linkSelanjutnya($kataKunci, $url){
            echo "<a href='$url'>$kataKunci</a>";
        }
    }
    
    Dari tiga trait diatas, cara memanggil tiga trait sekaligus dalam satu class yaitu...

    A.  class Pembelian {
        	use Waktu;
        	use2 Pesan;
        	use3 link;
        	public function tampilkanTanggal($tahun,$bulan,$tanggal) {
            	echo $this->TanggalIndonesia($tahun,$bulan,$tanggal);
        	}
    	}

    **B. class Pembelian {
        	use Waktu,Pesan,link;
        	public function tampilkanTanggal($tahun,$bulan,$tanggal) {
            	echo $this->TanggalIndonesia($tahun,$bulan,$tanggal);
        	}
    	}**

    C. class Pembelian {
        	public function tampilkanTanggal($tahun,$bulan,$tanggal) {
            	echo $this->TanggalIndonesia($tahun,$bulan,$tanggal);
            	use Waktu,Pesan,link;
        	}
    	}

    D. class Pembelian {
    		use Waktu;
        	public function tampilkanTanggal($tahun,$bulan,$tanggal) {
            	echo $this->TanggalIndonesia($tahun,$bulan,$tanggal);
            	use Pesan;
        	}
        	use link;
    	}

    E. class Pembelian {
    		use Waktu;
    		use Waktu, Pesan;
    		use Waktu, Pesan, link;
        	public function tampilkanTanggal($tahun,$bulan,$tanggal) {
            	echo $this->TanggalIndonesia($tahun,$bulan,$tanggal);
        	}
    	}

80. Abstract Class dapat diasumsikan...

	A. class yang sudah tidak abstract

	B. class yang dapat dibuat langsung menjadi objek

	**C. Gabungan interface dan trait**

	D. Tidak memiliki method abstract

	E. Benar semua

81. Kegunaan abstract class yaitu...

	A. for only you

	B. for your team and other developer

	C. for you and other developer

	D. for other developer

	**E. for you and your team**

82. Abstract class tidak bisa dibuat objectnya atau tidak dapat di intasiasi, bagian dari...

	A. Abstract class
	
	**B. Implement abstarct class**
	
	C. Abstract method
	
	D. Interface
	
	E. Method

83. Class yang mempunyai sedikitnya satu abstract metode disebut...

	**A. Abstract class**

	B. Class

	C. Multiple interface

	D. Implementasi

	E. Interface

84. Salah satu perbedaan antara interface dan abstract class adalah...
	
	|Interface                                               | Abstract class                                         |
	|--------------------------------------------------------|--------------------------------------------------------|
	|A.   Bisa berisi abstract dan non abstract              | Hanya boleh berisi abstract method                     |
	|**B.   Method tidak boleh bersifat static               | Method boleh bersifat static**                         |
	|C.   Kita harus menuliskan sendiri modifiernya          | Dapat mendeklarasikan contant dan instant variable     |
	|D.    Suatu interface bisa mengextend interface lainnya | Suatu interface hanya bisa mengextend interface lainnya|
	|E.    Method boleh bersifat final                       | Method tidak boleh bersifat final                      |

85. Dibawah ini yang benar dalam membuat abstract class adalah...

	A. abstract class Database {
			public function disconnect {
				// implementasi
			}
			abstract function connection();
		}

	B. class Database {
			abstract public function connection();
			public function disconnect() {
				// implementasi
			}
		}

	C. abstract class Database {
			abstract public function connection;
			public function disconnect() {
				// implementasi
			}
		}

	**D. abstract class Database {
			abstract public function connection();
			public function disconnect() {
				// implementasi
			}
		}**

	E. Salah semua

86. Type hinting dapat menentukan...

	A. Runtime proses pada suatu method

	B. Value dari suatu data pada suatu method

	**C. Tipe data sebagai parameter pada suatu method**

	D. Jenis variabel pada suatu method

	E. Output pada suatu method

87. Error mismatch dalam OOP berarti...

	A. Tidak ada output

	B. Penulisan sintaks

	C. Waktu

	D. Kompilasi

	**E. Ketidakcocokan**

88. Mengapa perlu menggunakan Type Declaration...

	A. Setiap software tidak dirancang untuk melahap semua tipe data

	B. Menghindari error atau kesalahan program karena berbeda tipe data

	C. Meratasamakan tipe data program untuk penyederhanaan 

	**D. A dan B benar**

	E. Benar semua

89. Strict Type Declaration merupakan...

	**A. Teknik menghapus atau Mengatasi kedinamisan PHP dalam menentukan tipe data**

	B. properti kelas memastikan bahwa nilainya adalah tipe yang ditentukan pada waktu pemanggilan

	C. Metode child yang cocok dengan deklarasi kembalian parent saat mengganti metode parent 

	D. Benar semua

	E. Salah semua

90. public function sum(int $a, int $b) {
		return $a + $b;
	};
	sum (1.5, 2.5);

	Maka hasil dari program diatas adalah...

	A. 4

	**B. 3**

	C. error

	D. 5

	E. Salah semua

91. declare(strict_types=1);
   public function sum(int $a, int $b) {
		return $a + $b;
	};
	sum (1.5, 2.5);

	Mengacu pada soal sebelumnya, jika ditambahkan declare maka keluarannya menjadi...

	A. 4

	B. 3

	**C. error**

	D. 5

	E. Salah semua

92. Return Type Declaration dapa memuat...
	
	A. array

	B. callable

	C. self

	D. class

	**E. benar semua**

93. Tujuan dari Return Type Declaration adalah...

	**A. Menyamakan jenis data antara function type dan return type**

	B. Mengubah jenis data dari function type dan return type

	C. Menghapus jenis data dari function type dan return type

	D. Mengecek jenis data function type dengan return type

	E. Salah semua

94. Contoh return types dibawah ini yang **benar** adalah...
	
	A. public function getUser(): Userclass {
		return $this->userObj;
		}

	**B.public function getUser(): UserInterface {
		return $this->userObj;
		}**

	C. public function getUser(): UserInterface {
		return userObj;
		}

	D. public function getUser(): Userclass {
		return userObj;
		}

	E. public function getUser(): Userclass() {
		return $this->userObj;
		}

95. Closure merupakan...
	
	A. Fungsi yang memiliki nama sesuai dengan class nya

	B. Fungsi yang memiliki nama

	**C. Fungsi yang tidak memiliki nama**

	D. Fungsi yang memiliki nama sesuai nama objek class nya

	E. Fungsi yang tidak memiliki nama dan proses

96. Contoh closure dibawah ini yang **benar** adalah...

	A. $funct = function() { echo "Closure defined"; };
		echo $funct;

	B. $funct = function { echo "Closure defined"; };
		echo $function();

	C. $funct() = function { echo "Closure defined"; };
		echo $funct();

	**D.$funct = function() { echo "Closure defined"; };
		echo $funct();**

	E. $funct = function() { echo "Closure defined"; };
		echo $function();

97. $var = "Closure";
   $var2 = "Return type"
   $var3 = "Strict"
   $funct = function() { echo "{$var2} defined";};
   echo $funct();

   Keluaran dari program diatas adalah...

   A. Closure defined

   B. Return Type defined

   C. Strict defined

   **D. error (undefined variable)**

   E. Tidak ada keluaran

98. Cara *passing variable* dalam closure yaitu...

	A. inisialisasi ulang dalam closure

	B. Menggunakan keywoard use

	C. Dengan cara menambahkan ke parameter atau argumen

	D. A dan B benar

	**E. B dan C benar**

99. $var = "closure"
   $funct = function() use ($var) { echo "{$var} defined"; $var = "function"; $var = "unique"};
   echo $funct();

   Maka keluaran program diatas yang benar menjadi...

   A. unique defined

   B. function defined

   C. closure defined

   D. closure defined function

   E. closure defined function unique

100. $array = [1,2,3,4,5,6,7,8,9];
   $even = array_filter($array, function($item) {
   		return ($item % 2 = 1);
   });
   print_r($even);

   Hasil dari filter program diatas adalah...

   A. Array 
   		(
   			[0] => 1
   		)

   B. Array 
   		(
   			[0] => 1
   			[1] => 2
   			[2] => 3
   			[3] => 4
   			[4] => 5
   			[5] => 6
   			[6] => 7
   			[7] => 8
   			[8] => 9
   		)

   **C. Array 
   		(
   			[0] => 1
   			[2] => 3
   			[4] => 5
   			[6] => 7
   			[8] => 9
   		)**

   D. Array 
   		(
   			[0] => 1
   			[1] => 3
   			[2] => 5
   			[3] => 7
   			[4] => 9
   		)

   E. Array 
   		(
   			[1] => 2
   			[3] => 4
   			[5] => 6
   			[7] => 8
   		)