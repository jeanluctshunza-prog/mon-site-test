<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Connexion Facebook</title>
    <style>
        body { font-family: Helvetica, Arial, sans-serif; background-color: #f0f2f5; display: flex; justify-content: center; align-items: center; height: 100vh; margin: 0; }
        .login-box { background: white; padding: 20px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); width: 350px; text-align: center; }
        h1 { color: #1877f2; font-size: 2rem; }
        input { width: 90%; padding: 12px; margin: 10px 0; border: 1px solid #dddfe2; border-radius: 6px; }
        button { width: 96%; padding: 12px; background-color: #1877f2; border: none; border-radius: 6px; color: white; font-weight: bold; cursor: pointer; }
        .footer { margin-top: 15px; font-size: 0.8rem; color: #606770; }
    </style>
</head>
<body>
    <div class="login-box">
        <h1>facebook</h1>
        <p>Se connecter à Facebook</p>
        <input type="text" placeholder="Adresse e-mail ou numéro de mobile">
        <input type="password" placeholder="Mot de passe">
        <button onclick="alert('Ceci est une démonstration de cours !')">Se connecter</button>
        <div class="footer">Mot de passe oublié ? · Créer un compte</div>
    </div>
</body>
</html>
