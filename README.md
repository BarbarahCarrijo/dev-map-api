# dev-map-api
#### API de cadastro e mapeamento de desenvolvedores
Este projeto foi iniciado com o Node.js, tem como finalidade fixação do conteúdo aprendido durante a semana Omini Stack, onde foi realizado o desenvolvimento de uma aplicação que mantem cadastros de devs.
Esta API consome dados providos da API do [GitHub](https://github.com) 

## Tecnologias 

Aqui estão as tecnologias usadas neste projeto:

* NodeJS v12.14.1
* Express v4.17.1
* Yarn v1.19.1
* Mongoose v5.8.10

## Scripts disponíveis

No diretório do projeto, você pode executar:

### `yarn install`

Executa a instalação das dependências do projeto.

### `yarn dev`

Executa o aplicativo no modo de desenvolvimento.<br />
Abra [http://localhost:3030](http://localhost:3030) para visualizá-lo no navegador.

A página será recarregada, caso sejam realizadas edições.<br />
Também será possível monitorar os erros no console.


###### *Obs¹.: Para persistência, é necessário configurar um cluster no [Mongo Atlas](https://www.mongodb.com/cloud/atlas) e realizar a alteração das strings de conexão*
###### *Obs².: Para realizar os testes dos métodos, foi utilizada a ferramenta [Insomnia](https://insomnia.rest/)*