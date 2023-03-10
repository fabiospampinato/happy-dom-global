# Happy DOM Global

Make Node a browser-like environment, by using [Happy DOM](https://github.com/capricorn86/happy-dom).

## Install

```sh
npm install --save happy-dom-global
```

## Usage

Simply importing it will register browser-like globals:

```ts
import 'happy-dom-global';

console.log ( typeof globalThis.window ); // => 'object'
console.log ( typeof globalThis.document ); // => 'object'
console.log ( typeof globalThis.location ); // => 'object'
```

## License

MIT © Fabio Spampinato
