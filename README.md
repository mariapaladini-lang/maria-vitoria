<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport"
  content="width=device-width, initial-scale=1.0" />
  <meta name="description"
  content="Blog sobre tecnologia e programação - por " />
  <title>Blog Tech - Estefany Potmaier</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f9;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
      min-height: 100vh;
    }

    /* Container principal - centralizado */
    .container {
      max-width: 800px;
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    /* Cabeçalho */
    header {
      background-color: #183c63;
      color: #ffffff;
      padding: 24px 16px;
      border: 5px solid #cf1010;
      border-radius: 12px 12px 0 0;
      text-align: center;
      width: 100%;
    }

    header h1 {
      font-size: 2.2rem;
      letter-spacing: 1px;
      margin-bottom: 6px;
    }

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport"
  content="width=device-width, initial-scale=1.0" />
  <meta name="description"
  content="Blog sobre tecnologia e programação - por " />
  <title>Blog Tech - Estefany Potmaier</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f9;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
      min-height: 100vh;
    }

    /* Container principal - centralizado */
    .container {
      max-width: 800px;
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    /* Cabeçalho */
    header {
      background-color: #183c63;
      color: #ffffff;
      padding: 24px 16px;
      border: 5px solid #cf1010;
      border-radius: 12px 12px 0 0;
      text-align: center;
      width: 100%;
    }

    header h1 {
      font-size: 2.2rem;
      letter-spacing: 1px;
      margin-bottom: 6px;
    }

.botoes-like {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
  flex-wrap: wrap;
}

.botoes-like button {
  background: #f0f0f5;
  border: none;
  border-radius: 30px;
  padding: 10px 24px;
  font-size: 1.2rem;
  font-weight: 600;
  color: #1a1a2e;
  cursor: pointer;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  transition: background 0.2s, transform 0.1s;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.08);
}

.botoes-like button:hover {
  background: #e0e0ea;
  transform: scale(1.02);
}

.botoes-like button:active {
  transform: scale(0.96);
}

.botoes-like button span {
  background: #183c63;
  color: #fff;
  border-radius: 20px;
  padding: 0 12px;
  font-size: 1rem;
  line-height: 1.8;
  min-width: 28px;
  text-align: center;
}

/* Rodapé */
footer {
  max-width: 800px;
  width: 100%;
  margin-top: 24px;
  text-align: center;
  color: #5c70ca;
  padding: 12px 0;
  border-top: 2px solid #cf1010;
}

 font-size: 0.9rem;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <!-- Cabeçalho -->
      <header>
        <img
          class="logo"
          src="
        />
        <h1>  Meu blog tech</h1>
        <p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>
      </header>

      <!-- Conteúdo principal -->
      <main>
        <img
          class="destaque"
          src="
        />

        <h2>Meu primeiro post</h2>
        <p class="autor">Por: Ana Clara Goulart</p>
        <p>
          Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação e curiosidades da área de tecnologia.
        </p>
        <p>
          Fique por dentro das novidades sobre HTML, CSS, JavaScript e muito mais!
        </p>

        <!-- Botões de like (unidos do segundo código) -->
        <div class="botoes-like">
          <button id="like-coracao"><span>0</span></button>
          <button id="like-joinha"><span>0</span></button>
        </div>
      </main>
    </div>

    <!-- Rodapé -->
    <footer>
      <p>© 2026 - Blog da professora Estefany Potmaier | Todos os direitos reservados</p>
    </footer>
<!-- Script para contagem de likes -->
<script>
  const botoes = document.querySelectorAll('.botoes-like button');

  botoes.forEach(function (botao) {
    botao.addEventListener('click', function () {
      const span = botao.querySelector('span');
      span.textContent = parseInt(span.textContent, 10) + 1;
    });
  });
</script>
</body>
</html>