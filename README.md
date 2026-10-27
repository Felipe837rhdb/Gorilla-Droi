# Gorila Droid – APK

App Android (WebView em tela cheia, sem barra de endereço) do Gorila Droid 5.2.

- Abre direto o jogo que está dentro do APK (`app/src/main/assets/game.html`), sem depender de link.
- Ícone: foto do Gorilla Tag. A tela gira livre (vertical e deitada).

## Como gerar o APK

1. Crie um repositório no GitHub e envie **todos** os arquivos desta pasta (inclusive a pasta oculta `.github`).
2. Vá na aba **Actions** → **Build APK** (começa sozinho a cada envio; se não, clique em **Run workflow**).
3. Espere ~3–5 min. Depois baixe o `GorilaDroid.apk` na aba **Releases** (ou em Actions → execução → Artifacts).
4. Instale no celular (permita "instalar apps desconhecidos").

## Personalizar

- Fixar na horizontal: em `AndroidManifest.xml`, troque `fullSensor` por `sensorLandscape`.
