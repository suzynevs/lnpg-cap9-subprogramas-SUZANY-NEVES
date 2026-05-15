# lnpg-cap9-subprogramas-SUZANY-NEVES
Suzany Valeska Dias das Neves

BSI, Linguagem de Programação - 2º período

# Tarefa 1: Modularização em Java

O programa foi dividido em métodos pequenos para evitar repetição de código e deixar a estrutura mais organizada.
Método `main()`
É o método principal do programa.
Ele:
- repete o processo 5 vezes;
- lê o nome do aluno;
- calcula a média;
- mostra a situação.

## Comparação - Monolítica e Modularizada: 
Na versão monolítica, todo o código fica dentro do main().
Isso faz com que o código seja maior, mais difícil de entender, tenha repetição de código e possui uma manutenção mais difícil.
Já na versão modularizada, o código foi dividido em métodos. Os métodos criados foram: nota, media e situacao(). Isso deixou o código mais organizado, com menos repetição e bem mais fácil de realzar a manutenção.

## Comparação Técnica

### Legibilidade: 
A versão modularizada possui melhor legibilidade porque o código fica dividido em partes menores.

### Reutilização: 
Os métodos podem ser reutilizados várias vezes sem repetir código.

### Facilidade de manutenção: 
Modificar um método é mais simples do que alterar um código grande dentro do main().

### Clareza do fluxo: 
A execução do programa fica mais fácil de entender porque cada método possui uma função específica.

### Tamanho dos métodos: 
Os métodos ficaram pequenos e objetivos.

### Coesão: 
Cada método possui apenas uma responsabilidade:

nota() lê nota;
media() calcula média;

# Tarefa 2 — Modularização em Python
## Comparação - Versão Monolítica e Modularizada

Na versão monolítica, todo o código ficou em um único bloco. Ou seja, o código maior, com menor organização, difícil reutilização e manutenção; Já na versão modularizada o código foi dividido em funções, como por exemplo  `ler_produto()`, `subtotal()`, `desconto()`, `total()`, `cupom()`

---

## Discussão

### Partes repetitivas

Cálculos e impressão poderiam ser repetidos em programas maiores.

---

### Reutilização

As funções podem ser usadas novamente sem copiar código.

---

### Legibilidade

A versão modularizada ficou mais organizada e mais fácil de entender.
situacao() define situação.


