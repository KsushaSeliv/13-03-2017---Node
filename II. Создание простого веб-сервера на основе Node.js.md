1. Создание папки  с текущей датой и временем с помощью командной строки и вызова-mkdir $(date +%Y%m%d_%H%M%S) && cd $_ && npm init -y
2. Подключение npm i -D nodemon и npm i moment
3. В созданной папке, в файле package.json дописываем в разделе scripts "start": "nodemon"
4. Добавляем файл index.js  с нужным содержимым 
5. Запускаем сценарий yarn start и выполняем curl localhost:4321,  в консоли появляется текущая дата и время:
![alt text](https://github.com/nastyandreeva/13-03-2017---Node/blob/master/дата.PNG)
6. Изменяем код в index.js для выдачи данных в формате JSON
7. Повторяем  5 пункт и переходим в браузер для проверки работы:
![alt text](https://github.com/nastyandreeva/13-03-2017---Node/blob/master/время.PNG)
8. Ещё раз меняем код для события request и убеждаемся, что время и дата выводится
