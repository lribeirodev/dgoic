<doctype html/>

<html>
  <title>Calculadora DGOIC - Lucas Ribeiro</title>
  <head></head>
  
  <body>
    <center>
      
      <h1>Calculadora DGOIC</h1>
      <h3>Criado por Lucas Ribeiro</h3>
      <h4>Atualize a página para calcular novamente</h4>
      <h4>Contato: 11 94131-4539</h4>
      <h4>Adicione a página a sua tela inicial </h4>
      
      <h1>Como utilizar</h1>
      
<img src="https://i.ibb.co/BrgtcPD/Caixa-dgoic.jpg" alt="Caixa-dgoic" border="0" width=300px height=300px>
<br><br>
<h3>Faça a leitura da Caixa em relação aos splitters secundários coloque na ordem da caixa, o resultado seria assim! 
  <br>
 4,5,6,7,1,2,3,6</h3>
 <br>
<img src="https://i.ibb.co/WK69Hvd/Screenshot-20200927-004500.png" alt="Screenshot-20200927-004500" border="0" width=400px height=300px>
<br>
<h3>Agora de um OK</h3>
<br>
<img src="https://i.ibb.co/TTqgbw2/Screenshot-20200927-004519.png" alt="Screenshot-20200927-004500" border="0" width=400px height=300px>
<br>
<h3>Acima está o resultado do exemplo, agora podemos achar a anilha e a cor facilmente</h3>
    </center>
    <script>
alert("Calculadora de DGOIC Programa feito por Lucas Ribeiro");

alert("Faça a leitura da tampa e insira os dados no programa");

var cores = ['VERDE' ,'AMARELO', 'BRANCO', 'AZUL', 'VERMELHO', 'VIOLETA', 'MARROM', 'ROSA', 'PRETO', 'CINZA', 'LARANJA', 'AQ MAR'];

let splitter=[
  [0,0],
  [1,2,3,4,5,6,7,8],
  [9,10,11,12,13,14,15,16],
  [17,18,19,20,21,22,23,24],
  [25,26,27,28,29,30,31,32],
  [33,34,35,36,37,38,39,40],
  [41,42,43,44,45,46,47,48],
  [49,50,51,52,53,54,55,56],
  [57,58,59,60,61,62,63,64]
  ];

var ss = prompt("Agora escreva na ordem os splitters secundários que contem na caixa \n exemplo: 5,4,3,7,4,3");

var sss = ss.split(",");
 var x = "";
  
for(var i = 0; i < sss.length; i++){
  var n = sss[i];
  var j = +n ;
x = x + cores[i] + " SS"+ j + " " + splitter[n] + "\n";
}

alert(x);
    </script>
    
  </body>
</html>
