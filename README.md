[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/LostInBrittanygranite-led)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/LostInBrittanygranite-led.svg)](https://vaadin.com/directory/component/LostInBrittanygranite-led)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/LostInBrittany/granite-led)

# granite-led

> A webcomponent to display a LED-like ON/OFF status indicator
>
> Polymer 1.7 ready


## Doc & demo

[https://lostinbrittany.github.io/granite-led](https://lostinbrittany.github.io/granite-led)

## Usage example

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="granite-led.html">
      <style is="custom-style">    
        granite-led {
          --granite-led-background-color:  #db4437;
        }
      </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<granite-led powered></granite-led>
```

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install LostInBrittany/granite-led --save
```

Or [download as ZIP](https://github.com/LostInBrittany/granite-led/archive/gh-pages.zip).

## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/granite-led/granite-led.html">
    ```

3. Start using it!

    ```html
    <granite-led>
    </granite-led>
    ```


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)
