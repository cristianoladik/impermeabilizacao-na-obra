# Impermeabilização na Obra

Apresentação online da aula de impermeabilização da Mentoria **Viver de Construção**
(@cristianoladik). Os slides passam para o lado (setas, clique ou arrastar no celular) e o
site é responsivo, funcionando em computador e celular.

## Como abrir
- Online: GitHub Pages (link na descrição do repositório).
- Local: abrir uma vez via servidor, por exemplo `python -m http.server` na pasta e acessar
  `http://127.0.0.1:8000`.

## Como imprimir em PDF
Abrir o site com `?print-pdf` no final da URL e usar Imprimir do navegador (Chrome), salvando
como PDF em paisagem. Cada slide vira uma página.

## Estrutura
- `index.html` : os slides (reveal.js via CDN).
- `assets/css/theme.css` : identidade visual preto + dourado.
- `assets/img/` : logo e fotos dos produtos/etapas.

## Tecnologia
reveal.js 5.x carregado por CDN. Não precisa instalar nada para editar: basta mexer no
`index.html` e no `theme.css`.
