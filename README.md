# TESTES EM JAVASCRIPT (PARA MFDS)

-> REPOSITÓRIO DESTINADO À EXERCÍCIOS DE JAVASCRIPT

![image](https://github.com/mareshbard/testesJS/assets/125154278/22a214f6-2439-4fa7-a07d-41168c9cda5e)

CODEPEN


<html>
 <head>
  <meta charset="utf-8">
   <title>USRR</title>
 </head>
  <div align = "center"
 <body background = "">
 <h1 class="centralizado" style="color: green;">Boa tarde, camarada</h1>
 <p style="color: black;">Meu nome é Karl Marx. </p>
  <p id="negrito"> Já ouviu falar sobre o <a href="https://pt.wikipedia.org/wiki/Comunismo">COMUNISMO</a>? </p>
<img height="400
em" src="https://th.bing.com/th/id/R.22b7deba86a2947f02ec3a90a5db7bb9?rik=U9P5wx4uI2lgaQ&pid=ImgRaw&r=0"/>
  </div>
  </p>
 </body>
</html>
<div align = "center"
<h1 id = "xyz" >Virar comunista? </h1>
<button> OK </button>

  
<style>
h1 {border-style: solid}
#negrito {font-style: italic}
</style>


document.querySelector("#negrito").innerHTML = "menina"
//document.querySelector("#negrito").remove()

var btn = document.querySelector('button');
function random(numero) {
 return Math.floor(Math.random()*(numero+1));
}
btn.onclick = function() {
 var rndCol = 'rgb(' + random(255) + ',' + random(255) + ',' + 
random(255) + ')';
 document.body.style.backgroundColor = rndCol;
}
window.onscroll = ()=>console.log("rolando")
window.onresize = ()=>console.log("redimensionando") 
document.querySelector('body').onclick = ()=>console.log("clicando")
