## Лабораторная работа №5. Введение в HTML
**ФИО:** Ханов Владислав Вячеславович
**Группа**: ИСП-231
**Дата:** 30.01.2026
## Описание работы
В данной лабораторной работе мы создаём проект для изучения основ HTML.
Vы настраиваем рабочую директорию, создаём базовые файлы, подключаем Git и GitHub, а также
подготавливаем HTML-файл для последующего изучения структуры веб-страницы.

## Структура проекта
* index.html — основной HTML-файл
* index2.html — дополнительный HTML-файл
* about.html — HTML-файл с информацией обо мне
* webpageCard.html  — HTML-файл с визиткой студента
* README.md — описание лабораторной работы
* **img/** — скриншоты

## Теги в HTML
Структура парного тега:
**<тег>тело</тег>**

*Пример:*
```html
<h1>Это заголовок</h1>
```

## Базовые HTML-теги
### Примеры:
```html
<h2>Заголовок</h2>
<p>Абзац текста</p>
<strong>Жирный</strong>
<em>Курсив</em>
<hr>
<a href="https://example.com">Ссылка</a>
<img src="example.jpg" alt="Описание">
Таблица
<table border="1">
      <tr>
        <th>ФИО</th>
        <th>Группа</th>
        <th>Любимый язык программирования</th>
        <th>Город</th>
      </tr>
      <tr>
        <th>Ханов Владислав Вячеславович</th>
        <th>ИСП-231</th>
        <th>С#</th>
        <th>Волжский</th>
      </tr>
    </table>

Форма 
<form>
      <input type="text" placeholder="Введите имя" />
      <input type="email" placeholder="Введите email" />
      <input type="password" placeholder="Введите пароль" />
      <input type="number" placeholder="Возраст" />
      <input type="date" />
      <input type="checkbox" /> Я согласен <input type="radio" name="gender" /> Мужчина <input type="radio" name="gender" /> Женщина

      <textarea placeholder="Введите сообщение" rows="4"></textarea>

      <select>
        <option>ИСП-231</option>
        <option>ИСП-232</option>
        <option>ИСП-233</option>
      </select>

      <button type="submit">Отправить</button>
      <button type="reset">Очистить</button>
      <label for="username">Ваше имя:</label>
      <input id="username" type="text" />
    </form>

Списки
<ul>
    <li>
        Пункт 1
        <ol>
          <li>Вложенный 1</li>
          <li>Вложенный 2</li>
        </ol>
    </li>
</ul>

    <h2>Мои списки</h2>
    <p><strong>Мои любимые фильмы:</strong></p>
    <ol>
      <li>Борат</li>
      <li>Джей и молчаливый Боб</li>
      <li>Мажор</li>
      <li>Буратино</li>
      <li>Чебурашка</li>
    </ol>
    <p><strong>Мои хобби:</strong></p>
    <ul>
      <li>Рыбалка</li>
      <li>Борьба</li>
    </ul>

    <p><strong>Вложенный список:</strong></p>
    <ul>
      <li>
        Как приручить дракона?:
        <ol>
          <li>Поймать дракона</li>
          <li>Приручить дракона</li>
        </ol>
      </li>
    </ul>
```