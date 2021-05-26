This repository contains a basic glossary CRUD Web API implemented in ASP.NET and secured with [Auth0](https://auth0.com/).

The following article describes the implementation details: [Managing Authorization for ASP.NET Web APIs](https://auth0.com/blog/aspnet-web-api-authorization/)

## To run this application:

1. Clone the repo with the following command: 

   ```bash
   git clone --branch add-authorization --single-branch https://github.com/auth0-blog/glossary-web-api-aspnet.git
   ```

2. Move to the `glossary-web-api-aspnet` folder 

3. Add your Auth0 domain and API identifier to the `appsettings.json` configuration file (see [Registering the Web API with Auth0](https://auth0.com/blog/aspnet-web-api-authorization/#Registering-the-API-application-with-Auth0) for more details).

4. Type `dotnet run` in a terminal window to launch the Web API.

5. Point your browser to `https://localhost:5001/swagger` to test the available endpoints and actions.

![webapi-swagger-ui](https://images.ctfassets.net/23aumh6u8s0i/1rNBChKdbCr9fKdpbbYcKR/014f6ace0411febc726959cd88ed8e6a/protected-swagger-ui-webapi.png)

## Requirements:

- [.NET Core SDK](https://dotnet.microsoft.com/download/dotnet/current) installed on your machine

