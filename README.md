# Когнитивные искажения

Одностраничный лендинг «Когнитивные искажения в программировании» — статичная
вёрстка по готовому макету: пять карточек искажений (эффект ИКЕА,
преждевременная оптимизация, искажение новизны, гиперболическое
обесценивание, ошибка планирования) с описанием каждого.

## Стек

- HTML5
- CSS3 (собран из SCSS, `src/styles/scss/app.scss` → `src/styles/style.css`)
- HTMLHint, Stylelint (`stylelint-config-standard-scss`) — проверка вёрстки
- Surge — деплой статики

## Использование

```bash
make install   # npm install
make lint      # htmlhint + stylelint
```

Открыть `src/index.html` в браузере, либо поднять локальный сервер:

```bash
npx http-server src -p 8080
```

---

[![Hexlet Ltd. logo](https://raw.githubusercontent.com/Hexlet/assets/master/images/hexlet_logo128.png)](https://hexlet.io?utm_source=github&utm_medium=link&utm_campaign=html-boilerplate)

This repository is created and maintained by the team and the community of Hexlet, an educational project. [Read more about Hexlet](https://hexlet.io?utm_source=github&utm_medium=link&utm_campaign=html-boilerplate).

See most active contributors on [hexlet-friends](https://friends.hexlet.io/).
