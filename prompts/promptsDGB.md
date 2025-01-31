# MegaMan Boss API

Este projeto é uma API desenvolvida em .NET para listar os dados dos bosses de MegaMan. O objetivo principal é fornecer JSONs com informações detalhadas sobre cada boss.

## Estrutura do JSON

A API retorna os dados no seguinte formato:

```json
{
  "Id": 1,
  "Code": "DLN/DRN-003",
  "Name": "Cutman",
  "HP": 150,
  "Picture": "https://vignette.wikia.nocookie.net/megaman/images/2/22/Cutman.png"
}

#### Especificações do Projeto
<Project Sdk="Microsoft.NET.Sdk.Web">

#### Como executar
git clone https://github.com/seu-usuario/megaman-boss-api.git

#### Navegue até o repositório do projeto
cd megaman-boss-api

#### Restaure as dependencias do projeto
dotnet restore

#### Execute a aplicação
dotnet run

Endpoints
GET /bosses
Retorna a lista de todos os bosses.

GET /bosses/{id}
Retorna os detalhes de um boss específico.

Tecnologias Utilizadas
.NET Core

ASP.NET Core

Entity Framework Core

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.


