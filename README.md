EXERCÍCIOS JAVASCRIPT (PARTE 1)

MODELO DE SITE

Tela de fundo azul, com um título. Vamos ter um rodapé. E no meio, vamos colocar algo funcionando. Background color, fica por conta do body. Titulo no header. Rodapé, com o footer. E no meio, criar uma section ou articler e divs. Então  no arquivo html em body vou ter header, section e footer. A div vai ficar dentro da section. E dentro de header, vou ter um h1 título. E o CSS3 vou fazer em um arquivo separado. Para isso no arquivo html, utilizo linkcss. E depois seguro crtl e clico no nome do arquivo e ele é criado. Exemplo:

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Modelo de Exercício</title>
</head>
<link rel="stylesheet" href="style.css">
<body>
  <header>
    <h1>Título</h1>
  </header>
  <section>
    <div>

    </div>
    <div>

    </div>
  </section>
  
  <footer>
    <p>&copy; Curso em Vídeo.</p>
  </footer>
  
</body>
</html>

Nesse arquivo style.css faço as alterações do meu site com css3.  EXEMPLO:

body {

}

header {

}

section {
  
}

header {

}

EXEMPLO COM ALTERAÇÕES

body {
  background: rgb(0, 0, 107);
  font: normal 15pt Arial;
}

header {
  color: rgb(255, 255, 255);
  text-align: center;

}

section {
  background: rgb(255, 255, 255);
  border-radius: 10px;
  padding: 15px;
  width: 500px;
  margin: auto;
  box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.397);

}

footer {
  color: rgb(255, 255, 255);
  text-align: center;
  font-style: italic;
}

Feito isso, agora no arquivo html faço um script. Mas escolho script:src para nossos arquivos em JS, também ficarem em arquivos separados. EXEMPLO:

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Modelo de Exercício</title>
</head>
<link rel="stylesheet" href="style.css">
<body>
  <header>
    <h1>Título</h1>
  </header>
  <section>
    <div>
      Testando...
    </div>
    <div>
      Olá
    </div>
  </section>
  
  <footer>
    <p>&copy; Curso em Vídeo.</p>
  </footer>
  
  <script src="script.js"></script>
</body>
</html>


