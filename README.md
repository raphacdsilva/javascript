//LOOP DE REPETIÇÃO - FOR
// incremento - x++ -> x = x + 1
// decremento - x-- -> x = x - 1

//sintaxe do FOR
//for(valor_inicial;valor_final; incremento ou decremento){
//document.write("saída de dados")
//}

let a = 0;

for (a = 1; a <= 20; a++) {
  if (a % 2 === 0) {
    document.write(a, "<br/>");
  }
}

let b = 15;

for (b = 15; b >= 1; b--) {
  if (b % 3 === 0) {
    document.write(b, "<br/>");
  }
}

//WHILE
//sintaxe do while
// while(valor_final){
//  saída("mensagem")
//  incremento ou decremento
//}

let nome = "Raphael";
let c = 0;
while (c <= 20) {
  c++;
  if (c % 2 === 0) {
    document.write(nome, "<br/>");
  }
}
