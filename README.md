# IPTV Checker Pro — Android

Projeto Android com WebView para executar o HTML original como aplicativo instalável.

## Build local
Requer JDK 17 e Android SDK.

    gradle assembleDebug

APK:
`app/build/outputs/apk/debug/app-debug.apk`

## GitHub Actions
O workflow em `.github/workflows/build-apk.yml` compila automaticamente o APK e publica o arquivo como artifact da execução.

## Observação
O HTML original foi preservado em `app/src/main/assets/index.html`.
