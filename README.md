# CODES

<!DOCTYPE html>
<html lang="pt-br">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Meus objetivos do ano</title>
</head>
<body>
 <section class="conteudo-principal">
   <h2 class="titulo-principal">Meus Objetivos do ano_</h2>
   <div class="botoes">
     <button class="botao">Cursos na Alura</button>
     <button class="botao">Criar projetos em JavaScript</button>
     <button class="botao">Criar um portfólio</button>
     <button class="botao">Atualizar meu currículo</button>
   </div>
 </section>
</body>
</html>
 

css
@import url('https://fonts.googleapis.com/css?family=Chakra+Petch:wght@400;700&display=swap');


:root {
 --cor-de-fundo: #161618;
 --verde: #6FFF57;
 --branco: #FFFFFF;
 --botao-ativo: #3A375E;
 --botao-inativo: rgba(58, 55, 94, 0.5);
 --texto-fundo: rgba(58, 55, 94, 0.3);
}


body {
 background-color: var(--cor-de-fundo);
 color: var(--branco);
 font-family: 'Chakra Petch', sans-serif;
}
.conteudo-principal { 

display: flex;
 flex-direction: column;
 justify-content: center;
 align-items: center;
 max-width: 1200px;
 width: 100%;
 margin: 0 auto;
}


 .titulo-principal {
   text-align: left;
   width: 100%;
   font-size: 32px;
}


.titulo-principal span {
 color: var(--verde);
}



