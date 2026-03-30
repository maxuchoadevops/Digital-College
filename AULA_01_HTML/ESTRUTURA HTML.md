<!DOCTYPE html>
<!-- Declaração do tipo de documento: define que é HTML5 -->

<html lang="pt-BR">
<!-- Elemento raiz da página. lang define o idioma -->

<head>
  <!-- Cabeçalho: contém metadados e configurações -->

  <meta charset="UTF-8">
  <!-- Define a codificação de caracteres (UTF-8 suporta acentos) -->

  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Responsividade: adapta para dispositivos móveis -->

  <title>Guia HTML Completo</title>
  <!-- Título da aba do navegador -->

  <link rel="stylesheet" href="style.css">
  <!-- Importa um arquivo CSS externo -->

  <style>
    /* CSS interno */
    body { font-family: Arial; }
  </style>

  <script>
    // JavaScript interno
    function exemplo() {
      alert('Função JS funcionando!');
    }
  </script>
</head>

<body>
  <!-- Corpo da página: tudo que aparece para o usuário -->

  <header>
    <!-- Cabeçalho da página -->
    <h1>Título Principal</h1>
  </header>

  <nav>
    <!-- Menu de navegação -->
    <a href="#">Link</a>
  </nav>

  <main>
    <!-- Conteúdo principal -->

    <section>
      <!-- Seção temática -->
      <h2>Seção</h2>
      <p>Parágrafo de texto</p>
    </section>

    <article>
      <!-- Conteúdo independente (ex: blog) -->
      <h2>Artigo</h2>
      <p>Conteúdo do artigo</p>
    </article>

    <aside>
      <!-- Conteúdo lateral -->
      <p>Barra lateral</p>
    </aside>

    <figure>
      <!-- Agrupa mídia -->
      <img src="imagem.jpg" alt="Descrição">
      <figcaption>Legenda da imagem</figcaption>
    </figure>

    <audio controls>
      <!-- Player de áudio -->
      <source src="audio.mp3" type="audio/mpeg">
    </audio>

    <video controls width="300">
      <!-- Player de vídeo -->
      <source src="video.mp4" type="video/mp4">
    </video>

    <form>
      <!-- Formulário -->

      <label for="nome">Nome:</label>
      <!-- Rótulo de campo -->

      <input type="text" id="nome" name="nome">
      <!-- Campo de entrada -->

      <textarea></textarea>
      <!-- Área de texto -->

      <select>
        <!-- Lista suspensa -->
        <option>Opção 1</option>
      </select>

      <button type="submit">Enviar</button>
      <!-- Botão -->
    </form>

    <table border="1">
      <!-- Tabela -->

      <thead>
        <!-- Cabeçalho da tabela -->
        <tr>
          <th>Coluna 1</th>
        </tr>
      </thead>

      <tbody>
        <!-- Corpo da tabela -->
        <tr>
          <td>Dado</td>
        </tr>
      </tbody>

      <tfoot>
        <!-- Rodapé da tabela -->
        <tr>
          <td>Resumo</td>
        </tr>
      </tfoot>
    </table>

    <ul>
      <!-- Lista não ordenada -->
      <li>Item</li>
    </ul>

    <ol>
      <!-- Lista ordenada -->
      <li>Item</li>
    </ol>

    <dl>
      <!-- Lista de definição -->
      <dt>Termo</dt>
      <dd>Descrição</dd>
    </dl>

    <progress value="50" max="100"></progress>
    <!-- Barra de progresso -->

    <meter value="0.6"></meter>
    <!-- Medidor -->

    <details>
      <!-- Conteúdo expansível -->
      <summary>Mais info</summary>
      <p>Detalhes ocultos</p>
    </details>

    <canvas id="meuCanvas"></canvas>
    <!-- Área para gráficos via JS -->

    <iframe src="https://example.com"></iframe>
    <!-- Incorpora outra página -->

  </main>

  <footer>
    <!-- Rodapé -->
    <p>© 2026</p>
  </footer>

  <script src="script.js"></script>
  <!-- Importa JS externo -->

</body>

</html>
