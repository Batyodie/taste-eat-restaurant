# Для контрибьюторов

Для разработки нужно: 

* [Node.js](https://nodejs.org/en/) - программная платформа, основанная на движке V8, превращающая JavaScript из узкоспециализированного языка в язык общего назначения.
* [NPM](https://www.npmjs.com/) - менеджер пакетов node.js.
* [Git](https://git-scm.com/) - система контроля версий.
* [github ssh ключ](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) - для работы с репозиторием.
* [Figma](https://www.figma.com/) - онлайн-сервис для создания прототипов интерфейсов.
* [Visual Studio Code](https://code.visualstudio.com/) - текстовый редактор с поддержкой множества языков программирования и сценариев.
Плагины для работы с vscode:
  * DotENV
  * EditorConfig
  * ESLint
  * Git Graph
  * Prettier
  * stylelint

  Настройки vscode:
```json
{
    "editor.rulers": [
        100
    ],
    "scssFormatter.tabWidth": 4,
    "scssFormatter.singleQuote": true,
    "scss.validate": false,
    "files.autoSave": "off",
    "explorer.confirmDelete": false,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
}
```
* [webstorm](https://www.jetbrains.com/ru-ru/webstorm/) - IDE для веб-разработки. Аналог Visual Studio Code.
Конфиг [настроек](https://drive.google.com/file/d/1fWSgDrolqzIjj7PeLclsIrptjERDoq2D/view?usp=sharing)

### Локальная разработка

1. Склонировать репозиторий
```bash
$ git clone git@github.com:Batyodie/taste-eat-restaurant.git
```
2. Установить зависимости
```bash
$ npm install
```
3. Запустить проект
```bash
$ npm run dev
```
