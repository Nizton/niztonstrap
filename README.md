# NIZTONSTRAP v1.0

**Расширенный CSS фреймворк от Nizton**
Версия: 1.0.0
Лицензия: MIT
Тема: оранжево-черная
Более 100 готовых компонентов, полная адаптивность, утилиты и сетка.

---

## ✨ Особенности

* Полностью адаптивная 12-колоночная сетка
* Оранжево-черная цветовая схема с градиентами
* 100+ CSS компонентов: кнопки, карточки, формы, навигация, алерты, модальные окна, карусели, аккордеоны
* Полный набор утилит: от display и flex до цветов, отступов, размеров и теней
* Легкая интеграция без JS (JS можно подключать для интерактивных компонентов, например, модальных окон и каруселей)

---

## 📦 Установка

### Подключение через CDN

```html
<link rel="stylesheet" href="https://yourcdn.com/niztonstrap.min.css">
```

### Локальное подключение

Скачайте `niztonstrap.css` или `niztonstrap.min.css` и подключите в HTML:

```html
<link rel="stylesheet" href="path/to/niztonstrap.css">
```

---

## 🎨 Цвета и переменные

```css
--ns-primary: #ff6b35;      /* основной оранжевый */
--ns-secondary: #495057;    /* темный серый */
--ns-success: #198754;      /* зеленый */
--ns-danger: #dc3545;       /* красный */
--ns-warning: #ffc107;      /* желтый */
--ns-info: #0dcaf0;         /* голубой */
--ns-light: #e9ecef;        /* светлый */
--ns-dark: #121212;         /* черный */
--ns-white: #ffffff;        /* белый */
```

Градиенты: `--ns-gradient-orange`, `--ns-gradient-black`, `--ns-gradient-dark`

---

## 🖋 Типографика

* Шрифты: sans, serif, monospace
* Размеры от `xs` до `9xl`
* Межстрочные интервалы: `lh-1`, `lh-sm`, `lh-base`, `lh-lg`

Пример:

```html
<h1 class="display-1">Заголовок 1</h1>
<p class="lead">Ведущий абзац текста</p>
```

---

## 📐 Контейнеры и сетка

* Контейнеры: `.container`, `.container-fluid`, `.container-sm/md/lg/xl/xxl`
* Сетка: 12 колонок, `.row` + `.col-1`..`.col-12`
* Отступы между колонками: `.g-0`..`.g-5`

Пример:

```html
<div class="container">
  <div class="row">
    <div class="col-6">Колонка 1</div>
    <div class="col-6">Колонка 2</div>
  </div>
</div>
```

---

## 🔘 Кнопки

* Варианты: `.btn-primary`, `.btn-secondary`, `.btn-success`, `.btn-danger`, `.btn-warning`, `.btn-info`, `.btn-light`, `.btn-dark`
* Outline: `.btn-outline-primary`
* Ghost: `.btn-ghost-primary`
* Размеры: `.btn-xs`, `.btn-sm`, `.btn-lg`, `.btn-xl`
* Иконки: `.btn-icon`, `.btn-icon-start`, `.btn-icon-end`
* Плавающие кнопки: `.btn-floating`

Пример:

```html
<button class="btn btn-primary btn-lg">Основная кнопка</button>
<button class="btn btn-outline-primary btn-sm">Outline</button>
```

---

## 🃏 Карточки

* Типы: `.card-basic`, `.card-border`, `.card-shadow`, `.card-gradient`, `.card-dark`, `.card-hover`
* Части: `.card-header`, `.card-body`, `.card-footer`, `.card-img-top`, `.card-img-overlay`, `.card-icon`

Пример:

```html
<div class="card card-shadow">
  <div class="card-header">Заголовок</div>
  <div class="card-body">Контент карточки</div>
  <div class="card-footer">Футер</div>
</div>
```

---

## 📝 Формы

* Контейнеры: `.form-group`
* Метки: `.form-label`
* Поля: `.form-control`, `.form-control-lg`, `.form-control-sm`
* Checkbox / Radio: `.form-check`, `.form-check-input`
* Switch: `.form-switch`
* Range: `.form-range`

Пример:

```html
<div class="form-group">
  <label class="form-label">Email</label>
  <input type="email" class="form-control" placeholder="Введите email">
</div>
<div class="form-check">
  <input class="form-check-input" type="checkbox" id="check1">
  <label class="form-check-label" for="check1">Согласен</label>
</div>
```

---

## 🌐 Навигация

* Navbar: `.navbar`, `.navbar-brand`, `.navbar-nav`, `.nav-link`
* Навигационные табы: `.nav-tabs`, `.nav-link.active`
* Pagination: `.pagination`, `.page-link`, `.page-item.active`

Пример:

```html
<ul class="nav-tabs">
  <li><a class="nav-link active" href="#">Вкладка 1</a></li>
  <li><a class="nav-link" href="#">Вкладка 2</a></li>
</ul>
```

---

## ⚠️ Алерты

* Варианты: `.alert-primary`, `.alert-secondary`, `.alert-success`, `.alert-danger`, `.alert-warning`, `.alert-info`, `.alert-dark`
* С иконкой: `.alert-icon`
* Dismissible: `.alert-dismissible`, `.btn-close`

Пример:

```html
<div class="alert alert-success alert-dismissible">
  <span class="alert-icon">✔</span> Успешно сохранено!
  <button type="button" class="btn-close"></button>
</div>
```

---

## 🏷 Бэджи

* `.badge-primary`, `.badge-secondary`, `.badge-success`, `.badge-danger`, `.badge-warning`, `.badge-info`, `.badge-light`, `.badge-dark`

Пример:

```html
<span class="badge badge-primary">Новинка</span>
```

---

## 📊 Прогресс-бары

* `.progress`, `.progress-bar`, `.progress-bar-striped`, `.progress-bar-animated`

Пример:

```html
<div class="progress">
  <div class="progress-bar progress-bar-striped progress-bar-animated" style="width: 50%"></div>
</div>
```

---

## 🔄 Спиннеры

* `.spinner`, `.spinner-sm`

Пример:

```html
<div class="spinner"></div>
```

---

## 📌 Модальные окна

* `.modal`, `.modal-dialog`, `.modal-content`, `.modal-header`, `.modal-body`, `.modal-footer`

Пример:

```html
<div class="modal fade" id="myModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">Заголовок</div>
      <div class="modal-body">Контент модального окна</div>
      <div class="modal-footer">Футер</div>
    </div>
  </div>
</div>
```

---

## 📂 Аккордеоны

* `.accordion`, `.accordion-item`, `.accordion-header`, `.accordion-button`, `.accordion-body`

---

## 🎠 Карусель

* `.carousel`, `.carousel-inner`, `.carousel-item`, `.carousel-control-prev`, `.carousel-control-next`

---

## ⬇ Dropdown

* `.dropdown`, `.dropdown-toggle`, `.dropdown-menu`, `.dropdown-item`

---

## 🛠 Утилиты

* **Display:** `.d-none`, `.d-inline`, `.d-block`, `.d-flex`, `.d-grid`
* **Flex:** `.flex-row`, `.flex-column`, `.justify-content-*`, `.align-items-*`
* **Grid:** `.grid`, `.grid-cols-1..12`, `.gap-*`
* **Spacing:** `.m-*`, `.p-*`, `.mt-*`, `.pt-*`, `.ms-*`, `.pe-*`
* **Position:** `.position-relative`, `.position-absolute`, `.top-0`, `.start-50`
* **Text:** `.text-primary`, `.text-center`, `.fw-bold`, `.fst-italic`
* **Borders:** `.border`, `.border-0`, `.rounded`, `.rounded-circle`
* **Shadows:** `.shadow`, `.shadow-sm`, `.shadow-lg`
* **Colors:** `.bg-primary`, `.bg-dark`, `.text-white`
* **Sizing:** `.w-25`, `.w-50`, `.h-100`
* **Overflow:** `.overflow-auto`, `.overflow-hidden`
* **Opacity:** `.opacity-0`, `.opacity-25`, `.opacity-100`

---

## ⚡ Лицензия

MIT License © Nizton

