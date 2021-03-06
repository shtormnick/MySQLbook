# Вступление 
## Что такое базы данных
База данных представляет собой отдельное приложение, которое хранит набор данных. Каждая база данных имеет один или несколько различных API для создания, доступа, управления, поиска и репликации данных, которые она хранит.

Могут также использоваться другие типы хранилищ данных, такие как файлы в файловой системе или большие хеш-таблицы в памяти, но извлечение и запись данных не будут такими быстрыми и легкими в этих типах систем.

В настоящее время мы используем системы управления реляционными базами данных (RDBMS) для хранения и управления огромным объемом данных. Это называется реляционной базой данных, поскольку все данные хранятся в разных таблицах, а отношения устанавливаются с использованием первичных ключей или других ключей, известных как внешние ключи.

**Система управления реляционными базами данных** (RDBMS)- это программное обеспечение, которое -

* Позволяет реализовать базу данных с таблицами, столбцами и индексами.

* Гарантирует ссылочную целостность между строками различных таблиц.

* Автоматически обновляет индексы.

* Интерпретирует SQL-запрос и объединяет информацию из разных таблиц.

 ## RDBMS Терминология 

Прежде чем мы перейдем к объяснению базы данных MySQL, давайте пересмотреть несколько определений, связанных с базой данных.

* **База данных**. База данных представляет собой набор таблиц со связанными данными.

* **Таблица**. Таблица - это матрица с данными. Таблица в базе данных выглядит как простая электронная таблица.

* **Столбец**. Один столбец (элемент данных) содержит данные одного и того же типа, например почтовый индекс столбца.

* **Строка**. Строка (= кортеж, запись или запись) представляет собой группу связанных данных, например данные одной подписки.

* **Избыточность** - сохранение данных дважды, избыточно, чтобы сделать систему быстрее.

* **Первичный ключ** - первичный ключ уникален. Значение ключа не может встречаться дважды в одной таблице. С помощью ключа вы можете найти только одну строку.

* **Внешний ключ**. Внешний ключ - это связующий штырь между двумя таблицами.

* **Compound Key** - составной ключ (составной ключ) - это ключ, состоящий из нескольких столбцов, потому что один столбец недостаточно уникален.

* **Индекс**. Индекс в базе данных напоминает индекс в конце книги.

* **Ссылочная целостность** - ссылочная целостность гарантирует, что значение внешнего ключа всегда указывает на существующую строку.

## MySQL База Данных

MySQL - это быстрая и простая в использовании (RDBMS), используемая для многих малых и крупных предприятий. MySQL разрабатывается, продается и поддерживается MySQL AB, которая является шведской компанией. MySQL становится настолько популярным из-за многих веских причин -

* MySQL выпущен под лицензией с открытым исходным кодом. Поэтому вам нечего платить, чтобы использовать его.

* MySQL - очень мощная программа сама по себе. Он обрабатывает большой набор функциональных возможностей самых дорогих и мощных пакетов баз данных.

* MySQL использует стандартную форму хорошо известного языка данных SQL.

* MySQL работает во многих операционных системах и на многих языках, включая PHP, PERL, C, C ++, JAVA и т. Д.

* MySQL работает очень быстро и хорошо работает даже с большими наборами данных.

* MySQL очень дружит с PHP, самым ценным языком для веб-разработки.

* MySQL поддерживает большие базы данных, до 50 миллионов строк и более в таблице. Предел размера файла по умолчанию для таблицы составляет 4 ГБ, но вы можете увеличить его (если ваша операционная система справится с этим) до теоретического предела в 8 миллионов терабайт (ТБ).

* MySQL настраивается. Лицензия GPL с открытым исходным кодом позволяет программистам изменять программное обеспечение MySQL в соответствии с их конкретными средами.

Прежде чем начинать этот учебник, вы должны иметь базовые знания в информации, содержащейся в наших учебниках по PHP и HTML.

В этом учебном пособии основное внимание уделяется использованию MySQL в среде PHP. Многие примеры, приведенные в этом уроке, будут полезны для программистов PHP.
