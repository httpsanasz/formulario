# formulario
<html>
  
  
<?php


<head>


    <meta charset="UTF-8">


</head>


<body>


//declarar as variaveis 


$nome = " ";


$cidade = " ";


$idade = " ";


//entrada de dados


$nome = $_POST['NOME']


$cidade = $_POST ['CIDADE']


$idade = $_POST ['IDADE']


//	saida de dados


echo "</br> DADOS LIDOS";


echo "</br> Nome: " .$nome;


echo "</br> Cidade: " .$cidade;


echo "</br> Idade: " .$idade;


?>

  
</html>
