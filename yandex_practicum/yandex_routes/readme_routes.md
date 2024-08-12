При работе над данным проектом я провел тест-анализ, спроектировал проверки и провел тестирование части сервиса Яндекс Маршруты. Яндекс Маршруты – это учебный сервис, который строит маршруты и рассчитывает стоимость поездки для различных видов транспорта.

Требования и макеты собраны в Notion, Google Docs и Figma:
1. Требования к сервису Яндекс Маршруты: https://docs.google.com/document/d/1xED1bxE68lAVSZFHxi7EEpjg6SbT58dVNThPmCK20ls/edit#heading=h.syb5xo544tq8
1. Требования к функциональности вида транспорта "каршеринг": https://praktikum.notion.site/07f02ccc272e494db6501def032e9258
2. Макеты для каршеринга: https://praktikum.notion.site/07f02ccc272e494db6501def032e9258

При работе над данным проектом я:
- проанализировал и декомпозировал требования;
- составил MindMap на часть функциональности и интерфейса самого сервиса (1*);
- составил блок-схему для вида транспорта: такси, чтобы детально разобраться в логике расчета средней скорости движения транспорта в зависимости от времени суток (2*); 
- подготовил таблицу с классами эквивалентности, выделил граничные значения, чтобы подготовить тестовые данные для будущих тест-кейсов (3*);	
- разработал несколько тест-кейсов для проверки расчета времени и стоимости в пути для вида транспорта: такси (3*). 

Следующим этапом было написание тестовой документации для тестирования новой функциональности приложения, а именно заказ каршеринга и аэротакси. 
Тестовую документацию я вел в Google Sheets. Файл 4. Яндекс Маршруты (ЧЛ, ТК) https://docs.google.com/spreadsheets/d/1T1A-2hTPAYuR0vjLKhbB15bQzYjs968OOZgpOodqb7k/edit?usp=share_link

- разработал чек-листы и тест-кейсы, провел по ним проверки;
- подменил ответы бэкенда для тестирования нового вида транспорта "аэротакси" с помощью Charles (5*);
- завел 50 баг-репортов в баг-трекинговой системе YouTrack (посмотреть их можно тут: https://stachevm.youtrack.cloud/issues?q=tag:%20%7BSprint%202%7D). Дополнительно для каждого элемента тестирования выделил по одному баг-репорту для большей наглядности (6-8*).

1* MindMap Яндекс Маршруты - https://drive.google.com/file/d/1WtnSekMCPNq6SwqnpNkVBvpAuwEhMSjE/view?usp=share_link  
2* Блок схема: стоимость такси - https://drive.google.com/file/d/1tAzCToKGeNyYFMCXyhCBfJvsGl7TqgdT/view?usp=share_link  
3* Таблица с КЭ, ГЗ и подготовленными на их основе тест-кейсами - https://docs.google.com/spreadsheets/d/1Yt-fHD-nLExsDjNyVXgiDWrUzkVc2Ujx9hvLiVPt87U/edit?usp=share_link
5* Скриншоты из Charles с подменой данных https://drive.google.com/drive/folders/19PM4cYJIBcd8aZ-7Kb-iCckC0hvfBiBR?usp=share_link  
6* Баг-репорт вёрстка - https://drive.google.com/file/d/1P-88roTz32-4uPiBG8wp5G_kUqMnNrYa/view?usp=share_link  
7* Баг-репорт логика - https://drive.google.com/file/d/1uHzeyA_XdraXJuAPlUc2DyZJ0zAABSA_/view?usp=share_link  
8* Баг-репорт Сharles - https://drive.google.com/file/d/14x2u8gkg7B01aLNV5Uzzu61UddIHuR5R/view?usp=share_link 