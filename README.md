# b5alert
b5alert is javascript function to create and show bootstrap 5 alert inside element.

## Requirements

Add b5 alert script anywhere you want. It has no dependencies.

```html
<script defer src="/b5alert.js"></script>
```

## Demo
[Demo](https://auct.github.io/b5alert/demo)


## Usage

#### Minimal

```javascript
b5alert.success(parentElement, 'my message'); //show alert success
b5alert.error(parentElement, 'my message'); //show alert danger
b5alert.show(parentElement, 'warning', 'my message'); //show alert with warning/any bootstrap color
```

#### With optional title

```javascript
b5alert.success(parentElement, 'my message', 'optional title'); //show alert success
b5alert.error(parentElement, 'my message', 'optional title'); //show alert danger
b5alert.show(parentElement, 'warning', 'my message', 'optional title'); //show alert with warning/any bootstrap color
```