# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function DoisArgumentos(A, B){
    return A + B;
}
// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
C = DoisArgumentos(3,3) + 5;

// Qual o valor atualizado dessa variável?
C = 11;

// Declare uma nova variável, sem valor.
var D;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function MostraValor(){
    D = 5
    return "O valor da variável agora é " + D;
}


// Invoque a função criada acima.
MostraValor();

// Qual o retorno da função? (Use comentários de bloco).

/*Retorna o valor 5*/

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function Validacao(A, B, C){
    if(A==null | B==null | C==null){
        return "Preencha todos os valores corretamente!"
    }
    return (A*B*C)+2
}

// Invoque a função criada acima, passando só dois números como argumento.
Validacao(3,2)

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
//"Preencha todos os valores corretamente!"

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
Validacao(3,3,3)

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).

//29

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/

function CalcNum(A, B, C){

if(A>null){
    return A
}

if(A>null || B>null){
    return A+B
}

if(A>null || B>null || C>null){
    return (A+B)/C
}

if(A== null || B== null || C== null){
    return false
}

else{
    return null
}
}


// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
//Um argumento//
CalcNum(2);
2
//Dois Argumentos//
CalcNum(2,3)
5
//Três Argumentos//
CalcNum(3,3,2);
3
```
