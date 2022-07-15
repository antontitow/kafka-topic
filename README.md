Создает топик


Запуск кафки
start zookeeper-server-start.bat c:\kafka\config\zookeeper.properties

start kafka-server-start.bat c:\kafka\config\server.properties (В случае ошибок zookeeper-server-stop.bat и kafka-server-stop.bat)

Проверка работоспособности
http://localhost:8099/health