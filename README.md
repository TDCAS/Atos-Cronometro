# Atos Cronômetro

Atos Cronômetro é um aplicativo de cronômetro simples e eficiente construído com Electron. Ele permite que você inicie, pause e resete o tempo, com uma interface responsiva que se adapta a diferentes tamanhos de tela.

## Preview do Progrema

![image](https://github.com/user-attachments/assets/043f10fa-9cd6-4ca6-b445-0db314d3016e)

## Funcionalidades

- **Iniciar/Pausar/Resetar:** Controle total sobre o cronômetro.
- **Definição de Alarme:** Defina um tempo final e receba indicações visuais à medida que o tempo se aproxima do fim.
- **Interface Responsiva:** A interface se adapta a diferentes tamanhos de tela, garantindo uma experiência otimizada em desktops e laptops.

## Requisitos

- Node.js (versão 12 ou superior)
- npm (geralmente incluído com o Node.js)

## Instalação

Siga os passos abaixo para clonar e rodar o projeto localmente:

1. Clone o repositório:

   ```bash
   git clone https://github.com/TDCAS/Atos-Cronometro.git
2. Navegue até o diretório do projeto:
   ```bash
   cd Atos-Cronometro

4. Instale as dependências:
   ```bash
   npm install

5. Inicie o aplicativo:
   ```bash
   npm start

## Empacotando o Aplicativo
Para criar uma versão distribuível do aplicativo, você pode usar o electron-packager ou electron-builder.

1. Usando electron-packager:
   ```bash
   npm install -g electron-packager

2. Empacote o aplicativo:
   ```bash
   electron-packager . Atos-Cronometro --platform=win32 --arch=x64 --icon=assets/icon.ico

## Usando electron-builder:

1. Instale o electron-builder como dependência de desenvolvimento:
   ```bash
   npm install --save-dev electron-builder

2. Adicione um script ao package.json:
   ```bash
    "scripts": {
     "build": "electron-builder"
   }

3. Empacote o aplicativo:
   ```bash
   npm run build


## Licença
Este projeto está licenciado sob a licença MIT.


### O que foi feito:
- Todo o conteúdo foi ajustado para o padrão Markdown.
- Código foi formatado usando blocos de código com ```bash``` e ```json``` onde necessário.
