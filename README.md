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

# Tarefa 3: Passagem de Valor

Neste programa foi possível observar como funciona a passagem de parâmetros por valor em Java.

No método `main()`, foi criada uma variável chamada `numero` com valor `10`. Esse valor foi enviado para o método `alterarNumero()`.

Dentro do método, o valor recebido foi alterado para `50`. Porém, quando o programa voltou para o `main()`, a variável original continuou com valor `10`.

Isso acontece porque, em Java, tipos primitivos utilizam passagem por valor. Ou seja, o método não recebe a variável original, mas apenas uma cópia do valor dela.

Nesse caso, o valor copiado foi `10`.

Por isso, a alteração feita dentro do método aconteceu apenas localmente, sem modificar a variável criada no `main()`.
## Comentários sobre o código

A versão modularizada ficou mais fácil de ler e entender, porque o código foi separado em partes menores.

Também ficou mais fácil de reutilizar algumas partes do programa sem repetir código.

A manutenção ficou melhor, já que dá para alterar um método sem mexer no programa inteiro.

O fluxo do programa ficou mais organizado e simples de acompanhar.

Os métodos ficaram pequenos e objetivos.

A coesão ficou boa porque cada método faz apenas uma tarefa específica.

# Tarefa 4: Objetos e Referencias

Neste programa foi possível entender como objetos funcionam em chamadas de métodos em Java.

Foi criado um objeto da classe `Produto` com nome e preço. Depois, o objeto foi enviado para o método `aplicarDesconto()`.

Dentro do método, o preço do objeto foi alterado. Quando o programa voltou para o `main()`, o valor continuou alterado.

Isso acontece porque o Java copia a referência do objeto, e não o objeto inteiro.

O Java não possui passagem por referência verdadeira. Ele sempre utiliza passagem por valor.

No caso dos objetos, o valor copiado é a referência que aponta para o objeto na memória.

Por isso, tanto o `main()` quanto o método `aplicarDesconto()` acessam o mesmo objeto, fazendo com que as alterações permaneçam após a chamada do método.
