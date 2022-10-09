<h1>
	API-Restful 
	<img 
		align="right"
		width="150"
src="https://raw.githubusercontent.com/maiconDeSouza/assets/master/API-Restful/api-restful.png" 
	/>
</h1>

<h2>Sobre o projeto</h2>

<p>
O core do projeto foi criar uma <strong>Api Restful</strong>.</p>
<p>
Um Crud salvando as informações no MongoDB o Front é básico feito em HTML apenas para testar a API.
</p>
<img 
src="https://raw.githubusercontent.com/maiconDeSouza/assets/master/API-Restful/crud.gif"
/>
<p>
 O Interessante em desenvolver uma API é que você consegue que seu backend converse com vários dispositivos diferentes (por exemplo, Website e Apps de celular), porque você retorna como resposta da requisições um único formato de arquivos para ambos os dispositivos (por exemplo, JSON).
</p>
<p>
 Neste projeto eu segui eu os padrões Rest (Representational State Transfer) e é um tipo de arquitetura de software. Uma REST indica então um conjunto de restrições que devem ser seguidas no desenvolvimento de uma aplicação na internet.
</p>
<p>
Estas regras permitem o desenvolvimento de uma aplicação com interface bem definida, com rotinas padronizadas e facilmente representadas, que facilitam a comunicação entre máquinas e usuários.
</p> 
<p>
	Um artigo bem completo sobre este assunto pode ser encontrado no site da <a href="https://aws.amazon.com/pt/what-is/restful-api/">AWS</a>.
</p>



<h3>Tecnologias utilizadas</h3>
<h4>Back end</h4>
<ul>
	<li>NodeJS</li>
	<li>ExpressJS - Framework backend para NodeJS</li>
	<li>Cors - biblioteca NodeJS para segurança da dua API, pois você informa quais endereços terão acesso a sua API</li>
	<li>MongoDB - com Banco de Dados</li>
	<li>Mongoose - uma biblioteca JS para usar com o MongoDB</li>
	<li>Nodemon - pacote NodeJS para desenvolvimento</li>
</ul>
<h4>Front end</h4>
<ul>
	<li>HTML</li>
	<li>CSS</li>
	<li>Axios - Biblioteca JS para fazer requisições HTTP</li>

</ul>
<hr>
<h2>Como executar o projeto</h2>

## Back end
Pré-requisitos: NodeJS e MongoDB

```bash
# clonar repositório
git clone git@github.com:maiconDeSouza/api-restful.git

# Abra no terminal a pasta /api-restful
# rode o comando
npm i

# executar o projeto
npm start
# Para executar com desenvolvimento 
npm run dev
```
<img 
src="https://raw.githubusercontent.com/maiconDeSouza/assets/master/API-Restful/rodando%20app.gif"
/>
## Front end web
Pré-requisitos: Um Navegador e VSCode com a extenção Live Server.
<img 
src="https://raw.githubusercontent.com/maiconDeSouza/assets/master/API-Restful/liveServer.gif"
/>


<h2>Autor</h2>
<strong>Maicon Souza</strong>