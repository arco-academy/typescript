# Typescript

TypeScript é um superconjunto de JavaScript, ou seja, um conjunto de ferramentas e formas mais eficientes de escrever código JavaScript, adicionando recursos que não estão presentes de maneira nativa na linguagem. Saiba mais sobre TypeScript, suas principais vantagens e como utilizá-lo em seus projetos.

---

> Agora que já estamos craques em Typescript, vamos fazer alguns exercicíos para fixar todo o conteúdo que aprendemos, bora?

## Exercícios

### Primeiro Exercício

Com base nas interfaces a seguir, crie uma tipagem chamada **TeacherLesson**, na qual concatena as informaçoes de **Teacher** e **Lesson**. Ao final do exercicio, deverá conter as informações do professor e um array de lições.  

```typescript=
interface Lesson {
  name: string
  studentLimit: number
  workload: number
  required: boolean
}

interface Teacher {
  name: string
  formation: string
  age: number;
  lessons: unknown
}

```

### Segundo Exercício

Crie um tipo `Mapper` customizado que adicione a propriedade **null** dinâmicamente aos seguintes parâmetros.

```typescript=
type Student = {
  id: string
  name: string
  email: string
  age: number
  active: boolean
}
```

### Terceiro Exercício

Crie um tipo `Mapper` customizado que converta todas as propriedades para não obrigatórios.

```typescript=
type Student = {
  id: string
  name: string
  email: string
  age: number
  active: boolean
}
```

### Quarto Exercício

Crie uma tipagem condicional que filtre um ou mais nomes presentes a baixo e atribua a uma variavel para aceitar apenas os nomes 'Kindra & Shiroma':

```typescript=
type Names = "Kindra" | "Shiroma" | "DG" | "Bezerra" | "Jean" | "May" | "Carolis"
```

### Quinto Exercício

Crie uma tipagem condicional que filtre um ou mais nomes presentes a baixo e atribua a uma variavel para aceitar apenas os nomes 'Kindra & Shiroma':

```typescript=
type Names = "Kindra" | "Shiroma" | "DG" | "Bezerra" | "Jean" | "May" | "Carolis"
```

### Sexto Exercício

Crie uma interface com base no exemplo abaixo que remove o `readonly` de todos os parametros tornando assim informações mutáveis:

```typescript=
type Student = {
  readonly id: string
  readonly name: string
  readonly email: string
  age: number
  active: boolean
}

```
