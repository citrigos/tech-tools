# Tech Tools

## Terminal/IDE Setup (VSCode)

- [Code .](https://code.visualstudio.com/docs/setup/mac) - Shortcut from terminal
- [Spotify Manager](https://github.com/hnarayanan/shpotify) - Control Spotify from terminal
- [Bash --> Zsh](https://www.freecodecamp.org/news/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38/) - Nice way to set up terminal to using zsh. Here's what [mine](static/zsh-sample-terminal.md) currently looks like
  > Preview md in Vscode with: `Command + Shift + V` on the file

---

## New Project Setup

- Code Formatting
  - [Prettier](https://prettier.io/docs/en/install.html) - Code Formatter
  - [ESLint](https://eslint.org/docs/latest/use/getting-started) - Code Linter
- Pre-Commit Hooks
  - [Husky](https://typicode.github.io/husky/#/) and [Lint-staged](https://www.npmjs.com/package/lint-staged) - pre-commit hook managers
  - [Set up and sample package.json](./pre-commit-hooks.md) - for pre-commit hook to run prettier + eslint via husky and lint-staged
- Github Branch Protection
  - [Branch Protections](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule) - Set up rules to protect your branches. Sample set up [here](./branch-protections.md)

---

## Publishing Docs

- [Github Pages](https://pages.github.com/) - publish your static docs with github pages
- [Docsify](https://docsify.js.org/#/quickstart) - customize your github pages using docsify-cli (what this current document uses)
- [Streamlit](https://docs.streamlit.io/get-started/installation) - create and publish interactive data apps in Python

---

## Monorepos

- [Lerna](https://lerna.js.org/) - multi-javascript/typescript package manager. Can build new packages directly or pull from existing repo, bringing in all commit history

---

## Front-End

### Frameworks

- [React](https://react.dev/) - Meta-managed JS framework. Here's a [set up guide](./react-with-typescript.md) for React with Typescript.
- [Angular](https://angular.io/guide/setup-local) - Google-managed TS-based JS framework for mobile/web, using `ng ..` command
- [Vue.js](https://vuejs.org/) - Easiest to pick up (now on v3)

> React has a faster learning curve than Angular with less built-in, but Vue.js has the fastest ramp-up. React expects you to choose the additional libraries to add based on need, where Angular is "ready to go". React only uses JSX; Vue.js utilizes html. Here's is a [comparison](https://academind.com/tutorials/angular-vs-react-vs-vue-my-thoughts/).

### Creating Web Components

- [Open-WC](https://open-wc.org/) - Guides and tools to create Web Components
- [Lit](https://lit.dev/) - Base class for creating fast, lightweight web components that are framework-agnostic. Creates much lighter packages than a framework can (i.e. Angular, React)
- [Storybook](https://storybook.js.org/) - Open source tool for developing and demoing UI components

> [Sample set up](./lit-element-web-components.md) to create Lit Web Components using open-wc's init, introducing storybook demoing capabilities and mocha testing

### Responsive Web App Frameworks

- [MUI (Material-UI)](https://mui.com/material-ui/) - the most popular React UI component library with generous [customization](https://mui.com/material-ui/customization/theming/)
- [React Bootstrap](https://react-bootstrap.github.io/getting-started/introduction) - Extensive Component Library based on Bootstrap 5

> Here's a [comparison](https://uxplanet.org/material-ui-vs-bootstrap-a-detailed-comparison-8fc9151db5ed) of MUI vs. React Bootstrap

### Design

- [Material Design](https://material.io/design) - system of guidelines, components, and tools supporting best practices of UI design
- [Styled Components](https://styled-components.com/) - library for React and React Native that allows you to use CSS in modern JavaScript. Very quick set up, easy customization
- [coolors.io](https://coolors.co/) - Color scheme generator or explore trending palettes

> Here's a [list of beautiful websites](./website-designs.md) (imo)

---

## Data Science & Demography

### Data Science Tools

- [Streamlit](https://streamlit.io/) - Create and share interactive data apps in Python
- [Jupyter Notebook](https://jupyter.org/) - Interactive computing environment for data science
- [Google Colab](https://colab.research.google.com/) - Free Jupyter notebooks in the cloud with GPU support
- [Pandas](https://pandas.pydata.org/) - Data manipulation and analysis library for Python
- [Plotly](https://plotly.com/python/) - Interactive visualization library for Python, R, and JavaScript
- [Altair](https://altair-viz.github.io/) - Declarative statistical visualization library for Python
- [Dash](https://dash.plotly.com/) - Build analytical web applications with Python

### Data Platforms & Datasets

- [Kaggle](https://www.kaggle.com/) - Data science platform with datasets, notebooks, and competitions
- [Observable](https://observablehq.com/) - Collaborative data visualization notebooks using JavaScript
- [Tableau Public](https://public.tableau.com/) - Free data visualization tool for creating interactive dashboards

### Demography & Census Data

- [US Census API](https://www.census.gov/data/developers/data-sets.html) - Access US demographic and economic data
- [IPUMS](https://www.ipums.org/) - Integrated public use microdata series for demographic research
- [World Bank Data](https://data.worldbank.org/) - Global development and demographic data
- [tidycensus (R)](https://walker-data.com/tidycensus/) - R package for accessing and working with US Census data

---

## Testing

- [Mocha](https://mochajs.org/#installation) - JS-based tests organized in test suites (‘describe’-blocks) and test cases (‘it’-blocks)
- [Cucumber](https://cucumber.io/) - acceptance testing framework organized via Feature/Scenario tests and GIVEN/WHEN/THEN "steps". Very readable for non-programmers
- [Cypress](https://www.cypress.io/) - E2E testing written in JS typically used for frontend or UI testing with ability to fire REST requests via `cy.request`
