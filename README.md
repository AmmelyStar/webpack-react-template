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
  * **[@babel/polyfill](https://babeljs.io/docs/en/babel-polyfill)**: Забезпечує підтримку старих браузерів для нових JavaScript функцій.
  * **[@pmmmwh/react-refresh-webpack-plugin](https://github.com/pmmmwh/react-refresh-webpack-plugin)**: Плагін для інтеграції React Refresh з Webpack, що забезпечує швидке оновлення компонентів без перезавантаження сторінки.
  * **[@reduxjs/toolkit](https://redux-toolkit.js.org/)**: Набір інструментів для написання Redux логіки, що спрощує створення Redux store і написання редукторів.
  * **[@testing-library/jest-dom](https://github.com/testing-library/jest-dom)**: Набір матчерів для використання з Jest, що дозволяє перевіряти стан DOM.
  * **[@testing-library/react](https://testing-library.com/docs/react-testing-library/intro/)**: Бібліотека для тестування React компонентів, що зосереджується на взаємодії користувача.
  * **[axios](https://axios-http.com/)**: Бібліотека для виконання HTTP запитів.
  * **[firebase](https://firebase.google.com/)**: SDK для роботи з Firebase, що забезпечує автентифікацію, базу даних, хостинг та інші сервіси.
  * **[jest](https://jestjs.io/)**: Фреймворк для тестування JavaScript коду.
  * **[prop-types](https://www.npmjs.com/package/prop-types)**: Бібліотека для перевірки типів props в React компонентах.
  * **[react-dom](https://react.dev/)**: Пакет для маніпуляцій з DOM для React додатків.
  * **[react-hook-form](https://react-hook-form.com/)**: Бібліотека для роботи з формами у React, що дозволяє легко обробляти введення користувачів і валідацію.
  * **[react-modal](https://github.com/reactjs/react-modal)**: Бібліотека для створення модальних вікон у React додатках.
  * **[react-redux](https://react-redux.js.org/)**: Бібліотека для інтеграції Redux з React.
  * **[react-router-dom](https://reactrouter.com/)**: Бібліотека для маршрутизації у React додатках.
  * **[redux](https://redux.js.org/)**: Бібліотека для управління станом додатку.
  * **[styled-components](https://styled-components.com/)**: Бібліотека для стилізації React компонентів з використанням tagged template literals.
  * **[yup](https://github.com/jquense/yup)**: Бібліотека для валідації схем об'єктів.

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
    * Uses [React](https://react.dev/) for user interface development
* The project uses the following dependency packages:
  * **[@babel/polyfill](https://babeljs.io/docs/en/babel-polyfill)**: Ensures support for new JavaScript features in older browsers.
  * **[@pmmmwh/react-refresh-webpack-plugin](https://github.com/pmmmwh/react-refresh-webpack-plugin)**: Plugin for integrating React Refresh with Webpack, providing fast component updates without page reloads.
  * **[@reduxjs/toolkit](https://redux-toolkit.js.org/)**: Toolkit for writing Redux logic, simplifying the creation of Redux store and writing reducers.
  * **[@testing-library/jest-dom](https://github.com/testing-library/jest-dom)**: Set of matchers for use with Jest to check the state of the DOM.
  * **[@testing-library/react](https://testing-library.com/docs/react-testing-library/intro/)**: Library for testing React components, focusing on user interactions.
  * **[axios](https://axios-http.com/)**: Library for making HTTP requests.
  * **[firebase](https://firebase.google.com/)**: SDK for working with Firebase, providing authentication, database, hosting, and other services.
  * **[jest](https://jestjs.io/)**: Framework for testing JavaScript code.
  * **[prop-types](https://www.npmjs.com/package/prop-types)**: Library for type-checking props in React components.
  * **[react-dom](https://react.dev/)**: Package for manipulating the DOM for React applications.
  * **[react-hook-form](https://react-hook-form.com/)**: Library for working with forms in React, making it easy to handle user input and validation.
  * **[react-modal](https://github.com/reactjs/react-modal)**: Library for creating modal windows in React applications.
  * **[react-redux](https://react-redux.js.org/)**: Library for integrating Redux with React.
  * **[react-router-dom](https://reactrouter.com/)**: Library for routing in React applications.
  * **[redux](https://redux.js.org/)**: Library for managing application state.
  * **[styled-components](https://styled-components.com/)**: Library for styling React components using tagged template literals.
  * **[yup](https://github.com/jquense/yup)**: Library for object schema validation.
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
      * Das Projekt verwendet die folgenden Abhängigkeitspakete:
  * **[@reduxjs/toolkit](https://redux-toolkit.js.org/)**: Ein Toolkit zum Schreiben von Redux-Logik, das die Erstellung des Redux-Stores und das Schreiben von Reduzierern vereinfacht.
  * **[@testing-library/jest-dom](https://github.com/testing-library/jest-dom)**: Ein Satz Matcher für die Verwendung mit Jest, mit dem der Zustand des DOM überprüft werden kann.
  * **[@testing-library/react](https://testing-library.com/docs/react-testing-library/intro/)**: Eine Bibliothek zum Testen von React-Komponenten, die sich auf die Benutzerinteraktion konzentriert.
  * **[axios](https://axios-http.com/)**: Eine Bibliothek für das Ausführen von HTTP-Anfragen.
  * **[firebase](https://firebase.google.com/)**: SDK für die Arbeit mit Firebase, das Authentifizierung, Datenbank, Hosting und andere Dienste bereitstellt.
  * **[jest](https://jestjs.io/)**: Framework zum Testen von JavaScript-Code.
  * **[prop-types](https://www.npmjs.com/package/prop-types)**: Eine Bibliothek zur Überprüfung von Prop-Typen in React-Komponenten.
  * **[react-dom](https://react.dev/)**: Ein Paket zum Manipulieren des DOM für React-Anwendungen.
  * **[react-hook-form](https://react-hook-form.com/)**: Eine Bibliothek zur Arbeit mit Formularen in React, die die Verarbeitung von Benutzereingaben und die Validierung vereinfacht.
  * **[react-modal](https://github.com/reactjs/react-modal)**: Eine Bibliothek zur Erstellung von Modalansichten in React-Anwendungen.
  * **[react-redux](https://react-redux.js.org/)**: Eine Bibliothek zur Integration von Redux mit React.
  * **[react-router-dom](https://reactrouter.com/)**: Eine Bibliothek zur Routenführung in React-Anwendungen.
  * **[redux](https://redux.js.org/)**: Eine Bibliothek zur Verwaltung des Anwendungsstatus.
  * **[styled-components](https://styled-components.com/)**: Eine Bibliothek zur Gestaltung von React-Komponenten unter Verwendung von tagged template literals.
  * **[yup](https://github.com/jquense/yup)**: Eine Bibliothek zur Validierung von Objektschemata.
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


