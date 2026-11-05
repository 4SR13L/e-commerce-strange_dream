# STRANGEDREAM Store

Loja virtual (e-commerce) de produtos de jogos indie: figures, chaveiros, pins e roupas. Projeto da atividade de Criação de Sites. A marca, as cores, os textos e os produtos são próprios. O layout vem do design feito no Figma.

## Tecnologias
HTML, CSS e JavaScript puro, com Git e GitHub. Não precisa instalar nada.

## Como executar
Baixe ou clone o repositório e abra o arquivo `index.html` no navegador.

```
git clone https://github.com/4SR13L/e-commerce-strange_dream.git
```

## Estrutura
```
strange_dream/
├── index.html        página única com as telas (home, catálogo, produto, carrinho, checkout, confirmação)
├── css/style.css     identidade visual, layout e responsividade
├── js/data.js        catálogo de produtos
├── js/app.js         navegação, carrinho, cálculos e pagamento simulado
└── img/              fotos e ilustrações dos produtos
```

## Funcionalidades
- Menu de navegação, categorias (Acessórios, Roupas, Figures) e busca
- Produtos com imagem, nome, descrição e preço; página de detalhes com galeria e tamanho
- Carrinho: adicionar, alterar quantidade, remover, total e frete (grátis acima de R$ 120)
- Checkout com dados do cliente e validação dos campos
- Pagamento simulado: cartão de crédito (com parcelamento em até 12x), cartão de débito e Pix (código copia e cola e QR de demonstração)
- Confirmação de compra realizada
- Extras: favoritos, cupom `STRANGE10` (10%), modo escuro, carrinho salvo no navegador, layout responsivo (computador e celular)

Nenhum pagamento real é feito e nenhum dado bancário verdadeiro deve ser informado.
