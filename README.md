<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bet013 - Painel Oficial</title>
    <style>
        body { font-family: sans-serif; background-color: #1a1a1a; color: #ff8c00; text-align: center; padding: 20px; }
        .card { background: #262626; border: 2px solid #ff8c00; border-radius: 15px; padding: 20px; margin: 20px auto; max-width: 400px; }
        button { background: #ff8c00; color: #000; border: none; padding: 12px; border-radius: 8px; font-weight: bold; cursor: pointer; width: 100%; }
        input { width: 90%; padding: 10px; margin: 10px 0; border-radius: 5px; border: none; background: #333; color: white; }
        h1 { text-transform: uppercase; letter-spacing: 2px; }
    </style>
</head>
<body>
    <h1>B E T 0 1 3</h1>
    <div class="card">
        <h3>Lançar Novo Jogo</h3>
        <input type="text" id="jogo" placeholder="Ex: Santos x Corinthians">
        <input type="number" id="odd" placeholder="Cotação (Ex: 2.50)">
        <button onclick="alert('Jogo enviado para o APK Bet013!')">PUBLICAR NO APK</button>
    </div>
</body>
</html>
