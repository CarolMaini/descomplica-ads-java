# Descomplica ADS — Java

Repositório acadêmico para organizar os estudos, exercícios, atividades e projetos desenvolvidos durante a graduação em **Análise e Desenvolvimento de Sistemas (ADS) na Faculdade Descomplica**, com foco na linguagem **Java**.

O objetivo é manter um histórico progressivo de aprendizagem, com exemplos de código organizados por assunto e versionados com Git.

## Objetivos de estudo

- Registrar a evolução no aprendizado de Java.
- Praticar lógica de programação e fundamentos da linguagem.
- Organizar conteúdos por assunto para facilitar a consulta.
- Desenvolver gradualmente conhecimentos de orientação a objetos.
- Reunir exercícios, atividades acadêmicas e projetos.
- Utilizar Git e GitHub para acompanhar a evolução do código.

## Conteúdo atual

Neste momento, o repositório contém um primeiro exemplo executável:

- `exercicios/ExemploHelloWorld.java` — classe com método `main` que imprime a mensagem `Olá, mundo!`.

As demais pastas de estudo estão preparadas para receber os próximos exercícios e anotações. Elas ainda não representam módulos ou conteúdos já concluídos.

## Estrutura

```text
descomplica-ads-java/
├── fundamentos/
│   ├── variaveis/
│   ├── tipos-de-dados/
│   └── operadores/
├── estruturas-controle/
│   ├── condicionais/
│   └── repeticao/
├── poo/
│   ├── classes/
│   ├── objetos/
│   └── heranca/
├── exercicios/
│   └── ExemploHelloWorld.java
├── atividades/
├── projetos/
├── anotacoes/
├── .gitignore
└── README.md
```

As pastas ainda sem arquivos de estudo utilizam `.gitkeep` para permanecerem versionadas.

## Executar o exemplo

É necessário ter um JDK instalado e disponível no terminal.

A partir da raiz do repositório, compile o exemplo:

```bash
javac -d out exercicios/ExemploHelloWorld.java
```

Execute a classe:

```bash
java -cp out ExemploHelloWorld
```

Saída esperada:

```text
Olá, mundo!
```

Os arquivos compilados são gerados na pasta `out/`, que não faz parte do código-fonte versionado.

## Organização dos próximos conteúdos

Os exercícios serão adicionados gradualmente às pastas correspondentes:

- `fundamentos/`: variáveis, tipos de dados e operadores.
- `estruturas-controle/`: estruturas condicionais e repetição.
- `poo/`: classes, objetos e herança.
- `exercicios/`: práticas independentes.
- `atividades/`: entregas e atividades acadêmicas.
- `projetos/`: projetos desenvolvidos durante os estudos.
- `anotacoes/`: resumos e referências de aula.

## Convenção sugerida para commits

- `docs:` documentação e anotações.
- `feat:` novos exercícios ou funcionalidades.
- `fix:` correções.
- `refactor:` melhorias na organização do código.
- `test:` inclusão ou ajuste de testes.

Exemplo:

```text
feat: adiciona exercício de estruturas condicionais
```

## Tecnologias e ferramentas

- Java
- JDK
- Git e GitHub
- IDE de preferência (IntelliJ IDEA, Eclipse ou VS Code)

## Instituição

**Faculdade Descomplica**  
Curso: Análise e Desenvolvimento de Sistemas  
Linguagem de estudo: Java

---

*Repositório acadêmico em evolução contínua. O conteúdo será ampliado conforme o avanço dos estudos.*
