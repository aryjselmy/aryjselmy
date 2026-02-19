<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Mettre à jour le profil</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .container {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
            width: 400px;
            text-align: center;
        }

        form label {
            display: block;
            margin-top: 15px;
            text-align: left;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border-radius: 5px;
            border: 1px solid #ccc;
            box-sizing: border-box;
            transition: 0.3s;
        }

        form input:focus, form textarea:focus {
            border-color: #4a90e2;
            box-shadow: 0 0 5px #4a90e2;
            outline: none;
        }

        button {
            margin-top: 20px;
            padding: 10px 20px;
            background: #4a90e2;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #357ABD;
        }

        .message {
            margin-top: 20px;
            padding: 10px;
            background: #d4edda;
            color: #155724;
            border-radius: 5px;
            opacity: 0;
            transform: translateY(-20px);
            transition: all 0.5s ease;
        }

        .message.show {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Mettre à jour le profil</h2>
        <form id="updateForm">
            <label>Nom :</label>
            <input type="text" id="name" placeholder="Votre nom" required>

            <label>Email :</label>
            <input type="email" id="email" placeholder="Votre email" required>

            <label>Photo de profil :</label>
            <input type="file" id="photo" accept="image/*">

            <label>Bio :</label>
            <textarea id="bio" placeholder="Parlez de vous..."></textarea>

            <button type="submit">Mettre à jour</button>
        </form>

        <div class="message" id="message">Profil mis à jour avec succès ! ✅</div>
    </div>

    <script>
        const form = document.getElementById('updateForm');
        const message = document.getElementById('message');

        form.addEventListener('submit', function(e) {
            e.preventDefault();

            // Récupérer les valeurs du formulaire
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const bio = document.getElementById('bio').value;
            const photo = document.getElementById('photo').files[0];

            // Simulation d'update (ex: envoyer via AJAX à votre backend)
            setTimeout(() => {
                message.classList.add('show');

                // Masquer après 3 secondes
                setTimeout(() => {
                    message.classList.remove('show');
                }, 3000);

                // Reset formulaire si besoin
                // form.reset();
            }, 1000);
        });
    </script>
</body>
</html>
