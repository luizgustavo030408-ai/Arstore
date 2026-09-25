# AR Store Menswear — Site

Site estático (HTML + CSS + JS). Não precisa instalar nada.

## Estrutura
- `index.html` — o site
- `assets/img/` — logo e fotos (troque mantendo o mesmo nome)
- `vercel.json` — configuração da Vercel

## Publicar
1. Crie um repositório no GitHub e envie todos os arquivos desta pasta.
2. Na Vercel: **Add New → Project → Import** o repositório.
3. Framework Preset: **Other**. Não precisa de build. Clique em **Deploy**.

## Endereço do mapa
No `index.html`, procure `CONFIG` e troque:
```js
const CONFIG = { endereco: "Rua X, 123 - Bairro, Boa Vista - RR", enderecoVisivel: "Rua X, 123 — Bairro" };
```
