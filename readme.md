# APP UI: Tags

Web Component using Polymer that creates an element to create/edit tags.


## Examples

* [Static](http://rawgit.com/app-ui/tags/master/examples/static.html)
* [Dynamic](http://rawgit.com/app-ui/tags/master/examples/dynamic.html)

## Dependencies

This component relies on the following third-party libraries:

* Polymer
* Backbone.js
* Underscore


## Install

Using bower:
```
bower install app.ui.tags
```


## Usage

1. Import Web Components' polyfill:

```html
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.2.3/platform.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.2.3/polymer.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="component/ui-tags.html">
```

3. Start using it!

```html
<ui-tags></ui-tags>
```


## Options

This is a direct extension of the [Backbone UI component](http://github.com/backbone-ui/tags) with the same name. Its options are defined as ```option-``` parameters in the tag, for example:
```
<ui-tags option-editable="false" option-data="landscape|nature|farm|january|lake"></ui-tags>
```


## Credits

Initiated by Makis Tracend ( [@tracend](http://github.com/tracend) )

Distributed through [Makesites.org](http://makesites.org)


## License

Released under the [MIT License](http://makesites.org/licenses/MIT)
