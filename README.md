# App Padronizado (Stellantis)
Arquivos atualizados para usar um design system único via **style.css**.

## O que foi feito
- Remoção de blocos `<style>` embutidos em cada página.
- Inclusão de `<link rel="stylesheet" href="style.css">` no `<head>` de todas as páginas.
- Mantidos os scripts originais e links de fontes Google.
- `style.css` inclui: containers, tipografia, botões, inputs, tabelas, toasts e modais.

## Como usar
Basta abrir `index.html` no navegador. Todas as páginas já apontam para `style.css`.

## Observação
Se houver algum estilo inline (em `style="..."`) muito específico ainda presente, ele continuará funcionando.
