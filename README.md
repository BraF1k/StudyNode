### Модули

Чтобы экспортитовать ту или иную функцию, мы должны их задать как свойства объекта `exspots`. Таким образом:

```exports.canadianToUS = canadian => roundTwo(canadian * canadianDollar);```

```exports.USToCanadian = us => roundTwo(us / canadianDollar);``` 

Чтобы использовать новый модуль в программе, воспользуйтесь функцией Node `require` и передайте путь к нужному модулю в аргументе.

`const currency = require("./learnnode/module.js");`