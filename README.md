Курсовая работа по теме имитационная модель ВКО

Чтобы запустить все станции одновременно нужно исполнить скрипт system_launch.sh

Чтобы остановить stop_system.sh

Алгоритмы работы и карта расположения станций находятся в директории files/

Папки ZRDN1-3,SPRO,RLS1-3 используются для работы станций, а также туда приходят сообщения от КП для подтверждения того, что станция жива

Станции отсылают всю информацию о работе в зашифрованном виде в директорию messages, откуда эти сообщения читает КП и записывает в журнал работы и базу данных

Скорее всего есть проблема с определением летит ли баллистический блок, обнаруженный РЛС в зону действия СПРО
