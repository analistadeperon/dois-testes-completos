# dois-testes-completos
<html>
<head>
<title> Cadastro de Usuário e Pet </title>
</head>
<body>
<form method="POST" action="cadastro.php">
<label>Login:</label><input type="text" name="login" id="login"><br>
<label>Senha:</label><input type="password" name="senha" id="senha"><br>
<input type="submit" value="Cadastrar" id="cadastrar" name="cadastrar">
</form>
</body>
</html>

<button>aperte o botao 1 pra cadastrar novos contatos pessoais </button>
functions [class]="dados pessoais"
<div>nome completo</div>
<div>Telefone</div>
<div>endereço</div>
<div>email</div>
<div>local onde mora</div>

<html>
<head>
<title> Cadastro do seu Pet com pedigree </title>
</head>
<body>
<form method="POST" action="cadastro.php">
<label>Login:</label><input type="text" name="login" id="login"><br>
<label>Senha:</label><input type="password" name="senha" id="senha"><br>
<label>pedigree</label><input type="password"senha="pedigree"id="pedigree"><br>
<input type="submit" value="Cadastrar" id="cadastrar" name="cadastrar">
</form>
</body>
</html>


<button>aperte o botao 2 pra cadastrar novos pets </button>
functions [class]="dados pets"
<div>nome completo</div>
<div>raça</div>
<div>porte</div>
<div>idade</div>
<div>pedigree/div>

novo trabalho


<!DOCTYPE html>
<html>

<head>
<title>--Formulário Contato dos funcionarios e Empresa--</title>
<meta charset="utf-8" />
<!--   <link href="ContatoEstilo.css" rel="stylesheet" media="all" />
    <script src="JavaScript1.js"></script>-->
</head>

<body>
<form name="meu_form">

  <h1>Entre em contato</h1>

  <input type="text" id="nomeid" placeholder="nome completo" required="required" name="nome" />
  <label for="nome">Nome</label>

  <input type="tel" id="foneid" placeholder="(xx)xx-xx-xx-xx" name="fone" />
  <label for="fone">Fone</label>

  <input type="email" id="emailid" placeholder="fulano@mail.com" name="email" />
  <label for="email">Email</label>

  <input type="endereço" id="endereçoid" placeholder="rua marechal fonseca 11" name="endereço" />
  <label for="endereço">endereço</label>

  <textarea placeholder="Deixe sua opnião"></textarea>

  <input type="submit" class="enviar" onclick="Enviar();" value="Enviar" />
</form>
</body>
</html>

<div class="container"><button>cor botao amarelo escrito Container</button>
  <form action="#" class="form-contact" method="post" tabindex="1">
     <input type="text" class="form-contact-input" name="nome" placeholder="Nome" required />
     <input type="text" class="from-contact-input"endereço="endereço"placeholder="endereço"required/>
     <input type="email" class="form-contact-input" name="email" placeholder="Email" required />
     <input type="tel" class="form-contact-input" name="tel" placeholder="Telefone" />
        <input type="datetime-local" name="contatos" id="functions">
        <textarea class="form-contact-textarea" name="conteudo" placeholder="Deixe uma mensagem" required></textarea>
        <button type="submit" class="form-contact-button">Enviar</button>

      </form>
</div>
<h1>entre em contato com as empresas</h1>

<div class="container"><button>cor botao vermeha escrito Container</button>
  <form action="#" class="form-contact" method="post" tabindex="1">
     <input type="text" class="form-contact-input" name="nome" placeholder="Nome" required />
     <input type="text" class="from-contact-input"endereço="endereço"placeholder="endereço"required/>
     <input type="email" class="form-contact-input" name="email" placeholder="Email" required />
     <input type="cnpj" class="form-contact-input" name="cnpj" placeholder="cnpj" />
     <input type="fone" class="from-contact-input" name="fone" placeholder="fone"/>
        <input type="datetime-local" name="contatos" id="functions">
        <textarea class="form-contact-textarea" name="conteudo" placeholder="Deixe uma mensagem" required></textarea>
        <button type="submit" class="form-contact-button">Enviar</button>

      </form>
</div>
