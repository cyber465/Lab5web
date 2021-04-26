# Lab5web
# Persiapan membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.

***
<!DOCTYPE html>
<html lang="en">
<head>
<title>Mengenal JavaScript</title>
</head>
<body>
<h1>Pengenalan JavaScript</h1>
<h3>Contoh document.write dan console.log</h3>
<script>
document.write("Hello World");
console.log("Hello World");
</script>
</body>
</html>
***

![1](https://user-images.githubusercontent.com/37741274/116022068-ab47ee80-a673-11eb-92b0-dfd4ca313036.png)

# Pemakaian Alert sebagai property window.
***
<html>
    <head>
        <title>Alert Box</title>
    </head>
    <body>
        <script language = "Javascript">
            <!--
            window.alert("selamat datang mahasiswa pelita bangsa");
            //-->
            </script>
    </body>
</html>
<html>
  
 # Pemakaian method dalam objek
 **
 <html>
    <head>
        <title>script JavaScript</title>
    </head>
    <body>
        percobaan memakai JavaScript:<br>
        <script language = "JavaScript">
        <!--
            document.write("selamat mencoba javascript.<br>");
            document.write("semoga sukses!")
            //-->    
        </script>
    </body>
</html>

![2](https://user-images.githubusercontent.com/37741274/116022435-68d2e180-a674-11eb-8e3d-e73a90cdaac6.png)

# Pemakaian Prompt
***
<html>
    <head>
        <title>pemasukan data</title>
    </head>
    <body>
        <script language ="Javescript">
            <!--
                var nama = prompt("siapa nama anda?"."Nama Saya Renaldi");
                document.write("Hai,"+ Renaldi);
                //-->
        </script>
    </body>
</html>
***
# Pembuatan fungsi dan cara pemanggilannya
***
<html>
    <head>
        <title>Contoh Program JavaScript</title>  
        <script language ="javascript">
            function pesan()
        alert("memanggil javascript lewat body onload")
    }
        </script>
    </head>
    <body onload=pesan()>
    </body>
</html>
***
# Dasar Pemrograman Di Javascript
Operasi dasar aritmatika
***
<html>
    <head>
        <title>contoh pemrograman javascript</title>

        <script language="javascript">
            function test (val1,val2)
            {
                document.write("<br>"+"perkalian: val1*val2 "+"<br>")
                document.write(val*val2)
                document.write("<br>"+"pembagian: val1/val2 "+"<br>")
                document.write(val/val2)
                document.write("<br>"+"penjumlahan: val1+val2 "+"<br>")
                document.write(val+val2)
                document.write("<br>"+"pengurangan: val1-val2 "+"<br>")
                document.write(val-val2)
                document.write("<br>"+"modul: val1%val2 "+"<br>")
                document.write(val%val2)
            }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>

    </body>
</html>
***

# Seleksi kondisi (if..else)
***
<html>
    <head>
        <title>contoh if-else</title>

    </head>
    <body>
        <script language ="javascript">
            <!--
                var nilai = prompt("Nilai terakhir nim mahasiswa (0-100): ", 0);
                var hasil ="";
                if (nilai >=60)
                hasil ="lulus";
                else
                hasil ="tidak lulus";
                document.write("hasil: " + hasil);
                //-->
        </script>
    </body>
</html>

![3](https://user-images.githubusercontent.com/37741274/116024309-23181800-a678-11eb-850c-72cb68f84ad7.png)

# Penggunaan operator switch untuk seleksi kondisi
***
<html>
    <head>
        <title>contoh program javascript</title>
        <script language="javascript">
            function test()
            {
                val1=window.prompt("input nilai (1-5):")
                switch (val1)
                {
                    case "1" :
                        document.write("bilangan satu")
                        break
                        case "2" :
                        document.write("bilangan dua")
                        break
                        case "3" :
                        document.write("bilangan tiga")
                        break
                        case "4" :
                        document.write("bilangan empat")
                        break
                        case "5" :
                        document.write("bilangan lima")
                        break
                        default :
                        document.write("bilangan lain nya")
                        
                }
            }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="switch" onclick=test()>
    </body>
</html>

![4](https://user-images.githubusercontent.com/37741274/116024444-683c4a00-a678-11eb-90f6-c7467f92a412.png)

# Pembuatan Form
***
<html>
    <head>
        <script language="javascript">
            function test(){
                var val1=document.kirim.T1.value
                if (val1$2==0)
                document.kirim.T2.value="bilangan genap"
                else
                document.kirim.T2.value="bilangan ganjil"
            }
        </script>
    </head>
    <body>
        <form method="POST" name="kirim">
            <p>BIL <input type="text" name="T1" size="20">
                MERUPAKAN BIL <input type="text" name="T2" size="20">
            </p>
            <p> <input type="button" value="TEBAK" name="B1" onclick=test()></p>
        </form>
    </body>
</html>

![5](https://user-images.githubusercontent.com/37741274/116024571-ae91a900-a678-11eb-8a84-c1ac078143a2.png)


# Form Button.
***
<html>
    <head>
        <title>object document</title>
    </head>
    <body>
        <script language="javascript">
            <!--
                function ubahwarnaLB(warna){
                    document.bgColor=warna;
                }
            {
                function ubahwarnaLD(warna){
                    document.fgColor=warna;
            
            }
                //-->
        </script>
        <h1>test</h1>
        <form>
           <input type="button" value="latar belakang hijau" onclick="ubahwarnaLB ('GREEN')">
           <input type="button" value="latar belakang putih" onclick="ubahwarnaLB ('WHITE')">
           <input type="button" value="Teks kuning" onclick="ubahwarnaLD ('YELLOW')">
           <input type="button" value="Teks biru" onclick="ubahwarnaLD ('BLUE')">
            </form>
            <script language="javascript">
             <!--
                document.write("dimodifikasi terakhir pada" + document.lastModified);
               //-->
                   
    </script>
    </body>
</html>

![6](https://user-images.githubusercontent.com/37741274/116024647-de40b100-a678-11eb-9a06-0382cc36771f.png)


# HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis
***
<!--
    file: daftar_Html
    //-->
    <html>
    <head>
        <title>Daftar menu</title>
        <script>
            function hitung(ele){
                var total = document.getElementById('total').value;
                total = (total ? perseint(total) : 0);
                var harga = 0);
                if (ele.checked) {
                    harga = ele.value;
                    total += perseint(harga)
                } else {
                    harga = ele.value;
                    if (total > 0)
                    total -= perseint (harga);
                    
                }
                document.getElementById('total').value = total;
            }

            </script>
            </head>
            <body>
                <h1>daftar menu makanab</h1>
                <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"/> ayam goreng 5.000</label><br />
                <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"/> tempe goreng 5.00</label><br />
                <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"/> telur dadar 2.500</label><br />
                <strong>total bayar: Rp. <input id="total" type="tekt"/><strong>
                </body>
    </html>
    ***
    ![7](https://user-images.githubusercontent.com/37741274/116024743-0defb900-a679-11eb-81ec-198086e9a69d.png)
    
   # Jawab 
   
   ![hhh](https://user-images.githubusercontent.com/37741274/116025561-fdd8d900-a67a-11eb-8815-20b72b4ca4e8.png)







  
