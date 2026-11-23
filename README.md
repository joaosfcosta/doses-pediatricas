# Doses Pediátricas de Emergência

App web (PWA) para cálculo rápido de doses pediátricas em emergência pré-hospitalar, ajustadas ao peso e **sempre limitadas à dose máxima** indicada no guia de referência.

- Fonte: *Guia de Emergência Pediátrica* — CFC / DRC, outubro 2022.
- Funciona **offline** depois da primeira abertura e pode ser instalada no ecrã inicial.
- Aplicação independente e não oficial. Ferramenta de apoio à decisão: confirme sempre a dose antes de administrar.

## Publicar no GitHub Pages

1. Crie um repositório novo (ex.: `doses-pediatricas`).
2. Carregue todos os ficheiros desta pasta para a raiz do repositório (`index.html`, `sw.js`, `manifest.json`, ícones).
3. Em **Settings → Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`, e guarde.
4. Ao fim de 1–2 minutos a app fica em `https://<utilizador>.github.io/doses-pediatricas/`.

## Instalar no telemóvel

- **iPhone (Safari):** Partilhar → *Adicionar ao ecrã principal*.
- **Android (Chrome):** menu ⋮ → *Instalar aplicação*.

## Atualizar doses

Os dados estão no bloco `DRUGS` dentro de `index.html`. Depois de alterar, aumente a versão em `sw.js` (`CACHE`) para que os telemóveis descarreguem a nova versão.
