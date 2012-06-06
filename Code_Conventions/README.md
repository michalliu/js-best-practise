Best Code Conventions of Javascript
===================================

This is tended to be the best code convertions of javascript programming.

Rules
-----

1. `Functions` that start with capital letters are considered constructors

    ```js
    // Point must be used with the new prefix
    // eg. 
    //     p = new Point(0,0);
    function Point(x,y) {
        this.x = x;
        this.y = y;
    }
    ```

2. `Variables` in all caps are considered as global variable

    ```js
    var FOOBAR; // i am global
    ```