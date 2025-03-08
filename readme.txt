BitCoin v0.1.3 ALPHA

Авторские права (c) 2009 Satoshi Nakamoto
Распространяется по лицензии программного обеспечения MIT/X11, см. прилагаемый
файл license.txt или http://www.opensource.org/licenses/mit-license.php.
Этот продукт включает программное обеспечение, разработанное OpenSSL Project для использования в
OpenSSL Toolkit (http://www.openssl.org/). Этот продукт включает
криптографическое программное обеспечение, написанное Эриком Янгом (eay@cryptsoft.com).

Введение
-----
Биткойн — это система электронных денег, которая использует одноранговую сеть для предотвращения
двойных трат. Она полностью децентрализована без сервера или
центрального управления.

Операционные системы
-----------------
Windows NT/2000/XP (и, вероятно, Vista)

Vista еще не тестировалась. Все используемые библиотеки являются кроссплатформенными, поэтому
нет ничего, что бы мешало будущим сборкам Linux и Mac.

Настройка
-----
Распакуйте файлы в каталог и запустите bitcoin.exe.

Программное обеспечение автоматически находит другие узлы для подключения. Вам следует настроить
брандмауэр на переадресацию порта 8333 на ваш компьютер, чтобы вы могли принимать входящие
подключения, в противном случае количество узлов, к которым вы можете подключиться, будет ограничено.

Чтобы поддержать сеть, запустив узел, выберите:

Параметры-> Генерировать монеты

и оставьте программу открытой или свернутой. Она работает с приоритетом простоя, когда никакие другие
программы не используют ЦП. Ваш компьютер будет решать очень сложную
вычислительную задачу, которая используется для блокировки блоков транзакций. Время
генерации блока каждый раз разное, но может занять дни или месяцы, в зависимости
от скорости вашего компьютера и конкуренции в сети. Это не
вычисление, которое должно начинаться с самого начала, если вы остановите и перезапустите его. Решение может быть найдено в любой момент его работы. В качестве награды
за поддержку сети вы получаете монеты, когда успешно генерируете
блок.

---

BitCoin v0.1.3 ALPHA

Copyright (c) 2009 Satoshi Nakamoto
Distributed under the MIT/X11 software license, see the accompanying
file license.txt or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).  This product includes
cryptographic software written by Eric Young (eay@cryptsoft.com).


Intro
-----
Bitcoin is an electronic cash system that uses a peer-to-peer network to
prevent double-spending.  It's completely decentralized with no server or
central authority.


Operating Systems
-----------------
Windows NT/2000/XP (and probably Vista)

Vista hasn't been tested yet.  All the libraries used are cross-platform, so
there's nothing preventing future Linux and Mac builds.


Setup
-----
Unpack the files into a directory and run bitcoin.exe.

The software automatically finds other nodes to connect to.  You should set
your firewall to forward port 8333 to your computer so you can receive incoming
connections, otherwise the nodes you can connect with will be limited.

To support the network by running a node, select:

  Options->Generate Coins

and keep the program open or minimized.  It runs at idle priority when no other
programs are using the CPU.  Your computer will be solving a very difficult
computational problem that is used to lock in blocks of transactions.  The time
to generate a block varies each time, but may take days or months, depending
on the speed of your computer and the competition on the network.  It's not a
computation that has to start over from the beginning if you stop and restart
it.  A solution might be found at any given moment it's running.  As a reward
for supporting the network, you receive coins when you successfully generate a
block.
