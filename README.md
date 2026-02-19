<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Update Profil</title>
<link rel="stylesheet" href="style.css">
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

<script src="script.js"></script>
</body>
</html>
