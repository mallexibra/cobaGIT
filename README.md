# cobaGIT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hal-hal yang diabaikan browser</title>
</head>
<body>
    Apa yang Diabaikan Browser?<br>
    Beberapa informasi dalam dokumen sumber akan diabaikan ketika dilihat<br> 
    dalam web browser, yaitu:<br>
    Pergantian baris.
    <p>Teks dan elemen akan disatukan secara kontinyu sampai blok elemen baru,<br> 
    seperti heading (h1), paragraf (p) atau pergantian baris(br)<br>
    Tab dan spasi lebih dari satu.<br></p> 
    Jika dokumen mengandung:<br>
    <dd>tab,  &nbsp;&nbsp;   spasi &nbsp;&nbsp; dan spasi lagi</dd>
    browser akan menampilkan:<br>
    tab, spasi dan spasi lagi<br>
    Tag yang tidak dikenali. <br>
    Browser mungkin tidak menampilkan apa-apa, atau mungkin menampilkan isi <br>
    dalam tag sebagai teks biasa.<br>
    Teks dalam komentar.<br> 
    Browser tidak akan menampilkan teks antara tag <!-- dan -->.<br>
</body>
</html>
