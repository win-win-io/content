---
title: Название статьи
name: Название файла
author: Никнейм основного автора
co-authors: Никнейм ввсех соавторов
designers: Никнейм дизайнера
contributors:
  - Никнейм контрибутора
summary:
  - Альтернативные теги для работы поиска
cover:
  desktop: 'desktop.png'
  mobile: 'mobile.png'
  alt: 'Альтернативное описание для обложки'
---

## Описание проблемы

Описываем проблему, указанную в заголовке статьи (отдельно блок может не выделяться в заголовке).

<details>
  <summary>Пример</summary>
  Если вы пишете много кода, то однажды обнаружите, что вы постоянно делаете одно и то же. Те же самые куски переписываются, тратят время. Если работаете в команде, то работа вашего коллеги может вызвать неудобные зависимости.

Чтобы этого избежать, стоит определить общие правила и их придерживаться.

</details>

## Решение проблемы №1

Описание решение проблемы

<details>
  <summary>Пример</summary>

Чтобы положить один блок в другой, надо представить дочерний блок как элемент блока родительского.

Посмотрим на код на примере полки на книге.

```html
<div class="shelf">
  <div class="shelf__book book"></div>
</div>
```

</details>

## Решение проблемы №2

Описание решение проблемы

<details>
  <summary>Пример</summary>

    Внутри всё это дело подключается через `@import url();`, поэтому файл index.css выглядел бы так:

    ```css
    @import url(../../blocks/shelf.css);
    @import url(../../blocks/book.css);

    /* тут можно указать какие-то глобальные стили, но по правилам БЭМ. Например, задать шрифт странице */
    ```

</details>

## Как в жизни

Мнения frontend-ниндзя о том, как они работают с проблемой

- Общие правила по описанию статей:
  1. Посмотрите как сделаны другие статьи, и напишите статью в том же стиле: "Пиши, сокращай" - отличный гайд
  2. Когда вводите новое понятие, выделите его и объясните за что оно отвечает
  3. Сразу после того, как ввели новое понятие приведите пример кода, как использовать новые данные
  4. Не стесняйтесь повторять для закрепления материала
  5. Используйте заголовки, чтобы выделить разделы, не используйте `<h1>`
  6. Используйте сворачиваемые блоки для отображения опциональной информации
  7. Обязательно дайте ссылки на статьи из справочника
  8. Можно кратно описать содержимое другой статьи, если требуется. Дайте ссылку, чтобы прочитать подробнее
  9. Один раздел должен переходить в другой
  10. Предпочитайте markdown, а не html при оформлении статьи

Вы можете ориентироваться на статью ([Гайд по flexbox](https://github.com/Y-Doka/y-doka.site/blob/master/src/posts/css/long/flexbox-guide.md)) в качестве примера оформления.