# elastic-match-query

A Polymer Element which renders an input box and produces an elasticjs query based on the input value.

### Example
```html
<elastic-match-query
  field="field.path"
  label-value="My Input"
  value={{inputValue}}
  query={{resultingQuery}}>
  autobuild="true"
</elastic-match-query>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

