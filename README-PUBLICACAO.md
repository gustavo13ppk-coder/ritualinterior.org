# Publicação - Treino em Casa

Este pacote está pronto para subir no GitHub e fazer deploy na Vercel.

## Arquivos principais

- `index.html` - página de vendas com os dois produtos.
- `combo-obrigado.html` - página de obrigado do produto de R$ 17.
- `desafio-obrigado.html` - página de obrigado do produto de R$ 9 com upsell para o combo.
- `treino-obrigado.html` - cópia da página do combo, mantida por compatibilidade.
- `downloads/treino-em-casa-plano.pdf` - PDF do plano de treino.
- `downloads/desafio-7-dias-treino.pdf` - PDF do desafio.
- `downloads/planilha-acompanhamento-treino.csv` - planilha de acompanhamento.

## Links que entram na Kiwify

Depois que publicar na Vercel, use a URL do seu projeto:

Produto Combo R$ 17:

```text
https://SEU-DOMINIO-OU-VERCEL.app/combo-obrigado.html
```

Produto Desafio R$ 9:

```text
https://SEU-DOMINIO-OU-VERCEL.app/desafio-obrigado.html
```

## Links de checkout que precisam ser trocados

No `index.html`, substitua:

```text
https://pay.kiwify.com.br/SEU-LINK-COMBO
https://pay.kiwify.com.br/SEU-LINK-DESAFIO
```

No `desafio-obrigado.html`, substitua também:

```text
https://pay.kiwify.com.br/SEU-LINK-COMBO
```

## Deploy na Vercel

1. Crie um repositório no GitHub.
2. Suba todos os arquivos deste pacote.
3. Na Vercel, importe o repositório.
4. Framework: `Other`.
5. Build command: deixe vazio.
6. Output directory: deixe vazio ou use a raiz.
7. Depois do deploy, copie a URL gerada e coloque os redirecionamentos na Kiwify.
