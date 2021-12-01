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
            alert(2402);
            
        }
    </script>
</head>
<body>


<meta http-equiv="Content-Type" content="text/html;charset=utf-8" >
<html>
	<head>
		<title>Calcular Salario</title>
		<link rel="stylesheet" type="text/css" href="style.css">
	</head>
	
	<body>
		<h1>Calcular salario</h1>
		
		
	
	</body>
</html>

    <fieldset>
        <legend>Cálculo do salário</legend>
        <p>Nome</p  >
        <input id="valor" type="text"/>
        <p>Valor da hora</p>
        <input id="valor" type="text"/>
        <p>Quantidade de horas trabalhadas</p>
        <input id="quantidade" type="text"/>
        <p>Salario Bruto</p>
        <input id="quantidade" type="text"/>
        <p>IRRF</p>
        <input id="quantidade" type="text"/>
        <p>Gratificação</p>
        <input id="quantidade" type="text"/>
        <p>Salario liquido</p>
        <input id="quantidade" type="text"/>
        <button id="calcular" onclick="calculaSalario()">Calcular salário</button>
    </fieldset>   
</body>
</html>
