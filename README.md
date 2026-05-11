# NB 42k POA · Checklist

Checklist semanal para a prova NB 42k POA — 21k — 12 de julho de 2026.

## Como usar

### Deploy no Vercel (recomendado)

1. Crie um repositório no GitHub e suba os arquivos:
   ```bash
   git init
   git add .
   git commit -m "checklist nb42k"
   git remote add origin https://github.com/SEU_USUARIO/nb42k-checklist.git
   git push -u origin main
   ```

2. Acesse [vercel.com](https://vercel.com) e faça login com o GitHub.

3. Clique em **Add New Project** → selecione o repositório `nb42k-checklist`.

4. Clique em **Deploy** — sem nenhuma configuração extra.

5. Em segundos você tem uma URL pública. Salve no celular como atalho na tela inicial.

### Local

Abra `index.html` direto no navegador — funciona sem servidor.

## Features

- Checklist por dia (Seg → Dom)
- Progresso geral em tempo real
- Contador de dias até a prova
- Salvamento automático no `localStorage`
- Totalmente responsivo (funciona no celular)
