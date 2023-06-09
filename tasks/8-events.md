# Введение в события

В этом упражнении нужно реализовать логику добавления алертов по клику на кнопку.

Изначально на странице есть одна кнопка. Верстка выглядит так:

```html
<button id="alert-generator" class="btn btn-primary">Generate Alert</button>
<div class="alerts m-5"></div>
```

После клика на кнопку в контейнер с классом alerts добавляется алерт Alert 1:

```html
<div class="alerts m-5">
  <div class="alert alert-primary">Alert 1</div>
</div>
```

Последующий клик добавляет новый алерт сверху:

```html
<div class="alerts m-5">
  <div class="alert alert-primary">Alert 2</div>
  <div class="alert alert-primary">Alert 1</div>
</div>
```

Каждый клик добавляет новый алерт, меняя число в его имени.

## Задание

Реализуйте и установите обработчик события click на кнопке по логике выше.

## Подсказки

- Саму кнопку можно получить в коде через ее `id`.
- После выполнения задания подумайте, как добавить возможность скрывать алерты.