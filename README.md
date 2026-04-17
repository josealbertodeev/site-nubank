# 💜 Site Nubank - Landing Page Responsiva

<div align="center">
  <img src="src/img/nulogo.png" alt="Nubank Logo" width="120">
  
  <p><em>Uma landing page moderna e responsiva inspirada no design do Nubank</em></p>

  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![Responsive](https://img.shields.io/badge/Design-Responsive-purple?style=for-the-badge)
</div>

## 📱 Sobre o Projeto

Este projeto é uma recriação da landing page do Nubank, desenvolvida com foco em **design responsivo** e **experiência do usuário**. A página apresenta todos os principais elementos visuais da marca, incluindo gradientes roxos, cartões interativos e uma interface moderna.

## ✨ Funcionalidades

- 🎨 **Design Moderno** - Interface clean inspirada no Nubank
- 📱 **100% Responsivo** - Otimizado para todos os dispositivos
- 🚀 **Performance** - Carregamento rápido e suave
- 💳 **Cartão Animado** - Simulação visual do cartão Nubank
- 🎯 **CTAs Estratégicos** - Botões de conversão bem posicionados
- 🔒 **Formulário de Cadastro** - Captura de CPF com validação visual

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização avançada com:
  - Flexbox e CSS Grid
  - Media Queries responsivas
  - Gradientes e animações
  - Variáveis CSS (Custom Properties)

## 📂 Estrutura do Projeto

```
site-nubank/
│
├── index.html              # Página principal
├── README.md              # Documentação
│
└── src/
    ├── css/
    │   ├── styles.css     # Estilos principais
    │   └── responsive.css # Regras de responsividade
    │
    └── img/               # Imagens e assets
        ├── nulogo.png
        ├── logo.png
        └── fundo.png
```

## 🎯 Breakpoints Responsivos

| Dispositivo | Largura | Características |
|-------------|---------|-----------------|
| **Desktop** | 1025px+ | Layout completo com sidebar |
| **Tablet** | 768px - 1024px | Ajustes de espaçamento |
| **Mobile** | 481px - 768px | Layout em coluna, nav oculta |
| **Mobile Pequeno** | ≤ 480px | Otimizações para telas pequenas |

## 🚀 Como Executar

1. **Clone o repositório:**
```bash
git clone https://github.com/seu-usuario/site-nubank.git
```

2. **Navegue até o diretório:**
```bash
cd site-nubank
```

3. **Abra o projeto:**
   - Abra o arquivo `index.html` no seu navegador, ou
   - Use um servidor local como Live Server (VS Code)

## 📱 Visualização Mobile

<div align="center">
  <p><em>Design totalmente adaptado para dispositivos móveis</em></p>
  
  **Principais adaptações:**
  - Header com navegação colapsada
  - Hero section em layout vertical
  - Cards empilhados responsivamente
  - Botões otimizados para toque
  - Formulários acessíveis
</div>

## 🎨 Paleta de Cores

```css
:root {
    --purple: #830AD1;        /* Roxo principal Nubank */
    --purple-dark: #6B0297;   /* Roxo escuro para hover */
    --white: #FFFFFF;         /* Branco */
    --dark: #000000;          /* Preto */
    --gray-text: #B0B0B0;     /* Cinza para textos */
}
```

## 🔥 Destaques Técnicos

- **CSS Grid & Flexbox** para layouts flexíveis
- **Media queries** mobile-first
- **Touch-friendly** botões (44px+ de altura)
- **iOS optimization** (font-size 16px nos inputs)
- **Smooth scrolling** habilitado
- **Overflow prevention** para scroll horizontal

## 📄 Seções da Página

1. **Header** - Logo, navegação e CTA principal
2. **Hero** - Título impactante + formulário de captura
3. **Services** - Grid de serviços do Nubank
4. **Card Section** - Apresentação do cartão de crédito
5. **CTA Final** - Última oportunidade de conversão
6. **Footer** - Links institucionais e informações

