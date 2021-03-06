[![Build status](https://travis-ci.org/TherapyChat/layout-elements.svg?branch=master)](https://travis-ci.org/TherapyChat/layout-elements)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/therapychat/layout-elements)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com)

# \<layout-elements\>

Web Component to display an incremental timer

Intall:
```bash
bower install -S layout-elements
```

Example of use:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="layout-elements.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<absolute-drawer-layout>

  <absolute-drawer slot="drawer">
    <div class="drawer-container">Drawer content goes here</div>
  </absolute-drawer>

  <div class="content-container">Main content goes here</div>

</absolute-drawer-layout>
```

## Documentation

Checkout the [webcomponents page](https://www.webcomponents.org/element/therapychat/layout-elements).

## Changelog

See [CHANGELOG](./CHANGELOG.md) file.

## Contributing

Please read [CONTRIBUTING](./CONTRIBUTING.md) file to follow good practices.

You will need [NodeJS](https://nodejs.org).

1. Close the repo: `git clone git@github.com:TherapyChat/layout-elements.git`
1. Install dependencies: `npm install`
1. Code!
1. Test: `npm test`
1. Create a [Pull Request](https://github.com/therapychat/layout-elements/pulls)

### Contributors

- [Alberto Fernandez](https://github.com/AlbertoFdzM)

## License

This project is available under the `Apache License 2.0`. See the [LICENSE](./LICENSE) file for more info.
