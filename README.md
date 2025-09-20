# Sistema de Cadastro de Aluno - Java Swing

Este projeto é um exemplo de aplicação em Java com interface gráfica (GUI) usando **Swing**. Ele permite cadastrar alunos, informando nome, idade e matrícula, e exibe os dados na própria janela.

---

## 🛠 Estrutura do projeto

- **Pessoa.java**  
  Classe base que representa uma pessoa, com os atributos `nome` e `idade`, métodos getters e setters, e o método `exibirDados()`.

- **Aluno.java**  
  Subclasse de `Pessoa` que adiciona o atributo `matricula`. Possui métodos para acessar e alterar a matrícula e sobrescreve o método `exibirDados()` para incluir a matrícula.

- **InterfaceGrafica.java**  
  Classe que cria a interface gráfica usando **JFrame**. Contém campos de texto para inserir nome, idade e matrícula, um botão para exibir os dados, e um label para mostrar o resultado.

- **Main.java**  
  Classe principal que inicializa a aplicação e exibe a janela da interface gráfica.

---

## ⚙️ Funcionalidades

- Inserir **nome**, **idade** e **matrícula** de um aluno.  
- Criar um objeto `Aluno` com os dados fornecidos.  
- Exibir os dados do aluno na janela ao clicar no botão **Exibir Dados**.

---

## 📋 Como usar

1. Compile todas as classes do pacote `gui`.  
2. Execute a classe `Main.java`.  
3. A janela do sistema será exibida.  
4. Preencha os campos de **nome**, **idade** e **matrícula**.  
5. Clique no botão **Exibir Dados** para visualizar as informações do aluno.

---

## 🔍 Conceitos aprendidos

- Herança em Java (`Aluno` estendendo `Pessoa`).  
- Criação e manipulação de objetos.  
- Uso de **Swing** para criar interface gráfica.  
- Manipulação de eventos (`ActionListener`) em botões.  
- Interação entre GUI e classes de modelo (POJO - Plain Old Java Object).

---

## 💡 Observações

- O campo de idade deve ser um número inteiro; caso contrário, o programa lançará uma exceção.  
- A aplicação pode ser expandida para incluir validações de entrada, armazenamento em banco de dados, ou múltiplos alunos em uma lista.

---
