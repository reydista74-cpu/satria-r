<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Satria</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            height: 100vh;
            background: linear-gradient(135deg, #1d2b64, #f8cdda);
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .card {
            backdrop-filter: blur(15px);
            background: rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 30px;
            width: 320px;
            text-align: center;
            color: white;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            animation: fadeIn 1.5s ease;
        }

        .card img {
            width: 100px;
            border-radius: 50%;
            margin-bottom: 15px;
            border: 3px solid white;
        }

        h1 {
            font-size: 22px;
            font-weight: 600;
        }

        p {
            font-size: 14px;
            opacity: 0.8;
        }

        .btn {
            margin-top: 20px;
            padding: 10px 20px;
            border: none;
            border-radius: 25px;
            background: white;
            color: #333;
            cursor: pointer;
            transition: 0.3s;
        }

        .btn:hover {
            background: #ff7eb3;
            color: white;
            transform: scale(1.05);
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <div class="card">
        <img src="https://via.placeholder.com/100" alt="foto">
        <h1>Satria Reidista Pratama</h1>
        <p>XI TKJ 2</p>
        <p>Teknik Komputer dan Jaringan</p>

        <button class="btn" onclick="halo()">Say Hello</button>
    </div>

    <script>
        function halo() {
            alert("Halo! Saya Satria 🚀");
        }
    </script>

</body>
</html>
