# 🧩 Prova de Conceito – Arquitetura MVC em ASP.NET

Este projeto foi desenvolvido como **prova de conceito da arquitetura de software MVC (Model-View-Controller)**, dentro da disciplina **Desenvolvimento Back-End** do curso de **Análise e Desenvolvimento de Sistemas** da PUC Minas.

A aplicação foi construída em **C#** utilizando o **ASP.NET** no **Visual Studio**, seguindo todos os passos apresentados no microfundamento da disciplina.


## 🚀 Tecnologias Utilizadas
- **ASP.NET Core MVC**
- **C#**
- **Entity Framework Core**
- **SQL Server**
- **Razor**
- **BCrypt.Net-Next** (para criptografia de senhas)
- **Visual Studio 2022**


## 🏗️ Arquitetura do Projeto
O projeto segue o padrão **MVC**, separando as responsabilidades em três camadas:

- **Model:** define as classes que representam as entidades do sistema (ex.: `Veiculo`, `Usuario`).
- **View:** contém as páginas Razor responsáveis pela interface do usuário.
- **Controller:** gerencia as ações da aplicação e faz a comunicação entre o usuário, as Views e o banco de dados.

O **Entity Framework Core** foi utilizado para fazer o mapeamento objeto-relacional (ORM), permitindo a criação e atualização automática das tabelas no banco de dados por meio de *migrations*.


## ⚙️ Funcionalidades Implementadas
- Cadastro de veículos (nome, quilometragem, ano etc.)
- Listagem, edição e exclusão de registros (CRUD completo)
- Autenticação e autorização de usuários (admin e cliente)
- Criptografia de senhas com **BCrypt**
- Integração com banco de dados **SQL Server**


## 🧠 Conceitos Aplicados
- Padrão de arquitetura **MVC**
- **Entity Framework Core** com *migrations*
- **Razor** para criação dinâmica de páginas
- **Criptografia** de dados sensíveis
- Integração entre **front-end (HTML, CSS, JavaScript)** e **back-end (C# / ASP.NET)**

  
## ⚙️ Como Executar o Projeto
- 1 . Clone este repositório:
   ```bash
   git clone https://github.com/grazitorres/mf-dev-backend-2025.git
  
- 2 . Abra o projeto no Visual Studio.
- 3 . Restaure os pacotes NuGet (se necessário).
- 4 . Execute o projeto com Ctrl + F5.
O Visual Studio iniciará a aplicação automaticamente no navegador.

### 🧠 Observação:
Este projeto foi desenvolvido com fins educacionais, como parte da formação em Análise e Desenvolvimento de Sistemas (PUC Minas), na matéria Desenvolvimento Backend.
O front-end é simples, apenas o necessário para visualizar e testar o funcionamento do back-end.
