# FiapCloudGames.Gateway

## 📌 Objetivos
API Gateway para gerir os microsserviços:
  - [FiapCloudGames.Users](https://github.com/MarioGuilherme/FiapCloudGames.Users);
  - [FiapCloudGames.Games](https://github.com/MarioGuilherme/FiapCloudGames.Games);
  - [FiapCloudGames.Payments](https://github.com/MarioGuilherme/FiapCloudGames.Payments).

## 🚀 Instruções de uso
Faça o clone do projeto e já acesse a pasta do projeto clonado:
```
git clone https://github.com/MarioGuilherme/FiapCloudGames.Gateway
```

### ▶️ Iniciar Projeto
  1 - Navegue até o diretório da camada API da aplicação:
  ```
  cd .\FiapCloudGames.Gateway
  ```

  2 - Insira o comando de execução do projeto:
  ```
  dotnet run --launch-profile https
  ```

  3 - Acesse https://localhost:7129/swagger/index.html

## 🛠️ Tecnologias e Afins
- .NET 8 com C# 12;
- ASP.NET Core;
- Ocelot Gateway;
- Swagger;
- MMLib.SwaggerForOcelot
- Autenticação JWT;
- Rate Limit.
