# Современный аналог карт ген штаба (база данных-САКГШ).

Предложение для всех создать не убиваемый современный аналог карт ген штаба (САКГШ). актуальные не убиваемых данных в которых можно быть уверенным. Если OSM не хочет меняться в лучшую сторону и не хочет вводить модерацию, дабы сохранить наши данные, то пора создавать форк.

# План схема и основные черты проекта:
1. Настройка и поднятия своего сервера по типу OSM.
2. Делаем разграфку на весь мир. по типу ген штаба. разграфка 1 км. (то есть пирог на весь мир с сеткой как у генштаба по аналогии)
3. Отрисовываем детально по квадратно каждый 1 км - то есть один лист, после отрисовки закрываем данный квадрат для правок Последующие правки в отрисованных квадратах, только с модерацией (то есть Вы можете запросить этот квадрат для правки поправить его и прислать его на модерацию.) Причем обсуждение будет всеми модераторами области и близлежащих областей принимать или нет правку, только после проверки эти данные добавляются или полностью заменяют старые.

Такая схема существуют лишь до тех пор, пока не будет Основной ЗД гео базы данных.
Ппосле должны быть разработанны инструменты получения данных из неё по классу импорта:
3D → в 2D, → простая карта, → карты бумажные согласно каждого куска разграфки 1 км данных – в формате 1 км. 500 м 250 м PNG или любой другой формат.. указываем номер карты ЧМГ карты. по желанию авторство соавторство правящих этот квадрат и ответственных за данные.

Проект должен поддерживать Основную проекцию, + переконвертацию на лету в другие проекции или работать или просто работа с ними.

# Слои: 

1. все мефические виртуальные слои хранятся отдельна и работа с ними тоже отдельно: 
Границ, - мульты;
Границ квартолов леса - мульты;
Лендюзы жылые не жилые зоны, пром зоны;
POI - только точки;

2. все реальные объекты:

дома;
реки; 
дороги и т.д..

3. Данные о почвах и полезных ископаемых.

Составные части проекта: поддержка полная ЗД, описание объектов полное что то в стили викимапии , планы зданий и т.д. (развитие составных частей планируется в рамках неделимости проекта).

Послесловие также хочется обклацать-оцифровть все доступные старые карты, что бы они были доступны в цифровом формате как данные.) как это сделать надо подумать, как это организовать все в рамках одного проекта или как то по другому отдельными ветками.


Часть данных можно затянуть из осм. идеально - хорошо отрисованных мест. но с корректирокой взяли квадрат , скачали из осм. поправили отправили в проект САКГШ

Рендер сгодится и от осм. для визуализациии в вебе можно сделать несколько видов переключаемых.

карты бумажные - PNG (какой вид будут иметь надо подумать? на первое время и OSM формат вполне нормальный.

Еще что хотелось бы это все мифические границы были отдельным слоем такие как границы государств, областей, районов, всякие кварталки лесные, прочие лен дюзы, нефиг их лепить. Вмести, они должны отдельно быть и корректировать их так легче, когда они не привязаны к объектам на карте.



База данных должна быть доступна к выгрузке по областям, государствам, местным крупным территориальным крупным единицам, единицам номенклатуры листам карты.

# Лиценция 

для совместного участия для:

1. Для коммерческих организаций внесших вклад данными или оказавшими мат. поддержка или тех ресурсами (отдача на бесплатной основе аналогично и для участников которые в будущем захотят сделать коммерческий проект или использовать в своих ком. целях.) 


2. Лицензия Открытая для Всех: Раз в три года мы будем отказывается от всех своих прав и выпускаем специальный срез с открытыми данными под открытой лиценцией данные будут доступны в полном объеме из нашей базы.

(Выкладываем срез на торент. данные и бумажные карты.)


# Финансовая сторона:

Получанные деьги от продажи данных мы планируем тратить на:

1. Организационную часть;
2. Собственные снимки, аренда оборудования для получение точных данных из пункта 6 или оплату и покупка работ для проекта из этого же пункта.
3. Техническую часть (сервера, сайты);
4. Програмное обеспечение; 
5. Вознаграждения участникам проекта; (маперы + переводчики + 3D дизайнерам моделей)
6. Участники предоставившем: фото и ортфото планы и видео, GPS треки, данные с личных эхолотов (о промерах глубин), прочие гео данные с точных измерений с приборов такие, как :замеры высот, GPS объектов. лазерное сканирование) 

От каждой продажи деньги будут разделены и будут направлены на выделенные части равными, частями, деление последующее в процентном соотношение между участниками и проетов, но только полной уплаты налогов от продаж согласно действующему законодательству и оплаты хозяйственной деятельности.)

То есть, тем самым не получится слабого звена, каждый из участник или организация будет на целен на улучшение конечного продукта - данных.

Часть денег в размера какой то суммы должна оставаться на счету участника, которой он будет отвчечать в случае порчи данных (страховой капитал).


