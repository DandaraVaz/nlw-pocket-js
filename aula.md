## Linguagem de Programação

Maneira de dar instrução ao computador.

**Algoritmo**: Sequência de passos lógica e finita para resolução de um problema.

## Peças de uma linguagem

- Comentários 
- Declaração de variáveis (const, let)
- Operadores (atribuição, concatenação, matemáticos lógicos)
- Tipos de dados (string, number, boolean)
- Estrutura de dados (functions, object, array)
- Controle de fluxo (if/else)
- Estrutura de repetição (for, while)

## Fases da resolução de um problema

- Coletar os dados
- Processar os dados (manipular, alterar...)
- Apresentar os dados

## Escopo e variáveis:

- [x] Variáveis globais e locais
- [x] Constantes

## Tipos de dados

- [x] Strings (textos): "" '' ``
- [x] Number: 2 1.4 
- [x] Boolean: true or false

## Operadores

- [x] Operadores de atribuição de valor =
- [x] Operador de concatenação +
- [x] Operadores de comparação: == != < > <= >=
- [x] Spread operator: ...

## Arrays

- [x] Uma lista que contém qualquer tipo de dado
- [x] Métodos de array: push, [find, forEach, filter, map] : HOF (Higher Order Functions) 
      As HOF (Higher Order Functions) sempre vão receber uma função.   Ex: ((meta) => {return meta.checked})

## Objetos
- [x] Atributos e métodos
- [x] Criação e manipulação de objetos
- [x] Acesso a propriedades de objetos

## Function
- [x] Criar uma função, passar argumento
    function start() {}

- [x] Executar uma função

- [x] arrow function / named function
    const criarMeta = () => {}

## Estrutura de repetição 
- [x] While

    const start = () => {
    let count = 1
    while(count <= 10) {
        console.log(count)
        count = count + 1
    }
}

start()

Explicação: count é = 1 então, count é menor e igual a 10. count é igual a count + 1. Essa função será executada por 10 vezes.

## Condicionais

- [x] Switch
- [x] if/else

## Módulos em Node.js:

- [x] Importação de módulos (require, commonJS)
- [x] Biblioteca 'inquirer' para criar prompts interativos
- [x] FS (File System)

## JSON
- [x] JavaScript Object Notation (.json)
- [x] Json.parse(): transforma de JSON para JS
- [x] JSON.stringify(): transforma de JS para JSON

## Programação assíncrona e Promises:

- [x] Uso de funções assíncronas (async/await)