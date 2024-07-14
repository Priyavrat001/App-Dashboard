# App Dashboard UI Dependencies

These are the key dependencies used to build the UI for our app dashboard:

- **chart.js:** A popular library for creating interactive and customizable charts.
- **react:** Core library for building user interfaces in React applications.
- **react-chartjs-2:** React wrapper for Chart.js, providing easy integration of charts into React components.
- **react-dom:** Provides DOM-specific methods that can be used at the top level of your application.
- **react-icons:** Provides a set of scalable icons for React applications, enhancing visual representation.
- **react-router-dom:** Essential for declarative routing in single-page applications built with React.
- **react-table:** A lightweight, fast, and extendable data table library for React, enabling efficient data presentation and manipulation.
- **sass:** A mature, stable, and powerful CSS extension language that helps keep stylesheets organized and maintainable.

These dependencies collectively contribute to the functionality, user experience, and visual appeal of our app dashboard.



# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
