# PolitiShop

Site fictício de e-commerce que reúne, em um só lugar, lojas de produtos de apoio a diferentes candidatos. Cada loja tem seu próprio catálogo de produtos, e todas compartilham uma única página de checkout.

> ⚠️ **Aviso:** Este é um projeto de estudo/portfólio, feito 100% em HTML puro (sem CSS, JavaScript ou backend). Não processa pagamentos reais e não representa nenhuma posição política oficial dos envolvidos.

## Sobre o projeto

O PolitiShop simula uma vitrine de e-commerce com três lojas distintas:

- 🧢 Loja do Bolsonaro
- 🧢 Loja do Lula
- 🥤 Loja do Renan Santos

A partir da página principal, o usuário pode navegar entre as lojas, comparar preços de produtos em destaque e finalizar a compra em um checkout único e compartilhado entre todas as lojas.

## Pagina Home

![Página Principal do PolitiShop](.//Screenshots/Home-preview.jpeg)

## Estrutura do projeto

```
politishop/
├── html/
│   ├── Home.html          # Página principal (Loja Principal)
│   ├── pagina1.html       # Loja do Bolsonaro
│   ├── pagina2.html       # Loja do Lula
│   ├── pagina3.html       # Loja do Renan Santos
│   └── checkout.html      # Checkout compartilhado entre as lojas
├── img/
│   └── ...                # Imagens dos produtos de cada loja
└── screenshots/
    └── home-preview.jpg   # Captura de tela usada no README
```

## Funcionalidades

- **Página Principal (Home.html)**: lista as três lojas disponíveis e exibe uma tabela comparativa com um produto em destaque de cada loja (imagem, loja, produto e preço).
- **Páginas das lojas**: catálogo de produtos em tabela, com imagem, nome, descrição e preço de cada item.
- **Botão "Comprar"**: leva o usuário até a página de checkout, já indicando qual loja e produto foram selecionados via parâmetros na URL.
- **Checkout (checkout.html)**: formulário único de finalização de compra, usado pelas três lojas, com campos para dados do produto, dados do comprador e forma de pagamento.
- **Rodapé padronizado**: navegação rápida entre todas as páginas, presente em todas as telas.

## Tecnologias utilizadas

- **HTML5** — 100% do projeto, sem uso de CSS, JavaScript ou frameworks.
- Recursos nativos do HTML usados para melhorar a experiência sem sair da linguagem: `<table>` para catálogos e comparativos, `<details>`/`<summary>` para conteúdo recolhível, `<fieldset>`/`<legend>` para organizar o formulário do checkout, e atributos `required`/`pattern` para validação nativa de campos.

## Como executar o projeto

Não é necessário nenhum servidor ou instalação. Basta:

1. Clonar o repositório.
2. Manter a estrutura de pastas `html/` e `img/` lado a lado.
3. Abrir o arquivo `html/Home.html` diretamente no navegador.

## Limitações conhecidas

- Por ser HTML puro, o checkout **não preenche automaticamente** os campos de produto/preço a partir da URL — isso exigiria JavaScript, que foi propositalmente deixado de fora do escopo do projeto.
- Não há processamento real de pagamento; o formulário de checkout é apenas ilustrativo.

## Possíveis melhorias futuras

- Adicionar preenchimento automático do checkout via JavaScript (opcional).
- Expandir o catálogo de produtos de cada loja.
- Adicionar mais opções de comparação na página principal.

## Autor

Projeto pessoal desenvolvido para fins de estudo e portfólio.