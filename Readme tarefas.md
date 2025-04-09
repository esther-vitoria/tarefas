# 📅 Gerenciador de Tarefas Simples em Java

Este é um projeto simples de **Gerenciador de Tarefas** para terminal, desenvolvido em Java. O programa permite que o usuário cadastre até 10 tarefas e as visualize por meio de um menu interativo.


---

## 🧠 Conceitos Utilizados

- Arrays
- Estruturas de repetição (`while`) e decisão (`switch`)
- Entrada de dados com `Scanner`
- Manipulação de strings e índices

---

## 🎮 Funcionalidades

- Cadastrar uma tarefa em uma das 10 posições
- Listar todas as tarefas
- Encerrar o programa

---

## 🔄 Como Funciona

1. O programa inicia com uma lista de 10 tarefas vazias, representadas por "x".
2. Um menu é exibido com 3 opções:
   - `1` para cadastrar uma tarefa
   - `2` para listar todas as tarefas
   - `3` (ou qualquer outro número diferente de 1 e 2) para sair
3. O usuário pode escolher uma posição de 1 a 10 para cadastrar uma nova tarefa.
4. As tarefas são armazenadas em um array de `String`.

---

## 🚀 Exemplo de Execução

```
Opções:
1. Cadastrar tarefa
2. Listar tarefas
3. Sair
1
Digite o número da tarefa (1 à 10):
3
Digite a tarefa:
Estudar Java

Opções:
1. Cadastrar tarefa
2. Listar tarefas
3. Sair
2
Tarefa 1 - x
Tarefa 2 - x
Tarefa 3 - Estudar Java
Tarefa 4 - x
...
```

---

## ⚙️ Como Executar

1. Salve o código no arquivo `Tarefas.java`.
2. Compile com o comando:
   ```bash
   javac Tarefas.java
   ```
3. Execute:
   ```bash
   java Tarefas
   ```


---

Feito com ❤️ em Java para praticar lógica e estruturas básicas de programação.

