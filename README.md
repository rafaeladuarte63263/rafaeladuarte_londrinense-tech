# rafaeladuarte_londrinense-tech



<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>App Bancário</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fce4ec;
      margin: 0;
      padding: 20px;
      display: flex;
      gap: 20px;
    }

    .tela {
      background-color: #ffeef2;
      border-radius: 15px;
      padding: 20px;
      width: 300px;
    }

    .perfil {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
      font-weight: bold;
    }

    .bloco {
      background-color: white;
      padding: 15px;
      border-radius: 10px;
      margin-bottom: 10px;
      box-shadow: 0 1px 5px rgba(0,0,0,0.1);
    }

    .botoes {
      display: flex;
      justify-content: space-between;
      margin-bottom: 20px;
    }

    .botao {
      background-color: white;
      border-radius: 10px;
      padding: 15px;
      flex: 1;
      text-align: center;
      margin: 5px;
      box-shadow: 0 1px 5px rgba(0,0,0,0.1);
    }

    .transacoes {
      background-color: #f8b7c3;
      padding: 15px;
      border-radius: 10px;
    }

    .transacao {
      background-color: white;
      padding: 10px;
      border-radius: 8px;
      margin-bottom: 10px;
      display: flex;
      justify-content: space-between;
    }

    .icones {
      display: flex;
      justify-content: space-around;
      margin-bottom: 15px;
    }

    .icone {
      background-color: #f8b7c3;
      padding: 10px;
      border-radius: 50%;
    }
  </style>
</head>
<body>

  <!-- Tela 1 -->
  <div class="tela">
    <div class="perfil">👤 seu perfil</div>
    <div class="bloco">
      <p>saldo</p>
      <h3>R$ 1.000.000</h3>
      <small>limite da conta ></small>
    </div>
    <div class="botoes">
      <div class="botao">pix e transferir</div>
      <div class="botao">pagar</div>
      <div class="botao">segurança</div>
    </div>
    <div class="bloco">
      <p>cartão de crédito ></p>
    </div>
  </div class= "top-right"> 
   <a href="home.html">home</a> 
</body>
</html>












home.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
          font-family: Arial, sans-serif;
          background-color: #fce4ec;
          margin: 0;
          padding: 20px;
          display: flex;
          gap: 20px;
        }
    
        .tela {
          background-color: #ffeef2;
          border-radius: 15px;
          padding: 20px;
          width: 300px;
        }
    
        .perfil {
          display: flex;
          align-items: center;
          margin-bottom: 20px;
          font-weight: bold;
        }
    
        .bloco {
          background-color: white;
          padding: 15px;
          border-radius: 10px;
          margin-bottom: 10px;
          box-shadow: 0 1px 5px rgba(0,0,0,0.1);
        }
    
        .botoes {
          display: flex;
          justify-content: space-between;
          margin-bottom: 20px;
        }
    
        .botao {
          background-color: white;
          border-radius: 10px;
          padding: 15px;
          flex: 1;
          text-align: center;
          margin: 5px;
          box-shadow: 0 1px 5px rgba(0,0,0,0.1);
        }
    
        .transacoes {
          background-color: #f8b7c3;
          padding: 15px;
          border-radius: 10px;
        }
    
        .transacao {
          background-color: white;
          padding: 10px;
          border-radius: 8px;
          margin-bottom: 10px;
          display: flex;
          justify-content: space-between;
        }
    
        .icones {
          display: flex;
          justify-content: space-around;
          margin-bottom: 15px;
        }
    
        .icone {
          background-color: #f8b7c3;
          padding: 10px;
          border-radius: 50%;
        }
      </style>
</head>
<body>
    <!-- Tela 2 -->
  <div class="tela">
    <div style="text-align: center; margin-bottom: 10px;">
      <strong>seu saldo</strong><br>
      <h2>R$1.000.000</h2>
    </div>

    <div class="icones">
      <div class="icone">⬆️</div>
      <div class="icone">⬇️</div>
      <div class="icone">📋</div>
      <div class="icone">➕</div>
    </div>

    <div class="transacoes">
      <p><strong>transações</strong></p>
      <div class="transacao">
        <span>fulano<br><small>ter 13:30</small></span>
        <span>+R$3.000</span>
      </div>
      <div class="transacao">
        <span>ciclano<br><small>seg 23:40</small></span>
        <span>+R$250.000</span>
      </div>
      <div class="transacao">
        <span>beltrano<br><small>dom 12:38</small></span>
        <span>+R$10.000</span>
      </div>
    </div>
  </div>

</body>
</html>
