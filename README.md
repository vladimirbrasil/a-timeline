[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/vladimirbrasil/a-timeline)
[![Build Status](https://travis-ci.org/vladimirbrasil/a-timeline.svg?branch=master)](https://travis-ci.org/vladimirbrasil/a-timeline)
[![Coverage Status](https://coveralls.io/repos/github/vladimirbrasil/a-timeline/badge.svg?branch=master)](https://coveralls.io/github/vladimirbrasil/a-timeline?branch=master)

**&lt;a-timeline&gt;**

**Description**

`<a-timeline>` plots your dates.

<!---
```
<custom-element-demo>
  <template>
    <style>
      a-timeline { 
        --timeline-color: green; 
        --timeline-text-color: grey; 
      }
    </style>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="a-timeline.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<a-timeline id="demo"></a-timeline>
<script>
  const datetimes = ['2017-08-11T14:17', '2017-08-07T16:00','2017-08-23T15:22', '2017-09-13T14:48'];
  document.getElementById('demo').datetimes = datetimes;
</script>
<script>
  window.addEventListener('WebComponentsReady', function() {
    Polymer({
      is: 'a-timeline',

      connectedCallback: function() {
        var items = [];

        for (var i = 0; i < 100; i++) {
          items.push({firstName: 'First Name ' + i, lastName: 'Last Name ' + i});
        }

        this.items = items;
      }
    });
  });
</script>
```

**Usage**

`<a-timeline>` accepts an array of datetimes.
```html
<a-timeline datetimes="[[datetimes]]"></a-timeline>
```
```js
const datetimes = ['2017-08-11T14:17', '2017-08-07T16:00','2017-08-23T15:22', '2017-09-13T14:48'];
```

Edit `<a-timeline>` color using `--timeline-color` style.
```html
<style>
  a-timeline { 
    --timeline-color: green; 
    --timeline-text-color: grey; 
  }
</style>
```

### Big Thanks

![Logo](images/Sauce-Labs_Horiz_Red-Grey_RGB.png)

Cross-browser Testing Platform and Open Source <3 Provided by [Sauce Labs](https://saucelabs.com)

**Contributing**

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

**History**

**September 22th**

First version.

**Credits**

Vladimir Bergier Dietrichkeit

**License**

    This software is licensed under the MIT License, quoted below.

    MIT License

    Copyright (c) 2017 Vladimir Bergier

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
</content>
  <tabTrigger>readme</tabTrigger>
</snippet>
