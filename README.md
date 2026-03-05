🏅 Calculadora de Média de Atletas
📌 Sobre o Projeto

Este projeto foi desenvolvido em JavaScript com o objetivo de calcular a média das notas de atletas em uma competição de ginástica artística.

Durante a competição, cada atleta é avaliado por cinco jurados, e cada jurado atribui uma nota de 1 a 10 com base em diferentes critérios, como:

Tempo de duração da apresentação

Originalidade da coreografia

Postura do atleta

Dificuldade das acrobacias

Sincronismo

Para garantir uma avaliação mais justa, a regra da competição determina que:

A maior nota deve ser descartada.

A menor nota também deve ser descartada.

A média final é calculada utilizando apenas as três notas restantes.

A aplicação recebe os dados dos atletas, realiza o cálculo da média válida e exibe os resultados no console.

📥 Estrutura de Entrada

A aplicação utiliza uma matriz de objetos contendo o nome do atleta e suas cinco notas.

let atletas = [
 {
   nome: "Cesar Abascal",
   notas: [10, 9.34, 8.42, 10, 7.88]
 },
 {
   nome: "Fernando Puntel",
   notas: [8, 10, 10, 7, 9.33]
 },
 {
   nome: "Daiane Jelinsky",
   notas: [7, 10, 9.5, 9.5, 8]
 },
 {
   nome: "Bruno Castro",
   notas: [10, 10, 10, 9, 9.5]
 }
];

Cada objeto possui:

nome → nome do atleta

notas → array contendo as cinco notas atribuídas pelos jurados

🧠 Lógica da Aplicação

O cálculo da média segue os seguintes passos:

Percorrer todos os atletas utilizando um laço for.

Copiar e ordenar as notas do atleta.

Remover a menor e a maior nota.

Somar as três notas restantes.

Calcular a média.

Exibir o resultado no console.

💻 Código do Projeto
let atletas = [
 {
   nome: "Cesar Abascal",
   notas: [10, 9.34, 8.42, 10, 7.88]
 },
 {
   nome: "Fernando Puntel",
   notas: [8, 10, 10, 7, 9.33]
 },
 {
   nome: "Daiane Jelinsky",
   notas: [7, 10, 9.5, 9.5, 8]
 },
 {
   nome: "Bruno Castro",
   notas: [10, 10, 10, 9, 9.5]
 }
];

📚 Conceitos de JavaScript Utilizados

Durante o desenvolvimento foram utilizados diversos conceitos da linguagem:

Arrays

Objetos

Laços de repetição (for)

Métodos de array:

sort()

slice()

forEach()

Manipulação de dados

console.log()
