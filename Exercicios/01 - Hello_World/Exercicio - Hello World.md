# Exercicio - Hello World

Replica a seguinte estrutura utilizando os metodos de React & ReactDOM (`createElement`, `createRoot`) em javascript para que seja representada na página:

```HTML
<div class="main-container">
    <h2 class="titulo">Hello Edit!</h2>
    <div class="cubo"></div>
    <div class="cubo"></div>
    <div class="cubo"></div>
    <div class="cubo"></div>
    <div class="cubo"></div>
    <div class="cubo"></div>
</div>
```

```js
const elemento = React.createElement(
	"h1",
	{
		id: "cenas",
		title: "Cenas maaradas",
	},
	"Conteudo do H1",
	React.createElement("button", {}, "Btn")
);

```
