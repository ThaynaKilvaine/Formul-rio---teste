<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <header>
        <h1>Seja bem-vindo a nossa página de cadastro de produtos</h1>
        <p>Observe o formulário a seguir, e preencha todos os campos corretamente.</p>
        <br>
    </header>
    <main>
        <form id="productForm" method="POST" onsubmit="return pergunta1();">
            <fieldset>
                <legend>Cadastros</legend>

                <label for="Produto">Produto</label>
                <input type="text" name="Produto" id="Produto" required>

                <label for="Marca">Marca</label>
                <input type="text" name="Marca" id="Marca" required>

                <label for="Quantidade">Quantidade</label>
                <input type="number" name="Quantidade" id="Quantidade" required>

                <label for="preco">Preço</label>
                <input type="number" name="preco" id="preco" step="0.01" required>
                <button type="button" onclick="exibirPreco()">Verificar Preço</button>
                <p id="resultado"></p>

                <label for="PrecoMin">Preço Mínimo (opcional)</label>
                <input type="number" name="PrecoMin" id="PrecoMin" step="0.01">

                <label for="PrecoMax">Preço Máximo (opcional)</label>
                <input type="number" name="PrecoMax" id="PrecoMax" step="0.01">

                <input type="submit" value="Enviar">
                <input type="reset" value="Limpar" onclick="pergunta2();">
            </fieldset>
        </form>
    </main>

    <script>
        function exibirPreco() {
            const preco = document.getElementById("preco").value;
            
            if (preco === "" || isNaN(preco) || preco <= 0) {
                document.getElementById("resultado").innerHTML = "Por favor, insira um preço válido.";
            } else {
                document.getElementById("resultado").innerHTML = "O preço inserido é: R$ " + parseFloat(preco).toFixed(2);
            }
        }

        function pergunta1() {
            return confirm("Deseja enviar agora?");
        }

        function pergunta2() {
            alert("Todos os campos serão apagados.");
        }

        document.getElementById('productForm').addEventListener('submit', function(event) {
            const preco = parseFloat(document.getElementById('preco').value);
            const precoMin = parseFloat(document.getElementById('PrecoMin').value);
            const precoMax = parseFloat(document.getElementById('PrecoMax').value);

            if (!isNaN(precoMin) && preco < precoMin) {
                alert("O preço não pode ser inferior ao preço mínimo.");
                event.preventDefault(); 
            }

            if (!isNaN(precoMax) && preco > precoMax) {
                alert("O preço não pode ser superior ao preço máximo.");
                event.preventDefault(); 
            }
        });
    </script>
</body>
</html>
