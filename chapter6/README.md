###Глава 6. API Яндекс.Карт  
В этой части рассматриваются возможности визуализации точечных объектов с помощью API Яндекс.Карт.

[Видео скринкаста (10:25)](https://vimeo.com/minikarma/geotalk-chapter6)

####Ссылки 
* [Документация API Яндекс.Карт](http://tech.yandex.ru/maps/) и [примеры](https://tech.yandex.ru/maps/jsbox/2.1/)
* [Модуль Heatmap для тепловых карт](https://github.com/yandex/mapsapi-heatmap)
* [Документация jQuery](http://jquery.com)

####Файлы
* `data/bikepoints.json` — данные о станциях велопроката в Москве с сайта [data.mos.ru](http://data.mos.ru/datasets/918). При помощи QuantumGIS я переконвертировал исходный CSV файл (`data/bikepoints.csv`) в geoJSON формат.
* `src/bikepoints.svg` — пример значка кастомизированной метки

####Важно!

Для того, чтобы работать с JSON-файлами локально вам потребуется стартовать веб-сервер на локальном комьютере.
Для Mac OS, например, наиболее простой способ запуска веб-сервера локально, команда в терминале: `python -m SimpleHTTPServer`

####Примеры 
* [simple.html](simple.html) — отображение пунктов велопроката простыми метками [демо](http://getwalk.me/experiments/chapter6/simple.html)
* [custom.html](custom.html)— использование собственного значка для отображения объектов [демо](http://getwalk.me/experiments/chapter6/custom.html)
* [custom-sizes.html](custom-sizes.html) — значки различного размера [демо](http://getwalk.me/experiments/chapter6/custom-sizes.html)
* [collection.html](collection.html) — добавление объектов в геоколлекцию, использование кастомного значка для всей коллекции [демо](http://getwalk.me/experiments/chapter6/collection.html)
* [cluster.html](cluster.html) — кластеризация объектов [демо](http://getwalk.me/experiments/chapter6/cluster.html)
* [circles.html](circles.html) — отображение объектов в виде окружностей заданного размера [демо](http://getwalk.me/experiments/chapter6/circles.html)
* [heatmap.html](heatmap.html) — тепловая карта пунктов проката [демо](http://getwalk.me/experiments/chapter6/heatmap.html)