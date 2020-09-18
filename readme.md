# Simple Jquery Alert
**Simple Jquery Alert** is a jquery based, mobile-ready & highly customizable Alert Box 

## Installation
#####  Downloading Repo
clone this repo & add following line to your code.
```html
<link rel="stylesheet" href="src/jquery-simple_alert.css">
<!--Please add Jquery file here-->
<script src="src/jquery-simple_alert.js"></script>
```
#####  Directly From Github
You can without downloading by adding following line in your code
```html
<link rel="stylesheet" href="https://abhishekjnvk.github.io/jquery-simple-alert/src/jquery-simple_alert.css">
<!--Please add Jquery file here-->
<script src="https://abhishekjnvk.github.io/jquery-simple-alert/src/jquery-simple_alert.js"></script>
```

### Customisation
Simple alert is customizable with following parameter

| Parameter | type |default|Available Options|Example|
| ------ | ------ |-----|----|----|
| text | optional| |Text | Hello World this is a simple alert with jquery
| orientation | optional| br|br,tr,tl,bl |for example [tr] is for top right
| bg_color | optional| green  | any color you want as a background color|bg_color: 'black'
| text_color | optional| white  | any color you want as a text color|text_color: 'black'
| after_alert | optional| null  | callback function after clicking okay|after_alert: function () {alert('Showing alert  as a callback');}

## Example

```js
simpleAlert({
            text:"Hello World",
            orientation:'bl',
            bg_color: 'lightgreen',
            text_color: 'black',
            after_alert: function () {
                alert('Showing alert as a callback');
            }
        })
```

# Demo
View [Demo Page](https://abhishekjnvk.github.io/jquery-simple-alert/demo) 

### Happy contributing!



