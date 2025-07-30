# Site de Vendas - eBook "Emagreça de Verdade"

## Visão Geral

Este é um site completo para venda do eBook "Emagreça de Verdade: Guia Prático para Perder Peso com Saúde". O site foi desenvolvido com foco em conversão e inclui todas as páginas necessárias para um processo de venda eficiente.

## Estrutura do Site

```
ebook-site/
├── index.html              # Página principal (landing page)
├── obrigado.html           # Página de agradecimento pós-compra
├── css/
│   └── style.css          # Estilos responsivos
├── js/
│   └── script.js          # Funcionalidades interativas
├── images/
│   ├── ebook-cover.png    #<img width="1024" height="1536" alt="ebook_cover emagrecimento" src="https://github.com/user-attachments/assets/4101fb3c-e9e6-47c4-9c1a-87ba2dd337cd" />

│   ├── ebook-pages.jpg    # Mockup das páginas
│   ├── testimonial-1.jpg  # Foto depoimento 1
│   ├── testimonial-2.jpg  # Foto depoimento 2
│   └── testimonial-3.jpg  # Foto depoimento 3
├── assets/
│   └── ebook-emagreca-de-verdade.pdf  # eBook para download
├── guia-ferramentas-pagamento.md      # Guia de integração
└── README.md              # Este arquivo
```

## Páginas Incluídas

### 1. Página Principal (index.html)
- **Hero Section**: Título impactante com capa do eBook
- **Benefícios**: 6 cards explicando o que o cliente vai aprender
- **Sobre o eBook**: Detalhes do conteúdo e estatísticas
- **Depoimentos**: 3 depoimentos com fotos e avaliações
- **Preços**: Seção com preço promocional e garantia
- **FAQ**: Perguntas frequentes para reduzir objeções
- **Footer**: Informações de contato

### 2. Página de Agradecimento (obrigado.html)
- **Confirmação**: Mensagem de sucesso da compra
- **Download**: Botão para baixar o eBook
- **Próximos Passos**: Guia do que fazer após a compra
- **Bônus**: Oferta de conteúdo adicional
- **Suporte**: Informações de contato
- **Compartilhamento**: Botões para redes sociais

## Características Técnicas

### Design Responsivo
- **Mobile-first**: Otimizado para dispositivos móveis
- **Breakpoints**: 320px, 768px, 1024px, 1200px
- **Flexbox/Grid**: Layout moderno e flexível

### Otimizações para Conversão
- **CTAs estratégicos**: Botões de compra bem posicionados
- **Prova social**: Depoimentos e estatísticas
- **Urgência**: Oferta por tempo limitado
- **Garantia**: Redução de risco para o cliente
- **FAQ**: Resposta a objeções comuns

### Performance
- **CSS otimizado**: Estilos minificados e organizados
- **Imagens otimizadas**: Tamanhos adequados para web
- **JavaScript leve**: Funcionalidades essenciais apenas

## Como Usar

### 1. Hospedagem
Você pode hospedar este site em qualquer provedor:
- **GitHub Pages**: Gratuito para sites estáticos
- **Netlify**: Deploy automático e gratuito
- **Vercel**: Hospedagem rápida e gratuita
- **Hostinger/Hostgator**: Hospedagem tradicional

### 2. Configuração de Pagamento
Consulte o arquivo `guia-ferramentas-pagamento.md` para:
- Escolher a plataforma de pagamento
- Integrar com o site
- Configurar entrega automática

### 3. Personalização

#### Alterar Preços
No arquivo `index.html`, procure por:
```html
<span class="old-price">R$ 97,00</span>
<span class="current-price">R$ 47,00</span>
```

#### Alterar Informações de Contato
Substitua os emails de exemplo:
- `contato@emagreçadeverdade.com`
- `suporte@emagreçadeverdade.com`

#### Alterar Depoimentos
Substitua as imagens em `/images/testimonial-*.jpg` e edite os textos no HTML.

#### Alterar Cores
No arquivo `css/style.css`, modifique as variáveis de cor:
```css
/* Cores principais */
--primary-color: #4CAF50;
--secondary-color: #2196F3;
--accent-color: #FF9800;
```

## Integração com Plataformas de Pagamento

### Opção 1: Hotmart (Recomendada para Iniciantes)
1. Crie conta na Hotmart
2. Cadastre o produto
3. Substitua o botão "Comprar Agora" pelo link da Hotmart
4. Configure redirecionamento para `/obrigado.html`

### Opção 2: Kiwify (Melhor Custo-Benefício)
1. Crie conta na Kiwify
2. Adicione o produto
3. Configure checkout
4. Integre o link no botão de compra

### Opção 3: Stripe (Mais Profissional)
1. Crie conta no Stripe
2. Configure webhook para entrega automática
3. Implemente Stripe Checkout
4. Configure redirecionamento pós-pagamento

## Checklist de Lançamento

### Antes de Publicar
- [ ] Testar todos os links
- [ ] Verificar responsividade em diferentes dispositivos
- [ ] Configurar plataforma de pagamento
- [ ] Testar processo de compra completo
- [ ] Verificar entrega automática do eBook
- [ ] Configurar emails de confirmação
- [ ] Testar formulários de contato

### Após Publicar
- [ ] Configurar Google Analytics
- [ ] Configurar Facebook Pixel (se usar)
- [ ] Testar velocidade de carregamento
- [ ] Verificar SEO básico
- [ ] Monitorar taxa de conversão
- [ ] Configurar backup automático

## Métricas Importantes

### Acompanhe
- **Taxa de conversão**: Visitantes que compram
- **Taxa de abandono**: Pessoas que saem no checkout
- **Tempo na página**: Engajamento do conteúdo
- **Origem do tráfego**: De onde vêm os visitantes
- **Dispositivos**: Mobile vs Desktop

### Otimize
- **Headlines**: Teste diferentes títulos
- **Preços**: Teste diferentes valores
- **CTAs**: Teste cores e textos dos botões
- **Depoimentos**: Adicione mais prova social
- **FAQ**: Adicione novas perguntas baseadas em dúvidas

## Suporte e Manutenção

### Atualizações Regulares
- Adicionar novos depoimentos
- Atualizar estatísticas
- Melhorar textos baseado em feedback
- Otimizar para novos dispositivos

### Backup
- Faça backup regular dos arquivos
- Mantenha cópia do eBook atualizada
- Documente todas as alterações

## Contato

Para dúvidas sobre o site ou sugestões de melhorias, entre em contato através dos canais configurados no próprio site.

---

**Desenvolvido com foco em conversão e experiência do usuário.**

