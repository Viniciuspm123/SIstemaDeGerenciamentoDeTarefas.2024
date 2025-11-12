## Projeto - Sistema de Gerenciamento de Tarefas (Console Java)

Este projeto implementa um **sistema básico de lista de tarefas (To-Do List)** em Java, executado diretamente no console (terminal). O aplicativo permite adicionar, listar e marcar tarefas como concluídas.

### 🚀 Sobre o Projeto

O aplicativo é estruturado em duas classes: **(Tarefa)**, que modela o objeto individual, e **(SistemaGerenciamentoTarefas)**, que contém a lógica principal, o *loop* do menu e o gerenciamento da lista de tarefas. O foco é demonstrar a **programação orientada a objetos (POO)** e a manipulação de coleções (`ArrayList`) para gerenciar dados em tempo de execução.

### 🛠️ Tecnologias e Conceitos Abordados

**Estrutura de Classes (POO):**

* **Classe (Tarefa):** Possui atributos privados (`descricao`, `concluida`) e métodos públicos (`getDescricao`, `isConcluida`, `marcarConcluida`) para encapsulamento.
* **Método `(toString)`:** Sobrescrito na classe (Tarefa) para fornecer uma representação textual clara do objeto no console.

**Coleções e Estruturas de Dados:**
Uso de `(ArrayList)` para armazenar dinamicamente a lista de objetos (Tarefa) na memória.

**Interação via Console:**
Utilização da classe `(Scanner)` para ler a entrada de dados do usuário (opções do menu, descrição da tarefa, número da tarefa).

**Controle de Fluxo:**
Uso de um *loop* `(while (true))` para manter o menu do sistema ativo até que o usuário escolha a opção **Sair**.
Uso de `(if/else if)` para direcionar o fluxo do programa com base na opção do menu escolhida.

**Lógica de Negócios:**

* **Adicionar:** Cria uma nova instância de (Tarefa) e a adiciona à `ArrayList`.
* **Listar:** Itera sobre a `ArrayList`, exibindo o índice e o conteúdo de cada tarefa.
* **Marcar como Concluída:** Solicita o índice da tarefa, acessa o objeto correto na lista e chama o método `marcarConcluida()`.

### 💻 Como Executar

Clone este repositório.

Este projeto deve ser compilado e executado através de um ambiente de desenvolvimento Java (IDE), como Eclipse ou IntelliJ, ou via terminal, sendo totalmente interativo via **console**.
