1.Створіть схему pandemic у базі даних за допомогою SQL-команди.
Оберіть її як схему за замовчуванням за допомогою SQL-команди.

![image](https://github.com/user-attachments/assets/92b4471c-656b-4199-b563-56bf998c29d7)

2. Нормалізуйте таблицю infectious_cases до 3ї нормальної форми. Збережіть у цій же схемі дві таблиці з нормалізованими даними.

![image](https://github.com/user-attachments/assets/857dcd4b-642f-40d3-8ea5-89d22171128e)
![image](https://github.com/user-attachments/assets/52fd9645-97c0-4afd-b551-8fb643fba358)

3. Проаналізуйте дані:

Для кожної унікальної комбінації Entity та Code або їх id порахуйте середнє, мінімальне, максимальне значення та суму для атрибута Number_rabies.
💡 Врахуйте, що атрибут Number_rabies може містити порожні значення ‘’ — вам попередньо необхідно їх відфільтрувати.


Результат відсортуйте за порахованим середнім значенням у порядку спадання.
Оберіть тільки 10 рядків для виведення на екран.

![image](https://github.com/user-attachments/assets/0b81545d-c21e-47e6-be63-89744120141e)

4. Побудуйте колонку різниці в роках.

Для оригінальної або нормованої таблиці для колонки Year побудуйте з використанням вбудованих SQL-функцій:

атрибут, що створює дату першого січня відповідного року,
атрибут, що дорівнює поточній даті,
атрибут, що дорівнює різниці в роках двох вищезгаданих колонок.

![image](https://github.com/user-attachments/assets/65b896ff-d529-4a9b-9602-603e8817b80c)

5. Побудуйте власну функцію.

Створіть і використайте функцію, що будує такий же атрибут, як і в попередньому завданні: функція має приймати на вхід значення року, а повертати різницю в роках між поточною датою та датою, створеною з атрибута року (1996 рік → ‘1996-01-01’).

![image](https://github.com/user-attachments/assets/76fa8d75-80de-42d8-aa2b-42f6b4083986)

![image](https://github.com/user-attachments/assets/47ffe959-8fcf-4f0a-aa82-7531b231a3a5)

