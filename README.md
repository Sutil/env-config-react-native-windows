# Configuração de ambiente Windows para desenvolver com React Native

## instalar vs code

https://code.visualstudio.com/

## Instalar extenções

- vscode-icons
- Color Highlight
- editorconfig - Editor config for vscode
- eslint
- prettier
- rocketseat React Native

## Alterar o settings.json do vscode

```
Ctrl + shift + p
```

escolha a opção `preferences: Open Settings (JSON)` e cole o trecho abaixo dentro do arquivo

```json
{
  "editor.lineHeight": 20,
  "editor.formatOnSave": true,
  "editor.rulers": [80, 120],
  "editor.tabSize": 2,
  "editor.renderLineHighlight": "gutter",
  "terminal.integrated.fontSize": 14,
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "javascript.updateImportsOnFileMove.enabled": "never",
  "breadcrumbs.enabled": true,
  "editor.parameterHints.enabled": true
}
```

## Baixar e instalar Dev Docs App

https://devdocs.egoist.sh/

## Instalar chocolatey

https://chocolatey.org/

Execute o PowerShel como administrador e execute o comando:

```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

```

## Instalar NodeJS

Ainda com o Power Shel aberto, execute:

```
cinst nodejs
```

## Instalar Yarn

```
choco install yarn
```

## Instalar Python e JDK

```
choco install -y nodejs.install python2 jdk8
```

## Instalar do React Native CLI

```
yarn global add react-native-cli
```

## Baixe e instale o Android Studio

Ele será importante somente para as configurações do Android e Emulador.

https://developer.android.com/studio/#downloads

## Definir path do SDK
