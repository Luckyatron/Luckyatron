<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aplicativo de Registro Financeiro</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="container">
  <h1>Aplicativo de Registro Financeiro</h1>
  
  <!-- Formulário de registro financeiro -->
  <form id="registration-form">
    <div class="form-group">
      <label for="amount" class="label">Valor:</label>
      <input type="number" id="amount" name="amount" class="input-field" placeholder="Digite o valor">
    </div>
    
    <button type="submit" class="button">Registrar</button>
  </form>
  
  <!-- Calculadora -->
  <div class="calculator">
    <h2>Calculadora Automática</h2>
    <div class="result" id="result"></div>
  </div>
</div>

</body>
</html>
