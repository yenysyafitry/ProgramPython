<h2>  Program Python </h2>
<ul align="justify"> <li>Python termasuk bahasa pemrograman yang mudah untuk dipelajari. 
Sampai saat ini bahasa pemrograman Python hampir dipakai di segala sistem berbasis web, dan bahkan dapat membuat mesin pencari sendiri. 
Jadi secara umum, bahasa pemrograman ini dipakai dalam pengembangan website, pengembangan software, matematika, dan system scripting. </li>
<li> Menampilkan Karakter :</br> print("Hello Python") </br> Karakter di dalam tanda kurung akan ditampilkan di dalam console </br> Hasil Output : Hello Python
<li> Membuat Komentar pada program python : </br> Menambahkan # pada awal perintah akan membuat baris perintah itu menjadi komentar. </li>
Komentar tidak akan muncul ketika code dijalankan sehingga Anda bisa menggunakannya untuk catatan.</li>
<li> / adalah simbol pembagian dan * adalah simbol perkalian . Anda juga dapat menghitung sisa pembagian dengan %. </li>
<li> Untuk menyimpan nilai dalam variable, Anda perlu mendefiniskan variable. Anda dapat melakukannya dengan format berikut: variable_name = nilai. Operator = dalam Python bukan berarti "sama dengan". Operator tersebut digunakan untuk menetapkan nilai ke variable yang berada di sebelah kiri. Nama variable tidak perlu ditutup dengan tanda kutip. </li>
<li> Sekarang mari belajar cara mencetak nilai pada variable name. Anda dapat melakukannya dengan menulis print(name). Jika Anda menambahkan tanda kutip pada variable, seperti print('name'), name menjadi string, bukan variable. Maka dari itu, hasilnya akan menjadi name, bukan nilai dari variable.</li>
</ul>



<ul align="justify"><li> Tetapkan Bob sebagai nilai untuk variable name : </br>
 name = 'Bob' </br> print(name) </br> <i>Output : <u>Bob</i></li>
<li> Tetapkan integer 7 untuk variable number :</br>
number = 7 </br>
print(number) </br> <i>Output : 7</i></li>
<li>Tetapkan string Bob ke variable my_name : </br>
my_name = 'Bob'</br>
Cetak 'Nama saya Bob' dengan menggabungkan variable my_name dan sebuah string
print('Nama saya ' + my_name)</br> <i>Output : Nama saya Bob</i></li>
<li><b>Cetak 'Saya berusia 24 tahun' menggunakan variable age </b> </br>
<i> age = 24 </i> </br>
<i>print('Saya berusia ' + str(age) + ' tahun') </i></br>
<i>count = '5'</i></br>
<b> Ubah variable count ke tipe data integer, tambahkan 1, dan cetak hasilnya</b></br>
<i>print(int(count) + 1)</i></br>
 <b>Output : </br></b><i>Saya berusia 24 tahun</br>6</i></li>
 <li><b>Variable x dan y :</b></br><i>x = 7 * 10 </br>
y = 5 * 6 </i></br>
<b>Jika x sama dengan 70, cetak 'x adalah 70'</b></br>
<i>if x == 70: </br>
    print('x adalah 70')</i></br>
<b> Jika y tidak sama dengan 40, cetak 'y bukan 40' </b></br>
<i>if y != 40: </br>
    print('y bukan 40') </br>
    <b>Output :</b></br>
    x adalah 70 </br>y bukan 40</i></li>
    <li> <b>Variable x sudah disiapkan untuk Anda dengan nilai 10: </b></br>
<i>  x = 10</i> </br>
 <b> Jika x lebih besar dari 30, cetak 'x lebih besar dari 30' :</b></br>
<i> if x > 30:</br>
    print('x lebih besar dari 30')</br>
money = 5</br>
apple_price = 2</i> </br>
<b> Jika money sama dengan atau lebih besar dari apple_price, cetak 'Anda dapat membeli apel' </b></br>
<i> if money >= apple_price:</br>
    print('Anda dapat membeli apel') </i> </li>
    <li><b>Variable berikut sudah tersedia untuk Anda :</b></br> <i>
 money = 2 </br>
apple_price = 4 </br>
if money >= apple_price: </br>
    print('Anda dapat membeli apel') </br></i>
<b> Ketika kondisi di atas adalah False, cetak 'Uang Anda tidak mencukupi' </b></br>
<i>else: </br>
    print('Uang Anda tidak mencukupi') </i></br></li>
<li><b> Variable berikut sudah tersedia untuk Anda</b></br>
<i> money = 2 </br>
apple_price = 2 </br>
if money > apple_price: </br>
    print('Anda dapat membeli apel') </i></br>
<b> Ketika kedua variable memiliki nilai yang sama, cetak 'Anda dapat membeli apel tetapi dompet Anda akan menjadi kosong' :</b></br>
<i>elif money == apple_price: </br>
    print('Anda dapat membeli apel tetapi dompet Anda akan menjadi kosong') </br>
else: </br>
    print('Uang Anda tidak mencukupi') </i> </br> <b>Output :</b><i> Anda dapat membeli apel tetapi dompet Anda akan menjadi kosong</i></li>
    <li><b>Menggabungkan Kondisi </b></br><i> x = 20 </i></br>
<b> Jika x berkisar antara 10 dan 30 (inklusif), cetak 'x berkisar antara 10 dan 30' </b></br>
<i>if 10 <= x and x <= 30: </br>
    print('x berkisar antara 10 dan 30') </br>
y = 60 <i> </br>
<b> Jika y lebih kecil dari 10 atau lebih besar dari 30, cetak 'y lebih kecil dari 10 atau lebih besar dari 30' </b></br>
<i>if y < 10 or 30 < y: </br>
    print('y lebih kecil dari 10 atau lebih besar dari 30') </br>
z = 55</br></i>
<b> Jika z tidak sama dengan 77, print 'z bukan 77' </b></br>
<i>if not z == 77:</br>
    print('z bukan 77') </i></br>
    <b>Output :</b> </br><i>x berkisar antara 10 dan 30</br>y lebih kecil dari 10 atau lebih besar dari 30 </br>z bukan 77</i></li>
 <li><b> Berikan 2 ke variable apple_price :</b></br>
<i>apple_price = 2 </br> </i>
<b>Berikan 5 ke variable count </br></b>
<i>count = 5 </br></i>
<b> Berikan hasil dari apple_price * count ke variable total_price </br></b>
<i>total_price = apple_price * count </br></i>
<i> Dengan menggunakan variable count, cetak 'Anda akan membeli .. apel' </br>
print('Anda akan membeli ' + str(count) + ' apel') </br></i>
<b> Dengan menggunakan variable total_price, cetak 'Harga total adalah .. dolar' </br> </b>
print('Harga total adalah ' + str(total_price) + ' dolar')</br> 
<b>Output :</b> </br><i>Anda akan membeli 5 apel </br>
Harga total adalah 10 dolar</br></i>
</li>
<li><i>apple_price = 2</i></br> 
 <b> Terima jumlah apel dengan menggunakan input(), dan berikan hasilnya ke variable input_count </b></br> 
 <i>input_count = input('Mau berapa apel?: ')</i></br> 
 <b> Ubah variable input_count ke integer, dan berikan hasilnya ke variable count </b></br> 
<i>count = int(input_count)</br> 
total_price = apple_price * count</br> 
print('Anda akan membeli ' + str(count) + ' apel')</br> 
print('Harga total adalah ' + str(total_price) + ' dolar')</br> </i>
<b>Output :</b></br> <i>Mau berapa apel?... </br>Anda akan membeli ... </br>Harga total adalah ...</i>
</li>
<li> apple_price = 2 </br> 
<b> Berikan 10 ke variable money</b>  </br> 
<i>money = 10 </br> 
input_count = input('Mau berapa apel?: ') </br> 
count = int(input_count) </br> 
total_price = apple_price * count </br> 
print('Anda akan membeli ' + str(count) + ' apel') </br> 
print('Harga total adalah ' + str(total_price) + ' dolar') </br> </i>
<b> Tambahkan control flow berdasarkan perbandingan antara money dan total_price </b></br> 
<i>if money > total_price: </br> 
    print('Anda telah membeli ' + str(count) + ' apel') </br> 
    print('Uang Anda tinggal ' + str(money - total_price) + ' dolar') </br> 
elif money == total_price: </br> 
    print('Anda telah membeli ' + str(count) + ' apel') </br> 
    print('Dompet Anda kosong') </br> 
else: </br> 
    print('Uang Anda tidak mencukupi') </br> 
    print('Anda tidak dapat membeli apel sebanyak itu') </br> </i>
    <b>Output :</b></br> <i>Mau berapa apel? ... </br>Anda telah membeli ...</br>Uang Anda tinggal ...</br> Anda telah membeli ...</br>Dompet Anda kosong ...</i>
</li><li><b>Tetapkan sebuah list string ke variable fruits</b> </br>
<i>fruits = ['apel', 'pisang', 'jeruk'] </i></br>
<b> Cetak element di index 0 </b> </br>
<i>print(fruits[0]) </i></br>
<b> Gabungkan string dan element di index 2, dan cetak hasilnya </b></br>
<i>print('Saya suka ' + fruits[2])</i></br>
<b>Output</b></br><i>apel</br>Saya suka jeruk</i></li>

</ul>

<p align="center"><b>E-Sertifikat </b></br><img src="https://github.com/yenysyafitry/Python/blob/main/e-sertifikat.jpg"></p>
