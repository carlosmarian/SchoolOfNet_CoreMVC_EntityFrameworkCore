# SchoolOfNet_CoreMVC_EntityFrameworkCore
# ASP.NET Core 1.0

Projeto do curso ASP.NET Core MVC + Entity Framework Core


Projeto base foi usado o https://github.com/schoolofnetcom/aspnet-core-ef

Foi usado Visual Studio 2015 e foi necessário instalar o Core 1.0:
https://dotnet.microsoft.com/download/dotnet-core/1.1
e
https://go.microsoft.com/fwlink/?LinkId=827546

Fonte: https://stackoverflow.com/questions/39020289/microsoft-dotnet-props-was-not-found


Docker do MYSQL: docker-compose.yml Comand: docker-compose up db

Criar banco com o nome: coremvc_entityframework

Estoui usando o HeidiSQL

Para usar Mysql deve: Acessar https://www.nuget.org/ Pesquisar pelo pacote: MySQL Entity Framework Selecionar o pacote: Pomelo.EntityFrameworkCore.MySql copiar a linha de comando

No projeto add :

 Install-Package Pomelo.EntityFrameworkCore.MySql -Version 1.0.0
 
 depois:
 
 dotnet restore
 