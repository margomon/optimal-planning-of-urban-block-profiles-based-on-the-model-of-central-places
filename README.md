# optimal-planning-of-urban-block-profiles-based-on-the-model-of-central-places
Городские сервисы, которые я буду рассматривать:
Жилой тип квартала:	
Жильё, детские площадки, урны, точки раздельного мусора, дошкольные и школьные образовательные учреждения, поликлиники, аптеки, супермаркеты, стоматологии, бытовые услуги (ремонт ключей, обуви, одежды, копицентры), площадки для выгула собак, зоомагазины, спортивные площадки, парковка, почта, булочные, ветеринарные клиники, фастфуд
Общественно-деловой тип квартала:	
Больницы, визовые центры, консульства, салоны красоты, банки, кофейни, кафе, рестораны, отели, автосервисы, автозаправки, парковка, SPA, баня, почта, супермаркеты, специализированные магазины (техники, сантехники), ювелирные магазины, магазины одежды и обуви, сувенирные магазины, кальянные, бары, пабы, фастфуд, коворкинг, фитнес-клуб
Рекреационный тип квартала:
Арт пространство, библиотека, театр, музей, кинотеатр, боулинг, бильярд, клуб, аквапарк, бассейн, спорт площадка, стадион, фитнес клуб, кофейни, кафе, рестораны, парки, набережные, кальянные, бары, пабы, зоопарки, цирки, фастфуд, квеструм, сауны
Какие данные нужны: сами кварталы Санкт-Петербурга, граф мобильности(оценка перемещения во времени от кварталов), то есть транспортная связность (система, позволяющая посчитать расстояние от сервисов друг к другу), результат работы сервиса-алгоритма являются кварталы с циферкой, циферка - вероятность от от 0 до 1. Выход: слой с кварталами, где оценка с тем, насколько там нужен сервис. Оценить вероятность насколько необходимо открыть сервис в этом квартале и какого типа, чтобы подцентры объединились в центр. Отдать оценку для заданных типов сервисов, что если в каком-то квартале окроются эти типы сервисов, то эти кварталы резко превратятся в центр. Ближайщая работа - собрать данные по кварталам, типам сервисов, графом. Описать начальный состав данных - какие поля и атрибуты там будет и конечный выход ( это geojson с кварталами с такой-то такой таблицей атрибутов).   
