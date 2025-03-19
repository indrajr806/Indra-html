# Indra-html
Buat botol yakul 
semngat ya😹
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kata-Kata Indah</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f8f9fa;
            color: #333;
            padding-top: 50px;
        }
        h1 {
            color: #d63384;
        }
        #kata {
            font-size: 20px;
            font-style: italic;
            margin-top: 20px;
            background: #ffe4e1;
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
            max-width: 80%;
        }
        button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            background: #d63384;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background: #a61e57;
        }
    </style>
</head>
<body>
    <h1>Kata-Kata untuk Hari Ini</h1>
    <p id="kata"></p>
    <button onclick="tampilkanKata()">Tampilkan Kata-Kata</button>

    <script>
        function tampilkanKata() {
            let kataKata = [
                "Jangan takut gagal, karena kegagalan adalah awal dari keberhasilan.",
                "Hidup itu bukan hanya tentang menunggu badai berlalu, tapi belajar menari di tengah hujan.",
                "Cinta sejati itu seperti bayangan, semakin dikejar semakin menjauh, tapi jika kamu diam, dia akan mengikuti.",
                "Matahari tidak pernah lelah bersinar, seperti aku yang tak pernah lelah menyayangimu.",
                "Hidup itu sederhana, kita yang membuatnya rumit. Jalani dengan hati yang penuh syukur."
            ];
            let randomKata = kataKata[Math.floor(Math.random() * kataKata.length)];
            document.getElementById("kata").innerHTML = randomKata;
        }
    </script>
</body>
</html>
