# Experimento com a disposição de grade via CSS

[![licence mit](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](http://hemersonvianna.mit-license.org/)
[![issues](https://img.shields.io/github/issues/experiment-solutions/experiment-css-grid-layout.svg?style=flat-square)](https://github.com/experiment-solutions/experiment-css-grid-layout/issues)

## Traduções

* [ORIGINAL](https://github.com/experiment-solutions/experiment-css-grid-layout/)

## Suporte 

- Chrome 29+(Ativando a Bandeira)
- Firefox 40+(Ativando a Bandeira)
- Opera 28+(Ativando a Bandeira)
- IE 10+

Apenas IE 10+ e Edge dão suporte a `CSS grid`. Ele pode ser habilitado no Chrome através da bandeira `Recursos experimentais da Plataforma Web` em `chrome://flags`, na barra de endereço do navegador. Você pode habilitá-lo no Firefox usando o sinalizador `layout.css.grid.enabled`.

## Terminologia

### Grid Container

O elemento no qual `display: grid` é aplicada. É o pai direto de todos os itens da grade.

```html
<div class="grid-container">
  <div class="grid-item item-1"></div>
  <div class="grid-item item-2"></div>
</div>
```

```css
.grid-container { display: grid; }
```

### Grid Item

### Grid Line

### Grid Track

### Grid Cell

### Grid Area

## Propriedades

### Propriedades para o Grid Container

- display
- grid-template-columns
- grid-template-rows
- grid-template-areas
- grid-column-gap
- grid-row-gap
- grid-gap
- justify-items
- align-items
- justify-content
- align-content
- grid-auto-columns
- grid-auto-rows
- grid-auto-flow
- grid

### Propriedades para os Grid Items

- grid-column-start
- grid-column-end
- grid-row-start
- grid-row-end
- grid-column
- grid-row
- grid-area
- justify-self
- align-self

## Contribuindo

- Faça o fork!
- Crie a sua branch feature: `git checkout -b my-new-feature`
- Faça o commit das suas alterações: `git commit -m 'Add some feature'`
- Faça o push para o servidor: `git push origin my-new-feature`
- E realize o pull request

## Log

Verifique os [Releases](https://github.com/experiment-solutions/experiment-css-grid-layout/releases) ver detalhado o log de alterações.

## Licença

[MIT license](http://hemersonvianna.mit-license.org/) © Hemerson Vianna
