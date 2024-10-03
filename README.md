# trabalho-andre-gomes
# Aplicativo de Notícias

## 1.0 Funcionalidades  

- Interface de cadastro e login de usuários.
- Listagem de principais notícias.
- Visualização de detalhes das notícias ao clicar.
- Funcionalidade de selecionar uma das 4 categorias (Esportes, Saúde, Segurança e Previsão do Tempo).
- Listagem de notícias por categoria.
- Visualização de detalhes de cada notícia.

## 2. Requisitos Funcionais  

### 2.1 Autenticação de Usuários  

- **RF01**: O sistema deve permitir que novos usuários se cadastrem com nome, email e senha.
- **RF02**: O sistema deve permitir o login de usuários cadastrados com email e senha.
- **RF03**: O sistema deve exibir mensagens de erro em caso de falha no login (credenciais incorretas) ou cadastro (email já existente).

### 2.2 Tela Inicial

- **RF04**: Após o login, o sistema exibirá um menu com todas as funcionalidades onde o usuário poderá escolher qual acessar.
- **RF05**: O sistema deve permitir a busca pelo nome da categoria escolhida.
- **RF06**: O sistema deve permitir ao usuário clicar em uma notícia da lista para visualizar seus detalhes.

### 2.3 Tela Esportes

- **RF07**: Após o login, o sistema exibirá um menu onde o usuário poderá escolher a categoria Esportes.
- **RF08**: O sistema deve permitir que o usuário navegue nas notícias de esportes clicando no botão com o emoji de uma bola de futebol.

### 2.4 Tela de Previsão de Tempo

- **RF09**: Após o login, o sistema exibirá um menu onde o usuário poderá escolher a categoria Previsão do Tempo.
- **RF10**: O sistema deve permitir que o usuário navegue nas notícias de previsão do tempo clicando no botão com o emoji de uma nuvem.
- **RF11**: O sistema deve permitir que o usuário selecione um estado e veja sua previsão de tempo.

### 2.5 Tela de Saúde 

- **RF12**: Após o login, o sistema exibirá um menu onde o usuário poderá escolher a categoria Saúde.
- **RF13**: O sistema deve listar todas as notícias de saúde.
- **RF14**: O sistema deve permitir que o usuário selecione uma notícia e veja seus detalhes.

### 2.6 Tela de Segurança 

- **RF15**: Após o login, o sistema exibirá um menu onde o usuário poderá escolher a categoria Segurança.
- **RF16**: O sistema deve listar todas as notícias de segurança.
- **RF17**: O sistema deve permitir que o usuário selecione uma notícia e veja seus detalhes.

## 3. Requisitos Não Funcionais  

### 3.1 Usabilidade  

- **RNF01**: O aplicativo deve ter uma interface intuitiva, permitindo navegação fácil entre as telas: Inicial, Saúde, Esportes, Previsão do Tempo e Segurança.

### 3.2 Segurança  

- **RNF02**: As senhas dos usuários devem ser armazenadas de maneira segura utilizando criptografia.

## 4. Fluxo de Navegação  

### 4.1 Fluxo de Cadastro e Login  

- O usuário é recebido pela tela de login com a opção de "Entrar" ou "Cadastrar-se".
- Se o usuário não tiver uma conta, ele pode clicar em "Cadastrar-se" e preencher o formulário de cadastro.
- Após o cadastro, o usuário é redirecionado à tela de login para acessar o sistema.
- O usuário insere seu email e senha para fazer login.

### 4.2 Fluxo do Menu

- Após fazer login, o usuário é direcionado para a aba de menu, onde estão as funcionalidades disponíveis: Esportes, Saúde, Previsão do Tempo, Segurança e Home.
- Ao clicar em alguma dessas opções, seguir os requisitos funcionais da seção 2.2 até a 2.6.

## 5. Tecnologias e Ferramentas  

- **Linguagem de Programação**: Kotlin
- **API de Dados**: API de Notícias (IBGE)
- **Autenticação**: Firebase Authentication (ou similar)
- **Banco de Dados**: Firebase Realtime Database / PostgreSQL (ou outro)
- **IDE**: Android Studio
- **Design**: Figma
