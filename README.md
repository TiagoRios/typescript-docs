# Typescript

Repositório para estudar e revisar typescript

## ES6 modules com JEST/TEST.

### Exemplo:

```js
export moduloNormal;
export default moduloDefault

import moduloDefault {moduloNormal} from 'path/arq.js';
```

### Instale o babel:

```bash
npm install --save-dev babel-jest
```

### Altere o package.json:

```json
//package.json
{
  "scripts": {
    "test": "jest"
  },
  "jest": {
    "transform": {
      "^.+\\.jsx?$": "babel-jest"
    }
  }
}
```

### Instale as pre-configurações do babel:

```bash
npm install @babel/preset-env --save-dev
```

### Crie o arquivo: ".babelrc" na raiz do projeto:

```json
{
  "presets": ["@babel/preset-env"]
}
```

## 📄 License

Apache [License](./LICENSE) Version 2.0."# typescript-docs" 
