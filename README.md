
## Live Demo

Check out the live demo of the project here:  
[Vercel Deployment Link]

## Screenshot

![Screenshot of the Project](https://github.com/AnandSharma916/FRONTEND-DEVELOPER-ASSESSMENT-Register-Karo-Homepage-By-Anand-Sharma/blob/e88fd81270dfa8ce8e7eb5e8fed01771b85ced33/Screenshot%202025-01-21%20210022.png1.png)
![Screenshot of the Project](https://github.com/AnandSharma916/FRONTEND-DEVELOPER-ASSESSMENT-Register-Karo-Homepage-By-Anand-Sharma/blob/main/Screenshot%202025-01-21%20210057.png2.png?raw=true)
![Screenshot of the Project](https://github.com/AnandSharma916/FRONTEND-DEVELOPER-ASSESSMENT-Register-Karo-Homepage-By-Anand-Sharma/blob/f04ca268a8fe89dda797b4d6cc3edb9e4e6fda74/Screenshot%202025-01-21%20210241.png3.png)
![Screenshot of the Project](https://github.com/AnandSharma916/FRONTEND-DEVELOPER-ASSESSMENT-Register-Karo-Homepage-By-Anand-Sharma/blob/f259247acaad2e664867dd792558fc2e08a1dfa4/Screenshot%202025-01-21%20210310.png4.png)
![Screenshot of the Project](https://github.com/AnandSharma916/FRONTEND-DEVELOPER-ASSESSMENT-Register-Karo-Homepage-By-Anand-Sharma/blob/178dc82c5a97aa837966159ecd89c4a33e747194/Screenshot%202025-01-21%20210328.png5.png)
![Screenshot of the Project]()




# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
