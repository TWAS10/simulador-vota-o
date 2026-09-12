# Simulador de Votação — V4

Simulador educativo independente, inspirado visualmente em uma peça vertical de campanha, mas sem copiar identidade de candidato, partido ou sistema oficial.

## V4
- Funciona em GitHub Pages.
- Possui Service Worker para cache/offline depois do primeiro carregamento.
- Não usa bibliotecas externas nem fontes externas.
- Dados de candidatos são salvos apenas no `localStorage` do navegador.
- Fluxo Federal → Estadual, CORRIGE, CONFIRMA, VOTO EM BRANCO e REINICIAR.
- Editor local de candidatos.
- Interface responsiva para celular.
- Aviso permanente de que não é uma urna oficial e não registra votos reais.

## Publicar
Suba `index.html`, `styles.css`, `app.js`, `manifest.json`, `sw.js`, `icon.svg` no diretório raiz de um repositório público e ative GitHub Pages em `main` / `root`.

## Observação sobre offline
Na primeira visita é necessário carregar o site para que o navegador grave os arquivos no cache. Depois disso, a aplicação pode abrir sem internet no mesmo dispositivo/navegador.
