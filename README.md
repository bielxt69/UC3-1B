# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 
Nome: João gabriel cordeiro Matias

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

No JavaScript, if e else são estruturas condicionais que permitem controlar o fluxo de código, executando comandos de acordo com o resultado de uma condição
function soma(num1, num2) {
  return (num1 = +num2);
}
if (compra1 > compra2) {
  console.log(soma(compra1, compra2));
} else if (compra1 > compra2) {
  console.log(subtracao(compra1, compra2));
} else {
  console.log("erro")

  function somaNumerosPares(numeros) {
  // Filtra os números pares
  const numerosPares = numeros.filter((num) => num % 2 === 0);

  // Calcula a soma dos números pares
  const soma = numerosPares.reduce((acc, num) => acc + num, 0);

  return soma;
}

// Exemplo de uso
const arrayDeNumeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
const resultado = somaNumerosPares(arrayDeNumeros);
console.log(resultado); // Saída: 30

O que são funções
Funções no JavaScript são blocos de instruções que executam uma tarefa ou calculam um valor. Elas são um componente fundamental da linguagem, permitindo a reutilização, organização e modularização do código.
function minhaFuncao(objeto) {
  objeto.make = "Toyota";
}

var meucarro = { make: "Honda", model: "Accord", year: 1998 };
var x, y;

x = meucarro.make; // x recebe o valor "Honda"

minhaFuncao(meucarro);
y = meucarro.make; // y recebe o valor "Toyota"
// (a propriedade make foi alterada pela função)

No JavaScript, um array é uma estrutura de dados que armazena e organiza valores, sendo um conjunto de dados ordenados que pode ser referenciado por um nome e um índice:


const array = [1,2,3]
console.log(array) // [1,2,3]

array.push(4,5)
console.log(array) // [1,2,3,4,5]

No JavaScript, o tipo de dado Number representa números, tanto inteiros quanto de ponto flutuante, e pode ser usado em operações matemáticas
const a = 15;
const b = 16;
const calcular = a * b;
console.log(`o resultado é ${calcular}`);
const nome = prompt("qual é o seu nome?");
console.log(`boas vindas, amostradinho(a),${nome}.`);
const nome = promtp(`qual é o seu nome?`);
if (nome == "joao") {
  console.log(`boas vindas, amostradinho ${nome}`);
} else {
  console.log(`que pena ${nome}, você não esta no sistema`);
}
console.log(2 === "2");

switch case é uma instrução de controle de fluxo do JavaScript que permite executar diferentes blocos de código com base em valores específicos. É uma ferramenta útil para programadores JavaScript, pois permite lidar com várias condições de forma eficiente e evitar o uso excessivo de estruturas condicionais aninhadas
JS Options
1
const produto = prompt("qual fruta vocẽ deseja?")
2
 switch(produto) {
3
  
4
  case :"maça"
5
console.log("A maça custa R$2,50 a unidade.")
6
break;
7
case:"pitaya":
8
case:"framboesa"
9
console.log("A pitaya e a framboesa,custam R$20,00kg.")    
10
    break;
11
  default:
12
    console.log("")
13
     break;
14
     case:"banana":
15
     console.log("a banana custa R$4,00,cada palma.")
16
     break;
17
     defalt:
18
     console.log("infelizmente não temos essa fruta disponivel.")
19
 }
20
     
21
     const produto = prompt("qual jogo vocẽ deseja?")
22
     switch(produto)   {
23
    case:"efotbool"
24
    console.log("o efotboll custa R$7,00") 
25
    break;
26
    case:"efotbool"
27
    console.log("o jogo está em falta.")
28
     }

     




No JavaScript, booleano é um tipo de dado primitivo que pode assumir apenas dois valores: verdadeiro (true) ou falso (false). 
var x = new Boolean(false);
if (x) {
  // esse código é executado
}






desenvolvimento de um jogo em Ds
function mostrarMensagem(tipoDeLuta) {
  switch (tipoDeLuta.toLowerCase()) {
    case "muay thai":
      alert("Muay Thai é conhecido como a arte dos oito membros!");
      break;
    case "karatê":
      alert(
        "Karatê é uma arte marcial japonesa focada na velocidade e defesa!"
      );
      break;
    case "jiu-jitsu":
      alert(
        "Jiu-Jitsu é uma arte marcial que enfatiza o grappling e a defesa pessoal!"
      );
      break;
    case "taekwondo":
      alert(
        "Taekwondo é uma arte marcial coreana conhecida por seus chutes altos!"
      );
      break;
    case "boxe":
      alert("Boxe é um esporte de combate focado em socos e movimentação!");
      break;
    case "capoeira":
      alert(
        "Capoeira é uma expressão cultural afro-brasileira que combina dança, acrobacias e música!"
      );
      break;
    case "luta de rua":
      alert(
        "Luta de Rua é um estilo de combate sem regras específicas, focado na autodefesa!"
      );
      break;
    case "luta livre":
      alert(
        "Luta Livre é uma arte marcial brasileira que combina técnicas de grappling e submissão!"
      );
      break;
    default:
      alert("Tipo de luta não reconhecido. Tente novamente!");
  }
}

let tipoDeLuta = prompt(
  "Qual luta você deseja aprender? (Muay Thai, Karatê, Jiu-Jitsu, Taekwondo, Boxe, Capoeira, Luta de Rua, Luta Livre)"
);
mostrarMensagem(tipoDeLuta);




## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

function listarFeriados() {
    let mes = prompt("Digite o número do mês (1-12):");

    switch (mes) {
        case '1':
            alert("Janeiro: 1 - Confraternização Universal");
            break;
        case '2':
            alert("Fevereiro: 25 - Carnaval (data variável), 26 - Carnaval (data variável)");
            break;
        case '3':
            alert("Março: 31 - Páscoa (data variável)");
            break;
        case '4':
            alert("Abril: 21 - Tiradentes");
            break;
        case '5':
            alert("Maio: 1 - Dia do Trabalho");
            break;
        case '6':
            alert("Junho: 15 - Corpus Christi (data variável)");
            break;
        case '7':
            alert("Julho: Não há feriados nacionais.");
            break;
        case '8':
            alert("Agosto: Não há feriados nacionais.");
            break;
        case '9':
            alert("Setembro: 7 - Independência do Brasil");
            break;
        case '10':
            alert("Outubro: 12 - Nossa Senhora Aparecida");
            break;
        case '11':
            alert("Novembro: 1 - Dia de Todos os Santos, 2 - Finados, 15 - Proclamação da República");
            break;
        case '12':
            alert("Dezembro: 25 - Natal");
            break;
        default:
            alert("Mês inválido! Por favor, digite um número de 1 a 12.");
    }
}

// Chama a função para executar
listarFeriados();*/

