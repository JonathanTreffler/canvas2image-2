# canvas2image node module wrapper

Canvas2Image cannot be imported as a module and seems to no longer be maintained.
This repository contains the canvas to image code + a export default ...

### Usage
```bash
npm install canvas2image-module-wrapper
```

```js
import canvas2image from "canvas2image-module-wrapper";

canvas2image.convertToPNG(canvas, 400, 400);
```
