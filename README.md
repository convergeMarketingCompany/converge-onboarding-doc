# Converge — Onboarding de clientes

Apresentação interativa da estrutura inicial do sistema de onboarding da Converge.

## Visualização local

Abra `onboarding-estrutura.html` no navegador, ou execute:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Acesse http://127.0.0.1:8765/onboarding-estrutura.html.

## GitHub Pages

A versão para publicação está em `docs/index.html`, com logo e fontes incorporados.

No GitHub, abra **Settings → Pages**, selecione **Deploy from a branch** e escolha a branch `main` e a pasta `/docs`. Salve para publicar.

Após alterar a apresentação, atualize a cópia publicada:

```sh
cp onboarding-estrutura.html docs/index.html
```

As anotações ficam no navegador de cada visitante. Não são enviadas ao GitHub nem compartilhadas entre pessoas.

## Identidade visual

Logo, fonte Montserrat e cores baseados em https://converge.network/.
