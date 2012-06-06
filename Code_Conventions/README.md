Code Conventions of Javascript
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

Coding Style
------------
1. `Indentation` is 4 **spaces**.

2. Open curly brace is at the **end of the line**.

3. String literal uses single **quote** (') and not **double quote** (").
                                                                   
Commit Message
--------------

Bad:

    Fix a problem with Firefox.

Good:

    Add support for labeled statement.

    It is covered in ECMAScript Language Specification Section 12.12.
    This also fixes parsing MooTools and JSLint code.

    Running the benchmarks suite show negligible performance loss.

    http://code.google.com/p/esprima/issues/detail?id=10
    http://code.google.com/p/esprima/issues/detail?id=15
    http://code.google.com/p/esprima/issues/detail?id=16

1. The first line is the short description

2. The next paragraphs should provide more explanation (if needed)

3. The next is the link to the issues for cross-ref (if needed)

Laundry list
------------

1. Write understandable code. No need to be too terse (or even obfuscated).

2. [JSLint](http://jslint.com/) does not complain