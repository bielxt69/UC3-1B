# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.
const livros = ["javascript assertivo", "engenharia de teste"];
const atualizandolivros = livros.splice(0, 0, "node.js");
(indique localização,n de elementos p/deletar, adicionar)
console.log(atualizandolivros);
console.log(livros);

const tamanholivros = livros.length;
const corredorA1 = livros.slice(0, tamanholivros / 2);

const corredorA2 = livros.slice(tamanholivros / 2);

console.log("os livros do corredor A1 são.", corredorA1);
console.log("os livros do corredor A2 são.", corredorA2);

const hqs = ["superman", "x-man", "vingadores", "batman"];
const juntarlivros = livros.concat(hqs);
console.log(juntarlivros);

const livros = ["javascript assertivo", "engenharia de teste"];

const hqs = ["superman", "x-man", "vingadores", "batman"];

const gibi = ["x-man", "monica"];

const juntarlivros = livros.concat(gibis);

console.log(juntarlivros);

.includes -  retorna a um valor booleano, pesquisa se é verdadeiro ou falzo
.indexof - trás a posição do indice

console.log(hqs.indexOf("vingadores"));
2

console.log(hqs.includes("vingadores"));
 true

 const jogos = prompt ("qual jogo você quer?")
const bibliotecaDejogos = ["efotbool","souls","ufc24","free fire"]

switch (jogos){
  case "free fire":
    console.log("efotbool custa 55,00")
    break
    
    
}
switch (jogos){
  case "souls":
    console.log("souls custa23,00")
    break
    
}
switch (jogos){
  case "ufc4":
    console.log("ufc24 custa 87,00")
    break
    
    
}
switch (jogos){
  case "free fire":
  console.log("free fire custa 30,00")
  break
  default:
  console.log("infelizmente não temos esse jogo")
  
} 


const musica = ["coisas das vida", "ela gosta de fumar maconha", "só fé"];
const musicos = ["felipe do pascal", "grelo", "alcione"];

const musicasEcantores = musica.concat(musicos);

console.log(musicasEcantores);


const array = [1,2,3]
console.log(array) // [1,2,3]

array.push(4,5)
console.log(array) // [1,2,3,4,5]



String é um termo usado na programação de computadores para se referir a uma sequência de caracteres, ou seja, uma cadeia de caracteres. É uma forma de representar textos, frases ou palavras em um programa.

Array, também conhecido como vetor ou arranjo, é uma estrutura de dados que armazena e organiza uma coleção de elementos do mesmo tipo. 
 
Os arrays são muito utilizados na programação para armazenar e manipular conjuntos de dados, e são comparáveis a uma variável que pode armazenar mais de um valor. 

No JavaScript, o método push() adiciona elementos a um array, sempre no final do mesmo. Ele retorna o novo comprimento do array, que é atualizado após cada chamada do método. 
 
Por exemplo, a linha de código array.push(4) adiciona o número 4 ao final do array, enquanto a linha array.push(5, 6)

O console.log é uma função do JavaScript que imprime uma mensagem no console do navegador ou no ambiente de desenvolvimento. É uma ferramenta útil para desenvolvedores, pois permite depurar o código e verificar o valor de variáveis ou o estado do programa. 






## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 


