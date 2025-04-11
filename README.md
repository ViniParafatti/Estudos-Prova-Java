# Estudos-Prova-Java
Inicio de Javascrt
Tipos de Dados em JavaScript

Números
Números são usados para
representar valores numéricos,
como idade, altura e preços. Eles
podem ser inteiros (ex: 10) ou
decimais (ex: 3.14).

Strings
Strings são usados para
representar texto, como nomes,
endereços e mensagens. Eles são
delimitados por aspas simples ou
duplas (ex: 'Olá, mundo!' ou
"JavaScript é legal").

Booleanos
Booleanos representam valores de
verdade ou falsidade, como
verdadeiro ou falso. Eles são
usados para condições e
comparações (ex: true ou false).

let nome = "Amanda"
let nome1 = 'Amanda'
let numero = 10
let booleano = true
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

console.log('Conversão de tipos!');

console.log('ano ' + 2024);
console.log('2' + '2');

//conversão explícita
console.log(parseInt('2') + parseInt('2'));

//conversão implícita
console.log('10' / '2');

console.log('6.5');
console.log('6,5');
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
Uso do Typeof
let cliente = 'Maria'
let maiorDeIdade = true
let saldo = 1000

typeof cliente //string
// o js reconhece string pelo uso de aspas, simples ou duplas, ou crase

typeof maiorDeIdade //boolean

typeof saldo //number
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
Variáveis `let` e `const`

Variáveis declaradas com
`let` podem ter seu valor
alterado posteriormente.
ex:
let nome = "Amanda";
nome = "Maria";
// retorna Maria

Variáveis declaradas com
`const` são imutáveis, seu
valor não pode ser alterado
após a inicialização.
ex:
const idade = 25;
idade = 30; // Erro:Atribuição a uma variável constante

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

Funções Declarativas em
JavaScript

As funções declarativas são definidas usando a palavra-chave
`function`, seguida do nome da função, parênteses e chaves.
ex:
function saudacao() {
console.log("Olá, mundo!");
}
saudacao();

Funções com Retorno

Retorno com `return`
A palavra-chave `return` é
usada para retornar um valor
da função. O código após
`return` não é executado.
ex;
// Função que calcula a soma de dois números e retorna o resultado
function soma(a, b) {
return a + b;
}

// Chamando a função e armazenando o retorno em uma variável
let resultado = soma(5, 3);

// Exibindo o resultado no console
console.log("O resultado da soma é:", resultado);

Funções com Parâmetros
ex;
// Função que exibe uma mensagem personalizada
function saudacao(nome, idade) {
console.log(`Olá, ${nome}! Você tem ${idade} anos.`);
}

// Chamando a função com diferentes valores de parâmetros
saudacao("Ana", 25);
saudacao("Carlos", 30);

Funções de Expressão em JavaScript
// Definindo uma função de expressão
const saudacao = function(nome, idade) {
console.log(`Olá, ${nome}! Você tem ${idade} anos.`);
};

// Chamando a função com diferentes valores de parâmetros
saudacao("Ana", 25);
saudacao("Carlos", 30);

Outras Funções 
const estudante = (notaFinal, faltas) => {
if (notaFinal < 7 && faltas > 4) {
return true
}else {
return false
 }
}
const exibeNome = (nome) => nome
