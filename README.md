<h1 aling="center">Projeto Endereço</h1>

1. Neste Readme vou explicar oque foi feito [nesta atividade](https://caiotico.github.io/projeto-CadEndereco/index.html).

Atividade
-------

### EX01
* Aqui neste link está localizado o [exercicio 01](https://caiotico.github.io/projeto-CadEndereco/index.html) que nele aprendi um pouco mais sobre `Bootstrap`.

Explicação
-------
Dupliquei um codigo de formulario, sobre Endereço, atualizei o código para português.<br>

O códio se localiza Abaixo.
```ruby
 <!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Cadrastro de Endereço</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
    <script src='main.js'></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
</head>
<body>
    <form class="row g-3">
        <div class="col-md-2">
            <label for="inputZip" class="form-label">CEP</label>
            <input type="text" class="form-control" id="inputZip">
          </div>
        <div class="col-12">
          <label for="inputAddress" class="form-label">Rua</label>
          <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
        </div>
        <div class="col-12">
          <label for="inputAddress2" class="form-label">Bairro</label>
          <input type="text" class="form-control" id="inputAddress2" placeholder="Apartment, studio, or floor">
        </div>
        <div class="col-md-6">
          <label for="inputCity" class="form-label">Cidade</label>
          <input type="text" class="form-control" id="inputCity">
        </div>
        <div class="col-md-4">
          <label for="inputState" class="form-label">Estado</label>
          <input type="text" id="inputState" class="form-control">
        </div>
        <div class="col-12">
          <button type="submit" class="btn btn-primary">Cadastrar</button>
        </div>
      </form>
</body>
</html>
```
