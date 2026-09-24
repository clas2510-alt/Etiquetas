# Gerador de Etiquetas 10x10 cm

Gerador de etiquetas para impressora Zebra (10x10 cm), com moldura, logo, Exportador, Cliente, P.O e numeração de volumes (`01/60`).

Funciona 100% no navegador, sem servidor nem instalação.

## Como usar

1. Preencha Exportador, Cliente, Nº P.O., quantidade de volumes e volume inicial.
2. Clique em **Imprimir Etiquetas** (cada etiqueta sai como uma página de 10x10 cm) ou em **Gerar PDF**.
3. Os textos das etiquetas também podem ser editados direto na prévia.

> Na janela de impressão, deixe margens em "Nenhuma" e escala em 100%.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie estes arquivos:
   ```bash
   git init
   git add .
   git commit -m "Gerador de etiquetas"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   git push -u origin main
   ```
2. No repositório, vá em **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em cerca de 1 minuto o site fica em `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`.

## Dependências (via CDN)

- [html2canvas](https://html2canvas.hertzen.com/) 1.4.1
- [jsPDF](https://github.com/parallax/jsPDF) 2.5.1

É necessário acesso à internet para gerar o PDF.
