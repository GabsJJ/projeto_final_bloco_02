# Projeto Farmácia - Backend com Spring Boot

<br />

<div align="center">
    <img src="https://i.imgur.com/w8tTOuT.png" title="source: imgur.com" /> 
</div>

<br />

<div align="center">
  <img src="https://img.shields.io/github/languages/top/GabsJJ/projeto_final_bloco_02?style=flat-square" />
  <img src="https://img.shields.io/github/repo-size/GabsJJ/projeto_final_bloco_02?style=flat-square" />
  <img src="https://img.shields.io/github/languages/count/GabsJJ/projeto_final_bloco_02?style=flat-square" />
  <img src="https://img.shields.io/github/last-commit/GabsJJ/projeto_final_bloco_02?style=flat-square" />
  <img src="https://img.shields.io/github/issues/GabsJJ/projeto_final_bloco_02?style=flat-square" />
  <img src="https://img.shields.io/github/issues-pr/GabsJJ/projeto_final_bloco_02?style=flat-square" />
  <img src="https://img.shields.io/badge/status-construção-yellow" alt="Status: Em Construção">

</div>

## 1. Sobre esta API

A API Farmácia foi desenvolvida utilizando **Java** e o **framework Spring**, seguindo os princípios da Arquitetura MVC e REST. Ela oferece endpoints para o gerenciamento dos recursos **Usuário**, **Produtos** e **Categoria**, permitindo a interação entre os usuários e os produtos da farmácia.

### 1.1. Principais funcionalidades da API:

1. Consulta, cadastro, login e atualização dos dados dos usuários
2. Consulta, criação e gerenciamento de categorias para organizar os produtos
3. Cadastro, edição, listagem e exclusão de produtos
4. Associação de produtos à categorias
5. Autenticação via token JWT para segurança nas requisições


## 2. Requisitos

Para executar os códigos localmente, você precisará:

- [Java JDK 17+](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- Banco de dados [MySQL](https://dev.mysql.com/downloads/)
- [STS](https://spring.io/tools)
- [Insomnia](https://insomnia.rest/download) ou [Postman](https://www.postman.com/)

## 3. Como Executar o projeto no STS

### 3.1. Importando o Projeto

1. Clone o repositório do Projeto [Farmácia](https://github.com/GabsJJ/projeto_final_bloco_02) dentro da pasta do *Workspace* do STS

```bash
git clone https://github.com/GabsJJ/projeto_final_bloco_02.git
```

1. **Abra o STS** e selecione a pasta do *Workspace* onde você clonou o repositório do projeto
2. No menu superior do STS, clique em **File 🡲 Import...**
3. Na janela **Import**, selecione **General 🡲 Existing Projects into Workspace** e clique em **Next**
4. No item **Select root directory**, clique em **Browse...** e selecione a pasta do Workspace onde clonou o repositório
5. O STS reconhecerá o projeto automaticamente
6. Marque o Projeto Loja de Games no item **Projects** e clique em **Finish**

### 3.2. Executando o projeto

1. Na Guia **Boot Dashboard**, localize o **Projeto Farmacia**
2. Selecione o **Projeto Farmacia**
3. Clique no botão **Start or Restart**  para iniciar a aplicação
4. Caso solicitado, autorize o acesso à rede para o projeto
5. Acompanhe a inicialização no console do STS
6. Verifique se o banco de dados `db_farmacia` foi criado corretamente com as tabelas necessárias
7. Utilize o [Insomnia](https://insomnia.rest/) ou o [Postman](https://www.postman.com/) para testar os endpoints

<br />

> [!TIP]
>
> Ao acessar a URL `http://localhost:8080` em seu navegador, a interface do Swagger será carregada automaticamente, permitindo a visualização e interação com os endpoints da API e consulta dos modelos de dados.

<br />


## 4. Contribuição

Este repositório é parte de um projeto educacional, mas contribuições são bem-vindas! Caso tenha sugestões, correções ou melhorias, fique à vontade para:

- Criar uma **issue**
- Enviar um **pull request**
- Compartilhar com colegas que estejam aprendendo Java!


## 5. Contato

Desenvolvido por [**Gabriel**](https://github.com/GabsJJ)
