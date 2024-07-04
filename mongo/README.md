# practNode
Как можно работать с таблицами в MySQL на Node.js

Внешний вид главного окна представлен далее.

![image](https://user-images.githubusercontent.com/10297748/230503674-84807929-9e4c-4de7-b97d-7676b2de80b5.png)

Пример не требует Web-сервера. Достаточно установить Node.js, отредактировать пути в файле app.js, запустить файл run_server.bat, открыть страницу http://127.0.0.1:3000/

Перед запуском необходимо доустановить компонент с помощью команды: npm install sync-mysql. Дополнительный набор команд Chocolatey устанавливать необязательно.

Пример гарантированно работает:
1) Версия Node.js v18.15.0, установленная из node-v18.15.0-x64.msi
2) Версия npm: 9.6.4

Допустима работа скрипта как с асинхронным (sync-mysql), так и синхронным (mysql2) модулем взаимодействия с MySQL. Оба скрипта доступны в каталоге dop с примером. Первый модуль устанавливается командой: npm install sync-mysql, второй: npm install mysql2. В каталоге со скриптами появятся дополнительные модули.