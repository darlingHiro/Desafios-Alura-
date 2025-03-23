# Desafios-Alura-

alert('Boas vindas ai nosso site!');

let nome1 = 'lua';
let idade1 = 25;
let numeroDeVendas = 50;
let saldoDisponivel = 1000;

alert('Erro! Preencha todos os campos');
let mensagemDeErro = 'Erro! Preencha todos os campos';
alert(mensagemDeErro);

let nome2 = prompt('Qual o nome de Úsuario?');
let idade2 = prompt('Qual a sua Idade?');
if(idade2 >= 18){
    alert('Habilitação Permitida');
}
if(idade2 <= 17){
    alert('Habilitação nao concedida');
}
