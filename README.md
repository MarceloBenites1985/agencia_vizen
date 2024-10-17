# Agência de emprego Vizen - Sistema de Gerenciamento de Vagas e Candidaturas

Este é um sistema de agência de emprego desenvolvido com **Ruby on Rails**. Ele permite que empresas cadastrem vagas de emprego e que candidatos se candidatem a essas vagas. Também possui funcionalidades de autenticação de usuários, gerenciamento de perfis e envio de notificações por e-mail.

## Funcionalidades

- Cadastro e login de empresas e candidatos.
- Gerenciamento de vagas de emprego (CRUD: criação, leitura, atualização e exclusão).
- Candidatura de usuários às vagas.
- Listagem de vagas disponíveis com filtros por categoria, localização, etc.
- Sistema de notificações por e-mail para candidatos e empresas.
- Autenticação e gerenciamento de perfis.
- Integração com PostgreSQL para armazenamento de dados.

## Tecnologias Utilizadas

- **Ruby on Rails** (Framework)
- **PostgreSQL** (Banco de Dados)
- **HTML/CSS** (Frontend básico)
- **Bootstrap** (Estilização)
- **Devise** (Autenticação)
- **Action Mailer** (Notificações por e-mail)
- **Docker** (Opcional, para configuração do ambiente de desenvolvimento)

## Instalação

### Pré-requisitos

- Ruby 3.x
- Rails 7.x
- PostgreSQL
- Docker (opcional)

### Passos para instalação

1. Clone o repositório:
    
    ```bash
    bash
    Copiar código
    git clone https://github.com/seu_usuario/nome_do_repositorio.git
    cd nome_do_repositorio
    
    ```
    
2. Instale as dependências:
    
    ```bash
    bash
    Copiar código
    bundle install
    
    ```
    
3. Configure o banco de dados:
    
    ```bash
    bash
    Copiar código
    rails db:create
    rails db:migrate
    
    ```
    
4. Configure as variáveis de ambiente no arquivo `.env` (exemplo incluído).
5. Inicie o servidor:
    
    ```bash
    bash
    Copiar código
    rails server
    
    ```
    
6. Acesse a aplicação no navegador em `http://localhost:3000`.

## Testes

Para rodar os testes, utilize o comando:

```bash
bash
Copiar código
rails test

```

## Docker (Opcional)

Se preferir usar Docker, siga os passos abaixo:

1. Suba os containers:
    
    ```bash
    bash
    Copiar código
    docker-compose up
    
    ```
    
2. Acesse a aplicação no navegador em `http://localhost:3000`.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou relatar um problema.
