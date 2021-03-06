# List.js
Perfect library for adding **search**, **sort**, **filters** and **flexibility** to
**tables**, **lists** and various HTML elements. Built to be invisible and work on existing HTML.
Really simple and easy to use!

### Core idea
- Simple and invisible
- Easy to apply to existing HTML
- No dependencies
- Fast
- Small
- Handle thousands of items

### Features
- Works both lists, tables and almost anything else. E.g. `<div>`,`<ul>`,`<table>`, etc.
- Search [Read more ›](http://listjs.com/docs/list-api#search)
- Sort [Read more ›](http://listjs.com/docs/list-api#sort)
- Filter [Read more ›](http://listjs.com/docs/list-api#filter)
- Simple templating system that adds possibility to add, edit, remove items [Read more ›](http://listjs.com/docs/list-api#add)
- Plugins [Read more ›](http://listjs.com/docs/plugins)
- Support for Chrome, Safari, Firefox, IE6+

### Demo / Examples
- [Existing list](http://listjs.com/examples/existing-list)
- [Existing list + add](http://listjs.com/examples/existing-list-add)
- [New list](http://listjs.com/examples/new-list)
- [Add, get, remove](http://listjs.com/examples/add-get-remove)
- [Fuzzy search](http://listjs.com/examples/fuzzy-search)
- [Pagination](http://listjs.com/examples/pagination)

## Documentation
- [Getting started](http://listjs.com/docs)
- [Options](http://listjs.com/docs/options)
- [List API](http://listjs.com/docs/list-api)
- [Item API](http://listjs.com/docs/item-api)
- [Changelog](http://listjs.com/overview/changelog)

### Plugins
- [Introduction](http://listjs.com/docs/plugins)
- [Pagination](http://listjs.com/docs/plugins/pagination)
- [Fuzzy search](http://listjs.com/docs/plugins/fuzzysearch)
- [Build your own](http://listjs.com/docs/plugins/build)

### Known issues
- Sorting fails with `åä`, thinking that `ä` is before `å`.
- Class `asc` and `desc` should be removed as soon as the sorting breaks.
- Tables row items can't be created with the `{ item: '<html>' }`-method.


## Contributors
* [javve](https://github.com/javve) / [Jonny Strömberg](http://jonnystromberg.com)
* [lusentis](https://github.com/lusentis) / [Simone Lusenti](http://www.plasticpanda.com)
* [dancrew32](https://github.com/dancrew32) / [Dan Masquelier](http://danmasq.com)
* [himynameisjonas](https://github.com/himynameisjonas) / [Jonas Forsberg](http://jonasforsberg.se)
* [LuukvE](https://github.com/LuukvE) [Luuk van Egeraat](http://luukvanegeraat.com/)
* [endorama](https://github.com/endorama) / Edoardo Tenani
* [sprynmr](https://github.com/sprynmr) / Bob Spryn
* [francescolaffi](https://github.com/francescolaffi)
* [ryantanner](https://github.com/ryantanner)
* [idlefella](https://github.com/idlefella)
* [julienbechade](https://github.com/julienbechade) / [Julien Béchade/](http://julienbechade.com/)
* [matthewheston](https://github.com/matthewheston)
* [gvido](https://github.com/gvido) / Gvido Glazers
* [karlwestin](https://github.com/karlwestin) / [Karl Westin](http://karlwestin.com)
* [joakin](https://github.com/joakin) / [Joaquin](http://chimeces.com/)
* [dancrew32](https://github.com/dancrew32) / [Dan Masquelier](http://danmasq.com/)
* [jkeyes](https://github.com/jkeyes) / [John Keyes](http://keyes.ie/)
* [samosad](https://github.com/samosad) / Alexey Tabakman

Built with [Component](https://github.com/component/component) which is created by [TJ Holowaychuk](https://github.com/visionmedia).

### Want to contribute?
- Read more at [listjs.com/overview/contribute](http://listjs.com/overview/contribute)

## License (MIT)

Copyright (c) 2012 Jonny Strömberg <[jonny.stromberg@gmail.com](jonny.stromberg@gmail.com)>
[http://jonnystromberg.com](http://jonnystromberg.com)
