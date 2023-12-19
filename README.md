## Setup

`npm create vite@latest` seguindo os restantes passos recomendados

### criar ficheiro `vite.config.js`

```
export default {
	root: 'src',
	build: {
		target: 'es2015',
		outDir: '../build',
	},
};
```

Organizar a estrutura dos nossos folders, sendo importante no ficheiro `index.html` e `main.js` alterar os links em conformidade.

Caso queiramos utilizar sass já não estamos dependentes de extensões do visual studio code como o live watch sass. No caso do Vite como ferramenta de suporte à criação de aplicações em Javascript já vamos utilizar o sass através de instalação de dependência `npm install sass`. (importante colocar o import no main.js)

Outras dependências vão ser instaladas de forma similar através do node package module.

### Build do projeto

Após conclusão do projeto podemos no terminal usar o comando `npm run build` sendo que podemos verificar o cross browser da nossa aplicação usando o comando `npm run preview`

![file structure.](https://res.cloudinary.com/db1ckkq9c/image/upload/v1702980864/Miscs/folders_xpajgt.png)

