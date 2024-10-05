# trabalho-andre-gomes
# Aplicativo de Notícias

# APP DE NOTÍCIAS (NEWS)

Este projeto consiste em um aplicativo móvel, chamado **News**, que apresenta um catálogo de notícias utilizando a API de notícias do IBGE para obter informações sobre esportes, saúde, segurança e previsão do tempo.

## Equipe de Desenvolvimento
- **André Fellipe Gomes Ramos Filho**

## Links
- **API Notícias IBGE**: [Documentação](https://servicodados.ibge.gov.br/api/docs/noticias?versao=3#api-_)
- **Figma (Protótipo)**: [Visualizar no Figma](https://www.figma.com/proto/OdLOFHxvk7cxxxwgjy6vVa/NEWS?node-id=0-1&t=UfBH7Ambc4oaWcEf-1)
- **ARQUITETURA MVVM (VIDEO)**: [Visualizar no Navegador](https://youtu.be/f5Z1FtKW9sk)
- 
---

## 📑 Documento de Requisitos

### 1. Funcionalidades

- Interface de cadastro e login de usuários.
- Listagem de principais notícias.
- Visualização de detalhes das notícias ao clicar.
- Funcionalidade de selecionar uma das 4 categorias: Esportes, Saúde, Segurança e Previsão do Tempo.
- Listagem de notícias por categoria.
- Visualização de detalhes das notícias.

### 2. Requisitos Funcionais

#### 2.1 Autenticação de Usuários
- **RF01**: O sistema deve permitir que novos usuários se cadastrem com nome, email e senha.
- **RF02**: O sistema deve permitir o login de usuários cadastrados com email e senha.
- **RF03**: O sistema deve exibir mensagens de erro em caso de falha no login (credenciais incorretas) ou cadastro (email já existente).

#### 2.2 Tela Inicial
- **RF04**: Após o login, o sistema exibirá um menu com todas as funcionalidades para o usuário escolher.
- **RF05**: O sistema deve permitir a busca pelo nome da categoria escolhida.
- **RF06**: O sistema deve permitir ao usuário clicar em uma notícia para visualizar seus detalhes.

#### 2.3 Tela Esportes
- **RF07**: O sistema deve exibir um menu com todas as funcionalidades após o login, com foco na categoria Esportes.
- **RF08**: O sistema deve permitir que o usuário navegue pelas notícias de esportes clicando no botão de emoji de uma bola de futebol.

#### 2.4 Tela de Previsão do Tempo
- **RF09**: O sistema deve exibir um menu com todas as funcionalidades após o login, com foco na categoria Previsão do Tempo.
- **RF10**: O sistema deve permitir que o usuário navegue pelas notícias de previsão do tempo clicando no botão de emoji de uma nuvem.
- **RF11**: O sistema deve permitir que o usuário selecione um estado e visualize sua previsão do tempo.

#### 2.5 Tela de Saúde
- **RF12**: O sistema deve exibir um menu com todas as funcionalidades após o login, com foco na categoria Saúde.
- **RF13**: O sistema deve listar todas as notícias de saúde.
- **RF14**: O sistema deve permitir que o usuário selecione uma notícia para visualizar seus detalhes.

#### 2.6 Tela de Segurança
- **RF15**: O sistema deve exibir um menu com todas as funcionalidades após o login, com foco na categoria Segurança.
- **RF16**: O sistema deve listar todas as notícias de segurança.
- **RF17**: O sistema deve permitir que o usuário selecione uma notícia para visualizar seus detalhes.

### 3. Requisitos Não Funcionais

#### 3.1 Usabilidade
- **RNF01**: O aplicativo deve ter uma interface intuitiva, permitindo fácil navegação entre as telas: Inicial, Saúde, Esportes, Previsão do Tempo e Segurança.

#### 3.2 Segurança
- **RNF02**: As senhas dos usuários devem ser armazenadas de maneira segura utilizando criptografia.

### 4. Fluxo de Navegação

#### 4.1 Fluxo de Cadastro e Login
- O usuário é recebido pela tela de login com a opção de "Entrar" ou "Cadastrar-se".
- Se o usuário não tiver uma conta, ele pode clicar em "Cadastrar-se" e preencher o formulário de cadastro.
- Após o cadastro, o usuário é redirecionado à tela de login para acessar o sistema.
- O usuário insere seu email e senha para fazer login.

#### 4.2 Fluxo do Menu
- Após fazer login, o usuário é direcionado para a aba de menu, onde pode navegar entre as funcionalidades (Esportes, Saúde, Previsão do Tempo, Segurança, Home).
- Ao clicar em alguma das opções, o sistema seguirá conforme os requisitos funcionais das seções 2.2 até 2.6.

### 5. Tecnologias e Ferramentas

- **Linguagem de Programação**: Kotlin
- **API de Dados**: API Notícias IBGE
- **Autenticação**: Firebase Authentication (ou similar)
- **Banco de Dados**: Firebase Realtime Database / PostgreSQL / ou outro
- **IDE**: Android Studio
- **Design**: Figma

