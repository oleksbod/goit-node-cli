# goit-node-cli

## Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

```bash
node index.js -a list
```

## Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.

```bash
node index.js -a get -i 05olLMgyVQdWRwgKfg5J6
```

## Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

```bash
node index.js -a add -n Mango -e mango@gmail.com -p 322-22-22
```

## Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

```bash
node index.js -a remove -i qdggE76Jtbfd9eWJHrssH
```
