# NPM package starter kit with VITE + REACT

Welcome to my NPM Package starter kit! 🚀 This kit is designed to help you skip the repetitive setup process and dive straight into building your library and publish it in NPM registery. 

## Installation

1. **Clone the repository:**

```bash
   git clone https://github.com/bijayrauniyar0/npm-starter-kit-vite.git
   cd npm-starter-kit-vite
```

2. **Install dependencies:**
```bash
    npm install

```

## Creating Library

**1.** Create a file with .tsx extension in Components
**2.** Build a component in the corresponding file
**3.** Import the file in index.ts and export it again.

### Example to export 

```jsx

export {default as DemoComponent} from './Components/index';

```

## Publishing

#### Build

```bash
npm run build

```
#### NPM Login

```bash
npm login

```

#### Publishing

```bash 
npm publish

```

## Contributing
If you have suggestions or improvements, feel free to open an issue or submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.