To log errors onto the console, use 
```js
    try {
        doStuff();
    } catch (err) {
        console.log("gg get rekt: " + cv.exceptionFromPtr(err).msg);
    }
```
