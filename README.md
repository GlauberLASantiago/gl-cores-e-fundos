# GL Fundos

Galeria de assets visuais para aplicações e design instrucional.

## Visão geral

Este repositório contém uma página estática em `index.html` que lê as pastas públicas do próprio repositório via API do GitHub e monta uma galeria de imagens por categoria.

Cada pasta do projeto funciona como uma categoria, e cada imagem disponível dentro dela é exibida automaticamente na interface.

## Estrutura do projeto

```text
fundos/
├── index.html
└── musica/
```

## Como usar

1. Abra a página `index.html` em um ambiente estático ou publique o repositório no GitHub Pages.
2. Aguarde o carregamento das categorias encontradas no repositório.
3. Clique em uma categoria para visualizar as imagens.
4. Clique em uma imagem ou no botão de cópia para gerar um texto com a URL do asset.

## Como adicionar novos fundos

1. Crie uma nova pasta na raiz do repositório com o nome da categoria.
2. Adicione arquivos de imagem dentro dessa pasta.
3. Os formatos aceitos atualmente são:
   - `.jpg`
   - `.jpeg`
   - `.png`
   - `.gif`
   - `.webp`
   - `.svg`
4. Após publicar as alterações, a nova categoria aparecerá automaticamente na galeria.

## Observações

- O repositório precisa estar público para que a API do GitHub retorne os arquivos sem autenticação.
- Pastas sem imagens aparecem como categorias, mas exibem uma mensagem de vazio ao serem abertas.
