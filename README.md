# surprise-meriem-
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Pour Meriem</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffe4e1;
            font-family: Arial, sans-serif;
        }
        button {
            padding: 20px 40px;
            font-size: 24px;
            cursor: pointer;
            border: none;
            border-radius: 10px;
            background-color: #ff69b4;
            color: white;
        }
    </style>
</head>
<body>
    <button id="surpriseBtn">Clique ici, Meriem !</button>

    <script>
        const btn = document.getElementById('surpriseBtn');
        btn.addEventListener('click', () => {
            alert('Saha ftorek ! 🥰');
        });
    </script>
</body>
</html>
