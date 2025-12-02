# 🚀 Guia Rápido de Início

## Como Começar Sua Atividade

### 1️⃣ Primeiro Passo: Visualizar o Projeto
1. Abra o arquivo `index.html` no seu navegador
2. Observe como a página está estruturada
3. Redimensione a janela do navegador para ver a responsividade

### 2️⃣ Segundo Passo: Ler a Atividade
1. Abra o arquivo `ATIVIDADE.md`
2. Leia todos os requisitos e o checklist completo
3. Entenda os critérios de avaliação

### 3️⃣ Terceiro Passo: Estudar o Código Base
#### HTML (`index.html`)
- Veja como as tags semânticas são usadas
- Observe a estrutura dos cards
- Entenda a organização das seções

#### CSS (`css/styles.css`)
- Analise as variáveis CSS no `:root`
- Veja como o Flexbox é aplicado
- Observe as media queries (mobile-first)

### 4️⃣ Quarto Passo: Personalizar

#### A. Pesquisar Oportunidades
Visite estes sites para encontrar oportunidades reais:
- [Portal IFRN](https://portal.ifrn.edu.br/)
- [IFRN Pesquisa](https://portal.ifrn.edu.br/pesquisa)
- [IFRN Extensão](https://portal.ifrn.edu.br/extensao)
- [Editais IFRN](https://portal.ifrn.edu.br/editais)

**Dica**: Procure por:
- Projetos de iniciação científica
- Programas de extensão
- Bolsas de pesquisa
- Projetos integradores

#### B. Adicionar Mais Cards
Copie e cole um card existente no HTML:
```html
<article class="card">
    <div class="card-header">
        <span class="card-badge badge-pesquisa">Pesquisa</span>
    </div>
    <div class="card-body">
        <h3 class="card-title">Seu Título Aqui</h3>
        <p class="card-description">Sua descrição...</p>
        <!-- ... resto do card -->
    </div>
</article>
```

#### C. Personalizar Cores
Edite as variáveis CSS em `styles.css`:
```css
:root {
    --primary-color: #007a3d;  /* Mude esta cor */
    --secondary-color: #ffc107; /* E esta também */
    /* ... outras cores */
}
```

#### D. Adicionar Ícones (Opcional)
1. Adicione Font Awesome no `<head>` do HTML:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
```

2. Use ícones nos seus cards:
```html
<i class="fas fa-laptop-code"></i>
```

### 5️⃣ Quinto Passo: Testar Responsividade

#### No Navegador (Chrome/Edge/Firefox)
1. Pressione `F12` para abrir o DevTools
2. Clique no ícone de dispositivo móvel (📱)
3. Teste diferentes tamanhos:
   - iPhone SE (375px)
   - iPad (768px)
   - Desktop (1920px)

#### Verificar:
- [x] Texto é legível em todas as telas
- [x] Cards se reorganizam corretamente
- [x] Botões são clicáveis (tamanho adequado)
- [x] Imagens não quebram o layout
- [x] Menu funciona em mobile

### 6️⃣ Sexto Passo: Validar Código

#### HTML
Visite: https://validator.w3.org/
- Clique em "Validate by Direct Input"
- Cole seu código HTML
- Corrija os erros encontrados

#### CSS
Visite: https://jigsaw.w3.org/css-validator/
- Clique em "By direct input"
- Cole seu código CSS
- Corrija os erros encontrados

## 🎨 Dicas de Design

### Escolhendo Cores
1. Use [Coolors.co](https://coolors.co/) para criar paletas
2. Mantenha contraste adequado (acessibilidade)
3. Use no máximo 4-5 cores principais

### Escolhendo Fontes
1. Visite [Google Fonts](https://fonts.google.com/)
2. Escolha 1-2 fontes (uma para títulos, outra para texto)
3. Adicione no `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
```

### Layout dos Cards
Experimente:
- Adicionar imagens no topo dos cards
- Mudar cores de acordo com a área (IA, Web, Dados, etc.)
- Adicionar ícones representativos
- Criar diferentes estilos de hover

## ⚠️ Erros Comuns a Evitar

1. **Não começar mobile-first**
   - ❌ Errado: Desenvolver primeiro para desktop
   - ✅ Correto: Começar com estilos mobile, depois adicionar media queries

2. **Esquecer de testar**
   - ❌ Errado: Só visualizar no seu tamanho de tela
   - ✅ Correto: Testar em mobile, tablet e desktop

3. **CSS desorganizado**
   - ❌ Errado: Adicionar estilos aleatoriamente
   - ✅ Correto: Organizar por seções (header, hero, cards, footer)

4. **HTML não semântico**
   - ❌ Errado: Usar só `<div>` para tudo
   - ✅ Correto: Usar `<header>`, `<main>`, `<article>`, etc.

5. **Copiar código sem entender**
   - ❌ Errado: Copiar e colar tudo de exemplos
   - ✅ Correto: Entender cada linha e adaptar ao seu projeto

## 📚 Recursos Adicionais

### Aprender Flexbox (Interativo)
- [Flexbox Froggy](https://flexboxfroggy.com/) - Jogo divertido
- [Flexbox Defense](http://www.flexboxdefense.com/) - Torre de defesa com Flexbox
- [CSS Tricks Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Guia completo

### Inspiração de Design
- [Dribbble - Landing Pages](https://dribbble.com/search/landing-page)
- [Awwwards](https://www.awwwards.com/)
- [Behance](https://www.behance.net/)

### Ferramentas Úteis
- [Can I Use](https://caniuse.com/) - Compatibilidade de CSS
- [ColorZilla](https://www.colorzilla.com/) - Pegar cores de sites
- [Lorem Ipsum](https://www.lipsum.com/) - Texto placeholder

## 🤔 Perguntas Frequentes

**P: Posso usar frameworks CSS como Bootstrap ou Tailwind?**
R: Não para esta atividade. O objetivo é aprender Flexbox puro.

**P: Preciso fazer o site funcionar de verdade?**
R: Não. Os botões "Saiba Mais" podem ser links vazios (#). O foco é no layout e CSS.

**P: Quantas oportunidades devo adicionar?**
R: Mínimo 3 (já tem), recomendado 6-9 para demonstrar bem o layout.

**P: Posso adicionar JavaScript?**
R: Pode, mas não é necessário. O foco é HTML e CSS.

**P: Como faço um menu hambúrguer?**
R: É opcional. Você pode deixar o menu simples em mobile ou adicionar com JavaScript.

**P: Onde encontro imagens para o projeto?**
R: Use [Unsplash](https://unsplash.com/) ou [Pexels](https://www.pexels.com/) para imagens gratuitas.

## ✅ Checklist de Entrega Final

Antes de entregar, verifique:
- [x] Código HTML valida sem erros
- [x] Código CSS valida sem erros
- [x] Testado em 3 tamanhos de tela diferentes
- [x] Pelo menos 5-6 oportunidades adicionadas
- [x] README.md criado explicando seu projeto
- [x] Cores e design personalizados
- [x] Código organizado e comentado
- [x] Todos os links testados
- [x] Imagens com atributo `alt`
- [x] Projeto zipado ou no GitHub

## 💪 Bônus (Extra)

Se terminar rápido e quiser ir além:
- Adicionar animações CSS mais elaboradas
- Criar um filtro de oportunidades (por área)
- Adicionar um formulário de contato
- Implementar dark mode
- Adicionar um slider/carrossel no hero
- Criar mais páginas (sobre, contato, etc.)

---

**Boa sorte! 🎓 Use sua criatividade e divirta-se aprendendo!**
