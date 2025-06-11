# <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cartaz sobre Alimentação Saudável</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .cartaz {
            background-color: #ffebcd;
            border: 3px solid #008000;
            border-radius: 15px;
            width: 70%;
            max-width: 700px;
            padding: 30px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        h1 {
            color: #008000;
            font-size: 36px;
        }
        h2 {
            color: #d2691e;
            font-size: 28px;
        }
        p {
            color: #333;
            font-size: 18px;
            line-height: 1.6;
        }
        .imagem {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 20px 0;
        }
        .botao {
            background-color: #008000;
            color: white;
            padding: 15px 25px;
            font-size: 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
            transition: background-color 0.3s;
        }
        .botao:hover {
            background-color: #006400;
        }
    </style>
</head>
<body>

    <div class="cartaz">
        <h1>Alimentação Saudável</h1>
        <h2>Cuide do seu corpo, ele é o único lugar que você tem para viver!</h2>
        <img src="https://via.placeholder.com/600x300?text=Coma+Saudável" alt="Alimentos saudáveis" class="imagem">
        <p>
            A alimentação saudável é essencial para manter o corpo e a mente em equilíbrio. Inclua frutas, vegetais, grãos integrais e proteínas magras em sua dieta diária. Evite alimentos processados e ricos em açúcar. Lembre-se de beber bastante água e praticar atividades físicas regularmente!
        </p>
        <a href="https://www.exemplo.com/saude" class="botao">Saiba Mais</a>
    </div>

</body>
</html>
