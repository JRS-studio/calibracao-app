# Calibração de balanças

App Android para controle de calibração de balanças **dosadoras** e **de fluxo**: dois modos de calibração guiada passo a passo (**Modo calibração 01** e **Modo calibração 02**) com cronômetro, cálculo automático do erro, farol de vencimento, histórico com gráfico e relatório em PDF.

## Baixar
Vá em **Releases** (à direita) e baixe o `calibracao-balancas.apk` da versão mais recente. No celular, abra o arquivo e permita a instalação.

## Como usar
1. Abra o app e toque em **Criar conta** (nome, e-mail e senha).
2. Em **Meu perfil e relatórios**, informe o e-mail e o WhatsApp que recebem os relatórios, as tolerâncias e os prazos.
3. Cadastre suas balanças e comece a calibrar.

Cada conta vê somente os próprios equipamentos e calibrações.

## Como o APK é gerado
A cada mudança na branch `main`, o GitHub Actions (`.github/workflows/apk.yml`) monta o app com Capacitor, assina e publica o APK em Releases.

## Desenvolvedor
Desenvolvido por **Jeferson Rodrigo dos Santos**.
