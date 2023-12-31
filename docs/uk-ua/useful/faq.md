### Питання №1: Що робити, якщо антивірус не дозволяє завантажити файл або при завантаженні програми, видаляє файли?
> **Відповідь №1: Додайте папку у виключення антивірусу (пошукайте в інтернеті, як це зробити для вашої антивірусної програми), та скачайте свіжий .zip-файл**.

### Питання №2: Чи потрібно активувати Anti-Warden у програмі?
> **Відповідь №2: Ні, не потрібно, оскільки Anti-Warden вже активовано**.

### Питання №3: Що робити, якщо програма завантажується в гру, але на мінікарті не з'являється іконка?
> **Відповідь №3: Переконайтеся, що ви не активували Anti-Warden, і щоб програма працювала правильно, режим вікна (Windowed Mode) має бути включений у налаштуваннях гри (WoW)**.

### Питання №4: Що робити, якщо під час запуску програми з'являється таке вікно?
![Помилка](https://darhanger.github.io/rotations/uk-ua/_media/ni.png)
> **Відповідь №4: Це просто, ваш антивірус видалив важливі файли, прочитайте Відповідь №1 та скачайте свіжий .zip-файл**.

### Запитання №5: При спробі запустити гру через лаунчер програми з'являється помилка #134?
> **Відповідь №5: У вас є щось, що заважає програмі інжектитись, чи ігрові файли пошкоджені, чи конфлікт патчів. Якщо ви граєте на серверах Blizzlike (без кастомного контенту аля Sirus.su), скачайте [Чистий клієнт WoW 3.3.5a](https://www.mediafire.com/file/eldh1vuxh619co0/WoW_3.3.5a.torrent/file)* *.

### Питання №6: При спробі запустити гру через лаунчер програми з'являється помилка #132?
> **Відповідь №6: Помилка #132 може бути викликана безліччю причин, але здебільшого це відбувається, коли виникає проблема із читанням/записом ігрових даних у ОЗУ. Щоб виправити це, спробуйте такі методи: **.
> - Перевірити чи на лаучері програми у властивості файлу стоїть запуск від імені адміністратора;
> - Перевірити чи на файлі WoW.exe (у папці World of Warcraft), у властивостях файлу стоїть запуск від імені адмінстратора;
> - Видаліть усі тимчасові файли (папки Cache/WTF);
> - Оновіть драйвери;
> - Спробуйте запустити гру в режимі OpenGL в окремому вікні без звуку:
>   - Відкрийте папку World of Warcraft на жорсткому диску
>   - Відкрийте папку WTF
>   - Відкрийте файл Config.wtf і додайте або змініть наступні рядки:
>     - Для увімкнення режиму OpenGL: SET gxAPI "OpenGL"
>     - Для вимкнення звуку: SET Sound_EnableAllSound "0"
>     - Для запуску гри у віконному режимі: SET gxWindow "1"
> - Перевірте диск на наявність помилок;
> > **Примітка:** Запропоновані вище поради не є єдиними рішеннями цієї проблеми.