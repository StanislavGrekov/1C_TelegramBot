## Взаимодействие с 1С через Телеграм бота

### Задача:

Написать бота, который будет получать данные из телеграмм и загружать их в 1С. Необходимые данные: название организации, инн, контактное лицо, телефон/email. Загрузку необходимо осуществлять в справочник “контрагенты”

### Описание

Бот взаимодействует с мессенджером Телеграм через Систему взаимодействия. Для работы необходим токен Телеграм бота или возможно использовать токен сохраненный в Интеграции Системы взаимодействия базы. После активации бота ему можно написать сообщения по шаблону:

Наименование: РогаИКопыта;   
ИНН: 0327719957;   
Контактное лицо: Остап Бендер;   
Телефон/Email: bender@ya.ru  

Полученная информация будет обработана и записана в справочник НаименованияКонтрагентов



### Инструкция:

1. Скачать .dt, разdернуть на платформе 8.3.23

2. Зайти в режиме Предприятия и выполнить Активацию бота

3. Если Вы не используйте свой токен, то найти в телеграм бота @StasonToDo_Bot

4. Используя шаблон, представленный выше, отправить боту сообщение (или введите start для получения справки). Если ранее контрагент не был добавлен в справочник и Вы используйте валидный ИНН, информация будет записана в справочник
