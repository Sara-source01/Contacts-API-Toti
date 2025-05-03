# 📇 Contact Manager API (Node.js + JSON Server)

Um projeto simples para gerenciar contatos usando Node.js + JSON Server, com dados armazenados em um arquivo JSON. As requisições podem ser testadas facilmente usando o Insomnia.

## 🚀 Funcionalidades

- Criar novo contato (POST)
- Listar todos os contatos (GET)
- Atualizar contato existente (PUT)
- Deletar contato (DELETE)

## ⚙️ Requisitos

- Node.js instalado
- Editor de código (ex: VS Code)
- Insomnia (para testar a API)

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Sara-source01/Contacts-API-Toti.git

## ▶️ Como rodar o projeto

Acesse a pasta do projeto:

```bash
cd nome-do-projeto(React-Project-app)

Instale as dependências:
```bash
npm install

Inicie o servidor:
```bash
node exemplo.json
Se estiver usando JSON Server:
```bash
json-server exemplo.json
ou 
json-server --watch exemplo.json --port 3000

O servidor estará rodando em: http://localhost:3000/contacts



🔄 Forma1:Testando com Insomnia
Para importar as requisições:

Abra o Insomnia.

Vá até File > Import (ou clique em "Create" > "Import").

Escolha a opção From File.

Selecione o arquivo exemplo.json.

Isso vai importar automaticamente os endpoints GET, POST, PUT e DELETE já prontos para teste.

🔄 Forma2: Testando com Insomnia
Abra o Insomnia.
Clique em "Create"
Selecione a opção Request Collection 
Escolha nome da coleção como "Contatos API" e clique "creat"
Clique em "Create" e escolha"Add request to current collection" para crira uma solicitação de GET e coloque http://localhost:3000/contacts.


Você verá os endpoints para:

GET /contacts → Listar todos os contatos
POST /contacts → Criar um novo contato
PUT /contacts/:id → Atualizar um contato
DELETE /contacts/:id → Remover um contato


📝 Autor
Nome: Sara
Curso: Desenvolvimento Full Stack
