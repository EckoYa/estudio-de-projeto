# Estúdio de Projeto

Configurador de briefing da EckoYa: o cliente responde, vê o site dele tomar forma (layout, paleta, imagens) e recebe o orçamento de lançamento, com envio pelo WhatsApp.

**No ar:** https://eckoya.github.io/estudio-de-projeto/

## Não edite aqui

Este repositório só publica. A fonte é `PROJETOS/configurador-briefing` no patrimônio da EckoYa (`EckoYa/projetos-contexto`).
`scripts/publicar-estudio.mjs` espelha `index.html` + `img/` para cá, aplica o WhatsApp padrão de `.estudio.json` e faz push.
Cada push atualiza o GitHub Pages e, se ligado, o Netlify (`netlify.toml` publica a raiz).

Outro número de WhatsApp para um link específico: `?whats=55DDDNUMERO`.
