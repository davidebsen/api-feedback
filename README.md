<h1 align="center">API-Feedback</h1>

## Início
Projeto feito em cima da bae do PalpiteBox disponivel no [Github](https://github.com/)

* O projeto API fornece duas opções de avaliação para o estabelecimento. Na primeira opção, o cliente pode fornecer informações pessoais como nome e número do WhatsApp, escolher o local a ser avaliado e atribuir uma nota ao estabelecimento usando emotes. Na segunda opção, o cliente pode apenas selecionar o nível de satisfação com o estabelecimento usando emotes. Se em ambus o formulário for submetido, pode ou não ser gerado um cupom de desconto, dependendo das configurações estabelecidas na planilha do Google pelo proprietário do estabelecimento. O cupom pode ser salvo como PDF ou impresso. A aplicação tem integração com uma planilha do Google, permitindo que o proprietário configure as opções de cupom de desconto e visualize uma lista completa de clientes e avaliações.

## Pré-requisitos:

* [NodeJS](https://www.nodejs.org) (versão 12 ou superior) 
* [NPM](https://classic.yarnpkg.com) [instalado juntamento com o NodeJS]
* Editor de código ([Visual Studio Code](https://code.visualstudio.com), por exemplo) 

## Clonar e instalar:
* git clone [Api-Feedback](https://github.com/davidebsen/api-feedback)
* cd api-feedback (Go into the repository)
* npm install (Install dependencies)

## Executar Api:
* npm run dev (server linux)
* RumApp.bat (Windows Local) arquivo dentro do repositorio alterar endereço onde repositorio esta salvo


## Colocando em produção:

* Este projeto pode ser colocado em produção É necessário criar as variáveis de ambiente para configurar o acesso as planilhas do Google dentro do .env


## Construído com:
* [NodeJS](https://www.nodejs.org)
* [NextJS](https://nextjs.org/)
* [TailwindCSS](https://tailwindcss.com/)
* [Google Sheets](https://drive.google.com)

## Author:

* **David** - [LinkedIn](https://www.linkedin.com/in/david-ebsen/)


## Licença

Este projeto é licenciado sobre a licença MIT - veja [LICENSE](LICENSE.md) para mais informações.

## Preview.

<img width="1297" alt="Amostra 01" src="https://github.com/davidebsen/api-feedback/blob/main/Apresenta%C3%A7%C3%A3o/Amostra%2001.gif">
<img width="1297" alt="Amostra 02" src="https://github.com/davidebsen/api-feedback/blob/main/Apresenta%C3%A7%C3%A3o/amostra%2002.gif">
<img width="1297" alt="Amostra 03" src="https://github.com/davidebsen/api-feedback/blob/main/Apresenta%C3%A7%C3%A3o/amostra%2003.gif">
<img width="1297" alt="Amostra 04" src="https://github.com/davidebsen/api-feedback/blob/main/Apresenta%C3%A7%C3%A3o/amostra%2004.gif">
<img width="1297" alt="Amostra 05" src="https://github.com/davidebsen/api-feedback/blob/main/Apresenta%C3%A7%C3%A3o/amostra%2005.gif">
