# mdi-core

Node module for generating Material Design icons.

All icons are based on the [@mdi/svg][1] package, which is what [materialdesignicons.com][2] uses.


## Installation

```bash
$ npm install --save mdi-core
```


## Usage

```js
const mdi = require('mdi-core');
const options = {...};

mdi(options);
```


## Options

- `names` (`Array`): The names of the icons to generate. Please refer to [`@mdi/svg`'s available icons][3] for a complete list of icons that can be generated.
- `size` (`Number`): The size of the icon to generate, in pixels. Defaults to `24px`.
- `padding` (`Number`): The padding on the icon to generate, in pixels. Defaults to `0px`.
- `radius` (`Number`): The border radius of the icon to generate, in pixels. Defaults to `0px`.
- `foreground` (`String`): The foreground color of the icon to generate. Defaults to `#333`.
- `background` (`String`): The background color of the icon to generate. Defaults to `transparent`.
- `output` (`String`): The output directory where the generated icons will be written to. Defaults to the current directory `.`.


## License

MIT License


[1]: https://github.com/Templarian/MaterialDesign-SVG
[2]: https://materialdesignicons.com/
[3]: https://github.com/Templarian/MaterialDesign-SVG/tree/master/svg
