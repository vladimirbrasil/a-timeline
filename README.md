[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/vladimirbrasil/a-timeline)
[![Build Status](https://travis-ci.org/vladimirbrasil/a-timeline.svg?branch=master)](https://travis-ci.org/vladimirbrasil/a-timeline)
[![Coverage Status](https://coveralls.io/repos/github/vladimirbrasil/a-timeline/badge.svg?branch=master)](https://coveralls.io/github/vladimirbrasil/a-timeline?branch=master)

## &lt;a-timeline&gt;

## Description

`<a-timeline>` plots your dates.

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="a-timeline.html">
    <style>
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<a-timeline></a-timeline>
```

## Usage

`<a-timeline>` accepts an array of datetimes.
```html
<a-timeline datetimes="[[datetimes]]"></a-timeline>
```
```js
const datetimes = ['2017-08-11T14:17', '2017-08-07T16:00','2017-08-23T15:22', '2017-09-13T14:48']
];
```

Edit `<a-timeline>` color using `--timeline-color` style.
```html
<style>  
  --timeline-color: blue;
</style>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

### September 22th
First version.

## Credits

Vladimir Bergier Dietrichkeit

## License  

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
</content>
  <tabTrigger>readme</tabTrigger>
</snippet>