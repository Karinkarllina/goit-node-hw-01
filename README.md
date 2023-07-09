# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"
https://monosnap.com/file/xrAGaVRB0B5fkwdwQxFMb1A03JL5Tq

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/km9Uz6vRhKyCn6rCwAKf797dUwSRZL

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/hxZP4qXdAoIeAMjTK2tqptqkUomK4m

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
https://monosnap.com/file/RTk9BYpFsMeYwDvtUQ5a9PMNE6LCrA
