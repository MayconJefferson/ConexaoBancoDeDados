# Comandos para migração:
``` bash
dotnet tool install --global dotnet-ef
dotnet ef migrations add CarroAdd
dotnet ef database update