---
title: "<q>"
authors:
  - solarrust
contributors:
  - skorobaeus
summary:
  - тэг
  - тег
  - q
  - цитата
---

## Кратко

Тег `<q>` пригодится в ситуации, когда нужно вставить цитату другого человека прямо в текст предложения. Если цитата большая и состоит из нескольких абзацев, то понадобится тег [`<blockquote>`](/html/doka/blockquote).

## Пример

```html
<p>
  Великая актриса Фаина Раневская часто говорила:
  <q>
    Жизнь слишком коротка, чтобы тратить её на диеты, жадных мужчин и плохое
    настроение.
  </q>
</p>
```

## Как пишется

Прямо внутри абзаца между открывающим и закрывающим тегом `<q>` вставляем слова, которые хотим процитировать.

При этом тег добавляет кавычки вокруг цитируемой части предложения. Внешним видом кавычек можно управлять при помощи CSS-свойства [`quotes`](/css/doka/quotes/).

## Атрибуты

К тегу можно добавить любые глобальные атрибуты, а также атрибут `cite` для указания источника цитаты. Напоминаем, что атрибут `cite` или тег `<cite>` нужны для указания ссылки на источник или его названия. ☝️ Не для указания имени человека, которого вы цитируете! Можете подробнее почитать в статье про [`<blockquote>`](/html/doka/blockquote)

```html
<p>
  Великая актриса Фаина Раневская часто говорила:
  <q cite="https://www.soyuz.ru/articles/889">
    Жизнь слишком коротка, чтобы тратить её на диеты, жадных мужчин и плохое
    настроение.
  </q>
</p>
```

## Подсказки

💡 Тег `<q>` строчный, удобно встраивается в любой текст, не ломая его.

💡 Вокруг цитируемого текста добавляются стандартные кавычки “”. Вы можете изменить внешний вид кавычек при помощи CSS-свойства [`quotes`](/css/doka/quotes/).