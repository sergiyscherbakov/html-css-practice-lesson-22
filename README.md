# HTML/CSS Practice - Basic Web Pages

## Розробник
**Сергій Щербаков**
**Telegram:** [@s_help_2010](https://t.me/s_help_2010)

## Опис проекту

Цей проект містить два навчальних завдання з HTML/CSS, які демонструють базові навички верстки веб-сторінок:

**Завдання 1**: Проста HTML-сторінка з використанням всіх основних елементів
**Завдання 2**: Складніша сторінка з таблицями, списками, формами та CSS стилізацією

Кожне завдання має дві версії:
- **Базова версія** - чистий HTML/CSS
- **Bootstrap версія** - з використанням Bootstrap framework

## Структура проекту

```
22/
├── Index-1.html               # Завдання 1 (базова версія)
├── Index-1-bootstrap.html     # Завдання 1 (Bootstrap версія)
├── Index-2.html               # Завдання 2 (базова версія з CSS)
├── Index-2- bootStrip.html    # Завдання 2 (Bootstrap версія)
├── H22/                       # Додаткові файли
│   ├── Index-1.html
│   ├── Index-1-bootstrap.html
│   ├── Index-2.html
│   ├── Index-2- bootStrip.html
│   └── Video.txt
├── Посилання.txt              # Корисні посилання та умови завдань
├── Video.txt                  # Посилання на відео
├── .gitignore                 # Виключення відео файлів
└── README.md                  # Ця документація
```

## Завдання 1: Базова HTML структура

### Опис завдання

Створити просту HTML-сторінку з виконанням наступних умов:

- Використати всі теги заголовків h1-h6
- Створити нумерований список
- Створити ненумерований список із посиланнями
- Виділити слова всередині речення жирним текстом та курсивом
- Створити 2-3 параграфи

### Файли

- `Index-1.html` - базова версія
- `Index-1-bootstrap.html` - версія з Bootstrap

### Основні елементи (Index-1.html)

#### 1. Заголовки h1-h6

```html
<h1>Hello, World!</h1>
<h2>This is a Heading 2</h2>
<h3>This is a Heading 3</h3>
<h4>This is a Heading 4</h4>
<h5>This is a Heading 5</h5>
<h6>This is a Heading 6</h6>
```

#### 2. Нумерований список

```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

#### 3. Ненумерований список з посиланнями

```html
<ul>
    <li><a href="https://www.google.com">Google</a></li>
    <li><a href="https://www.wikipedia.org">Wikipedia</a></li>
    <li><a href="https://www.youtube.com">YouTube</a></li>
</ul>
```

#### 4. Форматування тексту

```html
<p>This sentence has <strong>bold text</strong> and <em>italic text</em>.</p>
```

### Відмінності Bootstrap версії

Bootstrap версія (`Index-1-bootstrap.html`) включає:

- Підключення Bootstrap CSS через CDN
- Використання Bootstrap класів для відступів (`mb-3`, `mb-4`)
- Клас `list-unstyled` для списку без маркерів
- Підключення jQuery, Popper.js, Bootstrap JS

## Завдання 2: Таблиці, списки та форми

### Опис завдання

Створити складнішу HTML-сторінку з:

**Таблиця**: Інформація про фрукти (назва, калорійність, колір, країна походження)
**Списки**: Три різні типи списків (ненумерований, нумерований, маркерований/description list)
**Форма**: Форма зворотнього зв'язку з полями імені, email, теми та повідомлення

### Файли

- `Index-2.html` - базова версія з custom CSS
- `Index-2- bootStrip.html` - версія з Bootstrap

### Основні елементи (Index-2.html)

#### 1. Таблиця фруктів

```html
<table border="1">
    <tr>
        <th>Fruit Name</th>
        <th>Calories</th>
        <th>Color</th>
        <th>Country of Origin</th>
    </tr>
    <tr>
        <td>Apple</td>
        <td>95</td>
        <td>Red</td>
        <td>Kazakhstan</td>
    </tr>
    <tr>
        <td>Banana</td>
        <td>89</td>
        <td>Yellow</td>
        <td>India</td>
    </tr>
    <tr>
        <td>Orange</td>
        <td>47</td>
        <td>Orange</td>
        <td>Brazil</td>
    </tr>
</table>
```

#### 2. Ненумерований список (Unordered List)

```html
<ul>
    <li>About Us</li>
    <li>Products</li>
    <li>Contact</li>
</ul>
```

#### 3. Нумерований список (Ordered List)

```html
<ol>
    <li>Select a product</li>
    <li>Add to cart</li>
    <li>Proceed to checkout</li>
    <li>Enter payment information</li>
    <li>Confirm order</li>
</ol>
```

#### 4. Description List (Список описів)

```html
<dl>
    <dt>HTML</dt>
    <dd>Hypertext Markup Language</dd>
    <dt>CSS</dt>
    <dd>Cascading Style Sheets</dd>
    <dt>JavaScript</dt>
    <dd>Programming language for the web</dd>
</dl>
```

#### 5. Форма зворотнього зв'язку

```html
<form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name"><br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>

    <label for="subject">Subject:</label>
    <select id="subject" name="subject">
        <option value="general">General Inquiry</option>
        <option value="support">Support</option>
        <option value="sales">Sales</option>
    </select><br><br>

    <label for="message">Message:</label>
    <textarea id="message" name="message"></textarea><br><br>

    <input type="submit" value="Submit">
</form>
```

### CSS Стилізація

`Index-2.html` включає вбудовані CSS стилі:

- Сірий фон сторінки (`#f5f5f5`)
- Стилізована таблиця з темними заголовками
- Форма з тінню та заокругленими кутами
- Responsive інпути (width: 100%)
- Hover ефект на кнопці submit

## Як використовувати

### Крок 1: Завантаження файлів

Клонуйте репозиторій або завантажте файли:

```bash
git clone https://github.com/sergiyscherbakov/html-css-practice.git
cd html-css-practice
```

### Крок 2: Відкриття файлів

**Спосіб 1**: Подвійний клік на HTML файлі

Просто клікніть двічі на будь-якому `.html` файлі, і він відкриється у вашому браузері за замовчуванням.

**Спосіб 2**: Відкрити через браузер

1. Відкрийте браузер (Chrome, Firefox, Edge, Safari)
2. Натисніть `Ctrl+O` (Windows/Linux) або `Cmd+O` (Mac)
3. Виберіть потрібний HTML файл

**Спосіб 3**: Drag & Drop

Перетягніть HTML файл у вікно браузера.

### Крок 3: Порівняння версій

Відкрийте базову та Bootstrap версію в різних вкладках браузера, щоб побачити відмінності:

- `Index-1.html` vs `Index-1-bootstrap.html`
- `Index-2.html` vs `Index-2- bootStrip.html`

### Крок 4: Перегляд вихідного коду

**У браузері**:
- Натисніть правою кнопкою миші → "View Page Source" / "Переглянути код сторінки"
- Або натисніть `Ctrl+U` (Windows/Linux) або `Cmd+Option+U` (Mac)

**У текстовому редакторі**:
- Відкрийте файли в VS Code, Sublime Text, Notepad++ тощо

## Інструменти розробника

### Відкрити DevTools у браузері

- **Chrome/Edge**: `F12` або `Ctrl+Shift+I` (Windows) / `Cmd+Option+I` (Mac)
- **Firefox**: `F12` або `Ctrl+Shift+I` (Windows) / `Cmd+Option+I` (Mac)

### Що можна робити в DevTools

1. **Elements/Inspector** - переглядати та редагувати HTML/CSS в реальному часі
2. **Console** - виконувати JavaScript код
3. **Network** - моніторити завантаження ресурсів
4. **Responsive Design Mode** - тестувати на різних розмірах екрану

## Корисні посилання

### CSS практика (ігри)

- [CSS Grid Garden](https://cssgridgarden.com/) - вивчення CSS Grid через гру
- [Flexbox Froggy](https://flexboxfroggy.com/) - вивчення Flexbox через гру
- [CSS Float Examples](https://www.w3schools.com/css/css_float_examples.asp)

### HTML довідка

- [HTML Input Types](https://www.w3schools.com/html/html_form_input_types.asp)
- [HTML Input Form Attributes](https://www.w3schools.com/html/html_form_attributes_form.asp)
- [HTML Table Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)
- [HTML Forms](https://www.w3schools.com/html/html_forms.asp)

### Bootstrap

- [Bootstrap 4 Documentation](https://getbootstrap.com/docs/4.0/getting-started/introduction/)

## Модифікація та експерименти

### Змінити вміст

Відредагуйте HTML файли у текстовому редакторі:

1. Змініть текст заголовків
2. Додайте нові елементи списків
3. Додайте нові рядки в таблицю
4. Змініть стилі CSS

### Додати нові елементи

Спробуйте додати:

- **Зображення**: `<img src="image.jpg" alt="Description">`
- **Відео**: `<video>` або embed з YouTube
- **Посилання**: `<a href="url">Link text</a>`
- **Кнопки**: `<button>Click me</button>`

### Експериментувати з CSS

У файлі `Index-2.html` змініть CSS стилі:

```css
/* Змініть колір фону */
body {
    background-color: #your-color;
}

/* Змініть колір кнопки */
input[type=submit] {
    background-color: #your-color;
}

/* Додайте анімацію */
button:hover {
    transform: scale(1.1);
    transition: 0.3s;
}
```

## Таблиця HTML елементів

| Елемент | Опис | Приклад використання |
|---------|------|----------------------|
| `<h1>` - `<h6>` | Заголовки | `<h1>Main Title</h1>` |
| `<p>` | Параграф | `<p>Text here</p>` |
| `<strong>` | Жирний текст | `<strong>Bold</strong>` |
| `<em>` | Курсив | `<em>Italic</em>` |
| `<ul>` | Ненумерований список | `<ul><li>Item</li></ul>` |
| `<ol>` | Нумерований список | `<ol><li>Item</li></ol>` |
| `<dl>` | Description list | `<dl><dt>Term</dt><dd>Desc</dd></dl>` |
| `<table>` | Таблиця | `<table><tr><td>Cell</td></tr></table>` |
| `<form>` | Форма | `<form>...</form>` |
| `<input>` | Поле вводу | `<input type="text">` |
| `<textarea>` | Текстове поле | `<textarea></textarea>` |
| `<select>` | Випадаючий список | `<select><option>...</option></select>` |

## Типові HTML теги для форм

| Тип input | Опис | Приклад |
|-----------|------|---------|
| `text` | Текстове поле | `<input type="text">` |
| `email` | Email поле | `<input type="email">` |
| `password` | Поле паролю | `<input type="password">` |
| `number` | Числове поле | `<input type="number">` |
| `date` | Дата | `<input type="date">` |
| `checkbox` | Чекбокс | `<input type="checkbox">` |
| `radio` | Радіо кнопка | `<input type="radio">` |
| `submit` | Кнопка відправки | `<input type="submit">` |

## Рекомендації

1. **Валідація HTML**: Перевірте свій код на [W3C Validator](https://validator.w3.org/)
2. **Семантична верстка**: Використовуйте правильні теги для правильних цілей
3. **Доступність**: Завжди додавайте `alt` до зображень та `label` до полів форм
4. **Responsive design**: Тестуйте на різних розмірах екранів
5. **Cross-browser testing**: Перевіряйте в різних браузерах

## Наступні кроки

1. Вивчити **CSS Grid** та **Flexbox** для layout
2. Додати **JavaScript** для інтерактивності
3. Вивчити **Responsive Design** та медіа-запити
4. Дізнатися про **CSS препроцесори** (SASS, LESS)
5. Експериментувати з **CSS анімаціями**

## Контакти

**Розробник:** Сергій Щербаков
**Telegram:** [@s_help_2010](https://t.me/s_help_2010)

## Відео демонстрація

Перегляньте відео на YouTube: https://youtu.be/kIYl2Qn2Glg

## Ліцензія

MIT
