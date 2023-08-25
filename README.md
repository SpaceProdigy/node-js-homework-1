# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"
[Imgur](https://i.imgur.com/6OssdrI.jpg)

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
[Imgur](https://i.imgur.com/jhNYcQL.jpg)
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6d
[Imgur](https://i.imgur.com/EJ2OaPi.jpg)

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
[Imgur](https://i.imgur.com/uap9Lp7.jpg)

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
[Imgur](https://i.imgur.com/eCN6S1J.jpg)
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
[Imgur](https://i.imgur.com/uqj8H0E.jpg)

# Редагуэмо контакт та виводимо в консоль об'єкт редагованого контакту або null, якщо контакту з таким id не існує.

node index.js --action="update" --name "Jon Wick" --email jonwick@gmail.com --phone 328-689-65 --id "rsKkOQUi80UsgVPCcLZZW"
[Imgur](https://i.imgur.com/MpD0aeg.jpg)

node index.js --action="update" --name "Jon Wick" --email jonwick@gmail.com --phone 328-689-65 --id "rsKkOQUi80UsgVPCcLZZWds"
[Imgur](https://i.imgur.com/8RUUQA8.jpg)
