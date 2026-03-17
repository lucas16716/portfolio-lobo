<div align="center">

# Portfólio Lobo

**Releitura técnica do projeto do curso de HTML e CSS da Origamid**

*Recodificado do zero com SASS/SCSS, arquitetura modular e tipografia fluida*

[![Status](https://img.shields.io/badge/status-concluído-e8e4de?style=flat-square&labelColor=3437e6&color=1c1b2e)]()&nbsp;
[![Finalidade](https://img.shields.io/badge/finalidade-estudo-e8e4de?style=flat-square&labelColor=orange&color=1c1b2e)]()&nbsp;
[![Licença](https://img.shields.io/badge/licença-MIT-e8e4de?style=flat-square&labelColor=ef4444&color=1c1b2e)](./LICENSE)

</div>

<p align="center">
  <a href="#projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#diferenciais">Diferenciais</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#estrutura">Estrutura</a>
</p>

<h2 id="projeto">PROJETO</h2>

Releitura técnica do site "Portfólio Lobo", desenvolvido originalmente no curso de HTML e CSS para Iniciantes da Origamid. Embora o curso ensine a construção com CSS nativo, o objetivo foi evoluir as habilidades técnicas recodificando o projeto do zero com SASS/SCSS — simulando um ambiente de desenvolvimento real com arquitetura modular e conceitos de design system.

🌐 [Acesse o projeto](https://lucas16716.github.io/portfolio-lobo/)

<h2 id="diferenciais">DIFERENCIAIS IMPLEMENTADOS</h2>

- **Arquitetura SASS modular** — partials organizados por responsabilidade e importados via `@use`
- **Design system** — mapas de cores, escala de espaçamento base 8px e variáveis centralizadas em `_variables.scss`
- **Tipografia fluida** — função `clamp()` para escala tipográfica responsiva sem media queries excessivas
- **Reset CSS customizado** — limpeza de estilos nativos para consistência entre navegadores
- **Botão de Voltar ao Topo** — implementação do botão de voltar ao topo para melhor navegabilidade entre seções do site.

<h2 id="tecnologias">TECNOLOGIAS</h2>

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura semântica e acessível |
| Sass (SCSS) | Arquitetura modular com partials, variáveis e mixins |
| CSS Grid & Flexbox | Estruturação de layouts e alinhamentos |
| Live Sass Compiler | Compilação em tempo real no VS Code |
| Git/Github | Versionamento e hospedagem |

<h2 id="estrutura">ESTRUTURA</h2>

```
📁 portfolio-lobo
├── index.html                       → Estrutura principal
├── src/
│   ├── assets/                      → Imagens, ícones e SVGs
│   ├── css/                         → CSS compilado
│   │   └── style.css
│   └── sass/
│       ├── abstracts/               → Arquivos de configuração: variáveis e mixins
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base/                    → Arquivos de Reset / Estilos Fundamentais
│       │   └── _global.scss
│       ├── layout/                  → Arquivos de estilização da estrutura organizado em Partials
│       │   ├── _header.scss
│       │   ├── _hero.scss
│       │   ├── _experience.scss
│       │   ├── _education.scss
│       │   └── _footer.scss
│       └── style.scss               → Entry Point
├── README.md                        
└── LICENSE 
```

---

<h2>LICENÇA</h2>

Este projeto está licenciado sob a licença MIT, confira os detalhes na documentação oficial.

O design original pertence à [Origamid](https://www.origamid.com) e foi utilizado para fins de estudo.

<h2>AUTOR</h2>

Desenvolvido por [Lucas Couto](https://linkedin.com/in/lucas-coutoti).  
Conheça meu trabalho em [Lucas Code](https://bio.site/lucascode).
