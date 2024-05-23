[УКР](#webpack-rent-ukr) | [EN](#webpack-english) | [DEU](#webpack-german)

  <h1 id="webpack-ukr">webpack-react-template</h1>

<div>
    <a href="https://github.com/AmmelyStar/webpack-frontend-template">
        <img width="150" height="150" src="https://webpack.js.org/assets/icon-square-big.svg">
    </a>
  <a href="https://github.com/AmmelyStar/webpack-frontend-template">
        <img width="140" height="140" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/320px-React-icon.svg.png" alt="React logo">
    </a>
</div>
<br/>
<br/>


## Особливості збірки

* використовується [Babel](https://babeljs.io/) для підтримки сучасного JavaScript (ES6) у браузерах
* обираєте будь-який препроцесор SASS/SCSS
* ваш CSS і JS оптимізується і мініфікується
* встановлений пакет webpack-dev-server - вам не потрібно постійно перезавантажувати браузер
* [ESlint](https://eslint.org/) дозволить зробити ваш код приємним і чистим
* Використовує [React](https://react.dev/) для розробки інтерфейсу користувача.
* У проєкті використовуються наступні пакети залежностей:
  * **@babel/polyfill**: Забезпечує підтримку старих браузерів для нових JavaScript функцій.
  * **@pmmmwh/react-refresh-webpack-plugin**: Плагін для інтеграції React Refresh з Webpack, що забезпечує швидке оновлення компонентів без перезавантаження сторінки.
  * **@reduxjs/toolkit**: Набір інструментів для написання Redux логіки, що спрощує створення Redux store і написання редукторів.
  * **@testing-library/jest-dom**: Набір матчерів для використання з Jest, що дозволяє перевіряти стан DOM.
  * **@testing-library/react**: Бібліотека для тестування React компонентів, що зосереджується на взаємодії користувача.
  * **axios**: Бібліотека для виконання HTTP запитів.
  * **firebase**: SDK для роботи з Firebase, що забезпечує автентифікацію, базу даних, хостинг та інші сервіси.
  * **jest**: Фреймворк для тестування JavaScript коду.
  * **prop-types**: Бібліотека для перевірки типів props в React компонентах.
  * **react-dom**: Пакет для маніпуляцій з DOM для React додатків.
  * **react-hook-form**: Бібліотека для роботи з формами у React, що дозволяє легко обробляти введення користувачів і валідацію.
  * **react-modal**: Бібліотека для створення модальних вікон у React додатках.
  * **react-redux**: Бібліотека для інтеграції Redux з React.
  * **react-router-dom**: Бібліотека для маршрутизації у React додатках.
  * **redux**: Бібліотека для управління станом додатку.
  * **styled-components**: Бібліотека для стилізації React компонентів з використанням tagged template literals.
  * **yup**: Бібліотека для валідації схем об'єктів.

## Файлова структура

```
webpack-react-template
├── dist
├── src
│   ├── fonts
|   ├── img
|        ├── webpack-plain.svg
|        ├── webpack-plain.svg
│   ├── style
|        ├── fonts.css
|        ├── normalize.css
|        ├── style.css
│   ├── index.css
│   ├── index.js
│   ├── index.html
|   ├── App.js
│
├── .babelrc
├── .browserslistrc
├── .eslintrc.js
├── .gitignore
├──  .prettierrc
├──  jest.config.js
├──  package.json
├──  README.md
└── setupTests.js
```



## Команди

* ```npm run dev``` - збираємо development
* ```npm build-prod``` - збираємо production
* ```npm start``` - стежимо за файлами та відкриваємо у браузері


## Встановлення

Встановлюємо всі необхідні пакети з package.json

```bash
npm install
```

Запускаємо

```bash
npm start
```

## Зібрано

*  [@Anna Radchenko](https://github.com/AmmelyStar) 
*  [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anna--radchenko/)

  ________________________________________________________________________________________________________________________________


  <h1 id="webpack-english">webpack-react-template</h1>
  
<div>
     <a href="https://github.com/AmmelyStar/webpack-frontend-template">
        <img width="150" height="150" src="https://webpack.js.org/assets/icon-square-big.svg">
    </a>
  <a href="https://github.com/AmmelyStar/webpack-frontend-template">
        <img width="140" height="140" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/320px-React-icon.svg.png" alt="React logo">
    </a>
</div>
<br/>
<br/>

<h2>Build Features</h2>
<ul>
    <li>Uses <a href="https://babeljs.io/">Babel</a> to support modern JavaScript (ES6) in browsers</li>
    <li>Choose any SASS/SCSS preprocessor</li>
    <li>Your CSS and JS are optimized and minified</li>
    <li>Includes webpack-dev-server package - no need to constantly reload the browser</li>
    <li><a href="https://eslint.org/">ESlint</a> helps keep your code pleasant and clean</li>
    <li>Utilizes<a href="https://eslint.org/"> React</a> for developing the user interface</li>
</ul>

<h2>File Structure</h2>
<pre>
    webpack-react-template
├── dist
├── src
│   ├── fonts
|   ├── img
|        ├── webpack-plain.svg
|        ├── webpack-plain.svg
│   ├── style
|        ├── fonts.css
|        ├── normalize.css
|        ├── style.css
│   ├── index.css
│   ├── index.js
│   ├── index.html
|   ├── App.js
│
├── .babelrc
├── .browserslistrc
├── .eslintrc.js
├── .gitignore
├──  .prettierrc
├──  jest.config.js
├──  package.json
├──  README.md
└── setupTests.js
</pre>

<h2>Commands</h2>
<ul>
    <li><code>npm run dev</code> - build for development</li>
    <li><code>npm build-prod</code> - build for production</li>
    <li><code>npm start</code> - watch files and open in browser</li>
</ul>

<h2>Installation</h2>
<p>Install all necessary packages from <code>package.json</code></p>
<pre>
    npm install
</pre>
<p>Run</p>
<pre>
    npm start
</pre>

<h2>Contributors</h2>
<ul>
    <li><a href="https://github.com/AmmelyStar">@Anna Radchenko</a></li>
    <li><a href="https://www.linkedin.com/in/anna--radchenko/"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a></li>
</ul>

  ________________________________________________________________________________________________________________________________
  <h1 id="webpack-german">webpack-react-template</h1>

<div>
     <a href="https://github.com/AmmelyStar/webpack-frontend-template">
        <img width="150" height="150" src="https://webpack.js.org/assets/icon-square-big.svg">
    </a>
  <a href="https://github.com/AmmelyStar/webpack-frontend-template">
        <img width="140" height="140" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/320px-React-icon.svg.png" alt="React logo">
    </a>
</div>
<br/>
<br/>

<h2>Build Funktionen</h2>
<ul>
    <li>Verwendet <a href="https://babeljs.io/">Babel</a>, um modernes JavaScript (ES6) in Browsern zu unterstützen</li>
    <li>Wählen Sie einen beliebigen SASS/SCSS-Präprozessor aus</li>
    <li>Ihr CSS und JS werden optimiert und minifiziert</li>
    <li>Enthält das webpack-dev-server-Paket - kein ständiges Neuladen des Browsers erforderlich</li>
    <li><a href="https://eslint.org/">ESlint</a> sorgt dafür, dass Ihr Code angenehm und sauber bleibt</li>
      <li>Verwendet<a href="https://eslint.org/"> React</a> zur Entwicklung der Benutzeroberfläche</li>
</ul>

<h2>Dateistruktur</h2>
<pre>
webpack-react-template
├── dist
├── src
│   ├── fonts
|   ├── img
|        ├── webpack-plain.svg
|        ├── webpack-plain.svg
│   ├── style
|        ├── fonts.css
|        ├── normalize.css
|        ├── style.css
│   ├── index.css
│   ├── index.js
│   ├── index.html
|   ├── App.js
│
├── .babelrc
├── .browserslistrc
├── .eslintrc.js
├── .gitignore
├──  .prettierrc
├──  jest.config.js
├──  package.json
├──  README.md
└── setupTests.js
</pre>

<h2>Befehle</h2>
<ul>
    <li><code>npm run dev</code> - Bauen für Entwicklung</li>
    <li><code>npm build-prod</code> - Bauen für Produktion</li>
    <li><code>npm start</code> - Dateien beobachten und im Browser öffnen</li>
</ul>

<h2>Installation</h2>
<p>Installieren Sie alle notwendigen Pakete aus <code>package.json</code></p>
<pre>
    npm install
</pre>
<p>Ausführen</p>
<pre>
    npm start
</pre>

<h2>Mitarbeiter</h2>
<ul>
    <li><a href="https://github.com/AmmelyStar">@Anna Radchenko</a></li>
    <li><a href="https://www.linkedin.com/in/anna--radchenko/"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a></li>
</ul>


