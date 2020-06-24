## Задание 1
- разобрать структуру приложенного Vagrantfile
- нарисовать схему
- расписать возможные подсети

---
## Здвние 2
- Найти свободные подсети;
- Подсчитать, сколько узлов в каждой подсети, включая свободные;
- Указать broadcast-адрес для каждой подсети;
- Проверить, нет ли ошибок при разбиении.

--- 

## Задание 3

- Все серверы и роутеры должны ходить в Интернет черз inetRouter;
- Все серверы должны видеть друг друга;
- У всех новых серверов отключить дефолт на NAT (eth0), который Vagrant поднимает для связи;
- в README приложить скриншоты tracepath и `ip r`

---

## задание 4
- поднять nginx на officе2Server
- пробросить порт с локалхоста на inetRouter
- настроить проброс порта до office2Server
- запретить office1Server ходить на office2Server на 80й порт, все остальные должны работать
- запретить office1Server отвечать на пинг, всем кроме inetRouter, но office1Server должен пинговать всех остальных

---

## Задани 5
- настроить knocking port скрипт для прохода с office1Server на Office2Server

Все действия должны быть описаны в README.md со скриншотами

---

## Полезные ссылки
https://otus.ru/nest/post/267/
https://www.opennet.ru/docs/RUS/iptables/
https://ru.wikibooks.org/wiki/Iptables
https://www.kernel.org/doc/Documentation/networking/nf_conntrack-sysctl.txt
https://14bytes.ru/blokirovat-li-icmp-trafik-bezopasno-li/
https://habr.com/post/136871/
https://netdevconf.info/1.1/proceedings/slides/kadlecsik-ipset-firewalling-iptables.pdf
