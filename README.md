Google Maps Downloader
================================
*загрузчик карт любого размера с Google Maps по заданным координатам и масштабу*
![Google Maps Downloader](https://github.com/oQue/GoogleMapsDownloader/blob/master/Examples/Interface.png)

Реализованные функции
-------------------------
* подсчет размера изображения при заданных координатах и масштабе
* скачивание и склеивание тайлов (в заданную пользователем директорию)
* использование публичных прокси во избежание блокировки по IP
* вывод в консоль прогресса

Известные баги
-------------------------
* Повторное нажатие кнопки "Create Map" приводит к зависанию приложения
* Прокси могут заметно замедлить процесс (нет фильтрации по скорости)
* При прерывании процесса все изображения будут скачиваться заново

Использованные внешние библиотеки
-------------------------
* JSoup для парсинга сайтов с прокси-серверами

-------------------------
Сборка из папки src консольной командой <br>
javac -cp ../lib/*:. MapsDownloader.java


Пример результата работы
![Google Maps Downloader](https://raw.githubusercontent.com/oQue/GoogleMapsDownloader/master/Examples/MoscowUniversity.jpeg)
![Google Maps Downloader](https://raw.githubusercontent.com/oQue/GoogleMapsDownloader/master/Examples/EiffelTower.png)
