# tugas-minggu-1
<h1>Terminal Basic</h1>
adalah suatu hal yang paling mendasar dan harus diketahui untuk pemula sebelum melakukan suatu pemograman. media yang digunakan dalam mempelajari terminal basic yaitu (powersheel,cmd gifbash)

>Navigator
<h3>
dalam terminal basic memiliki navigator-navigator yang harus diketahui </h3>

- ls : menampilkan list file didalam folder
- ls-la: menampilkan file yang dihidden 
- clear : digunakan untuk membersikan terminal jika ingin melakukan code baru
- cd : memindahkan directory
- cd .. : memindahkan directory ke sebelumnya
- tuch : perintah untuk membuat file contoh (nama file,extansi) berlaku di linux
-cp : mengcopy file
-mv : memindahkan file ke directory baru
- rm : menghapus file
- rm -r: menghapus folder 
- mkdir : membuat folder dan spasi 

> cacatan :Jika nama folder atau file memiliki karakter spasi maka perlu menambahkan "nama file"

# GIt &GITHUB
adalah tools yang dapat melacak setiap perubahan suatu file, sebagai tempat penyimpanan, karena lebih efektif, dan file tersebuat bisa terlacak jika ada perubahan 

# apa yang dilacak?
- kita bisa melacak perubahan 
- mengetahui siapa yang melacak code tersebut
# git di sediakan oleh beberapa vendor vendor antar lain 
- vendor git&github dibeli oleh (m.s)
- vendor Git lap ( berdiri sendir)
- vendor Git Bucket ( berdiri sendiri )

untuk menyambungkan kita harus mendownlod aplikasi GIT dan melakukan pendaftaran di github.com selanjutnya setup awal dengan meelakukan langkah-langkah berikut:
1. git Config --global user.nsme "AjiePM"
2. git config --global user email ajiemesa19@gmail.com

>catatan : email yang di satup harus sama dengan emaail yang digunakan pada git&hub

untuk mengecek setuo berhasil masukan code  
- git config --list

**Materi HTML 13 Juli 2022**
>html
</p>
<p>adalah bukan Bahasa pemograman namun html adalah kerangka atau pondasi untuk membuat web

>Tools yang ada di html**
- Browser
- code editor

>VSC
<p>adalah kode pengembangan dari MS, biasa digunakan karena memiliki tools yang banyak dan memiliki komunitas yang banyak artinya valit dan wajib diunakan </p>

**langkah-langkah membuat code**
<p>Pilih file,  klik new text file,klik file dan klik save lalu dengan ekstensi .html Contoh pengoprasiannya </p> 

*contoh.html* 
<!DOCTYPE html>
<html>
    <head>
        
    </head>
    <body>
        
    </body>
</html>

>Kita diberikan tugas untuk mengoprasikan html

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="with=device-width, initial-scale=1.8">
        <title>Hy Blog</title>
    </head>
    <body>
        <div>
            <h1>Hi this is my blog</h1>
            <p>I love Learning and sharing</p>
        </div>
        <div>
            <h1>my profile</h1>
            <ul>
                <li>Name : Ajie Prana Mesa</li>
                <li>Age : 23 years old</li>
                <li> Education : Sumbawa University of tecnologi</li>
                <li>major : mechanical engineering</li>
                <li>Address : Sumbawa, NTB </Address></li>
        </div>
        <div>my Gallery</div>
        <img src="ajie.jpg" alt="400">
    </body>
</html>

Cara menampilkan gambar yaitu dengan melakukan drag gambar yang kita inginkan dan masukan ke dalam file vcs yang sudah kita simpan, namun jika  tidak muncul makal klik alt

>Melakukan printah yang sama kemudian kemudian kita diajari membuat folder form
Contoh pengoprasian membuat form
<!DOCTYPE html>
<html>
    <head>
        
    </head>
    <body>
        <form>
            <input type="text"/>
            <input type="number"/>
            <input type="pasword"/>
            <input type="file"/>

            <select>
                <option value="">pilih kota</option>
                <option value="bandung">Bandung</option>
                <option value="sumbawa">Sumbawa</option>
            </select>
            <textarea></textarea>
            <button type="submit"></button>
        </form>
        
    </body>
</html>

>kemudian kita diajari membuat tabel
Contoh pengoprasian membuat tabel
<!DOCTYPE html>
<html>
    <head>
        
    </head>
    <body>
        <table>
            <thead border="1">
                <tr>
                    <td>no</td>
                    <td>nama</td>
                    <td>jenis kelamin</td>
                    <td>gol.dar</td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1</td>
                    <td>ajie</td>
                    <td>laki-laki</td>
                    <td>o</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
Printah <td> semakin banyak td maka kolom pada tabel semakin banyak dari contoh di ata memiliki 4 td maka kolom juga berjumlah 4


<h1>*tugas css 14 Juli**</h1>

<h1>css</h1>
<P>digunakan mendisain halaman web</p> 
<i>( bisa kita ungkapkan) </i> <b> seperti HTML yang hanya memiliki Tulang-berulang namun di berikan tubuh dan pakaian kepada tulang tersebut yang biasa di sebut CSS

<h1>strukutr css</h1>
<p>.elementHTML {
    property :value
}

- <i> selektor, property dan valur</i>

contoh : h1 {color : red ;}
 <p> h1 : (Selector), color : (property), red :(value)

- <p> (<b>propperty terdiri dari color font dll</b>) <i>sedangkan</i> (value terdiri dari anngka,merah dll)

<h1> 3 cara menggunakan CSS </h1>
<p>1. inline style :kita menambahkan css ke pada atribut html
<p>conrohnya:</p>

<p> style="color: red; font-size:12px

- inline  style berada di paragrap
<p>2. internal :cara menambahkan CSS dengan menggunakan tag style di dalam tag head </p>
<p>conrohnya:</p>
 <html>
<head>

	<style type="text/css">
	</style>
</head>
</body>
</html>
3. Eksternal <p>cara menambahkan CSS dengan menggunakan tag link</p>
<p>conrohnya:</p>

- link rel="stylesheet" type="text/css" href="style.css">
	
<h1> css class name</h3>
<p> digunakan lebih dari 1 kelas</p>

- id dan class :sama sama bisa digunhakan dalam css namun perbedaaan <i> jika id : hanya berfokus pada 1 value</i> sedangkan <i>Class :bisa melebihi 1 value</i>
- id secara penulisan tidak boleh lebi dari 1 elemen kecuali id dengan value yang berbeda
-yang paling di prioritaskan ketika ada kelas( id, class, tag html)

<h1> !important CSS</h1>
<p>dapat memaksa style yang harus di jalankan </p>
contoh

- h1 {

    color : red !important

    }

<i>maka style title akan override dengan style tag h1 karena menggunakan !important </i>

   - h1.title {

        color : yellow;
    }


<h1>Tugas ALGORITMA 15 Juli</h1>
Algoritma adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah

 > <h3><B>kualitaas wajib dari algoritma</b></h3>
1. input dan output yang didefinisikan dengan tepat
2. step harus benar-benar tidak ambigu
2. algoritma tidak mengandung suatu code pada bahasa pempgram tertentu, algoritma dibuat agar bisa agar bisa digunakan dalam bahasa pemogram apapun.

><h3><b>Kenapa harus belajar algoritma?</b></h3>
1. progreming itu algoritma dan struktur data 
2. struktur data digunakan memanajemen sebauah data
3. algoritma yang akan menyelesaikan suatu permasalahan data tersebut
<h1>Teknologi Sebagai Solusi</h1>

1. waktu sangat beharga (yang berarti dalam algoritma mana waktu yang optima dan mana yang bukan optimal)
2. memori perlu dihemat (karena pada saat melakukan pemograman data yang digunakan sangatlah banyak makav dari itu kita harus menghemat memori kita agar data tersebuat tidak mengakibatkan lemot)
3. pikiran jangka panjang ( sebelum melakukan sesuatu kita harus memikirkan apa yang akan kita lakkan kedepanya)

> cacatan !! untuk menggunakan bahasa pempgraman kita harus mempelajari dan memahami ALgoritma

- contoh algoritma sederhana 
    <h4>Step 1 : mulai </h4>
    <h4>Step 2 : devinisikan variabel input 1, input 2 dan output</h4>
    <h4> Step 3 : membaca nilai input 1 dan input 2
    <h4> Step 4 : menjumlahkan input 1 can input 2 lalu simpan pada variabel</h4>
    <h4>Step 5: menampilkan output</h4>

- contoh dengan bahasa pemogrman

        var a,b,c

        a = prompt ("Firs Number?");
        
        b = prompt ("Second Number?");
        
        c = Number (a) + Number (b);
        
        console.log (c);

        alert ("Result = " + c);
<h1>pseudocode</h1>
    adalah alat yang digunakan untuk menulis algoritma,bisa membantu kita mengimplementasikan ke bahasa program 

> cara menulis Psodocode
 
 1. menggunakan HURUP BESAR pada kata kunci 
    
    - CONTOH: IF number is > 1- THEN..
 2.  1 statement = 1 baris 
 3. gunakan identitas 
 4. lebih spesifik 
 5. tapi tetap simpel
<h1> procedural</h1>
 berpikir secara runtun, yang artinya serangkaian perintah yang berurutan 

 <h1> conditional</h1>
 digunakan saat membutuhkan percabangan khusus seperti menggunakan istilah (jika maka)
 <h1>looping</h1>
 adalah sebuah perintah yang diulang-ulang 
 
 - contohnya 
    
        STORE "full level" with 0

        WHELE " full level" < 5

        add " full level" by 1

        Display " i am Full!"
<h1>Resursive</h1>
pola pikir dalam algoritma yang memanggil method/fnction dalam sebuah fungsi 
<h1>Algoritma harus General </h1>
    sebagai seorang progreming kita harus menyelesaikan hal yang berat karena dalam pekerjaan progreming harus berpikir dengan logika yang yang sangat kuat
<h1>jenis- jenis Algoritma</h1>

1. menggnakan algoritma sendiri untuk menyelesaikan masalah ( yang artinya kita akan melatih logika kita untuk berpikir)
2. gunakan algoritma secara umum jika dibutuhkan 
<p><i>tidak sebua algoritma diselesaikan dengan menggunakan algoritma umu diutamakan membuat sendiri dan mencari referensi jika dibutuhkan</i></p>
