# ASSIGNMENT-1
### Khayla Rahma Levina_(G1A023045)

## LANDASAN TEORI

penggunaan array, pengulangan, dan penerapan if dan else dalam bahasa pemrograman Java adalah inti dari pemrograman komputer modern. Array adalah struktur data yang memungkinkan Anda untuk menyimpan sejumlah elemen data dengan tipe yang sama dalam satu variabel. Ini sangat berguna ketika Anda perlu mengelola data yang sama secara efisien, seperti daftar nama, angka, atau objek.

Penggunaan array memungkinkan penyimpanan data yang terorganisir, akses data dengan indeks, dan pengulangan untuk mengakses dan memanipulasi elemen-elemen dalam array. Pengulangan adalah teknik yang diperlukan dalam hampir setiap program untuk menjalankan operasi berulang-ulang, seperti pengolahan array, perulangan hingga kondisi tertentu terpenuhi, atau perulangan selama input data diperlukan.

Penerapan struktur kendali seperti if dan else memungkinkan program untuk membuat keputusan berdasarkan kondisi tertentu. Dalam konteks ini, if digunakan untuk mengevaluasi suatu kondisi dan menjalankan pernyataan tertentu jika kondisi tersebut benar, sedangkan else digunakan untuk menjalankan pernyataan alternatif jika kondisi itu salah. Ini memungkinkan penggunaan percabangan logika dalam program, yang memungkinkan program berperilaku berdasarkan kondisi yang berubah.

Dalam pemrograman Java, penggunaan array, pengulangan, if, dan else sangat umum dan penting untuk membuat program yang efisien, terstruktur, dan dapat mengatasi berbagai jenis tugas pemrosesan data. Pemahaman konsep-konsep ini akan membantu dalam pembuatan program yang lebih kuat dan aplikasi yang lebih beragam dalam berbagai bidang seperti ilmu pengetahuan, teknologi, bisnis, dan banyak lagi.

Penggunaan aplikasi Java di Visual Studio Code (VSCode) adalah hasil dari konvergensi antara bahasa pemrograman Java yang kuat dan editor kode yang sangat populer. VSCode adalah editor kode sumber terbuka yang sangat luwes, ringan, dan memiliki ekosistem plugin yang kuat. Kehadiran ekstensi Java di VSCode memungkinkan pengembang untuk mengembangkan dan menjalankan aplikasi Java dengan efisien tanpa harus bergantung pada lingkungan pengembangan terintegrasi yang lebih berat.

Penggunaan aplikasi Java di VSCode memungkinkan pengembang untuk menulis, menguji, dan mengelola kode Java dengan fitur-fitur modern seperti penyorotan sintaks, penyusunan ulang kode, dan pengembangan dengan integrasi Git. Dengan dukungan untuk perangkat keras yang berbeda dan sistem operasi yang beragam, penggunaan aplikasi Java di VSCode menjadi lebih dapat diakses dan dapat meningkatkan produktivitas pengembangan.

Kombinasi antara Java dan VSCode memberikan fleksibilitas dan daya saing yang dibutuhkan untuk pengembangan aplikasi Java modern dalam berbagai industri seperti perangkat lunak berbasis server, perangkat seluler, web, dan sebagainya. Oleh karena itu, penggunaan aplikasi Java di VSCode telah menjadi salah satu pilihan populer di kalangan pengembang Java saat ini.


##  NO.1 (PERULANGAN)
### Buatlah perulangan hingga 100 menggunakan java dengan menggunakan output sebagai berikut:
1

2

3

4

5

6

7

8

9

(your name)

(your name)

(your name)

### Jawaban NO.1
![image](https://github.com/KhaylaLevina19/ASSIGNMENT-1/assets/149869603/7208b044-3015-4ba8-979b-022b6169a381)

Gambar 1.1

#### code: 
public class task1{
  public static void main(String[] args){
    String name = "Khayla Rahma Levina";
    String NPM = "G1A023045";
    System.out.println("Nama: " + name);
    System.out.println("NPM : " + NPM);
    System.out.println("x:==================");
    for (int i = 0 ; i<=100 ; i++){
      if (i>= 10 ){
        System.out.println(name);
      }
      else{
        System.out.println(i);
      }
    }
  }
}


Berikut adalah penjelasan tentang fungsi dan cara kerja setiap baris dari kode pada gambar 1.1:

1. `public class task1 {`
   - Ini adalah deklarasi kelas utama dengan nama "task1".

2. `public static void main(String[] args) {`
   - Ini adalah metode utama (main method) dari kelas "task1". Program Java akan dijalankan dari sini.

3. `String name = "Khayla Rahma Levina";`
   - Ini mendefinisikan sebuah variabel dengan nama "name" dan menginisialisasinya dengan string "Khayla Rahma Levina".

4. `String NPM = "G1A023045";`
   - Ini mendefinisikan variabel "NPM" dan menginisialisasinya dengan string "G1A023045".

5. `System.out.println("Nama: " + name);`
   - Ini mencetak teks "Nama: " diikuti oleh isi dari variabel "name" ke layar.

6. `System.out.println("NPM : " + NPM);`
   - Ini mencetak teks "NPM : " diikuti oleh isi dari variabel "NPM" ke layar.

7. `System.out.println("x:==================");`
   - Ini mencetak teks "x:==================" ke layar.

8. `for (int i = 0 ; i<=100 ; i++){`
   - Ini adalah awal dari loop `for`. Loop ini akan berjalan dari `i` mulai dari 0 hingga 100, dengan `i` bertambah satu pada setiap iterasi.

9. `if (i>= 10 ){`
   - Ini adalah kondisi if yang memeriksa apakah nilai `i` lebih besar atau sama dengan 10.

10. `System.out.println(name);`
    - Jika kondisi if terpenuhi (yaitu `i` lebih besar atau sama dengan 10), maka kode ini akan mencetak isi dari variabel "name" ke layar.

11. `else {`
    - Ini adalah bagian else yang akan dieksekusi jika kondisi if tidak terpenuhi.

12. `System.out.println(i);`
    - Jika kondisi if tidak terpenuhi (yaitu `i` kurang dari 10), maka kode ini akan mencetak nilai `i` ke layar.

13. `}` 
    - Ini adalah penutup dari blok else.

14. `}` 
    - Ini adalah penutup dari loop `for`.

Kode ini mencetak nama dan NPM ke layar, kemudian mencetak "x:==================", dan selanjutnya mencetak angka dari 0 hingga 100 atau nama "Khayla Rahma Levina" tergantung pada nilai `i`. Jika `i` kurang dari 10, maka angka akan dicetak, dan jika `i` lebih besar atau sama dengan 10, maka nama akan dicetak.


## N0.2 (LOOP)
### Buatlah program bebas, dengan menerapkan if else dalam perulangan while
![image](https://github.com/KhaylaLevina19/ASSIGNMENT-1/assets/149869603/19f31a7a-1123-4400-a164-59a0d69902c5)

Gambar 1.2

#### code:

import java.util.Scanner;

public class task8{
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        System.out.print("Masukan sebuah bilangan bulat");
        int bilangan = input.nextInt();
        input.close();

        if (bilangan % 2 == 0){
            System.out.println("Bilangan " + bilangan + " adalah bilangan genap.");
        }else{
            System.out.println("Bilangan " + bilangan + " adalah bilangan ganjil.");
        }
        System.out.println("Menggunakan perulangan while untuk menghitung dari 1 hingga" + bilangan);

        
        int i = 1;
        while (i <= bilangan){
            System.out.println(i); i++;
        }
    }
}

Berikut adalah penjelasan tentang fungsi dan cara kerja setiap baris dari kode pada gambar 1.2:

1. `import java.util.Scanner;`
   - Ini adalah pernyataan impor yang mengimpor kelas `Scanner` dari pustaka `java.util`. Ini diperlukan untuk penggunaan `Scanner` dalam program.

2. `public class task8 {`
   - Ini adalah deklarasi kelas utama dengan nama "task8".

3. `public static void main(String[] args) {`
   - Ini adalah metode utama (main method) dari kelas "task8". Program Java akan dijalankan dari sini.

4. `Scanner input = new Scanner(System.in);`
   - Ini mendeklarasikan objek `input` yang akan digunakan untuk membaca input dari pengguna melalui keyboard.

5. `System.out.print("Masukan sebuah bilangan bulat");`
   - Ini mencetak teks "Masukkan sebuah bilangan bulat" ke layar tanpa baris baru.

6. `int bilangan = input.nextInt();`
   - Ini membaca sebuah bilangan bulat yang dimasukkan oleh pengguna dan menyimpannya dalam variabel `bilangan`.

7. `input.close();`
   - Ini menutup objek `Scanner` yang digunakan untuk input. Ini adalah praktik yang baik untuk memastikan sumber daya dibebaskan setelah penggunaan.

8. `if (bilangan % 2 == 0) {`
   - Ini adalah kondisi if yang memeriksa apakah `bilangan` adalah bilangan genap atau tidak. Operasi modulo (`%`) digunakan untuk memeriksa sisa pembagian `bilangan` dengan 2. Jika hasilnya 0, maka bilangan genap.

9. `System.out.println("Bilangan " + bilangan + " adalah bilangan genap.");`
   - Jika kondisi if terpenuhi (yaitu `bilangan` adalah bilangan genap), maka kode ini mencetak pesan yang menyatakan bahwa `bilangan` adalah bilangan genap.

10. `else {`
    - Ini adalah bagian else yang akan dieksekusi jika kondisi if tidak terpenuhi.

11. `System.out.println("Bilangan " + bilangan + " adalah bilangan ganjil.");`
    - Jika kondisi if tidak terpenuhi (yaitu `bilangan` bukan bilangan genap), maka kode ini mencetak pesan yang menyatakan bahwa `bilangan` adalah bilangan ganjil.

12. `System.out.println("Menggunakan perulangan while untuk menghitung dari 1 hingga" + bilangan);`
    - Ini mencetak pesan yang menyatakan bahwa program akan menggunakan perulangan `while` untuk menghitung dari 1 hingga `bilangan`.

13. `int i = 1;`
    - Ini mendeklarasikan variabel `i` dan menginisialisasinya dengan nilai 1.

14. `while (i <= bilangan) {`
    - Ini adalah awal dari perulangan `while`. Program akan menjalankan pernyataan di dalam blok `while` selama `i` kurang dari atau sama dengan `bilangan`.

15. `System.out.println(i); i++;`
    - Ini mencetak nilai `i` ke layar dan kemudian menaikkan nilai `i` dengan 1.

16. `}`
    - Ini adalah penutup dari perulangan `while`.

Kode ini mengambil input dari pengguna, memeriksa apakah bilangan tersebut genap atau ganjil, mencetak pesan sesuai dengan hasilnya, dan kemudian menggunakan perulangan `while` untuk mencetak angka dari 1 hingga `bilangan`.


## NO.3 (PROGRAM ZODIAK)
### Buatlah program zodiac dengan menggunakan fitur input dengan hasil menampilkan zodiac sesuai dengan tanggal lahir yang diinputkan
![image](https://github.com/KhaylaLevina19/ASSIGNMENT-1/assets/149869603/7a5f603c-6b3b-460f-8546-c7a79694a7d9)

Gambar 1.3

![image](https://github.com/KhaylaLevina19/ASSIGNMENT-1/assets/149869603/07b87250-8d3b-46a4-8a58-ae3cd5ebd23e)

Gambar 1.4

#### code:

import java.util.Scanner;

public class zodiac7 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Masukan tanggal lahir anda");
        int tanggal = sc.nextInt();
        System.out.println("masukan bulan lahir anda");
        int bulan = sc.nextInt();
        sc.close();

        String zodiac  = "";

        switch (bulan) {
            case 1:
                zodiac = (tanggal <= 19) ? "Capricon" : "Aquarius";
                break;
            case 2:
                zodiac = (tanggal <= 18) ? "Aquarius" : "Pisces";
                break;
            case 3:
                zodiac = (tanggal <= 20) ? "Pisces" : "Aries";
                break;
            case 4:
                zodiac = (tanggal <= 19) ? "Aries" : "Taurus";
                break;
            case 5:
                zodiac = (tanggal <= 20) ? "Taurus" : "Gemini";
                break;
            case 6:
                zodiac = (tanggal <= 20) ? "Gemini" : "Cancer";
                break;
            case 7:
                zodiac = (tanggal <= 22) ? "Cancer" : "Leo";
                break;
            case 8:
                zodiac = (tanggal <= 22) ? "leo" : "Virgo";
                break;
            case 9:
                zodiac = (tanggal <= 22) ? "Virgo" : "Libra";
                break;
            case 10:
                zodiac = (tanggal <= 22) ? "Libra" : "Scorpio";
                break;
            case 11:
                zodiac = (tanggal <= 21) ? "Scorpio" : "Sagitarius";
                break;
            case 12:
                zodiac = (tanggal <= 21) ? "Sagitarius" : "Capricon";
                break;

        }
        System.out.println("jadi zodiak anda adalah: " + zodiac);
    
    }
}

Berikut adalah penjelasan tentang fungsi dan cara kerja setiap baris kode:

1. `import java.util.Scanner;`
   - Ini adalah pernyataan impor yang mengimpor kelas `Scanner` dari pustaka `java.util`. Ini diperlukan untuk penggunaan `Scanner` dalam program.

2. `public class zodiac7 {`
   - Ini adalah deklarasi kelas utama dengan nama "zodiac7".

3. `public static void main(String[] args) {`
   - Ini adalah metode utama (main method) dari kelas "zodiac7". Program Java akan dijalankan dari sini.

4. `Scanner sc = new Scanner(System.in);`
   - Ini mendeklarasikan objek `sc` yang akan digunakan untuk membaca input dari pengguna melalui keyboard.

5. `System.out.println("Masukan tanggal lahir anda");`
   - Ini mencetak teks "Masukkan tanggal lahir anda" ke layar.

6. `int tanggal = sc.nextInt();`
   - Ini membaca sebuah bilangan bulat yang dimasukkan oleh pengguna dan menyimpannya dalam variabel `tanggal`.

7. `System.out.println("Masukan bulan lahir anda");`
   - Ini mencetak teks "Masukkan bulan lahir anda" ke layar.

8. `int bulan = sc.nextInt();`
   - Ini membaca sebuah bilangan bulat yang dimasukkan oleh pengguna dan menyimpannya dalam variabel `bulan`.

9. `sc.close();`
   - Ini menutup objek `Scanner` yang digunakan untuk input. Ini adalah praktik yang baik untuk memastikan sumber daya dibebaskan setelah penggunaan.

10. `String zodiac  = "";`
    - Ini mendeklarasikan variabel `zodiac` yang akan digunakan untuk menyimpan nama zodiak.

11. `switch (bulan) {`
    - Ini adalah konstruksi switch yang digunakan untuk memeriksa nilai dari variabel `bulan` dan menentukan zodiak berdasarkan bulan yang dimasukkan oleh pengguna.

12. Kode `case` dan `break` digunakan untuk menentukan zodiak berdasarkan bulan dan tanggal yang dimasukkan oleh pengguna. Misalnya, jika pengguna memasukkan bulan 1 (Januari) dan tanggal kurang dari atau sama dengan 19, maka zodiak akan diatur sebagai "Capricorn". Jika tanggal lebih dari 19, maka zodiak akan diatur sebagai "Aquarius".

13. `System.out.println("jadi zodiak anda adalah: " + zodiac);`
    - Ini mencetak zodiak yang telah ditentukan ke layar bersama dengan pesan "jadi zodiak anda adalah:".

Kode ini memungkinkan pengguna untuk memasukkan tanggal dan bulan lahir mereka, kemudian program ini menggunakan struktur `switch` untuk menentukan zodiak berdasarkan input tersebut. Hasil zodiak kemudian dicetak ke layar sebagai output.

## NO.4
### Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for
<img width="740" alt="image" src="https://github.com/KhaylaLevina19/ASSIGNMENT-1/assets/149869603/56bc96d7-7e3d-443c-b881-615ba0ddb5ab">

Gambar 1.5

#### code:

public class task5 {
    public static void main(String[] args) {
    

        String [] food = {"burger" , "noodle" , "pasta" , "choke" , "candy"};

        System.out.println(food[2]);

        for (int i=0; i < 5; i++){

            System.out.println(food[i]);
        }

    }
        


            
}

Kode pada gambar 1.5 adalah program sederhana dalam bahasa Java yang bekerja dengan array string. Berikut adalah penjelasan tentang fungsi dan cara kerja setiap baris kode:

1. `public class task5 {`
   - Ini adalah deklarasi kelas utama dengan nama "task5".

2. `public static void main(String[] args) {`
   - Ini adalah metode utama (main method) dari kelas "task5". Program Java akan dijalankan dari sini.

3. `String[] food = {"burger", "noodle", "pasta", "choke", "candy"};`
   - Ini mendeklarasikan sebuah array string dengan nama "food" yang berisi lima elemen string ("burger", "noodle", "pasta", "choke", "candy"). Array ini digunakan untuk menyimpan jenis makanan.

4. `System.out.println(food[2]);`
   - Ini mencetak elemen ketiga dari array "food" (indeks 2) ke layar. Ingatlah bahwa indeks array dimulai dari 0, sehingga `food[2]` mengacu pada elemen "pasta" dalam array.

5. `for (int i = 0; i < 5; i++) {`
   - Ini adalah awal dari loop `for`. Loop ini akan berjalan dari `i` mulai dari 0 hingga 4 (indeks 0 hingga 4) dengan `i` bertambah satu pada setiap iterasi.

6. `System.out.println(food[i]);`
   - Ini mencetak elemen-elemen array "food" sesuai dengan nilai `i` ke layar. Selama iterasi, ini akan mencetak semua jenis makanan dalam array "food" ke layar.

7. `}`
   - Ini adalah penutup dari loop `for`.

Dengan demikian, program ini mencetak jenis makanan dari array "food" dengan mengakses elemen array menggunakan perulangan `for`. Hasil cetakan adalah daftar makanan yang terdiri dari "burger," "noodle," "pasta," "choke," dan "candy." Selain itu, program juga mencetak elemen ketiga dari array "food," yaitu "pasta."










