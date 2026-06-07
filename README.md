# Desafio 7 Dias - Barriga Mais Lisa

Landing page de alta conversão para o Desafio 7 Dias Barriga Mais Lisa, com design dark premium e prova social integrada.

## 🚀 Características

- ✅ Design responsivo (Mobile-first)
- ✅ Tailwind CSS para estilização
- ✅ FAQ interativo com acordeão
- ✅ Prova social com depoimentos
- ✅ Timeline de cronograma
- ✅ Sticky footer com CTA
- ✅ Otimizado para conversão
- ✅ Link de checkout Kiwify integrado

## 📋 Seções da Página

1. **Hero** - Headline impactante com CTA principal
2. **Benefícios** - O que o cliente vai receber
3. **Dores** - Problemas que o produto resolve
4. **Cronograma** - Timeline dos 7 dias
5. **Comparação** - Dieta Tradicional vs Desafio 7 Dias
6. **Depoimentos** - Prova social com 5 estrelas
7. **FAQ** - Perguntas frequentes interativas
8. **Oferta** - Seção de preço e CTA final

## 🔗 Link de Checkout

Todos os botões de compra redirecionam para:
```
https://pay.kiwify.com.br/Gh6lbnp
```

## 📱 Como Fazer Deploy

### Opção 1: Vercel (Recomendado)

1. Faça login em [vercel.com](https://vercel.com)
2. Clique em "New Project"
3. Selecione este repositório do GitHub
4. Clique em "Deploy"

### Opção 2: Netlify

1. Faça login em [netlify.com](https://netlify.com)
2. Clique em "New site from Git"
3. Selecione este repositório do GitHub
4. Configure:
   - Build command: `npm run build`
   - Publish directory: `dist`
5. Clique em "Deploy"

### Opção 3: GitHub Pages

1. Faça push do código para GitHub
2. Vá para Settings > Pages
3. Selecione "Deploy from a branch"
4. Escolha a branch `main`

## 🛠️ Desenvolvimento Local

```bash
# Instalar dependências
npm install

# Rodar servidor de desenvolvimento
npm run dev

# Build para produção
npm run build

# Preview da build
npm run preview
```

## 📝 Customização

### Cores
Edite as cores no `tailwind.config` dentro de `index.html`:
- `brand: '#DFFF00'` - Cor principal (Lime Green)
- `dark: '#000000'` - Fundo preto

### Textos
Todos os textos estão no `index.html`. Procure pelas seções comentadas para editar.

### Imagens
As imagens dos depoimentos podem ser substituídas nos URLs:
```html
<img src="URL_DA_IMAGEM" class="w-full h-48 object-cover" alt="Antes e Depois">
```

## 📊 Otimizações de Conversão

- ✅ CTA em cores contrastantes (Lime Green)
- ✅ Prova social com avatares e estrelas
- ✅ Garantia de 7 dias em destaque
- ✅ Preço com desconto visível
- ✅ Sticky footer para fácil acesso ao CTA
- ✅ FAQ para reduzir objeções
- ✅ Timeline clara dos benefícios

## 📞 Suporte

Para dúvidas sobre o design ou funcionalidades, verifique o arquivo `index.html` ou entre em contato.

---

**Criado com ❤️ para o Desafio 7 Dias Barriga Mais Lisa**
