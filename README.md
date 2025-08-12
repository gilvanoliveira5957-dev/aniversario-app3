# Pagode do Gil 5.0 — App de Convidados (GitHub Pages)

> Bundle pronto para publicar em **GitHub Pages**. Inclui:
> - `index.html` (modo Admin + Convidado via query)
> - `guest.html` (atalho que redireciona para `index.html?guest=1&wa=5511940231627`)
> - `admin.html` (atalho para o modo Admin)

## Como publicar (passo a passo)

1. Crie/acesse sua conta no GitHub e clique em **New repository**.
2. Nome do repositório (sugestão): **aniversario-app**. Marque como **Public**.
3. Faça o upload destes 3 arquivos: `index.html`, `guest.html`, `admin.html`.
4. Vá em **Settings → Pages**:
   - Em **Build and deployment**, selecione **Deploy from a branch**.
   - Em **Branch**, selecione **main** e **/** (root).
5. Aguarde ~1–2 minutos. A URL ficará assim:
   `https://SEU-USUARIO.github.io/aniversario-app/`

## Links finais para usar e compartilhar

- **Admin (você):**
  `https://SEU-USUARIO.github.io/aniversario-app/admin.html`  
  (abre o modo Admin do app)

- **Convidados (RSVP):**
  `https://SEU-USUARIO.github.io/aniversario-app/guest.html`  
  (redireciona para `index.html?guest=1&wa=5511940231627` — já com seu WhatsApp embutido)

> Dica: Substitua `SEU-USUARIO` pelo seu usuário do GitHub. Ex.: `https://gilvanoliveira.github.io/aniversario-app/guest.html`

## Observações
- Você pode alterar o número do WhatsApp no link de convidado editando o arquivo `guest.html`.
- Caso deseje um domínio próprio (ex.: `pagodedogil.com.br`), crie um arquivo `CNAME` contendo o domínio e aponte o DNS para o GitHub Pages.
- Os dados ficam salvos no navegador (localStorage). Para backup: use **Exportar/Importar** no app (aba "Exportar/Backup").

Boa festa! 🎶
