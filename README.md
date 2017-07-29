# NgNavigation
angularJS navigation 可以固定在页面上的导航按钮

# Demo
[Demo](https://saiyanguo.github.io/NgNavigation/) (You can custom timeline style by editting style.css)

# Usage
* Include font-awesome in your app

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
```

* Include style.css in your app:

```html
<link rel="stylesheet" href="style.css">
```

* Include NgNavigation.js in your app:

```html
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/angular.js/1.6.5/angular.min.js"></script>
```

* Add NgNavigation as a new module dependency in your angular app.

```javascript
var app = angular.module('app', ['NgNavigation']);
```

* To define a navigaiton, do the following:

```javascript
//NgNavigation controller
$scope.navs = [
    {"title":"currentLocation","icon":"fa-map"}, 
    {"title":"currentState","icon":"fa-signal"}, 
    {"title":"alarmInfo","icon":"fa-exclamation-triangle"}
];
```
```html
<!-- view -->
<nav-btn>
  <nav-title></nav-title>
  <nav-list>
    <nav-item ng-click=""></nav-item>
  </nav-list>
  <nav-overlay></nav-overlay>
</nav-btn>
```


# History
* 1.0.0 Initial release

# TODO

# License
Released under the MIT License. See the LICENSE file for further details.