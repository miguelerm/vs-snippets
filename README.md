# vs-snippets
This repository contains my code snippets for Visual Studio, some of this spippets are:

## Javascript: IIFE
when you write `iife` in a JavaScript File, the snippet writes:

```js
(function () {
    // and put the cursos in this line
})();
```

## AngularJS: ngctrl
when you write `ngctrl` in a JavaScript File, the snippet writes (asking for your *$module$* and you controller *$name$*):

```js
(function () {
    angular.module('$module$').controller('$name$Controller');

    /**
     * Descripción del controlador $name$
     */
    function $name$Controller() {
        // and put the cursos in this line
    }
    
})();
```

# Setup
1. Clone this repo or [download it](https://github.com/miguelerm/vs-snippets/archive/master.zip).
2. Open your Visual Studio
3. Go to *Tools* -> *Code Snippets Manager...*
4. Click on "Add" button
5. Browse the folder where you put the snippets
   * Maybe you need to restart your VS.
6. Open a code file
7. Try it.
