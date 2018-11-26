# Loja Fone

## HTML5

É uma linguagem de marcação que tem algumas responsabilidades:

- Conteúdo
- Semântico (tags)

- `<h1>` - (heading) - Usamos ele quando queremos definir titulos
> Exite `<h1>``<h2>``<h3>``<h4>``<h5>``<h6>`

- `<a>` - Link (a - anchor) Usamos ela para definir a navegação do usuário. Se você tem um texto que você quer que o usuário clique e ele vá para outro lugar, você pode usar essa tag junto com o atributo `href`. Exemplo de um  `a` que o usuário é direcionando para o site do git no meu repositório atual.

```html
<a href="https://github.com/AdalbertoGarc/Loja-fone">Repo Loja Fone</a>
```

- `<h1>` - heading 1 ao 6

---

## CSS

- O Cascading Style Sheets (CSS) é uma "folha de estilo" composta por “camadas” e utilizada para definir a apresentação (aparência) em páginas da internet que adotam para o seu desenvolvimento linguagens de marcação (como XML, HTML e XHTML).
Exemplo de uma aplicação de estilo:

```css
header {
    background-color: #e24647;
    position: absolute;
    width: 100%;
    height: 100px;
    text-align: right;
}

h1, a {
    color: #fff;
}

a {
    text-decoration: none;
    font-size: 21px;
    font-family: "Segoe UI", Verdana, sans-serif;;
    margin-right: 60px;
}

.logo-header{
    float: left;
    margin-left: 65px;
    height: 100px;
    line-height: 100px;
}

#logo-logo {

}

```