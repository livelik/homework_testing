## Что такое DNS (Domain Name System)

В интернете, как и в обычной мире, чтобы найти кого-то или что-то, нужно знать, по каким признакам нужно производить поиск и отличать одно от другого. К примеру, в реальной жизни надо знать адрес, фамилию и имя друга для того, чтобы попасть к нему в гости и не обознаться местом, попав к какой-нибудь ворчливой старушке. Можно, конечно, старательно запомнить скучные номера дома и квартиры, а также с важностью обратиться по имени-отчеству к приятелю, однако не всегда человеческая память работает так совершенно. Вместо стройных номеров и названий проще отличить место обитания товарища по рисункам на стене дома и синей двери квартиры, а называть его гораздо приятней "Вася", чем "Василий Петрович". 
Так же и в интернете: реальный адрес сайта, называющимся *IP-адресом*, состоит из незапоминающихся чисел. Для того, чтобы людям было проще находить свои любимые и не очень сайты, была создана *DNS - система доменных имён*. *Доменное имя* - это "название" сайта, которое вводится в строке браузера (программы, обеспечивающей отображение сайтов), например, vk.com, и состоит из нескольких частей. "com" - это *корневой домен* или *домен первого уровня* (дом, где проживает товарищ), а "vk" - это *домен второго уровня* (квартира). Корневые домены часто показывают принадлежность сайта к какой-либо стране, например, .ru - Россия, .kz - Казахстан, поэтому их часто называют доменными зонами. Домен второго уровня - это собственное имя сайта, которое должно быть уникальным в пределах зоны. В теории уровней может быть бесчисленное количество, но, как правило, их не очень много. Такое имя гораздо проще запомнить, чем 87.240.165.82.

**Процесс поиска IP-адреса называется DNS-запросом и выглядит так:**

1. В адресной строке браузера вводится доменное имя.
2. Далее браузер узнаёт у компьютера, есть ли у него в *DNS-кэше* IP-адрес этого сайта. Кэшем называется память компьютера, в котором хранится всякая временная информация, в нашем случае IP-адреса сайтов. 
3. Если адреса в памяти нет, то браузер обращается к *DNS-серверу* - устройству, помогающему преобразовать человекочитаемые доменные имена в IP-адреса. 
4. DNS-сервер сообщает компьютеру IP-адрес и сайт появляется на экране во всей красе.