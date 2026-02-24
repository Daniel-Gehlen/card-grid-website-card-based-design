# DESIGN CARD-BASED / GRID

# 🃏 CardGrid - Design Card-Based / Grid

![Versão](https://img.shields.io/badge/versão-1.0.0-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![CSS Grid](https://img.shields.io/badge/CSS_Grid-advanced-6DB33F)
![Responsivo](https://img.shields.io/badge/responsivo-sim-success)

## 📋 Sobre o Projeto

Este é um protótipo funcional de um site com **Design Card-Based / Grid**, desenvolvido a partir de um diagrama ASCII art. O projeto demonstra a organização em cards com grid responsivo, típica de e-commerces, portfólios modernos, sites de conteúdo e dashboards.

### 🎯 Características do Design

- Organização em cards com grid responsivo
- Cabeçalho com logo, busca e menu
- Filtros interativos por categoria
- Cards com imagem, título, descrição, preço e avaliação
- Sistema de paginação completo
- Interface limpa e moderna

## 🏗️ Estrutura do Site
```

+--------------------------------------------------------------------+
| LOGO BUSCA MENU |
+--------------------------------------------------------------------+
| FILTROS: [Categoria1] [Categoria2] [Categoria3] |
+--------------------------------------------------------------------+
| +----------------+ +----------------+ +----------------+ |
| | [IMAGEM] | | [IMAGEM] | | [IMAGEM] | |
| | Título | | Título | | Título | |
| | Descrição | | Descrição | | Descrição | |
| | Preço | | Preço | | Preço | |
| +----------------+ +----------------+ +----------------+ |
| |
| +----------------+ +----------------+ +----------------+ |
| | [IMAGEM] | | [IMAGEM] | | [IMAGEM] | |
| | Título | | Título | | Título | |
| | Descrição | | Descrição | | Descrição | |
| | Preço | | Preço | | Preço | |
| +----------------+ +----------------+ +----------------+ |
+--------------------------------------------------------------------+
| PAGINAÇÃO: < 1 2 3 4 5 > |
+--------------------------------------------------------------------+

```

## ✨ Funcionalidades Implementadas

### Cabeçalho (Header)
- ✅ Logo "CardGrid" com gradiente azul
- ✅ Campo de busca funcional com botão
- ✅ Menu de navegação com 3 links
- ✅ Design limpo e moderno

### Filtros
- ✅ 5 botões de filtro (Todos, Eletrônicos, Moda, Casa, Esportes)
- ✅ Estado ativo visual (fundo azul)
- ✅ Efeitos hover suaves
- ✅ Feedback com alerta ao selecionar

### Grid de Cards
- ✅ 6 cards de produtos
- ✅ Grid responsivo com CSS Grid (`repeat(auto-fill, minmax(300px, 1fr))`)
- ✅ Cards com elevação ao hover
- ✅ Imagens representativas com emojis/ícones
- ✅ Título, descrição e preço
- ✅ Avaliação com estrelas (★★★★☆)
- ✅ Botão "Comprar" em cada card

### Cards - Detalhamento
| Produto | Imagem | Preço | Avaliação |
|---------|--------|-------|-----------|
| Smartphone Pro | 📱 | R$ 2.499 | ★★★★☆ |
| Camisa Social | 👕 | R$ 189 | ★★★★★ |
| Notebook Ultra | 💻 | R$ 4.299 | ★★★★☆ |
| Kit Cozinha | 🏠 | R$ 299 | ★★★☆☆ |
| Bola Oficial | ⚽ | R$ 189 | ★★★★★ |
| Fone Bluetooth | 🎧 | R$ 349 | ★★★★☆ |

### Paginação
- ✅ Botões: < 1 2 3 4 ... 10 >
- ✅ Estado ativo na página 1
- ✅ Botões clicáveis com feedback
- ✅ Design consistente com o tema

### Rodapé
- ✅ Informações de contato (e-mail, telefone)
- ✅ Endereço
- ✅ Links institucionais (Termos, Privacidade, Trocas)
- ✅ Copyright

### Interatividade JavaScript
- ✅ Filtros alteram estado ativo
- ✅ Paginação com highlight da página atual
- ✅ Alertas de feedback para ações
- ✅ Event bubbling controlado nos botões dos cards

## 🎨 Paleta de Cores

| Cor | Hexadecimal | Uso |
|-----|-------------|-----|
| Azul Escuro | `#1e3c72` | Gradiente do logo |
| Azul Médio | `#2a5298` | Botões, elementos ativos |
| Cinza Claro | `#f8fafc` | Fundo de filtros e paginação |
| Cinza Texto | `#64748b` | Descrições |
| Azul Hover | `#1e3c72` | Hover dos botões |
| Branco | `#ffffff` | Fundo dos cards |

## 📱 Responsividade

O grid se adapta perfeitamente a diferentes tamanhos de tela:

- **Desktop (1200px+):** 3 colunas de cards
- **Tablet (768px - 1199px):** 2 colunas de cards
- **Mobile (< 768px):** 1 coluna de cards
- **Header:** Empilha elementos no mobile
- **Filtros:** Centralizados e wrap automático

## 🔗 Links e Navegação

Todos os elementos interativos são clicáveis:

| Elemento | Ação |
|----------|------|
| Botão Buscar | Alerta de busca |
| Filtros | Alerta + estado ativo |
| Card (área total) | Abre link (#) |
| Botão Comprar | Alerta + add ao carrinho |
| Paginação | Alerta + estado ativo |
| Links do rodapé | Links simulados |

## 🚀 Como Executar

1. Clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Interaja com filtros, cards e paginação
4. Redimensione a tela para ver a responsividade

## 💻 Tecnologias Utilizadas

- **HTML5 semântico** - Estrutura clara e acessível
- **CSS3 Avançado:**
  - CSS Grid para layout de cards
  - Flexbox para header e filtros
  - Gradientes lineares
  - Transições suaves
  - Sombras e efeitos de elevação
- **JavaScript puro** - Interatividade sem dependências
- **Design responsivo** - Media queries estratégicas
- **Sistema de cores** - Esquema consistente

## 📊 Performance e UX

- ✅ Carregamento rápido (sem bibliotecas externas)
- ✅ Feedback visual em todas interações
- ✅ Estados hover em elementos clicáveis
- ✅ Transições suaves (0.3s)
- ✅ Grid otimizado para diferentes telas

## 📌 Casos de Uso

Este template é ideal para:
- **E-commerces** - Vitrines de produtos
- **Portfólios criativos** - Galerias de projetos
- **Sites de conteúdo** - Blogs com cards
- **Dashboards** - Painéis com métricas
- **Marketplaces** - Listagens de vendedores
- **Catálogos digitais** - Produtos e serviços

## 🧩 Diferenciais

- **ASCII art demonstrativo** no topo da página
- **Grid verdadeiro** com CSS Grid, não falsas colunas
- **Cards completos** com todas informações de produto
- **Sistema de filtros** funcional
- **Paginação realista** com estados
- **Cores profissionais** e agradáveis

## 👨‍💻 Autor

Desenvolvido como demonstração de design Card-Based / Grid baseado em diagrama ASCII art por Daniel Gehlen.

---

## 📝 Notas de Versão

### v1.0.0 (24/02/2026)
- Implementação completa do design ASCII art
- Grid responsivo com 6 cards de exemplo
- Sistema de filtros interativo
- Paginação funcional
- Todos elementos clicáveis
- Design testado em múltiplos dispositivos

### Próximas Melhorias (Sugestões)
- [ ] Adicionar modal com detalhes do produto
- [ ] Implementar carrinho de compras
- [ ] Adicionar mais produtos (dinâmico)
- [ ] Sistema de busca real
- [ ] Animações de entrada nos cards

---

**📅 Última atualização:** 24 de Fevereiro de 2026
```

---
