<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registre-se</title>
    <link rel="stylesheet" href="style.css"/>
</head>

<body>
    <!--CABEÇALHO-->
    <h1>Registre-se e receba nossa newsletter</h1>

    <p>Seja bem-vindo a nossa área de cadastro!</p> 
    <p>Preencha as informações abaixo para receber informações com periodicidade.</p><br>      
    
    <h2>Área de cadastro</h2>
    <!--DADOS PESSOAIS-->
    <form action="pagina/login.html" method="GET">
        <fieldset>
            <legend>Dados Pessoais</legend>
            <label>
                Nome:<br>
                <input type="text" name="nome" id="name" required minlength="2"/>
            </label>
            <br>
            <label>
                Sobrenome:<br>
                <input type="text" name="sobrenome" />
            </label>
            <br>
            <label>
                Data de nascimento:<br>
                <input type="date" name="idade"/>
            </label>
            <br>
            <label>
                E-mail:<br>
                <input type="email" name="e-mail" pattern=""/>
            </label><br><br>
        </fieldset>    
        <!--DADOS DE INTERESSE-->
        <fieldset>
            <legend>Interesses</legend>
            <label>Me conte suas características predominantes:<br>
                <textarea name="descricao"></textarea><br>
            </label>
            <br>
            <label>Me envie sua foto favorita:
                <input type="file" name="photo" accept="image/*" \>
            </label>
            <br><br>
            <label class="categoria">
                Selecione assuntos que gostaria de receber:<br>
                <select name="categoria" >
                    <option selected>--Selecione--</option>
                    <option value="1">Viagens</option>
                    <option value="2">Culinária</option>
                    <option value="3">Política</option>
                    <option value="4">Esportes</option>
                    <option value="5">Entretenimento</option>
                </select>
            </label>
            <br><br>
            <label>
                <input type="checkbox"/>
                Eu li e aceito os <a   href="paginas/termos.html" target="_blank" >termos de condições</a>.
                <br><br>
                <input class="botao" type="submit" value="Cadastrar"/>
            </label>
        </fieldset>

    </form> 
</body>
</html>
