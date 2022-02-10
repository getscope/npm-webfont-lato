# WebFont Lato

Пакет для установки веб-шрифта: Lato.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-lato
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-lato": "github:getscope/npm-webfont-lato"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Lato', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_100-normal.scss";
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_200-normal.scss";
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_300-normal.scss";
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_500-normal.scss";
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_600-normal.scss";
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_800-normal.scss";
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_900-normal.scss";
@import "node_modules/@getscope/npm-webfont-lato/src/scss/_all-normal.scss";
```
