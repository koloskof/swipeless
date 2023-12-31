---
description: >-
  Можно много рассуждать относительно блокчейн технологии в контексте разных
  отраслей, однако конкретно в этом диалоге нас интересует может ли он повлиять
  на финансы и денежную сферу (по мотивам лекции
---

# 1. Что такое блокчейн и почему он может быть катализатором больших изменений в фина

Автор конспекта: [Mikhail Koloskov](https://vc.ru/u/15222-mikhail-koloskov)

### Уроки истории для контекста

Чтобы понять, откуда пошел блокчейн, нам нужно разобраться с самим интернетом. История интернета началась в 1974 году. Вначале у нас была примитивная технология Ethernet 1974 году, которая просто соединяла два компьютера. Затем появился протокол TCP/IP 1974, который позволял объединять уже большое количество компьютеров. Это по сути позволяло обмениваться информацией широкому количеству участников сети, но потом 1990 появился HTTP, который представляет протокол позволяющий коммуницировать с помощью Веб-контента (например гипертекстовых ссылок). Это были первые три уровня инфраструктурного развития, после чего дальнейшим драйвером стали коммерческие компании такие, как 3com, Cisco, Amazon. Затем началась важная эпоха по коммерциализации сети и в 1994 году компания Pizza Hut совершила первую online продажу.

<figure><img src="https://leonardo.osnova.io/20bfccf7-db5b-5784-8d30-493ee1996579/-/preview/1900/-/format/webp/" alt=""><figcaption></figcaption></figure>

Сайт назвался [Pizza.net](http://pizza.net/), но если вы просто хотели заказать себе пиццу, была проблема, которая заключалась в отсутствии возможности оплаты онлайн, поэтому люди оплачивали заказ только после доставки.

### Что такое криптография

<figure><img src="https://leonardo.osnova.io/0ef487ea-5c8c-5994-a67c-e0c74d213457/-/preview/1900/-/format/webp/" alt=""><figcaption></figcaption></figure>

Для формирования контекста также хотелось бы затронуть тему криптографии и давайте разберемся, что это вообще такое. По сути дела криптография — это технология, которая шифрует какую-то информацию, чтобы не желательные люди её не расшифровали, то есть это «Коммуникация в присутствии противников». Например, у нас есть вражеская сторона, которая хочет получить нашу информацию, но нам нужно коммуницировать, причём так, чтобы та сторона эту информацию не получила. И природа такой коммуникации берет свое начало ещё с давних времен. Раньше была такая штука, которая представляет собой некий цилиндр, вокруг которого обматывается ткань или кожа и на этой коже были буквы. Суть была в том, чтобы обмотать эти буквы вокруг правильного цилиндра, чтобы прочитать их в нужном порядке. Затем появилась «Энигма» машина в 1920 году (про нее можно посмотреть в фильме «Игра в имитацию»). Дальше в 1976 году в MIT была уже изобретена асимметрическая криптография. Мы не будем углубляться в нее сегодня, однако это прям сердце Биткойна, всех криптовалют и интернета. Ключевой тут является технология, о которой мы говорили раньше — «Коммуникация в присутствии врагов». Речь идет о том, как сохранить секрет, когда все его хотят узнать. Вообще криптография — это причина того, почему у нас сегодня работает интернет.

В 1996 году был изобретен протокол SSL/TLS, который накладывается поверх уровня TCP/IP и используется для асимметричного шифрования (это технология, которая защищает весь интернет полностью). Вдруг сразу после появления этой технологии пиццу уже можно было заказывать полностью онлайн и с помощью определенного кода её оплачивать. С коммерческой стороны появилась компания PayPal.

### Неудачные электронные деньги 1989 - 1990

Раннее были и другие компании, которые пытались создать свою интернет валюту, но большинство из них безуспешно. Однако есть несколько инноваций, которые действительно работали, это Alipay 2003 и M-PESA 2007.

Тем не менее вопрос всё равно остался «Как двигать деньги или ценность по интернету без каких-либо посредников или централизатора» и вот это движение ценности без централизатора и есть основа блокчейна. Сатоши Накамото решил эту проблему. \[14:24]

<figure><img src="https://leonardo.osnova.io/4a779edd-19c4-52e2-aa68-ff7fbd8115b6/-/preview/1900/-/format/webp/" alt=""><figcaption></figcaption></figure>

Это то самое электронное письмо, которое отправили Сатоши на Хелоуин 2008-го года. Он очень кратко и ясно выразил мысль в своем электронном письме: «Я работал над новой электронной платёжной системой от человека к человеку, без нужды в каком-либо дополнительном посреднике». Это довольно скромное заявление, которое сделал Сатоши Накамото. Вопрос заключается в том, будет ли Биткойн некоторым следующим слоем в Интернете.

<figure><img src="https://leonardo.osnova.io/5a91224d-e655-525f-a8d7-1e8608d110a0/-/preview/2000/-/format/webp/" alt=""><figcaption></figcaption></figure>

На самом деле на этот вопрос сейчас никто не может ответить точно. Как всегда есть максималисты, которые думают, что это следующая большая штука и есть те, кто думают, что Биткойн никогда не выстрелит. Мы будем рассматривать обе этих точки зрения и это даст нам ключ к пониманию всей сути.

### Что такое блокчейн

И так что же такое блокчейн? Это база данных с отметками во времени. Это означает, что вы можете добавлять туда небольшие куски информации и они будут содержать время, когда они были добавлены.

<figure><img src="https://leonardo.osnova.io/5ecd77cd-f994-5386-9646-1f06567c5ab1/-/preview/2000/-/format/webp/" alt=""><figcaption></figcaption></figure>

Кстати, Сатоши не изобрел блокчейн. Его изобрел Стюарт Харбор, который работал в Bell Labs. Так вот эти отмеченные временем блоки информации создают базу данных. Прозрачную базу данных, которую можно всегда просматривать. Она конечно же защищена криптографией.

Также важной частью блокчейна является Хеш-функция, которую изначально использовали в базах данных для того, чтобы находить информацию в них и сохранять структурированную базу данных. Однако в блокчейне Хеш-функции приняли немного другое значение. Помимо того, что их начали использовать, чтобы присоединить новый блок к старому блоку в цепочке блоков их так же стали использовать для подтверждения транзакций и более наглядного хранения информации опять же в базе данных Блокчейнов.

Здесь криптография играет большую роль в защите от взлома блокчейна и его прозрачности. На самом деле Хеш-функции и асимметрическое шифрование являются двумя составляющими, которые играют наиболее важную роль в блокчейне.

Ещё одной фундаментальной составляющей является консенсус соглашения. То есть это та часть программного кода, которая определяет когда мы добавляем блок-за-блоком-блок-за-блоком, кто будет добавлять следующий блок. То есть вот этот процесс соглашения и выбора следующего блока как раз и называется - консенсус протокол. Относительно них есть куча дискуссий, но в общем они адресуют такую вещь, как стоимость доверия. Также мы поговорим про задачи византийских генералов. Это затрагивает теорию игр и теорию вероятности и многие другие вещи, которые плотно с этим связаны. Это на самом деле то, что и решил Сатоши Накамото (он решил проблему с византийскими генералами).

### Пицца за биткойны

Через полтора года после того, как Сатоши опубликовал свой Биткойн и запустил его в сеть, появляется вот такое сообщение. Это оригинальный текст.

<figure><img src="https://leonardo.osnova.io/6f0294df-eb32-589b-9d62-a4acfa0f7dfe/-/preview/2000/-/format/webp/" alt=""><figcaption></figcaption></figure>

«Я заплачу вам 10 000 Биткойн за парочку пицц…» и обратите внимание на дату это 18 мая 2010-го. Основной момент тут в том, что кто-то пытается использовать Биткоины для того, чтобы оплатить что-то. Пускай даже в интернете. 16 месяцев с момента выпуска Биткойна этого ещё никто не делал, но вот Лазло, информатик со штата Флорида вдруг захотел что-то купить Биткойнами.



Спустя 3 дня он так и не получил свою пиццу и он пишет.

<figure><img src="https://leonardo.osnova.io/6f0294df-eb32-589b-9d62-a4acfa0f7dfe/-/preview/2000/-/format/webp/" alt=""><figcaption></figcaption></figure>

«Что никто не хочет продать мне пиццу, я что предлагаю слишком мало Биткойнов». Проходит ещё один день, он наконец-то получает свои пиццы. На момент 22 мая 2010 года эти Биткойны стояли 41$ Это $20.50 за пиццу. 22 мая теперь всем известен как Биткойн Пицца День.

### Своими словами про биткойн

<figure><img src="https://leonardo.osnova.io/63aa1417-6b36-5d00-810d-daa0b32b1eae/-/preview/2000/-/format/webp/" alt=""><figcaption></figcaption></figure>

блокчейн достоверно перемещает данные внутри децентрализованной сети и экономика блокчейна как раз-таки и заключается в этих терминах. Это экономика верификации и экономика сети. Во многих случаях Блокчейн добавляет некоторые стоимости к процессу верификации для этого консенсус протокола, но в то же время он снижает другие стоимости. Потому что нам ненужно оплачивать расходы на какой-то третью сторону, которая будет проверять наши транзакции. Этот компромисс между стоимостью проверки. Эти самые данные могут иметь какую-то стоимость, как например Биткоин (в качестве формы денег) или эти данные могут быть компьютерным кодом. То есть мы можем переводить как деньги, так и подтвержденный компьютерный код (дальше мы затронем тему смарт-контрактов). Так же Биткойн идет фундаментально к идее прямо в основу финансов.

Потому что фундаментально деньги — это движение ценности и рисков внутри сети и вот эта вот сеть — это 8 млрд человек, которые живут на этой планете. Те кто проходил финансовый курс знают, что движение денег и рисков очень плотно связанны друг с другом. Это движение в целом и есть экономика. Однако есть и одно препятствие связанное с блокчейнами.

В основном к ним относятся технические, коммерческий и препятствия государственной политики. И будет ли они решены, мы пока ещё не знаем. блокчейн может быть катализатором до финансов в целом и денег в частности.

Будет ли он таким, мы пока ещё не уверенны.
