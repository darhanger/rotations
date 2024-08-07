## 1.4.0 (20/07/2024)
**Изменения**
- Небольшие улучшение в безопасности (чтобы не отлететь на других серверах);
- Количество эффектов [Неустойчивости] можно уменьшать до 0;
- Изменения "стопкаст тракера" - мало кто знал что эта функция есть более чем 4 года, но для её работы требуется выбирать некоторых НИП в фокус. Сейчас функция работает в полном автоматическом режиме;
- Оптимизация главного UI программы;
- Оптимизация / удаление старого/не ненужного кода;
- Оптимизация всех макросов которые используются в профилях;

**Новое**
- Добавлены нормальные кейбинды, по типу таких как были в PQR;

## 1.3.9d (20/04/2024)
- Небольшие улучшения в плане безопасности;
- Удаление старых и больше не нужных функций;
- «Обертка» для новых функций;
- Обновлена ​​функция **Автоматическое следование**:
  - Раньше все заклинатели (+охотники) имели небольшую дистанцию ​​~10 метров. На данный момент оно имеет случайное значение (расстояние от сопровождающей цели до вас), но не менее 7-8 метров;
    - Теперь, включив ближний бой, даже заклинатели (+охотники) смогут следовать за целью на расстоянии 1-2 метра;
  - То же самое с классами ближнего боя. На данный момент у них есть случайное расстояние следования, которое время от времени меняется;
- Изменение функции паузы ротаций;
- Добавлена ​​функция привязки клавиш для графического интерфейса /включения профилей, для любой клавиши (будет расширена позже);

## 1.3.9b (20/03/2024)
- Добавлен новый функционал;
- Небольшое обновление безопасности;

## 1.3.8 (24/01/2024)
- Поддержка сервера **Warmane Onyxia** и его классических заклинаний;
- Все функции и какое-то взаимодействие между ними, которое проверяло текущий спек персонажа - переделаны, и будут работать более корректно с минимальной нагрузкой;
- Немного исправлена и доработана функция автоследования. Теперь все ренжевики, ака охотники, лекари, маги/локи и тд, будут держать дистанцию ~ 10 м, от цели за которой следуете, все милишники по прежнему будут бегать в притык за целью;
- Сделал некоторые изменения для быстрого включения/отключения каких-то конкретных/отдельных функций в ядре дистанционно;
- Так же немного изменил систему активации профилей в общем и целом;
  - Сделал доступной функцию "Бесплатные выходные" - при которой будут доступны все классы для всех на какой-то короткий период времени;
- Сделал системные фреймы динамическими. При включенном режиме стримера, будет отображаться только текст в чате;
- Немного изменил проверку использования предметов, зелий и остального. Теперь будет сверка уровней, эффектов и выбор лучшего доступного для вас в данный момент;

## 1.3.7d (22/11/2023)
- Небольшие оптимазции и твики для Режима Стримера;
  - Исправлен баг когда отображалась ели заметная полоска цвета в GUI профилей при включенном режиме Классовые цвета;
- Небольшие доработки безопасности и защиты;
- Прогноз Исцеления
  - Оптимизация функции и подсчета;
    - Должно положительно сказаться на производительности при игре за лекарей. Даже если вы не использовали данную функцию;

## 1.3.7c (10/11/2023)
- Небольшие оптимазции и твики для Режима Стримера;
- Во все элементы программы добавлены звуковые сопровождения. Теперь весь интерфейс и 99% его состовляющих WoW-Looklike;
- Небольшие изменения в Healing Engine;
  - Более точные проверки некоторых юнитов;
- Вроде как должно немного улучшить производительность;
  - Скорее всего не будут такие сильные просадки по ФПС, или наоборот у некоторых даже ФПС подниметься;

## 1.3.6 (17/09/2023)
- Улучшена безопасность;
- Небольшие исправления;
- Авто-обновление/скачивание файлов Ядра при запуске лаунчера.

## 1.3.5b (16/08/2023)
- Улучшена безопасность;
- Небольшие исправления;
- Новые функции для GUI профилей;
   - Будут использованы в профилях в будущих обновления;
- Доработка Healing/Members engine;
   - Союзники в контроле будут автоматически игнорироваться и не исцеляться / не диспелиться и тд;

## 1.3.5a (01/08/2023)
- Улучшенная безопасность;
- Мелкий багфикс;

## 1.3.5 (21/07/2023)
**Новое:**
- Изменен дизайн MainUI (окна программы);
	- Некоторые элементы переехали на другие места;
	- Меню стало более понятным;
- Профили теперь умеют подгружать до 3-х (трех) пресетов настроек;
- Добавлена **"Настраиваемая кнопка #2"** (будет применена в новых обновлениях);
- Обновленный пункт меню **"Настройки ротаций"**;
- Обновлен дизайн с интеграцией ElvUI;
- Добавлены кнокпки "Быстрого удаления" ников танков;
- Добавлена возможность игнорировать/уменьшать/увеличивать стаки https://wotlk.evowow.com/?spell=70106 / https://wotlk.evowow.com/?spell=69766 ;

**Исправления**:
- Исправления по Healing / Members Engine;
- Небольшие фиксы багов;
- Оптимизация тяжелого кода;

## 1.3.4d (20/06/2023)
- Небольшие доработки;
- Исправлена проблема из-за которой ротации могли останавливаться после сбора добычи с мобов/сундуков и тд.

## 1.3.4c (05/06/2023)
- Небольшие доработки;

## 1.3.4b (26/05/2023)
- Обход + "защита" возможного детекта на Circle от 26/05/2023;

## 1.3.4a (21/05/2023)
- Исправление опечаток;

## 1.3.4 (21/05/2023)
**Новое:**
- Полностью новый Healing / Members Engine - быстрее, правильней, с более крупным функционалом;
	- Теперь программа и профили с 99% вероятностью определяют специализации союзников;
		- **ВАЖНО**: Функция достаточно хитрая и запись и проверка всей этой информации происходит когда вы не в бою, то есть, если Вы сделаете по    середине боя какой-то /reload вся информация очистится и профили и софт будет работать некорректно;
		- **ВАЖНО #2**: При любом включённом профиле может хромать осмотр других персонажей, так как функция задействует обходной путь проверки специализаций. **ЭТО НЕ БАГ, так должно быть, пока мне не удалось это победить но думаю через пару дней сделаю маленький релиз где смогу это обойти**;
- Новый метод загрузки профилей, получения настроек и тд.;
	-  В теории и на практике дает чуть более быструю загрузку и обработку всей информации и в целом кода;
	-  Так же позволило обновлять профили и некоторый функционал ядра практически бесшовно;
- Все профили ОПЯТЬ стали еще чуть меньше, в среднем на ~ 3-10% при более обширном функционале;
- Большой ряд оптимизаций ядра и в целом кода профилей;
- **Warmane**: Добавлен костыль для этого сервера, что-бы функционал профилей и ядра исполнял свою работу правильно;

**Исправления**:
- Небольшие фиксы багов;
- Оптимизация тяжелого кода;