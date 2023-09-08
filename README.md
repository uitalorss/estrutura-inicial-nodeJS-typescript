# estrutura-inicial-nodeJS-typescript

- Configuração inicial do projeto
	* ```npm init -y```

- Instalação das dependências de desenvolvimento.
	* ```npm install -D typescript nodemon ts-node @types/express @types/node```
		* typescript: superset que incorpora tipos ao javascript
		* nodemon: ferramenta que auxilia o desenvolvimento em nodeJS ao restartar a aplicação automáticamente ao detectar mudanças nos arquivos do diretório passado.
		* ts-node: ferramenta para executar códigos typescript com node, através do comando npx ts-node caminhoDoArquivo.
		* @types: Instala definições de tipo para as extensões passadas.
		
- Instalação das dependências de produção
	* ```npm install express pg dotenv```
		* express: Framework node para definição de configurações, gerenciamento de requisições http da sua aplicação
		* pg: Cliente node para postgreSQL
		* dotenv: Ferramenta para documentar variáveis de ambiente do projeto.