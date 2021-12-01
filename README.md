<!DOCTYPE html>
<html>
<head>
    <title>Cálculo de salário</title>
    <meta charset="UTF-8" />
    <script type="text/javascript">
        function calculaSalario(){
            var valor = document.getElementById("valor").value;
            var quantidade = document.getElementById("quantidade").value;
            var salario = valor*quantidade;
            alert(salario);
        }
    </script>
</head>
<body>
    <fieldset>
        <legend>Cálculo do salário</legend>
        <label>Nome</label>
        <input id="valor" type="text"/>
        <label>Valor da hora:</label>
        <input id="valor" type="text"/>
        <label>Quantidade de horas trabalhadas:</label>
        <input id="quantidade" type="text"/>
        <label>Salario Bruto</label>
        <input id="quantidade" type="text"/>
        <label>IRRF</label>
        <input id="quantidade" type="text"/>
        <label>Gratificação</label>
        <input id="quantidade" type="text"/>
        <label>Salario liquido</label>

        <label></label>
        <button id="calcular" onclick="calculaSalario()">Calcular salário</button>
    </fieldset>   
</body>
</html>
