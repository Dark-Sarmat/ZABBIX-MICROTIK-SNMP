![PROJECT_PHOTO](https://www.ionline.by/promo/logo/git-logo.png)
# Шаблон Zabbix для мониторинга устройств Mikrotik по SNMP

Поскольку стандартные шаблоны, которые мне попадались на просторах интернета мне не подошли, особенно потому что или собирали не те данные, или вообще были не работоспособны, в итоге я сам разобрался и разработал собственный шаблон. Шаблон получился хорошим и работоспособным. Работа тестировалась на следующих моделях: Mikrotik RouterBOARD 750GL, Mikrotik RouterBOARD 750, Mikrotik RouterBOARD 750UP, Mikrotik CRS125-24G-1S-RM, Mikrotik RouterBoard 912UAG-2HPnD

Шаблон для мониторинга устройств Mikrotik работает по SNMP и производит сбор следующих параметров:

	- Загрузка процессора устройства
	- Модель устройства
	- Уровень лицензирования
	- Software ID
	- Имя устройства
	- Температуру устройства (скорее всего снимает данные с датчика на плате)
	- Полный объем оперативной памяти
	- Использование оперативной памяти
	- Время работы устройства (аптайм)
	- Напряжение питания устройства

Все описание о шаблоне мониторинга размещено тут: https://www.ionline.by/administrirovanie/sistemy-monitoringa/zabbix/shablon-zabbix-dlya-monitoringa-ustrojstv-mikrotik-po-snmp-20-01-2015/	
	
![PROJECT_PHOTO] (https://static.ionline.by/2015/01/community-zabbix.png)
