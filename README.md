# CRUD - Sistema de Gerenciamento de Usuários

Este é um sistema básico de CRUD (Create, Read, Update, Delete) implementado em Python, utilizando MySQL como banco de dados. O objetivo é realizar operações simples de gerenciamento de usuários, como inserção, seleção, atualização e exclusão de registros.

## Requisitos

Para executar este código, é necessário ter instalado:
- MySQL Server
- Pacote `mysql-connector-python` (instalado via `pip`)

## Instalação e Configuração

1. **Instalação do MySQL Server:**
    - O código fornece comandos para instalação do MySQL Server.
    - Após a instalação, é configurada a senha do usuário root como '1210'.

2. **Instalação do pacote de conexão MySQL para Python:**
    - Utiliza-se o comando `pip` para instalar o pacote `mysql-connector-python`.

3. **Configuração da Conexão:**
    - A conexão com o banco de dados é estabelecida com as seguintes credenciais:
        - Host: localhost
        - Banco de Dados: crud
        - Usuário: root
        - Senha: 1210

## Funcionalidades

- **Create (INSERT):**
    - São realizadas inserções de registros na tabela 'usuarios' do banco de dados MySQL.

- **Read (SELECT):**
    - São realizadas seleções de registros na tabela 'usuarios', exibindo todos os registros e um único registro com base no ID do usuário.

- **Update:**
    - É possível atualizar os dados de um usuário específico com base no ID fornecido.

- **Delete:**
    - É possível excluir um usuário com base no ID fornecido.

- **Login:**
    - Implementação básica de login de usuário, onde é solicitado o email e a senha, verificando sua existência na tabela 'usuarios'.

## Utilização

- Execute o código em um ambiente Python compatível.
- O código interage com o usuário através de prompts de entrada no terminal para inserir dados, fazer login e realizar outras operações.

## Autor

- Luiz Fernando Pedrozo

