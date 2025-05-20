# mysyslog
Проект mysyslog

Описание

mysyslog — это система журналирования на языке C. Она включает:





Библиотеку libmysyslog для записи логов.



Драйверы libmysyslog-text (логи в текстовом формате) и libmysyslog-json (логи в JSON).



Приложение mysyslog-client для тестирования логов.



Демон mysyslog-daemon для автоматического логирования.



Метапакет mysyslog-meta для установки всех компонентов.

Как установить





Склонируйте репозиторий:

git clone https://github.com/vasya123/mysyslog.git



Перейдите в нужную папку (например, libmysyslog) и соберите:

cd libmysyslog
make
sudo make install

Структура





libmysyslog/ — основная библиотека.



libmysyslog-text/ — драйвер для текстовых логов.



libmysyslog-json/ — драйвер для JSON логов.



mysyslog-client/ — клиент для записи логов.



mysyslog-daemon/ — демон для автоматических логов.



mysyslog-meta/ — метапакет.

Требования





Компилятор GCC (sudo apt install gcc).



Библиотека json-c для JSON драйвера (sudo apt install libjson-c-dev).



Утилиты для deb-пакетов (sudo apt install dpkg-dev debhelper).



systemd для демона.

Подробности по каждому подпроекту — в их README.md.
