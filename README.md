This is simply a repository to store the compiled Opencv.js file with exceptions enabled. I had to compile it without allowing memory growth because of [some issues with doing so](https://github.com/opencv/opencv/issues/14691).

To log errors onto the console, use 
```js
    try {
        doStuff();
    } catch (err) {
        console.log("gg get rekt: " + cv.exceptionFromPtr(err).msg);
    }
```
