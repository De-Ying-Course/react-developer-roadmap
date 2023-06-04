# React Developer Roadmap

> Roadmap to becoming a React developer in 2023:

Below you can find a chart demonstrating the paths that you can take and the libraries that you would want to learn to become a React developer. I made this chart as a tip for everyone who asks me, "What should I learn next as a React developer?"

## Disclaimer

> The purpose of this roadmap is to give you an idea about the landscape. The road map will guide you if you are confused about what to learn next, rather than encouraging you to pick what is hip and trendy. You should grow some understanding of why one tool would be better suited for some cases than the other and remember hip and trendy does not always mean best suited for the job

## Roadmap

![Roadmap](./roadmap.png)

## Resources

<details>
    <summary><b>Basics</b></summary>
    <details>
      <summary><b>HTML</b></summary>
      <ul>
        <li>Learn the basics of HTML</li>
        <li>Make a few pages as an exercise</li>
      </ul>
    </details>
    <details>
      <summary><b>CSS</b></summary>
      <ul>
        <li>Learn the basics of CSS</li>
        <li>Style pages from previous step</li>
        <li>Build a page with grid and flexbox</li>
      </ul>
    </details>
    <details>
        <summary><b>JS Basics</b></summary>
        <ul>
          <li>Get familiar with the syntax</li>
          <li>Learn basic operations on DOM</li>
          <li>Learn mechanisms typical for JS (Hoisting, Event Bubbling, Prototyping)</li>
          <li>Make some AJAX (XHR) calls</li>
          <li>Learn new features (ECMA Script 6+)</li>
          <li>Additionally, get familiar with the jQuery library</li>
        </ul>
      </details>
</details>

<details>
    <summary><b>General Development Skills</b></summary>
    <p>1. Learn GIT, create a few repositories on GitHub, share your code with other people</p>
    <p>2. Know HTTP(S) protocol, request methods (GET, POST, PUT, PATCH, DELETE, OPTIONS)</p>
    <p>3. Don't be afraid of using Google, [Power Searching with Google](http://www.powersearchingwithgoogle.com/)</p>
    <p>4. Get familiar with terminal, configure your shell (bash, zsh, fish)</p>
    <p>Read a few books about algorithms and data structures</p>
    <p>Read a few books about design patterns</p>
</details>

<details>
    <summary><b>Learn React on [official website](https://reactjs.org/tutorial/tutorial.html) or complete some [courses](https://egghead.io/courses/the-beginner-s-guide-to-react)</b></summary>
</details>

<details>
    <summary><b>Get familiar with tools that you will be using</b></summary>
    <details>
      <summary><b>Package Managers</b></summary>
      <ul>
        <li>[npm](https://www.npmjs.com/)</li>
        <li>[yarn](https://yarnpkg.com/lang/en/)</li>
        <li>[pnpm](https://pnpm.js.org/)</li>
      </ul>
    </details>
    <details>
      <summary><b>Task Runners</b></summary>
      <ul>
        <li>[npm scripts](https://docs.npmjs.com/misc/scripts)</li>
        <li>[gulp](https://gulpjs.com/)</li>
      </ul>
    </details>
    <details>
        <summary><b>...s</b></summary>
        <ul>
          <li>[Webpack](https://webpack.js.org/)</li>
          <li>[Rollup](https://rollupjs.org/guide/en)</li>
          <li>[Parcel](https://parceljs.org/)</li>
        </ul>
      </details>
</details>

<details>
    <summary><b>Styling</b></summary>
    <details>
      <summary><b>CSS Preprocessor</b></summary>
      <ul>
        <li>[Sass/CSS](https://sass-lang.com/)</li>
        <li>[PostCSS](https://postcss.org/)</li>
        <li>[Less](http://lesscss.org/)</li>
        <li>[Stylus](http://stylus-lang.com/)</li>
      </ul>
    </details>
    <details>
      <summary><b>CSS Frameworks</b></summary>
      <ul>
        <li>[Bootstrap](https://getbootstrap.com/)</li>
        <li>[Materialize](https://materializecss.com/), [Material UI](https://material-ui.com/), [Material Design Lite](https://getmdl.io/)</li>
        <li>[Bulma](https://bulma.io/)</li>
        <li>[Semantic UI](https://semantic-ui.com/)</li>
      </ul>
    </details>
    <details>
        <summary><b>CSS Architecture</b></summary>
        <ul>
          <li>[BEM](http://getbem.com/)</li>
          <li>[CSS Modules](https://github.com/css-modules/css-modules)</li>
          <li>[Atomic](https://acss.io/)</li>
          <li>[OOCSS](https://github.com/stubbornella/oocss/wiki)</li>
          <li>[SMACSS](https://smacss.com/)</li>
          <li>[SUITCSS](https://suitcss.github.io/)</li>
        </ul>
      </details>
       <details>
        <summary><b>CSS in JS</b></summary>
        <ul>
          <li>[Styled Components](https://www.styled-components.com/)</li>
          <li>[Radium](https://formidable.com/open-source/radium/)</li>
          <li>[Emotion](https://emotion.sh/)</li>
          <li>[JSS](http://cssinjs.org/)</li>
          <li>[Aphrodite](https://github.com/Khan/aphrodite)</li>
        </ul>
      </details>
</details>

<details>
    <summary><b>State Management</b></summary>
    <details>
      <summary>[Component State](https://reactjs.org/docs/faq-state.html)/[Context API](https://reactjs.org/docs/context.html)</summary>
    </details>
    <details>
        <summary><b>[Redux](https://redux.js.org/)</b></summary>
        <details>
            <summary><b>Async actions (Side Effects)</b></summary>
            <ul>
                <li>[Redux Thunk](https://github.com/reduxjs/redux-thunk)</li>
                <li>[Redux Better Promise](https://github.com/Lukasz-pluszczewski/redux-better-promise)</li>
                <li>[Redux Saga](https://redux-saga.js.org/)</li>
                <li>[Redux Observable](https://redux-observable.js.org)</li>
            </ul>
        </details>
        <details>
            <summary><b>Helpers</b></summary>
            <ul>
                <li>[Rematch](https://rematch.gitbooks.io/rematch/)</li>
                <li>[Reselect](https://github.com/reduxjs/reselect)</li>
            </ul>
        </details>
        <details>
            <summary><b>Data persistence</b></summary>
            <ul>
                <li>[Redux Persist](https://github.com/rt2zz/redux-persist)</li>
                <li>[Redux Phoenix](https://github.com/adam-golab/redux-phoenix)</li>
            </ul>
        </details>
         <details>
            <summary><b>[Redux Form](https://redux-form.com)</b></summary>
        </details>
    </details>
    <details>
        <summary><b>[MobX](https://mobx.js.org/)</b></summary>
      </details>
</details>

<details>
    <summary><b>Type Checkers</b></summary>
    <p>[PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html)</p>
    <p>[TypeScript](https://www.typescriptlang.org/)</p>
    <p>[Flow](https://flow.org/en/)</p>
</details>

<details>
    <summary><b>Form Helpers</b></summary>
    <p>[Redux Form](https://redux-form.com)</p>
    <p>[Formik](https://github.com/jaredpalmer/formik)</p>
    <p>[Formsy](https://github.com/formsy/formsy-react)</p>
    <p>[Final Form](https://github.com/final-form/final-form)</p>
</details>

<details>
    <summary><b>Routing</b></summary>
    <p>[React-Router](https://reacttraining.com/react-router/)</p>
    <p>[Router5](https://router5.js.org/)</p>
    <p>[Redux-First Router](https://github.com/faceyspacey/redux-first-router)</p>
    <p>[Reach Router](https://reach.tech/router/)</p>
</details>

<details>
    <summary><b>API Clients</b></summary>
    <details>
      <summary><b>REST</b></summary>
      <ul>
        <li>[Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)</li>
        <li>[SuperAgent](https://visionmedia.github.io/superagent/)</li>
        <li>[axios](https://github.com/axios/axios)</li>
      </ul>
    </details>
    <details>
      <summary><b>GraphQL</b></summary>
      <ul>
        <li>[Apollo](https://www.apollographql.com/docs/react/)</li>
        <li>[Relay](https://facebook.github.io/relay/)</li>
        <li>[urql](https://github.com/FormidableLabs/urql)</li>
      </ul>
    </details>
</details>

<details>
    <summary><b>Utility Libraries</b></summary>
    <p>[Lodash](https://lodash.com/)</p>
    <p>[Moment](https://momentjs.com/)</p>
    <p>[classnames](https://github.com/JedWatson/classnames)</p>
    <p>[Numeral](http://numeraljs.com/)</p>
    <p>[RxJS](http://reactivex.io/)</p>
    <p>[ImmutableJS](https://facebook.github.io/immutable-js/)</p>
    <p>[Ramda](https://ramdajs.com/)</p>
</details>

<details>
    <summary><b>Testing</b></summary>
    <details>
      <summary><b>Unit Testing</b></summary>
      <ul>
        <li>[Jest](https://facebook.github.io/jest/)</li>
        <li>[Enzyme](http://airbnb.io/enzyme/)</li>
        <li>[Sinon](http://sinonjs.org/)</li>
        <li>[Mocha](https://mochajs.org/)</li>
        <li>[Chai](http://www.chaijs.com/)</li>
        <li>[AVA](https://github.com/avajs/ava)</li>
        <li>[Tape](https://github.com/substack/tape)</li>
      </ul>
    </details>
    <details>
      <summary><b>End to End Testing</b></summary>
      <ul>
        <li>[Selenium](https://www.seleniumhq.org/), [Webdriver](http://webdriver.io/)</li>
        <li>[Cypress](https://cypress.io/)</li>
        <li>[Puppeteer](https://pptr.dev/)</li>
        <li>[Cucumber.js](https://github.com/cucumber/cucumber-js)</li>
        <li>[Nightwatch.js](http://nightwatchjs.org/)</li>
      </ul>
    </details>
    <details>
      <summary><b>Integration Testing</b></summary>
    </details>
</details>

<details>
    <summary><b>Internationalization</b></summary>
    <p>[React Intl](https://github.com/yahoo/react-intl)</p>
    <p>[React i18next](https://react.i18next.com/)</p>
</details>

<details>
    <summary><b>Server Side Rendering</b></summary>
    <p>[Next.js](https://nextjs.org/)</p>
    <p>[After.js](https://github.com/jaredpalmer/after.js)</p>
    <p>[Rogue](https://github.com/alidcastano/rogue.js)</p>
</details>

<details>
    <summary><b>Static Site Generator</b></summary>
    <p>[Gatsby](https://www.gatsbyjs.org/)</p>
</details>

<details>
    <summary><b>Backend Framework Integration</b></summary>
    <p>[React on Rails](https://shakacode.gitbooks.io/react-on-rails/content/)</p>
</details>

<details>
    <summary><b>Mobile</b></summary>
    <p>[React Native](https://facebook.github.io/react-native/)</p>
    <p>[Cordova](https://cordova.apache.org/)/[Phonegap](https://phonegap.com/)</p>
</details>

<details>
    <summary><b>Desktop</b></summary>
    <p>[Proton Native](https://proton-native.js.org/)</p>
    <p>[Electron](https://electronjs.org/)</p>
    <p>[React Native Windows](https://github.com/Microsoft/react-native-windows)</p>
</details>

<details>
    <summary><b>Virtual Reality</b></summary>
    <p>[React 360](https://facebook.github.io/react-360/)</p>
</details>

## Wrap Up

If you think the roadmap can be improved, please do open a PR with any updates and submit any issues. Also, I will continue to improve this, so you might want to star this repository to revisit.

## Contribution

The roadmap is built using [Draw.io](https://www.draw.io/). Project file can be found at `/src` directory. To modify it, open draw.io, click **Open Existing Diagram** and choose `xml` file with project. It will open the roadmap for you. Update it, upload and update the images in readme and create a PR (export as png).

- Open a pull request with improvements
- Discuss ideas in issues
- Spread the word

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
