<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<title>Meu perfil</title>

<style>
    /*Ira ser o seletor por tag*/
    body{
        background-color: #A1615A;
        front-family:Arial, sans-serif;
    }

    /*seleção por Id*/
    .destaque{
        color: darkblue;
        text-align:center;
    }

    .destaque{
        color:#4169E1;
        front-weight: bold;
    }

    /*seletor agrupado*/
    h2,p{
        margin-left: 20px;
    }

    /* =Seletor descendente*/
    div il li{
        color: #110A09
    }

    footer {
      text-align: left;
      padding: 10px;
      background-color: #A1615A;
      color: black;
    }
    
</style>
</head>

<body>
<h1 id="titulo">Meu perfil pessoal</h1>
<h2>Sobre mim</h2>

<p>Meu nome é <span class: destaque>João Vitor</span> e gosto de tecnologias diversas, seja elas atuais ou prototipos futuros</p>

<h2>Minhas metas de vida</h2>
<ul>
  <div>
  <li>Ingressar mo ramo de TI</li>
  <li>Trablhar com frontend com hmtl</li>
  <lI>Melhorar nos instrumentos</lI>
  <li>Ter uma moto</li>
  </div>
</ul>

<h2>Meus Hobbies</h2>
<ul>
<div>
<li>Ouvir Musicas</li>
<li>Programar</li>
<li>Musica erudita e atuais</li>
<li>Dormir</li>
<li>Tocar Violino e Violão</li>
</ul>
</div>

<footer>
  <p> Machado de Assis II</p>
</footer>

</body>
</html>