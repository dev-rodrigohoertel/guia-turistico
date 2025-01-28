<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barcelona em turismo</title>
    <link rel="stylesheet" href="style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Alice&family=Bitter:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
</head>
<body>
    <div id="page">
        <img src="https://res.cloudinary.com/worldpackers/image/upload/c_fill,f_auto,q_auto,w_1024/v1/guides/article_cover/fdyt465ibow1fkqquu8v" alt="Foto de barcelona no por do sol">
    <main>
        <h1>Barcelona - Um guia turístico rápido:</h1>
        
        <section id="do">
            <h2>- O que fazer?</h2>
            <h3>Principais atrações</h3>
            <ul>
                <li> Sagrada Família: Obra de Gaudí, imperdível. </li>
                <li> Parque Güell: Mosaicos coloridos e vista panorâmica. </li>
                <li> La Rambla: Rua movimentada com lojas e o Mercado da Boqueria. </li>
                <li> Bairro Gótico: Ruas estreitas, Catedral de Barcelona e Plaça del Rei. </li>
                <li> Casa Batlló e La Pedrera: Arquitetura modernista de Gaudí. </li>
            </ul>
            <h3>
                Museus
            </h3>
            <ul>
                <li> Museu Picasso: Obras do artista em Barcelona. </li>
                <li> MNAC: Arte românica, renascentista e barroca. </li>
            </ul>
            <h3>
                Onde comer?
            </h3>
            <ul>
                <li> Tapas: Não perca as patatas bravas e pintxos em El Born. </li>
                <li> Paella: Restaurantes em Barceloneta. </li>
                <li> Churros: Com chocolate quente, uma delícia local. </li>
            </ul>
        </section>

        <section id="road-map">
            <h2>- Roteiro completo para 1 dia</h2>
            <p>
              <strong>Manhã:</strong> Sagrada Família e Parque Güell. <br>
                <strong>Almoço:</strong> Paella em Barceloneta. <br>
                <strong>Tarde:</strong> Bairro Gótico e Museu Picasso. <br>
                <strong>Final de Tarde:</strong> Praia ou Montjuïc. <br>
                <strong>Noite:</strong> Jantar em El Born e passeio por La Rambla. <br>
            </p>
        </section>
            
    </main>
    </div>
</body>

<footer>
    &copy; All rights reserved Rodrigo Hoertel  
</footer>
</html>

body {
    background: linear-gradient(
        90deg,
        rgb(241, 188, 88) 0%,
        rgb(241, 94, 94) 100%
    );
    background-size: cover;
}

#page {
    font-family: "Bitter", serif;
    color: rgb(112, 13, 13);
}

#page {
    width: 800px;
    padding: 24px;
    background-color: rgb(199, 148, 82);
    border-radius: 20px;
    margin: 48px auto; 
}

#page img {
    box-sizing: border-box;
    width: 700px;
    border-radius: 20px ;
    padding-left: 100px;
}

h1 {
    font-size: 43px;
    text-align: center;
    font-style: italic;
    text-decoration: underline;
}

h3, p {
    padding-left: 20px;
}

#do h2 {
    margin-top: 40px;
}

#road-map h2 {
    margin-top: 40px;
}

h3 {
    font-size: 20px;
}

h2 {
    font-size: 30px;
    text-decoration: underline;
}

footer {
    text-align: center;
    color: rgb(54, 2, 2);
    padding: 20px;
}
