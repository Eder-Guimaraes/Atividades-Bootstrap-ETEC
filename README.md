# Exercícios com Bootstrap

Projeto de prática com **Bootstrap 4**, desenvolvido para o curso técnico de Desenvolvimento de Sistemas (Etec). Reúne páginas independentes que exploram diferentes componentes do framework: cards colapsáveis, carrossel e grids de cards.

## 📁 Estrutura do projeto

```
projeto/
├── css/
│   └── bootstrap.min.css
├── js/
│   └── bootstrap.min.js
├── Images/          # imagens usadas pelos cards e pelo carrossel
├── imagem/          # imagens usadas pela agência de viagens
├── estados-brasileiros.html
├── herois-marvel.html
├── CarroselHerois.html
└── agencia-viagens.html
```

## 📄 Páginas

### `estados-brasileiros.html`
Atlas dos estados brasileiros organizado pelas 5 regiões do país (Sudeste, Sul, Centro-Oeste, Nordeste, Norte). Um botão por estado abre (`collapse`) um card com capital, PIB, área, comida típica e link para o site oficial do governo.

### `herois-marvel.html`
Mesma lógica de botão + card colapsável, aplicada a 5 heróis da Marvel (Homem de Ferro, Capitão América, Homem-Aranha, Thor e Pantera Negra), com identidade civil, primeira aparição nos quadrinhos, poderes e ator do MCU.

### `CarroselHerois.html`
Carrossel (`carousel`) com os mesmos 5 heróis, uma imagem por slide, indicadores, setas de navegação e troca automática a cada 2 segundos.

### `agencia-viagens.html`
Grade de cards de uma agência de viagens fictícia, com 10 pacotes para destinos europeus (Veneza, Roma, Paris, Berlim, Madrid, Barcelona, Londres, Lisboa, Amsterdã e Praga), cada um com preço e descrição curta.

## 🛠️ Tecnologias

- HTML5
- Bootstrap 4 (grid, cards, collapse, carousel)
- jQuery + Popper.js (dependências do Bootstrap 4 para os componentes interativos)

## ▶️ Como rodar

1. Baixe ou clone a pasta do projeto mantendo a estrutura de pastas acima.
2. Coloque o Bootstrap em `css/bootstrap.min.css` e `js/bootstrap.min.js`.
3. Adicione as imagens correspondentes em `Images/` (estados e heróis) e `imagem/` (agência de viagens), com os nomes de arquivo já referenciados em cada HTML.
4. Abra qualquer um dos arquivos `.html` diretamente no navegador — não é necessário servidor.

## ✍️ Autor

Eder — Etec Fernando Prestes, curso técnico de Desenvolvimento de Sistemas.
