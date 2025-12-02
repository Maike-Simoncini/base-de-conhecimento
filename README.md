# 📚 Base de Conhecimento

Uma aplicação web simples e responsiva para explorar tecnologias essenciais no mundo do desenvolvimento de software — desde linguagens de programação e frameworks até bancos de dados, ferramentas de DevOps e muito mais.

## 🌟 Funcionalidades

- **Busca rápida** por nome da tecnologia ou descrição.
- **Cards dinâmicos** carregados a partir de um arquivo JSON (`data.json`).
- **Design responsivo** — funciona bem em desktops, tablets e celulares.
- **Links oficiais** para documentação e recursos externos.
- **Zero frameworks externos** — apenas HTML, CSS e JavaScript puro.

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3** (com Flexbox, variáveis e media queries)
- **JavaScript (ES6+)** com `fetch`, `async/await` e manipulação do DOM
- **Fonte externa**: [Quicksand](https://fonts.googleapis.com/css2?family=Quicksand) do Google Fonts

## 📁 Estrutura do Projeto

```
base-de-conhecimento/
├── index.html
├── style.css
├── script.js
└── data.json
```

## 🚀 Como Executar Localmente

1. Clone este repositório (ou baixe os arquivos manualmente):
   ```bash
   git clone https://github.com/Maike-Simoncini/base-de-conhecimento.git
   cd base-de-conhecimento
   ```

2. Abra o arquivo `index.html` em seu navegador:
   ```bash
   open index.html  # macOS
   start index.html # Windows
   xdg-open index.html # Linux
   ```

## 📦 Exemplo de Entrada no `data.json`

```json
[
  {
    "nome": "JavaScript",
    "descricao": "Linguagem de programação fundamental para a web...",
    "data_criacao": "1995",
    "link_oficial": "https://developer.mozilla.org/pt-BR/docs/Web/JavaScript",
    "tags": ["linguagem de programação", "frontend", "backend", "web"]
  }
]
```

## 📬 Contato

- [LinkedIn](https://www.linkedin.com/in/maike-simoncini-da-silva-9769b2287)
