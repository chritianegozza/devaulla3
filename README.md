# devaulla3
alura imersão dev aula 3 
https://codepen.io/chritianegozza/pen/MWJKZXK?editors=1000



html

<html>

<head>
    <title>
        Imersão Dev - Aula 03
    </title>
</head>

<body>
    <div class="container">
        <h1 class="page-title">
            Mentalista
        </h1>
        <p class="page-subtitle">
            Digite um número de 0 a 10
        </p>
        <img src="https://www.alura.com.br/assets/img/imersoes/dev-2021/logo-imersao-mentalista.svg" class="page-logo"
            alt="">
    </div>
    <a href="https://alura.com.br/" target="_blank">
        <img src="https://www.alura.com.br/assets/img/home/alura-logo.svg" alt="" class="alura-logo">
    </a>
 
</body>

</html>




css


body {
    font-family: 'Roboto Mono',monospace;
    min-height: 600px;
    background-image: url('https://cdn.ome.lt/puNZLqjeMUnz4XdZ46n14SYkhsQ=/1200x630/smart/extras/conteudos/doutorestranho2diretor.jpeg');
    background-color: #000000;
    background-size: cover;
    background-position: center bottom;
    background-repeat: no-repeat;
  }
  
  .container {
    text-align: center;
    padding: 30px;
    height: 100vh;
  }
  
  .page-title {
    color: #ffffff;
    margin: 0 0 5px;
  }
  
  .page-subtitle {
    color: #ffffff;
    margin-top: 5px;
  }
 
  
  .page-logo {
    width: 200px;
  }
  
  .alura-logo {
    width: 40px;
    position: absolute;
    top: 10px;
    right:10px;
  }
  
  @media (max-height: 500px) {
    body {
      min-height:800px;
    }
    
   
   
   js
   
   
   var numeroSecreto = parseInt(Math.random() * 10)
var tentativas = 3

while (tentativas > 0){
var chute = parseInt(prompt("Digite um número entre 0 e 10"))

if (numeroSecreto == chute) {
alert("Acertou")
break
 }  else  if(chute > numeroSecreto) {
    alert("0 número secreto é menor")
    tentativas = tentativas - 1
 }  else if (chute  < numeroSecreto) {
     alert("O número secreto é maior")
      tentativas = tentativas - 1
 }
}     if (chute != numeroSecreto) {
     alert("Suas tentativas acabaram. O número secreto era " +  numeroSecreto)
     tentativas = tentativas - 1
}  





![image](https://user-images.githubusercontent.com/72118415/112658834-91c44480-8e32-11eb-9076-211ff09dc39c.png)
