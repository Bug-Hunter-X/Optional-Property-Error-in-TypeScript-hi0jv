This repository demonstrates a common error in TypeScript involving optional properties.  The `printCoord` function expects an object with both `x` and `y` properties.  However, if the object passed to the function only has a `y` property and `x` is omitted, TypeScript will throw an error.