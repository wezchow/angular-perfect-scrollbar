#cc-angular-perfect-scrollbar
> This fork will fix the broken dependency on [perfect-scrollbar](https://github.com/noraesae/perfect-scrollbar) and is
compatible with [perfect-scrollbar](https://github.com/noraesae/perfect-scrollbar) v-6.0.0 and up

Installation
=========================

Install via Bower:

````
$ bower install cc-angular-perfect-scrollbar --save
```

Include the angular-perfect-scrollbar files in your index.html:

````
<link rel="stylesheet" href="bower_components/perfect-scrollbar/min/perfect-scrollbar.min.css" />
<script src="bower_components/cc-perfect-scrollbar/min/perfect-scrollbar.min.js"></script>
<script src="bower_components/cc-perfect-scrollbar/min/perfect-scrollbar.with-mousewheel.min.js"></script>
<script src="bower_components/cc-angular-perfect-scrollbar/src/angular-perfect-scrollbar.js"></script>
```

Include some css for your scrollable content:

````
.scroller {
    white-space: pre-line;
    height: 500px;
    overflow-y: hidden;
    position: relative;
}
````

Add it as module to your app.js:

````
['perfect_scrollbar']
````

Use it wherever you want:

````
<perfect-scrollbar class="scroller">
  // your content
</perfect-scrollbar>
````

Further installation and usage hints can be found here:

https://github.com/noraesae/perfect-scrollbar

You can find an example in the *examples* folder in this repository.  Much respect to [Hyunje Alex Jun](https://github.com/noraesae) for his great scrollbar library.

License
-------

The MIT License (MIT) Copyright (c) 2013, 2014 Drew Miller and other contributors.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.