# Change Log v. 1.0
Esse projeto tem como objetivo a elaboração de uma API com a finalidade de integrar um programa em C# com um Banco de Dados (SQL Server) através do Entity Framework. Foram utilizados para a elaboração dessa integração a ferramenta Visual Studio Code e o Swagger pelo Browser além do SQL Server Management Studio.

## Observações:
É necessário baixar pacotes para o Visual Studio Code para que a API funcione normamalemente como:

- Instalação feita uma vez na sua máquina
  
dotnet tool install --global dotnet-ef 

- Instalação feita uma vez por projeto)
  
dotnet add package Microsoft.EntityFrameworkCore.Design  
dotnet add package Microsoft.EntityFrameworkCore.SqlServer

- Criação da tabela no banco de dados SQL

dotnet-ef database update

- Monitoramento e manipulação do banco de dados através do Swgger

dotnet watch run



## 💡 Features Added

- API criada com sucesso



## 🕷️ Bugs Reported

-

## 🔧 Issues Fixeds

- 
