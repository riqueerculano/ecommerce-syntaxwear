<div align="center">
  <img src="./assets/images/logo/Logo.svg" alt="SyntaxWear Logo" width="220" />

  <p>Um e-commerce de calçados e sneakers com foco no público tech e urbano.</p>

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/Status-Em%20Constru%C3%A7%C3%A3o-orange?style=for-the-badge" alt="Status" />
  </p>
</div>

<hr />

## 📌 Sobre o Projeto

O **SyntaxWear** é uma interface de e-commerce de tênis e sneakers desenvolvida como projeto prático durante o curso **Dev Quest**. 

O objetivo principal deste projeto é consolidar conceitos fundamentais do desenvolvimento front-end web, aplicando boas práticas de estruturação semântica, organização modular de estilos e técnicas modernas de estilização responsiva.

---

## ✨ Funcionalidades

- **Design Responsivo:** Adaptado para diferentes resoluções, desde telas menores de smartphones até telas amplas de desktop.
- **Menu Hamburguer Mobile:** Navegação adaptável para celulares construída com CSS puro (técnica de *checkbox hack*).
- **Seção Hero de Destaque:** Banner principal com chamada para ação (*Call to Action - CTA*) e visual atrativo.
- **Categorias de Produtos:** Cards dinâmicos para filtragem visual de estilos de calçados (*Casual, Esporte, Moderno e Futurista*) com efeitos de transição no cursor (*hover*).
- **Vitrine em Grade (Grid):** Composição visual em mosaico utilizando **CSS Grid** para exibição de calçados e modelos.
- **Rodapé Completo:** Seção com formulário para cadastro em newsletter, links rápidos para as categorias e ícones das principais redes sociais.

---

## 🛠️ Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Marcação semântica com tags como `<header>`, `<nav>`, `<main>`, `<section>` e `<footer>`, facilitando acessibilidade e SEO.
- **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):**
  - **Flexbox & CSS Grid:** Para estruturação de layouts flexíveis, alinhamento de itens e montagem da vitrine de produtos.
  - **Variáveis CSS (`Custom Properties`):** Centralização de fontes e configurações globais.
  - **Media Queries:** Para pontos de interrupção (*breakpoints*) responsivos.
  - **Arquitetura Modular:** Separação do CSS em componentes (`header.css`, `hero.css`, `footer.css`, etc.) para manter o código limpo e de fácil manutenção.
- **[Google Fonts](https://fonts.google.com/):** Tipografia utilizando a família de fontes *Ubuntu*.

---

## 📁 Estrutura de Arquivos

```text
ecommerce-syntaxwear/
├── assets/
│   └── images/              # Imagens dos tênis, banners, ícones SVG e logotipo
├── css/
│   ├── components/          # Estilos divididos por componente da página
│   │   ├── footer.css
│   │   ├── header.css
│   │   ├── hero.css
│   │   ├── product-category.css
│   │   └── product-grid.css
│   ├── base.css             # Estilos compartilhados e botões globais
│   ├── reset.css            # Normalização de estilos padrão do navegador
│   └── variables.css        # Declaração de fontes e variáveis globais
├── index.html               # Estrutura principal da página
└── README.md                # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto

Como este projeto foi construído utilizando apenas **HTML e CSS puros**, não é necessário instalar dependências complexas (como Node.js ou pacotes externos).

### Pré-requisitos
- Um navegador web atualizado (ex: Google Chrome, Mozilla Firefox, Microsoft Edge, Opera).
- (Opcional) Editor de código como o **[VS Code](https://code.visualstudio.com/)**.

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone git@github.com:riqueerculano/ecommerce-syntaxwear.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd ecommerce-syntaxwear
   ```

3. **Abra a aplicação:**
   - **Opção 1 (Direto pelo navegador):** Dê um duplo clique no arquivo `index.html` ou clique com o botão direito e selecione *Abrir com...* seguido do seu navegador preferido.
   - **Opção 2 (Recomendada via VS Code):** Abra a pasta no VS Code, instale a extensão **Live Server**, clique com o botão direito no arquivo `index.html` e selecione **"Open with Live Server"**. O projeto abrirá automaticamente com recarregamento em tempo real.

---

## 🔮 Próximos Passos (Melhorias Futuras)

- [ ] Implementar interatividade com JavaScript (abertura de menu, modal de visualização rápida de produto).
- [ ] Adicionar funcionalidade de carrinho de compras (armazenamento local via `localStorage`).
- [ ] Criar páginas secundárias (catálogo completo de produtos, página de produto individual).
- [ ] Realizar deploy online via **GitHub Pages** ou **Vercel** para disponibilizar o link de visualização pública.

---

## 👤 Autor

Desenvolvido por **Henrique Erculano**.

- GitHub: [@riqueerculano](https://github.com/riqueerculano)
- Repositório: [ecommerce-syntaxwear](https://github.com/riqueerculano/ecommerce-syntaxwear)

---

Feito para aprendizado e prática no curso Dev Quest.
