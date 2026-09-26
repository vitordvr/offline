# Varsel Solutions — Site desligado

Página estática de encerramento, pronta para publicação na Vercel.

## Visualização local

Abra `index.html` em um navegador. Não é necessário instalar dependências.

## Publicação na Vercel

1. Envie este projeto para um repositório Git.
2. No painel da Vercel, selecione **Add New → Project** e importe o repositório.
3. Use **Other** como Framework Preset e mantenha a raiz do projeto como Root Directory.
4. Clique em **Deploy**. O arquivo `vercel.json` configura a publicação sem etapa de build.

Também é possível publicar pelo terminal, dentro da pasta do projeto:

```sh
npx vercel
```

Para publicar em produção:

```sh
npx vercel --prod
```

Todas as rotas são direcionadas para `index.html`, para que visitantes de links antigos também vejam o aviso de encerramento.
