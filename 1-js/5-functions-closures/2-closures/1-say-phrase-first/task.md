# Что выведет say в начале кода?

[importance 5]

Что будет, если вызов `sayHi('Вася');` стоит в самом-самом начале, в первой строке кода?

```js
*!*
say('Вася'); // Что выведет? Не будет ли ошибки?
*/!*

var phrase = 'Привет';

function say(name) {
  alert( name + ", " + phrase );
}
```

