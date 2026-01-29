<h1 align="center">Portfólio Lobo 🐺</h1>

<p align="center">
  <a href="#projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#diferenciais-técnicos">Diferenciais</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#estrutura-de-pastas">Arquitetura</a>
</p>

---

<h2 id="projeto">PROJETO</h2>

[![Status](https://img.shields.io/badge/Status-Finalizado-blue)]()

Este projeto é uma **releitura técnica** do site "Portfólio Lobo", desenvolvido originalmente no curso de HTML e CSS para Iniciantes da **Origamid**.

Embora o curso ensine a construção utilizando CSS nativo, o objetivo deste repositório foi **evoluir minhas habilidades técnicas**, codando o projeto do zero utilizando **SASS/SCSS**. Durante a codificação, simulei um ambiente de desenvolvimento real, aplicando conceitos de **Design Systems**, **arquitetura de pastas** organizada e **manutenibilidade** de código.

🌐 **[Acesse o projeto online aqui](https://lucas16716.github.io/portfolio-lobo/)**

<h2 id="diferenciais-técnicos">DIFERENCIAIS IMPLEMENTADOS</h2>

Além de replicar o layout fielmente, foram aplicadas técnicas modernas de CSS e SASS:

- 🏗️ **Arquitetura SASS Modular:** O código não está em um único arquivo gigante. Foi utilizada a metodologia de **Partials** (`_header.scss`, `_footer.scss`, etc.) importados via `@use`, garantindo encapsulamento e organização.
- 🎨 **Variáveis & Design System:** Uso de mapas de cores, escalas de espaçamento (base 8px) e diversas variáveis organizadas em um arquivo de configuração (`_variables.scss`).
- 📐 **Tipografia Fluida:** Implementação da função `clamp()` para fontes que se adaptam suavemente entre mobile e desktop, sem a necessidade excessiva de breakpoints, facilitando a responsividade.
- 🧹 **Reset CSS Customizado:** Limpeza de estilos nativos para garantir consistência entre navegadores.
- 🏠 **Botão de Voltar ao Topo:** Implementação do botão de voltar ao topo para melhor navegabilidade entre seções do site.

<h2 id="tecnologias">TECNOLOGIAS E FERRAMENTAS</h2>

- **HTML5 Semântico →** estrutura semântica e acessível.
- **SASS (SCSS) →** Pré-processador utilizado para Aninhamentos, Variáveis, Mixins e outros fundamentos.
- **CSS Grid & Flexbox →** Para estruturação de layouts e alinhamentos em grade.
- **Live Sass Compiler →** Extensão do VS Code utilizada para compilação em tempo real.
- **Git/GitHub →** Versionamento e hospedagem.

---

<h2 id="estrutura-de-pastas">ESTRUTURAÇÃO DO PROJETO</h2>

A organização das pastas segue uma adaptação da **Arquitetura 7-1 do SASS**, separando configurações, base e layouts:

```bash
📁 portfolio-lobo
├── index.html                       # Estrutura principal
├── src/
│   ├── assets/                      # Imagens e ícones: ico, img e svg
│   ├── css/                         # CSS Compilado
│   │   └── style.css
│   └── sass/
│       ├── abstracts/               # Arquivos de configuração: variáveis e mixins
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base/                    # Arquivos de Reset / Estilos Fundamentais
│       │   └── _global.scss
│       ├── layout/                  # Arquivos de estilização da estrutura organizado em Partials
│       │   ├── _header.scss
│       │   ├── _hero.scss
│       │   ├── _experience.scss
│       │   ├── _education.scss
│       │   └── _footer.scss
│       └── style.scss               # Arquivo Principal (Gerenciador de imports)
├── README.md                        # Documentação do projeto
└── LICENSE                          # Licença MIT
```

---

<h2>📝 LICENÇA</h2>

<p>Este projeto está licenciado sob a licença MIT. Confira os detalhes na documentação oficial.</p>

<h2>🧑🏻‍💻 AUTOR </h2>

<p>Desenvolvido por <a href="https://bio.site/lucascode">Lucas Code</a>, com design original da Origamid, para fins de desenvolvimento técnico.</p>
