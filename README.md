# Yet another Zabbix Template for measuring Linux block-devices performance
Шаблон создан на базе идей, высказанных в хабра-статье [Мониторинг производительности дисковой подсистемы при помощи zabbix и block stat](https://habr.com/ru/post/377757/)


В данном шаблоне вместо UserParameter-s используются vfs.file.contents и Dependent items. Пока мониторится только одно блочное устройство, которое можно задать прямо в настройке "Raw data" item (sda, sdb и т.д.). Это будет исправлено после релиза Zabbix 4.4 с нативным auto-discovery блочных устройств в Linux-системах.
