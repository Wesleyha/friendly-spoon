<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blog sobre Racismo Ambiental</title>
  <style>
    body { font-family: Arial, sans-serif; background-color: #f9f9f9; margin: 0; line-height: 1.6; }
    header, footer { background-color: #2c7a7b; color: white; text-align: center; padding: 20px; position: relative; }
    main { max-width: 900px; margin: 20px auto; padding: 0 20px; }
    .post { background-color: white; border-radius: 8px; padding: 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    .post h2 { margin-top: 0; color: #2c7a7b; }
    ul { padding-left: 20px; }
    a { color: #2c7a7b; text-decoration: none; }
    a:hover { text-decoration: underline; }

    /* Menu hambúrguer */
    .menu-btn { position: absolute; top: 20px; right: 20px; cursor: pointer; font-size: 28px; }
    .menu { display: none; position: absolute; top: 60px; right: 20px; background: white; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.2); }
    .menu a { display: block; padding: 10px 20px; color: #2c7a7b; font-weight: bold; }
    .menu a:hover { background: #e6f2f2; }
    .active { display: block; }

    /* Seções */
    .section { display: none; }
    .section.active { display: block; }

    /* Chat IA */
    #messages { background:#f1f1f1; padding:10px; border-radius:8px; height:300px; overflow-y:auto; margin-bottom:10px; }
    #userInput { width:70%; padding:8px; }
    #chat button { padding:8px 12px; background:#2c7a7b; color:white; border:none; border-radius:6px; cursor:pointer; }
    #chat button:hover { background:#25696a; }
  </style>
</head>
<body>
  <header>
    <h1>Blog Educativo sobre Racismo Ambiental</h1>
    <!-- Botão do menu -->
    <div class="menu-btn" id="menuBtn">☰</div>
    <!-- Menu suspenso -->
    <div class="menu" id="menu">
      <a href="#" onclick="showSection('posts')">Posts</a>
      <a href="#" onclick="showSection('jogos')">Jogos</a>
      <a href="#" onclick="showSection('chat')">Chat IA</a>
    </div>
  </header>

  <main>
    <!-- Seção de Posts -->
    <div id="posts" class="section active">
      <div class="post"><h2>1. O que é racismo ambiental?</h2><p>Racismo ambiental é a prática de expor comunidades racializadas e vulneráveis a maiores riscos ambientais.</p></div>
      <div class="post"><h2>2. Exemplos históricos</h2><p>Muitas comunidades pobres e negras foram forçadas a viver perto de lixões, fábricas poluentes e rios contaminados.</p></div>
      <div class="post"><h2>3. Justiça ambiental</h2><p>É o movimento que luta pelo direito de todas as pessoas viverem em um ambiente limpo e saudável.</p></div>
      <div class="post"><h2>4. Consequências na saúde</h2><p>O racismo ambiental causa doenças respiratórias, câncer e baixa qualidade de vida em comunidades afetadas.</p></div>
      <div class="post"><h2>5. A luta das comunidades</h2><p>Muitos grupos locais se organizam para denunciar abusos e exigir políticas públicas justas.</p></div>
      <div class="post"><h2>6. O papel da educação</h2><p>A conscientização ajuda a identificar práticas racistas e buscar soluções sustentáveis.</p></div>
      <div class="post"><h2>7. Impacto nas periferias</h2><p>Áreas periféricas sofrem mais com enchentes, falta de saneamento e poluição.</p></div>
      <div class="post"><h2>8. Questão indígena</h2><p>Povos indígenas sofrem invasões de terras, desmatamento e contaminação de rios por mineração.</p></div>
      <div class="post"><h2>9. Racismo ambiental e gênero</h2><p>Mulheres em comunidades vulneráveis são as mais afetadas pela precariedade ambiental.</p></div>
      <div class="post"><h2>10. Políticas públicas necessárias</h2><p>É essencial criar leis que protejam as populações vulneráveis de danos ambientais.</p></div>
      <div class="post"><h2>11. Participação cidadã</h2><p>A mobilização social é fundamental para denunciar práticas de racismo ambiental.</p></div>
      <div class="post"><h2>12. Casos no Brasil</h2><p>Comunidades quilombolas e indígenas frequentemente enfrentam impactos ambientais injustos.</p></div>
      <div class="post"><h2>13. Casos no mundo</h2><p>Nos EUA, bairros negros historicamente sofrem mais com poluição do ar e da água.</p></div>
      <div class="post"><h2>14. Racismo ambiental urbano</h2><p>Nas cidades, áreas de risco de enchentes e deslizamentos afetam principalmente os mais pobres.</p></div>
      <div class="post"><h2>15. Racismo ambiental rural</h2><p>No campo, comunidades rurais sofrem com agrotóxicos e destruição ambiental.</p></div>
      <div class="post"><h2>16. A importância da mídia</h2><p>A divulgação de casos ajuda a pressionar governos e empresas por mudanças.</p></div>
      <div class="post"><h2>17. Racismo ambiental e clima</h2><p>Mudanças climáticas atingem de forma desigual populações vulneráveis.</p></div>
      <div class="post"><h2>18. Organizações e ONGs</h2><p>Muitas ONGs trabalham para combater o racismo ambiental e apoiar comunidades.</p></div>
      <div class="post"><h2>19. Ação individual</h2><p>Cada pessoa pode ajudar através da conscientização, mobilização e cobrança de políticas públicas.</p></div>
      <div class="post"><h2>20. Futuro sustentável</h2><p>Um mundo sem racismo ambiental é aquele em que todos têm direito ao mesmo ambiente saudável.</p></div>
      <div class="post"><h2>21. Conclusão</h2><p>O racismo ambiental é uma injustiça social e ambiental que precisa ser combatida coletivamente.</p></div>
    </div>

    <!-- Seção de Jogos -->
    <div id="jogos" class="section">
      <div class="post">
        <h2>Quiz e Jogos Interativos</h2>
        <p>Participe dos jogos e teste seus conhecimentos sobre racismo ambiental:</p>
        <ul>
          <li><a href="https://wordwall.net/pt/resource/95396523" target="_blank">Quiz 1 – Racismo Ambiental</a></li>
          <li><a href="https://wordwall.net/pt/resource/94835993" target="_blank">Quiz 2 – Justiça Ambiental</a></li>
        </ul>
      </div>
    </div>

    <!-- Seção de Chat IA -->
    <div id="chat" class="section">
      <div class="post">
        <h2>🤖 Converse com a IA</h2>
        <div id="messages"></div>
        <input type="text" id="userInput" placeholder="Digite sua pergunta...">
        <button onclick="sendMessage()">Enviar</button>
      </div>
    </div>
  </main>

  <footer>
    © 2025 Blog Educativo sobre Racismo Ambiental
  </footer>

  <script>
    const menuBtn = document.getElementById("menuBtn");
    const menu = document.getElementById("menu");

    menuBtn.addEventListener("click", () => {
      menu.classList.toggle("active");
    });

    function showSection(sectionId) {
      document.querySelectorAll(".section").forEach(sec => sec.classList.remove("active"));
      document.getElementById(sectionId).classList.add("active");
      menu.classList.remove("active");
    }

    // Função Chat IA
    async function sendMessage() {
      const input = document.getElementById("userInput");
      const message = input.value.trim();
      if (!message) return;
      input.value = "";

      const messagesDiv = document.getElementById("messages");
      messagesDiv.innerHTML += "<p><b>Você:</b> " + message + "</p>";

      try {
        const response = await fetch("https://api.openai.com/v1/chat/completions", {
          method: "POST",
          headers: {
            "Content-Type": "application/json",
            "Authorization": "Bearer SUA_CHAVE_API_AQUI"
          },
          body: JSON.stringify({
            model: "gpt-3.5-turbo",
            messages: [{ role: "user", content: message }]
          })
        });

        const data = await response.json();
        const reply = data.choices[0].message.content;

        messagesDiv.innerHTML += "<p><b>IA:</b> " + reply + "</p>";
        messagesDiv.scrollTop = messagesDiv.scrollHeight;
      } catch (error) {
        messagesDiv.innerHTML += "<p style='color:red'><b>Erro:</b> não foi possível conectar à IA.</p>";
      }
    }
  </script>
</body>
</html>
