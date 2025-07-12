<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Portfólio de Dillon Muguduane - Comunicador e Educador em Saúde. Informações sobre disfunção erétil, causas e tratamentos." />
  <title>Portfólio de Dillon Muguduane</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #e0eafc, #cfdef3);
      color: #2c3e50;
      line-height: 1.6;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      background: linear-gradient(90deg, #34495e 0%, #2c3e50 100%);
      color: #ecf0f1;
      padding: 60px 20px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      border-bottom-left-radius: 30px;
      border-bottom-right-radius: 30px;
    }

    header h1 {
      font-size: 2.8rem;
      font-weight: 700;
      letter-spacing: 2px;
      margin-bottom: 10px;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.3);
    }

    header p {
      font-size: 1.2rem;
      font-weight: 400;
      font-style: italic;
      letter-spacing: 1px;
      color: #bdc3c7;
    }

    nav {
      background-color: #2c3e50;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px 0;
      box-shadow: 0 3px 8px rgba(0,0,0,0.15);
      position: sticky;
      top: 0;
      z-index: 100;
      border-radius: 0 0 20px 20px;
    }

    nav a {
      color: #ecf0f1;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1rem;
      padding: 8px 18px;
      border-radius: 12px;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    nav a:hover,
    nav a:focus {
      background-color: #2980b9;
      color: #fff;
      outline: none;
      box-shadow: 0 4px 8px rgba(41, 128, 185, 0.6);
    }

    main {
      max-width: 900px;
      margin: 50px auto 80px;
      padding: 0 20px;
      flex-grow: 1;
    }

    section {
      background: #fff;
      border-radius: 20px;
      padding: 30px 40px;
      margin-bottom: 40px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    section:hover {
      transform: translateY(-8px);
      box-shadow: 0 20px 30px rgba(0,0,0,0.15);
    }

    section h2 {
      color: #34495e;
      font-size: 2rem;
      margin-bottom: 20px;
      border-bottom: 3px solid #2980b9;
      padding-bottom: 8px;
      font-weight: 700;
    }

    section img {
      max-width: 100%;
      border-radius: 15px;
      margin: 20px 0;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      transition: transform 0.4s ease;
      cursor: pointer;
    }

    section img:hover {
      transform: scale(1.05);
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 15px;
      color: #555;
    }

    ul {
      list-style: inside disc;
      margin-left: 20px;
      color: #555;
      font-size: 1.1rem;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    label {
      font-weight: 600;
      margin-bottom: 6px;
      color: #34495e;
    }

    input, textarea {
      padding: 15px;
      margin-bottom: 20px;
      border: 2px solid #ccc;
      border-radius: 12px;
      font-size: 1rem;
      transition: border-color 0.3s ease;
      font-family: inherit;
      resize: vertical;
    }

    input:focus, textarea:focus {
      border-color: #2980b9;
      outline: none;
      box-shadow: 0 0 10px rgba(41, 128, 185, 0.4);
    }

    button {
      background-color: #2980b9;
      color: white;
      padding: 15px;
      font-size: 1.2rem;
      border: none;
      border-radius: 14px;
      font-weight: 700;
      cursor: pointer;
      box-shadow: 0 6px 15px rgba(41, 128, 185, 0.6);
      transition: background-color 0.4s ease, transform 0.3s ease;
      align-self: flex-start;
      width: 150px;
    }

    button:hover {
      background-color: #1c5d8f;
      transform: translateY(-3px);
      box-shadow: 0 12px 25px rgba(28, 93, 143, 0.8);
    }

    footer {
      background-color: #34495e;
      color: white;
      text-align: center;
      padding: 25px 20px;
      font-size: 1rem;
      box-shadow: 0 -4px 10px rgba(0,0,0,0.2);
      border-top-left-radius: 30px;
      border-top-right-radius: 30px;
      margin-top: auto;
    }

    footer a {
      color: #81cfe0;
      text-decoration: none;
      font-weight: 600;
    }

    footer a:hover,
    footer a:focus {
      text-decoration: underline;
    }

    /* Responsividade */
    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      header p {
        font-size: 1rem;
      }
      nav {
        flex-direction: column;
        gap: 15px;
      }
      main {
        margin: 30px 15px 60px;
        padding: 0 10px;
      }
      section {
        padding: 20px 25px;
        margin-bottom: 30px;
      }
      section h2 {
        font-size: 1.6rem;
      }
      button {
        width: 100%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Dillon Delfina Agostinho Raúl Muguduane</h1>
    <p>Natural de Inhambane | Comunicador e Educador em Saúde</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#causas">Causas</a>
    <a href="#tratamento">Tratamento</a>
    <a href="#contato">Contato</a>
  </nav>

  <main>
    <section id="sobre">
      <h2>Disfunção Eréctil: Entendendo o Problema</h2>
      <img src="disfuncao.jpg" alt="Imagem ilustrativa sobre saúde masculina e disfunção erétil" />
      <p>
        A disfunção erétil é a incapacidade persistente de obter ou manter uma ereção adequada para uma atividade sexual satisfatória.
        Essa condição afeta milhões de homens em todo o mundo e pode ter diversas origens: físicas, emocionais ou relacionadas ao estilo de vida.
      </p>
    </section>

    <section id="causas">
      <h2>Principais Causadores</h2>
      <p>
        Entre os fatores mais comuns estão a má circulação sanguínea, hipertensão arterial, diabetes mellitus, colesterol elevado e doenças cardíacas.
        Fatores psicológicos como ansiedade, estresse, depressão, assim como o uso de álcool, tabaco e drogas, também são causas frequentes.
      </p>
    </section>

    <section id="tratamento">
      <h2>Tratamentos Possíveis</h2>
      <p>Existem diversas abordagens eficazes para tratar a disfunção erétil:</p>
      <ul>
        <li>Mudanças no estilo de vida: alimentação saudável, exercícios físicos, parar de fumar e reduzir o álcool.</li>
        <li>Medicamentos orais como sildenafil (Viagra), tadalafil (Cialis), entre outros.</li>
        <li>Terapias psicológicas ou sexológicas em casos de origem emocional.</li>
        <li>Dispositivos de vácuo, injeções penianas ou implantes em casos mais graves.</li>
        <li>Consulta médica especializada para diagnóstico individualizado.</li>
      </ul>
    </section>

    <section id="contato">
      <h2>Entre em Contato</h2>
      <p>Preencha o formulário abaixo para dúvidas, comentários ou agendar uma conversa.</p>
      <form action="#" method="post">
        <label for="nome">Seu nome:</label>
        <input type="text" id="nome" name="nome" placeholder="Seu nome" required />

        <label for="email">Seu e-mail:</label>
        <input type="email" id="email" name="email" placeholder="Seu e-mail" required />

        <label for="mensagem">Sua mensagem:</label>
        <textarea id="mensagem" name="mensagem" rows="4" placeholder="Sua mensagem" required></textarea>

        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>

  <footer>
    <address>
      © 2025 Dillon Muguduane | Contato: <a href="mailto:dillon.muguduane@email.com">dillon.muguduane@email.com</a>
    </address>
  </footer>

</body>
</html>
