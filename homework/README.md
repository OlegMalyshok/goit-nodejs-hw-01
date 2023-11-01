# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"
https://monosnap.com/file/Pv0ElC6OIvziPEKMjNIqkilxCqzG1I

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/cD0pJChg4Qu2ZEdVHmpVGxpdnWwO0s

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/ZXiuMsSTLK0bUR8nXqvekxwUCKYUtJ

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

node index.js --action="remove" --id rsKkOQUi80UsgVPCcLZZW
https://monosnap.com/file/oKJu4FqpI8kMZJSCT65jsa0HNHC6IW
