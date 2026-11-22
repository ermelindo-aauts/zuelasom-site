# zuelasom-site

Página de entrada da ZuelaSom em **https://zuelasom.aauts.pt** (GitHub Pages).
O botão "Abrir a app" leva a **https://zuelasom.streamlit.app** (a app, no Streamlit Community Cloud).
`https://zuelasom.aauts.pt/?app=1` abre logo a app.

- Gerada a partir da página Sobre do projeto ZuelaSom (`sobre/index.php`), sem PHP nem números ao vivo.
- `CNAME`: o endereço próprio. No DNS do aauts.pt: registo CNAME `zuelasom` → `<conta>.github.io`.
- GitHub → Settings → Pages → Deploy from a branch → `main` / raiz; depois ativar *Enforce HTTPS*.
