# canvas2image node module wrapper

Canvas2Image cannot be imported as a module and seems to no longer be maintained.

This repository contains the original code, a few changes and a export statement.

### Usage
```bash
npm install canvas2image-module-wrapper
```

```js
import canvas2image from "canvas2image-module-wrapper";

canvas2image.convertToPNG(canvas, 400, 400);
```
