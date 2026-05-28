# Passo a passo para colocar o site no GitHub Pages

Este site é estático. Não precisa instalar React, Vite, Node.js ou Tailwind.

## Opção 1: pelo navegador

1. Entre no GitHub.
2. Clique em **New repository**.
3. Nomeie o repositório como `ribbon-safe-site`.
4. Marque como **Public**.
5. Clique em **Create repository**.
6. Clique em **uploading an existing file**.
7. Envie:
   - `index.html`
   - pasta `assets`
   - pasta `docs`
   - `README.md`
8. Clique em **Commit changes**.
9. Vá em **Settings**.
10. Vá em **Pages**.
11. Em **Build and deployment**, selecione:
    - Source: **Deploy from a branch**
    - Branch: **main**
    - Folder: **/root**
12. Clique em **Save**.
13. Aguarde alguns minutos.
14. O site abre em:

```txt
https://SEU-USUARIO.github.io/ribbon-safe-site/
```

## Opção 2: pelo terminal

Entre na pasta do site e rode:

```bash
git init
git add .
git commit -m "Adicionar site Ribbon Safe"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/ribbon-safe-site.git
git push -u origin main
```

Depois ative o GitHub Pages em:

```txt
Settings → Pages → Deploy from branch → main → /root → Save
```

## Ajuste obrigatório

No `index.html`, troque o número do WhatsApp:

```txt
5511987654321
```

pelo número real que recebe os pedidos.
