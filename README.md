# 🧦 Syntaxwear - Ecommerce de Tênis e Sneakers

![Syntaxwear](./images/logo/logo.svg)

## 📋 Descrição

**Syntaxwear** é uma plataforma de ecommerce moderna e responsiva especializada em venda de tênis e sneakers online. O projeto foi desenvolvido utilizando **HTML5**, **CSS3** e segue as melhores práticas de web design, oferecendo uma experiência de compra intuitiva e visualmente atraente.

> "Transforme qualquer passo em presença." - Slogan da Syntaxwear

---

## ✨ Funcionalidades Principais

### 👕 Categorias de Produtos
- **Masculino** - Coleção de tênis para homens
- **Feminino** - Coleção de tênis para mulheres
- **Outlet** - Produtos com desconto

### 👟 Estilos de Sneakers
- **Casual** - Tênis para uso diário
- **Esporte** - Tênis para atividades físicas
- **Moderno** - Tênis com design contemporâneo
- **Futurista** - Tênis com estilo inovador e futurista

### 🛒 Seções da Loja
- **Header navegável** com menu responsivo
- **Hero section** destacando o produto principal (Krypton One)
- **Grid de categorias** com imagens e overlay
- **Grid de produtos em destaque** com diferentes variações de cores
- **Footer completo** com links, redes sociais e newsletter

### 📱 Recursos Adicionais
- Menu mobile hamburger responsivo
- Formulário de newsletter
- Links para redes sociais (Instagram, WhatsApp, TikTok, Facebook)
- Acesso rápido a conta, ajuda e carrinho
- Links para lojas físicas e informações sobre a empresa

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização moderna com variáveis CSS e media queries
- **Google Fonts** - Fontes Poppins, Roboto, Rubik Storm e Ubuntu
- **Design Responsivo** - Mobile-first e otimizado para todos os dispositivos

### Sistema de Design

#### Fontes
- **Principal**: Ubuntu
- **Alternativas**: Poppins, Roboto, Rubik Storm

#### Estrutura de Cores
Definidas em `css/variables.css` para consistência visual

#### Componentes Reutilizáveis
- Botões (outline e filled)
- Cards de produtos
- Categorias com overlay
- Componentes de navegação

---

## 📁 Estrutura do Projeto

```
ecommerce-syntaxwear/
├── index.html                 # Página principal
├── README.md                  # Este arquivo
├── css/
│   ├── reset.css             # Reset de estilos padrão
│   ├── variables.css         # Variáveis CSS (cores, fontes)
│   ├── base.css              # Estilos base e utilitários
│   └── components/           # Estilos de componentes
│       ├── header.css        # Estilos do cabeçalho
│       ├── hero.css          # Estilos da seção hero
│       ├── product-category.css # Estilos das categorias
│       ├── product-grid.css  # Estilos da grid de produtos
│       └── footer.css        # Estilos do rodapé
├── images/
│   ├── logo/                 # Logo da marca
│   ├── banners/              # Imagens de banners
│   ├── icons/                # Ícones SVG
│   ├── favicons/             # Favicons do site
│   └── products/             # Imagens dos produtos
└── .git/                      # Controle de versão Git
```

---

## 🚀 Como Usar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Nenhuma dependência externa necessária

### Instalação
1. Clone o repositório:
```bash
git clone https://github.com/Henrique970/ecommerce-syntaxwear.git
```

2. Navegue até a pasta do projeto:
```bash
cd ecommerce-syntaxwear
```

3. Abra o `index.html` no seu navegador:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Desenvolvimento Local
Para desenvolvimento local com live reload, você pode usar:
- **Live Server** (extensão do VS Code)
- **Python**: `python -m http.server 8000`
- **Node.js**: `npx http-server`

---

## 📄 Seções da Página Principal

### 1. Header
- Logo clicável que leva ao home
- Menu de navegação com categorias (Masculino, Feminino, Outlet)
- Submenu com links rápidos (Nossas Lojas, Sobre)
- Ícones de ação (Minha Conta, Ajuda, Carrinho)
- Menu responsivo com ícone hamburger para mobile

### 2. Hero Section
- Imagem de destaque com overlay
- Título principal: "Transforme qualquer passo em presença."
- Produto em destaque: Krypton One
- Chamadas para ação: "Ver modelos" e "Comprar"

### 3. Seção de Categorias
- 4 categorias principais com imagens
- Efeito hover com overlay
- Links para navegar por cada estilo

### 4. Grid de Produtos
- Card principal com informações do produto Krypton One
- 5 cards adicionais com diferentes variações:
  - Purple Sneaker
  - Model Showcase
  - Color Sneaker
  - White Sneaker
  - Silver Sneaker

### 5. Footer
- **Newsletter**: Formulário de inscrição para e-mail
- **Redes Sociais**: Links para Instagram, WhatsApp, TikTok, Facebook
- **Navegação por Categorias**:
  - Masculino (Casual, Esporte, Moderno, Futurista)
  - Feminino (Casual, Esporte, Moderno, Futurista)
  - Outlet (Masculino, Feminino)
  - Nossas Lojas (Física e Online)
  - Sobre (Quem somos, Missão)
- Copyright

---

## 🎨 Personalizações e Extensões

### Adicionar novos produtos
1. Coloque as imagens dos produtos em `images/products/`
2. Adicione novos cards na seção `grid-section` do HTML

### Modificar cores e temas
1. Edite `css/variables.css` para alterar as variáveis CSS
2. Todos os estilos utilizarão as novas cores automaticamente

### Adicionar novas categorias
1. Adicione um novo `category-card` na seção `categories-section`
2. Crie ou importe a classe CSS correspondente

### Melhorar responsividade
1. Edite os media queries em `css/base.css` e componentes
2. Teste em diferentes tamanhos de tela

---

## 📱 Responsividade

O projeto é totalmente responsivo com breakpoints em:
- **Desktop**: 1360px (máx. width)
- **Tablet**: até 1110px
- **Mobile**: ajustes adicionais conforme necessário

---

## ♿ Acessibilidade

O projeto segue boas práticas de acessibilidade:
- ✅ Semântica HTML apropriada
- ✅ Atributos `alt` em todas as imagens
- ✅ Labels em formulários
- ✅ Navegação por teclado
- ✅ Rótulos ARIA onde necessário
- ✅ Cores com contraste adequado

---

## 🐛 Problemas Conhecidos

- Links ainda não estão totalmente funcionais (em desenvolvimento)
- Funcionalidades de carrinho pendentes
- Integração com backend necessária

---

## 🔄 Próximas Melhorias

- [ ] Integrar backend para gerenciamento de produtos
- [ ] Adicionar carrinho de compras funcional
- [ ] Sistema de filtros de produtos
- [ ] Página de detalhes do produto
- [ ] Sistema de avaliações e comentários
- [ ] Integração com pagamento
- [ ] Sistema de endereço de entrega
- [ ] Histórico de pedidos para usuários
- [ ] Dark mode
- [ ] Otimização para performance (lazy loading, minificação)

---

## 📄 Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.

---

## 👤 Autor

Desenvolvido com ❤️ por **Henrique dos Santos**

---

## 📞 Contato e Redes Sociais

- 📧 Email: [santosdoshenrique1560@gmail.com]
- 📸 Instagram: [@henrique.dos.santos]

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

---

## 📖 Recursos Adicionais

- [MDN Web Docs - HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [Web.dev - Responsive Design](https://web.dev/responsive-web-design-basics/)
- [Google Fonts](https://fonts.google.com/)

---

**Última atualização**: 12 de março de 2026

*Syntaxwear - Transforme qualquer passo em presença.* 🧦✨
