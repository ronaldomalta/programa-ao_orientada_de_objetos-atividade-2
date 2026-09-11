# Avaliação Formativa I

## Fundamentos de Java e Introdução à POO

**Valor:** 1,0 ponto no 1º GQ

---

## Objetivo

A Avaliação Formativa I tem como objetivo verificar a capacidade de aplicar os conceitos de programação em Java trabalhados nas Aulas 01 a 10, evoluindo da construção de programas básicos para a criação de classes com construtores e encapsulamento.

---

## Conteúdos avaliados

- Introdução ao Java
- Tipos de dados, variáveis e operadores
- Estruturas condicionais
- Estruturas de repetição
- Métodos
- Strings
- Arrays
- Classes e objetos
- Construtores
- Encapsulamento

> **Importante:** `ArrayList` não faz parte desta avaliação.

---

# Questão 1 — Fundamentos de Java

**Valor: 0,10 ponto**

Uma universidade deseja obter algumas informações básicas de um estudante.

Crie um programa chamado `Questao01` que solicite ao usuário:

- nome;
- idade;
- curso.

Ao final, o programa deverá apresentar uma mensagem contendo essas informações.

### Requisitos

O programa deve:

1. utilizar variáveis adequadas para armazenar os dados;
2. utilizar `Scanner` para realizar a entrada de dados;
3. utilizar `String` para armazenar o nome e o curso;
4. utilizar um tipo inteiro para armazenar a idade;
5. apresentar os dados de forma organizada.

### Exemplo de execução

```text
Nome: Ana Souza
Idade: 20
Curso: Ciência da Computação

--- Dados do estudante ---
Nome: Ana Souza
Idade: 20 anos
Curso: Ciência da Computação
```

---

# Questão 2 — Condicionais e Estruturas de Repetição

**Valor: 0,15 ponto**

Uma professora deseja analisar as notas de uma turma.

Crie um programa chamado `Questao02` que solicite a quantidade de estudantes da turma.

Em seguida, o programa deverá ler a nota de cada estudante e calcular:

- a média da turma;
- a maior nota;
- a menor nota;
- a quantidade de estudantes aprovados.

Considere que um estudante é aprovado quando sua nota é maior ou igual a `7,0`.

### Requisitos

O programa deve:

1. utilizar uma estrutura de repetição para realizar a leitura das notas;
2. utilizar estruturas condicionais para identificar a maior e a menor nota;
3. calcular a média da turma;
4. contar quantos estudantes obtiveram nota maior ou igual a `7,0`;
5. apresentar os resultados ao final.

### Exemplo de execução

```text
Quantidade de estudantes: 4

Nota do estudante 1: 8.0
Nota do estudante 2: 6.5
Nota do estudante 3: 9.0
Nota do estudante 4: 7.5

--- Resultado ---
Média da turma: 7.75
Maior nota: 9.0
Menor nota: 6.5
Estudantes aprovados: 3
```

---

# Questão 3 — Métodos e Strings

**Valor: 0,15 ponto**

Crie um programa chamado `Questao03` que solicite o nome completo de uma pessoa.

O programa deverá utilizar métodos para realizar as seguintes operações.

### Método 1

Crie o método:

```java
public static int quantidadeCaracteres(String texto)
```

O método deve retornar a quantidade de caracteres da `String` recebida.

### Método 2

Crie o método:

```java
public static String formatarNome(String nome)
```

O método deve retornar o nome em letras maiúsculas.

### Método 3

Crie o método:

```java
public static boolean contemSilva(String nome)
```

O método deve verificar se o nome contém a palavra `"Silva"`.

### No método `main`

O programa deve:

1. solicitar o nome completo;
2. chamar os três métodos;
3. apresentar os resultados.

### Exemplo de execução

```text
Nome completo: Maria da Silva Santos

Quantidade de caracteres: 22
Nome em maiúsculas: MARIA DA SILVA SANTOS
Contém "Silva": true
```

### Requisitos

- Os métodos devem possuir os parâmetros indicados.
- Os métodos devem retornar os tipos indicados.
- Os métodos devem ser chamados a partir do `main`.
- Utilize métodos da classe `String`.

---

# Questão 4 — Arrays

**Valor: 0,15 ponto**

Crie um programa chamado `Questao04` para armazenar as notas de 5 estudantes.

As notas devem ser armazenadas em um array de `double`.

O programa deverá:

1. solicitar as cinco notas;
2. armazená-las no array;
3. apresentar todas as notas;
4. calcular e apresentar a média;
5. identificar e apresentar a maior nota;
6. identificar e apresentar a menor nota;
7. informar quantos estudantes obtiveram nota maior ou igual a `7,0`.

### Requisitos

- Utilize um array para armazenar as notas.
- Utilize uma estrutura de repetição para percorrer o array.
- Não utilize `ArrayList`.
- Organize o código de forma clara e legível.

### Exemplo de execução

```text
Nota 1: 8.0
Nota 2: 6.5
Nota 3: 9.0
Nota 4: 7.5
Nota 5: 5.0

--- Resultado ---
Notas: 8.0 6.5 9.0 7.5 5.0
Média: 7.2
Maior nota: 9.0
Menor nota: 5.0
Estudantes com nota >= 7.0: 3
```

---

# Questão 5 — Classes, Objetos e Construtores

**Valor: 0,20 ponto**

Uma universidade deseja representar seus estudantes por meio de uma classe.

Crie uma classe chamada `Aluno` com os seguintes atributos:

- `nome`
- `matricula`
- `curso`

Inicialmente, os atributos podem ser declarados sem modificador de acesso.

Crie um construtor que receba os três dados e inicialize os atributos.

Crie também o método:

```java
public void exibirDados()
```

O método deverá apresentar os dados do aluno.

### No método `main`

Crie pelo menos dois objetos da classe `Aluno`, utilizando o construtor, e apresente os dados dos estudantes.

### Exemplo de execução

```text
--- Aluno 1 ---
Nome: Ana Souza
Matrícula: 20260001
Curso: Ciência da Computação

--- Aluno 2 ---
Nome: Pedro Lima
Matrícula: 20260002
Curso: Engenharia da Computação
```

### Requisitos

A solução deve conter:

- uma classe `Aluno`;
- os atributos `nome`, `matricula` e `curso`;
- um construtor;
- o método `exibirDados()`;
- pelo menos dois objetos `Aluno`;
- utilização do construtor para inicializar os objetos.

---

# Questão 6 — Encapsulamento

**Valor: 0,25 ponto**

A classe `Aluno` criada na Questão 5 deverá ser modificada para aplicar o conceito de **encapsulamento**.

## 6.1 Atributos

Os atributos da classe `Aluno` devem ser declarados como `private`:

```java
private String nome;
private String matricula;
private String curso;
```

## 6.2 Getters e Setters

Crie métodos `get` e `set` para os três atributos.

Exemplos:

```java
public String getNome()
```

```java
public void setNome(String nome)
```

```java
public String getMatricula()
```

```java
public void setMatricula(String matricula)
```

```java
public String getCurso()
```

```java
public void setCurso(String curso)
```

## 6.3 Validação dos dados

Os métodos `set` deverão impedir valores inválidos.

### Nome

O nome não pode ser vazio.

Caso seja informado um nome vazio, o programa deverá apresentar uma mensagem de erro e manter o valor anterior.

### Matrícula

A matrícula não pode ser vazia.

Caso seja informada uma matrícula vazia, o programa deverá apresentar uma mensagem de erro e manter o valor anterior.

### Curso

O curso não pode ser vazio.

Caso seja informado um curso vazio, o programa deverá apresentar uma mensagem de erro e manter o valor anterior.

## 6.4 Teste do encapsulamento

No método `main`, crie um objeto `Aluno` e realize os seguintes testes:

1. crie o objeto utilizando o construtor;
2. apresente os dados utilizando os métodos `get`;
3. altere pelo menos um atributo utilizando um método `set`;
4. tente atribuir um valor inválido a pelo menos um atributo;
5. apresente os dados finais do objeto.

### Exemplo de comportamento

```text
--- Dados iniciais ---
Nome: Ana Souza
Matrícula: 20260001
Curso: Ciência da Computação

Alterando o curso...
Curso alterado com sucesso.

Tentando alterar o nome para vazio...
Erro: o nome não pode ser vazio.

--- Dados finais ---
Nome: Ana Souza
Matrícula: 20260001
Curso: Sistemas de Informação
```

### Requisitos

A solução deve demonstrar:

- atributos `private`;
- getters;
- setters;
- construtor;
- validação nos setters;
- criação e utilização de objetos;
- acesso aos atributos por meio dos métodos da classe.

---

# Orientações Gerais

- Utilize Java para resolver todas as questões.
- Organize o código de forma clara e legível.
- Utilize nomes significativos para classes, métodos e variáveis.
- Respeite as convenções de nomenclatura apresentadas em aula.
- Teste suas soluções antes da entrega.
- Cada questão deve ser implementada separadamente.
- O código deve ser compilável e executável.
- Utilize os conceitos trabalhados até a Aula 10.

---

# Conteúdos que não fazem parte da avaliação

Os seguintes conteúdos não serão necessários para resolver esta avaliação:

- `ArrayList`;
- Collections;
- Generics;
- Herança;
- Polimorfismo;
- Classes abstratas;
- Interfaces;
- Exceções;
- Manipulação de arquivos;
- Threads;
- Padrões de projeto.

> **A avaliação encerra no conteúdo de Encapsulamento.**

---

# Entrega

A entrega deverá seguir as orientações definidas pelo professor.

Os arquivos devem ser organizados da seguinte forma:

```text
entrega/
├── Questao01.java
├── Questao02.java
├── Questao03.java
├── Questao04.java
├── Aluno.java
├── Questao05.java
└── Questao06.java
```

### Antes de entregar

- [ ] Todos os arquivos possuem extensão `.java`.
- [ ] O nome da classe corresponde ao nome do arquivo.
- [ ] Todos os programas compilam.
- [ ] Todos os programas foram testados.
- [ ] Os códigos estão organizados e legíveis.
- [ ] Não existem arquivos desnecessários.
- [ ] Não foi utilizado `ArrayList`.
- [ ] Foram utilizados apenas os conteúdos previstos para a avaliação.

---

# Valor da Avaliação

| Questão | Conteúdo | Valor |
|---|---|---:|
| 1 | Fundamentos de Java | 0,10 |
| 2 | Condicionais e repetição | 0,15 |
| 3 | Métodos e Strings | 0,15 |
| 4 | Arrays | 0,15 |
| 5 | Classes, objetos e construtores | 0,20 |
| 6 | Encapsulamento | 0,25 |
| **Total** | | **1,00** |

**Valor da Avaliação Formativa I: 1,0 ponto no 1º GQ.**
