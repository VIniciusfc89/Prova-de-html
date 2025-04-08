<!DOCTYPE html>

<html>
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Quiz para programadores</title>
      <meta name="description" content="Quiz para testar seus conhecimentos" />
  </head>
  <body>
    <header>
      <h1>Quiz interativo para programadores </h1>
      <p>Teste seus conhecimentos para programação e veja qual sera sua pontuação!</p>
    </header>
    <main>
        <!--Introdução -->
      <section>
        <h2>Sobre esse quiz</h2>
        <p><strong>Este quiz</strong> foi desenvolvido para testar seus conhecimentos em programação, como <em> linguagem de programação</em>, conceitos basicos e mais</p>
         <p>Você encontrará diferentes tipos de perguntas, incluindo múltiplas escolhas, texto e perguntas de data.<br> Desafie-se com este quiz!</p>
        <p>Você poderá encontrar alguns acrônimos como <abbr title="Hypertext Markup Language">HTML</abbr> e <abbr title="Cascading Style Sheets">CSS</abbr>, que são comunente usados em questões relacionadas ao desenvolvimento web</p>
      </section>
      <!--Pergunta 1 : múltipla escolha-->
      <section>
        <h2>
        Pergunta 1: Qual a linguagem usada para estruturar páginas web?</h2>
        <form>
            <input type="radio" value="Python" id="p1a" title="Python"
            name="perguntas1">
            <label for="p1a">Python</label><br>
            <input type="radio" value="HTML" id="p1b" title="HTML"
            name="perguntas1">
            <label for="p1b">HTML</label><br>
            <input type="radio" value="Javascript" id="p1c" title="Javascript"
            name="perguntas1">
            <label for="p1c">Javascript</label><br>
            <input type="radio" value="Ruby" id="p1d" title="Ruby"
            name="perguntas1">
            <label for="p1d">Ruby</label><br>
        </form>
      </section>
       <!--Pergunta 2 : texto-->
      <section>
       <h2>Pergunta 2: na URL http://google.com o trecho é "google.com" é o _____ ? </h2>
       <form </form>
       <input type="text" id ="p2" name="perguntas2" placeholder="Digite sua resposta aqui">
      </form>
      </section>
      <!--Pergunta 3 : senha-->
      <section>
        <h2>Pergunta 3: Escreva um exemplo de senha forte</h2>
        <h2>
          <form>
            <input type="password" id="p3"
            name="perguntas3" placeholder="Digite uma senha..."></h2>
          </form>  
          </section>
      <!--Pergunta 4 : data-->
      <section>
        <h2>Pergunta 4: Em que ano HTML lançou sua primeira versão?</h2>
        <form>
          <input type="date" id="p4" name="perguntas4">

        </form>
      </section>
      <!--Pergunta 5 : seleção multipla-->
      <section>
        <h2>Pergunta 5: Quais  dessas tecnologias são consideradas linguagens de programação</h2>
        <form >
          <input type="checkbox" id="p5a" name="perguntas5" value="Javascript">
          <label for="p5a">Javascript</label><br>
          <input type="checkbox" id="p5b" name="perguntas5" value="HTML">
          <label for="p5b">HTML</label><br>
          <input type="checkbox" id="p5c" name="perguntas5" value="CSS">
          <label for="p5c">CSS</label><br>
          <input type="checkbox" id="p5d" name="perguntas5" value="Java">
          <label for="p5d">Java</label><br>
        </form>

      </section>
      <!--Pergunta 6 : Upload-->
      <section>
        <h2>pergunta 6: Faça o upload de um arquivo contendo codigo HTML</h2>
        <form>
          <input type="file" id="p6" name="perguntas6" accept=".html">
        </form>
        </h2>
      </section>
      <!--Pergunta 7 : Menu suspenso-->
      <section>
        <h2>Pergunta 7: Selecione o atributo do input que define o seu tipo:</h2>
        <form>
          <select name="pergunt7" id="p7">
            <option value="id">id</option>
            <option value="type">type</option>
            <option value="placeholder">placeholder</option>
          </select>
        </form>
      </section>
      <!--Pergunta 8 : Radio-->
      <section>
        <h2>Pergunta 8: Qual a linguagem de programação é representada pela logotipo abaixo?</h2>
        <img src=""
      </section>
    </main>
    <footer></footer>
  </body>
</html>
