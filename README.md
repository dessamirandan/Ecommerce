# 🛒 My Shop – Mini E-commerce com HTML5 e CSS3

Projeto criado com foco no desenvolvimento de um e-commerce estático e responsivo utilizando **HTML5** e **CSS3 puro**, como parte de estudos e prática pessoal em desenvolvimento front-end.

---

## 📸 Visão Geral

O site simula uma loja virtual com layout simples e responsivo, destacando a listagem de produtos com imagem, nome, preço e botão de compra. Apesar de estático, o projeto aplica conceitos importantes de **semântica**, **estilização moderna** e **responsividade**.

---

## 🧑‍💻 Tecnologias utilizadas

- **HTML5**: estrutura da página e marcação semântica  
- **CSS3**: estilização, responsividade e efeitos visuais  

---

## 📁 Estrutura do Projeto

```plaintext
📦 Ecommerce/
├── index.html          → Página principal da loja
└── estilo/
    └── style.css       → Arquivo com os estilos aplicados
 ```
---

## 💡 Destaques do projeto

| Elemento                  | Implementação                                                                 |
|--------------------------|-------------------------------------------------------------------------------|
| ✅ Layout responsivo     | Flexbox aplicado na seção de produtos com `flex-wrap`                         |
| 🎨 Estilo consistente    | Cores suaves, botões estilizados e hover com transição e escala              |
| 🧾 Semântica HTML        | Uso adequado de `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`       |
| 🖼️ Cards de produto      | Imagem, nome, preço e botão "Comprar" encapsulados no componente `.card`     |
| 👀 Interação visual      | `:hover` com `transform: scale(1.1)` nos cards e botões                       |

---

## 📱 Responsividade

A seção `.itens` usa **Flexbox** com quebra de linha (`flex-wrap: wrap`) e espaçamento proporcional. Isso permite que os cards se reorganizem automaticamente em telas menores, sem necessidade de media queries.

---

## 🎯 Funcionalidades

- Navegação com botões para seções "Sobre", "Contato" e "Início"
- Catálogo com 4 produtos exibidos em cards individuais
- Estilização interativa com hover e botões responsivos
- Rodapé simples e semântico com direitos autorais

---

## 🛠️ Como visualizar

Você pode visualizar o projeto localmente assim:

```bash
git clone https://github.com/dessamirandan/Ecommerce.git
cd Ecommerce
````

## 📌 Melhorias Futuras

- 🔧 Adicionar funcionalidades com **JavaScript**, como carrinho de compras e interação com os botões.
- 🧩 Integrar media queries para **melhorar a responsividade** em dispositivos móveis pequenos.
- 🗂️ Organizar melhor o CSS com uso de **variáveis, classes reutilizáveis** e possivelmente pré-processadores como SASS.
- 🛍️ Inserir mais produtos dinamicamente ou por meio de integração com API fake.
- 🌐 Implementar páginas adicionais: "Sobre", "Contato", "Login", entre outras.

---

## 📄 Licença

Este projeto está disponível sob a **Licença MIT**.  
Você pode usá-lo, modificá-lo e distribuí-lo livremente, desde que mantenha os créditos ao autor.

Para mais informações, leia o arquivo [`LICENSE`](LICENSE) (se aplicável).

