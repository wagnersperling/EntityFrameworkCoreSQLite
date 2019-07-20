Projeto de teste usando Entity Framework Core com SQLite.

Foi instalado os seguintes pacotes via Manage Nuget Packages for Solution.
Microsoft.EntityFrameworkCore.Sqlite
Microsoft.EntityFrameworkCore.Sqlite.Design

Foi instalado o seguinte pacote via Console do Gerenciador de Pacotes.
Install-Package Microsoft.EntityFrameworkCore.Tools -Version 2.1.0

Para criar o banco de dados abra o console posicionado na pasta que o projeto foi criado e execute os seguintes comandos:

dotnet ef migrations add TesteMigration     Comando que cria as tabelas iniciais.

dotnet ef database update          Comando que atualiza o banco de dados.

