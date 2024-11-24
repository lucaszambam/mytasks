# **MyTasks**

Um aplicativo simples para gerenciar tarefas, desenvolvido com Flutter.

## **Objetivo**
O **MyTasks** é um aplicativo projetado para ajudar o usuário a gerenciar suas tarefas do dia a dia de maneira simples e eficiente. Ele permite adicionar, listar e excluir tarefas, salvando os dados localmente no dispositivo.

---

## **Funcionalidades**
- **Adicionar tarefas**: O usuário pode criar novas tarefas rapidamente.  
- **Listar tarefas**: Exibe todas as tarefas criadas em uma lista organizada.  
- **Excluir tarefas**: Permite remover tarefas desnecessárias com um único clique.  
- **Armazenamento local**: As tarefas são salvas no dispositivo usando o pacote `shared_preferences`, garantindo que os dados não sejam perdidos ao fechar o aplicativo.

---

## **Telas do Aplicativo**

### 1. **Tela Inicial (Lista de Tarefas)**
- Exibe todas as tarefas criadas.
- Possui um botão flutuante para adicionar novas tarefas.
- Cada item da lista possui um botão para excluir a tarefa correspondente.

### 2. **Tela de Adicionar Tarefa**
- Permite que o usuário insira o nome de uma nova tarefa.
- Possui um campo de texto e um botão para salvar a tarefa.

---

## **Como Executar o Projeto**

### **Pré-requisitos**
- Flutter SDK instalado ([guia de instalação](https://docs.flutter.dev/get-started/install)).
- Um dispositivo ou emulador configurado (Android/iOS).

### **Passos**
1. Clone o repositório:
   ```bash
   git clone https://github.com/lucaszambam/mytasks.git
   cd mytasks
   ```
2. Instale as dependências:
   ```bash
   flutter pub get
   ```
3. Execute o aplicativo:
   ```bash
   flutter run
   ```

---

## **Tecnologias Utilizadas**
- **Flutter**: Framework para desenvolvimento de aplicativos multiplataforma.
- **Dart**: Linguagem de programação utilizada pelo Flutter.
- **shared_preferences**: Pacote para armazenamento local.
