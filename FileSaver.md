FileSaver
```
https://github.com/eligrey/FileSaver.js
```

```
var blob = new Blob(["Hello, world!"], {type: "text/plain;charset=utf-8"});
saveAs(blob, "hello world.txt");
```

```
var canvas = document.getElementById("my-canvas"), ctx = canvas.getContext("2d");
// draw to canvas...
canvas.toBlob(function(blob) {
    saveAs(blob, "pretty image.png");
});
```
