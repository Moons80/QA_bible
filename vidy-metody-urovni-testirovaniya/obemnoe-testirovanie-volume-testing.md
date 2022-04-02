# Объемное тестирование (Volume testing)

_Объемное тестирование (volume testing): Тип тестирования уровня производительности, проводимого для оценки способности элемента тестирования обработать определенные объемы данных (обычно равных или близких к максимальным указанным потенциальным возможностям) с точки зрения потенциальных возможностей пропускной способности, емкости памяти или того и другого. (ГОСТ 56920)_

Объемное тестирование (также flood testing) предназначено для прогнозирования того, может ли система / приложение обрабатывать большой объем данных в плане проверки объема данных, обрабатываемых базой данных. Это тестирование сосредоточено на наполнении БД продукта в реальных сценариях использования, отслеживании производительности приложения при различных объемах БД. Обычно продолжительность проверки объема составляет 1 час или время, необходимое для обработки n записей; оно может варьироваться в зависимости от вашего SLA / требований.

![https://www.softwaretestinghelp.com/wp-content/qa/uploads/2018/01/Connected-Data.jpg](https://www.softwaretestinghelp.com/wp-content/qa/uploads/2018/01/Connected-Data.jpg)

**Причины для проведения этого тестирования**:

* Самая основная потребность - проанализировать производительность вашей системы при увеличивающемся объеме данных. Создание огромного объема данных поможет вам понять производительность вашей системы с точки зрения времени отклика, потери данных и т. д.;
* Выявление проблем, которые могут возникнуть с огромными данными, а также пороговой точки (threshold point);
* За пределами устойчивой или пороговой точки (то есть при сбое БД) система перестает отвечать на запросы или появляются таймауты;
* Реализация решений по перегрузке БД и даже их проверка;
* Выявление крайней точки вашей БД (которая не может быть исправлена), за которой система выйдет из строя, и, следовательно, необходимо принять меры предосторожности;
* В случае наличия более одного сервера БД, выявление проблем с коммуникациями между БД;

**Примеры тест-кейсов**:

* Добавление данных может быть выполнено успешно и отражено ли оно в приложении или на веб-сайте;
* Удаление данных может быть выполнено успешно и отражается ли оно в приложении или на веб-сайте;
* Обновление данных может быть выполнено успешно, и отражается ли оно в приложении или на веб-сайте;
* Отсутствуют потери данных и вся информация отображается в приложении или на веб-сайте должным образом;
* Время ожидания приложения или веб-страниц не истекло из-за большого объема данных;
* При большом объеме данных нет сообщений о крешах;
* Данные не перезаписаны и отображаются соответствующие предупреждения;
* Другие модули вашего веб-сайта или приложения не завершают работу аварийно или не работают по таймауту из-за большого объема данных;
* Время отклика базы данных находится в допустимом диапазоне;

Источники:

* [Volume Testing Tutorial: Examples And Volume Testing Tools](https://www.softwaretestinghelp.com/what-is-volume-testing/)
* [Do you really know all types of Performance Tests (Non-Functional Tests)?](https://perfmatrix.blogspot.com/2017/01/type-of-performance-test.html)