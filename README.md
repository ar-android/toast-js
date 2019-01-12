# ToastJS
Display simple toast message using javascript.

[Demo](https://ar-android.github.io/toast-js/)

<img src="https://github.com/ar-android/toast-js/raw/master/toast-js.png" alt="ToastJS">

## Installation
Import css.
```html
<link rel="stylesheet" type="text/css" href="toast.css">
```

Import JS
```html
<script type="text/javascript" src="toast.js"></script>
```

## Usage
To display toast just use show method. You can set message and duration to show.
```javascript
Toast({
    text: "This is toast!",
    duration: 3000
}).show();
```

## Change toas style
You can change toas style css.
```css
.toast{
    background: -webkit-linear-gradient(315deg, #e67e22, #d35400);
    background: linear-gradient(135deg, #e67e22, #d35400);
}
```
