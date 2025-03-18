<?php
// Carrega as mensagens do arquivo JSON
$mensagens_file = 'mensagens.json';
$contador_file = 'contador.txt';

// Verifica e carrega o arquivo de mensagens
if (!file_exists($mensagens_file)) {
    die("Arquivo de mensagens não encontrado!");
}

$mensagens_json = file_get_contents($mensagens_file);
$mensagens = json_decode($mensagens_json, true);

if ($mensagens === null || !is_array($mensagens)) {
    die("Erro ao carregar mensagens!");
}

// Atualiza o contador de visitas
if (file_exists($contador_file)) {
    $contador = (int)file_get_contents($contador_file);
} else {
    $contador = 0;
}


// Seleciona a mensagem usando o contador
$indice = $contador % count($mensagens);

$mensagem = $mensagens[$indice];


// Atualiza o contador
file_put_contents($contador_file, $contador + 1);
?>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mensagens Rotativas</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #83a4d4, #b6fbff);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0;
        }
        .card {
            background: rgba(255, 255, 255, 0.9);
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 500px;
            backdrop-filter: blur(10px);
        }
        .mensagem {
            font-size: 1.5rem;
            color: #333;
            margin-bottom: 1rem;
        }
        .contador {
            color: #666;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="mensagem"><?= htmlspecialchars($mensagem["versiculo"]) ?></div>
        <div class="contador"> <?= htmlspecialchars($mensagem["localizacao"]) ?></div>
    </div>
</body>
</html>
