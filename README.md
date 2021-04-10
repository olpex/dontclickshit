# Як не стати кібер-жертвою

Правила персональної кібербезпеки, які врятують вам гроші, нерви, а може й життя.

Ця пам'ятка – результат роботи спеціалістів з кібербезпеки, які мають багаторічний досвід побудови, перевірки та етичного зламу комп'ютерних систем, додатків та мереж. Ці настанови надаються "як є", автори не несуть відповідальності за ваші дії або бездіяльність. Ви можете поширювати цю пам'ятку, використовувати її у бізнесі, та змінювати на власний розсуд. Це безплатно. Посилання на джерело вітаються та не є обов'язковими.

Дякую, що приділяєте увагу власній кібербезпеці. Поділіться цими правилами з близькими, друзями та колегами, щоб зробити світ трохи безпечнішим. Якщо у вас є що додати або ви знайшли в тексті помилку, напишіть на :email: sapran@protonmail.com або [створіть issue](https://github.com/sapran/dontclickshit/issues/new).


## Зміст

1. [Не натискайте каку](#user-content-не-натискайте-каку)
1. [Використовуйте парольні менеджери](#user-content-використовуйте-парольні-менеджери)
1. [Використовуйте двофакторну автентифікацію](#user-content-використовуйте-двофакторну-автентифікацію)
1. [Використовуйте безпечні месенджери](#user-content-використовуйте-безпечні-месенджери)
1. [Використовуйте віртуальні приватні мережі (VPN)](#user-content-використовуйте-віртуальні-приватні-мережі-vpn)
1. [Шифруйте дані](#user-content-шифруйте-дані)
1. [Операційна система та програми](#user-content-операційна-система-та-програми)
1. [Антивірус](#user-content-антивірус)
1. [Фаєрвол](#user-content-фаєрвол)
1. [Робіть резервні копії](#user-content-робіть-резервні-копії)
1. [Мобільна безпека](#user-content-мобільна-безпека)
1. [Фізична безпека](#user-content-фізична-безпека)
1. [Подяка](#user-content-подяка)

## Не натискайте каку

### Що мається на увазі?

Не відкривайте, не натискайте, та не запускайте підозрілі файли, посилання та програми. 💡 Головне правило: якщо ви на це (лист, файл, посилання тощо) не чекали, – це підозріло.

### Підозрілі файли

Не відкривайте підозрілі файли, вкладення електронної пошти, або архіви, якщо ви не довіряєте відправнику. Файли або посилання від людей, яких ви не знаєте, повинні розцінюватися як шкідливі за замовчуванням. Відправляйте небажані повідомлення в спам перед прочитанням.

Якщо ви знаєте відправника, але не очікуєте від нього повідомлень та файлів, перевірте, чи це він. Можливо, його месенджер або email було викрадено. Перевіряйте безпечність повідомлення іншим шляхом, ніж той, який використовувався для передачі. Наприклад, якщо ви отримали документ MS Word електронною поштою, зв'яжіться з відправником за допомогою месенджера або телефоном та спитайте в нього про мету відправки файлу та взагалі, чи він вам його відправив.

:exclamation: Найбільш ризиковані типи файлів:
- Будь-які виконувані файли: `EXE`, `COM`, `CMD`, `BAT`, `PS1`, `SWF`, `JAR`, `JS`, `VBS` тощо.
- Документи MS Office, особливо з макросами: `DOC/DOCX/DOCM`, `XLS/XSLX/XLSM` тощо.
- PDF документи: `PDF`.
- Файли векторної графіки з вбудованим кодом: `SVG`.
- Архіви файлів, особливо захищені паролем.

Іноді, особливо під тиском часу, буває важко розпізнати шкідливі файли. Для швидкої перевірки, користуйтесь сервісом VirusTotal. Це сервіс, який перевіряє файли одночасного в більш ніж 50 антивірусах. Але ❗ враховуйте той факт, що завантажуючи файли на VirusTotal ви надаєте доступ до нього третім особам.

:wrench: VirusTotal: https://virustotal.com

### Підозрілі посилання

Не відкривайте підозрілі покликання (URL), особливо ті, що вказують на вебсайти, які ви не відвідуєте. Завжди перевіряйте доменні імена вебсайтів, перш ніж натиснути на посилання. Зловмисники можуть замаскувати назву сайту під щось знайоме (`facelook.com`, `gooogle.com` тощо) Використовуйте HTTPS та перевіряйте SSL-сертифікат вебсайту, щоб переконатися в його справжності.

Шкідливі URL-адреси можуть ховатися за довільним текстом в HTML-файлах, документах та електронних листах. У веббраузері або поштовій програмі наведіть курсор миші на покликання (але не натискайте) і почекайте 1-2 сек, поки не "спливе" справжній URL за покликанням. Можна клацнути правою кнопкою миші на покликанні та скопіювати його в текстовий редактор, щоб побачити його справжню адресу. Використовуйте VirusTotal для перевірки підозрілих покликань так само як для сканування файлів.

Шкідливі вебадреси можуть бути закодовані в вигляді QR-кодів та навіть видруковані на папері, в тому числі в формі скорочених URL, згенерованих спеціальними сервісами на кшталт `tinyurl.com`, `bit.ly`, `cutt.ly` тощо. Не вводьте ці посилання в браузер та не скануйте QR-коди вашим смартфоном якщо ви не довіряєте їхньому вмісту та походженню.

:wrench: Розгорнути скорочені URL перед відкриттям можна за допомогою цих вебсайтів:
- http://checkshorturl.com/
- http://www.expandurl.net/

### Спливаючі (pop-up) вікна

Будьте обережні зі спливаючими вікнами та повідомленнями у браузері, програмах, операційній системі та смартфоні. Завжди читайте вміст спливаючих вікон та не "схвалюйте" або "приймайте" нічого похапцем.

Нападники використовують спливаючі вікна у різний спосіб: встановлюють у вашій системі підробні SSL-сертифікати, щоб перехоплювати ваш мережевий трафік; встановлюють зловмисні програми на ваш комп'ютер або смартфон, перенаправляти ваш веббраузер на шкідливі або зламані вебсайти, які заражають комп'ютери вірусами.

### Підозрілі пристрої

Не підключайте флешки та зовнішні диски, не вставляйте CD та DVD у ваш комп'ютер, якщо ви не довіряєте їхньому джерелу. Існують техніки зламу комп'ютера ще до того, як ви відкриєте файл на флешці, та задовго до того, як ваш антивірус його просканує. Якщо ви знайшли пристрій в офісі або на вулиці, якщо ви отримали його поштою або кур'єром, якщо незнайомець дав вам його з проханням роздрукувати документ на принтері або просто відкрити та перевірити його вміст – є шанси, що такий пристрій є шкідливим. Довіряйте лише власним носіям та будьте обережні з пристроями, які отримуєте від інших людей.

## Використовуйте парольні менеджери

Використовуйте парольні менеджери для створення, збереження та захисту паролів та виконуйте такі правила:

1. Генеруйте довгі, випадкові паролі довжиною від 20 символів.
1. Створіть складний та довгий майстер-пароль для входу в парольний менеджер.
1. Оберіть парольний менеджер, який шифрує базу даних перед зберіганням її в хмарі або синхронізацією між пристроями мережею.
1. Частіше, бажано автоматично, робіть резервні копії бази даних паролів.

:wrench: Приклади надійних парольних менеджерів:
- 1Password https://1password.com (non-free)
- Bitwarden https://bitwarden.com (free & opensource)
- Dashlane https://www.dashlane.com/ (free with limitations or non-free premium)
- KeePassXC https://keepassxc.org/ (free & opensource, DIY cloud sync)

### Тримайте паролі в секреті

Ніхто крім вас не повинен знати ваші паролі. Не розказуйте їх нікому, включаючи вашого боса, вашого сисадміна або службу підтримки, вашу дружину, ваших батьків, ваших дітей тощо. В них немає жодних логічних або законних підстав для отримання ваших паролів. З технічної точки зору, навіть система, в якій ви використовуєте пароль, не має доступу до нього в первісному вигляді. Замість цього система зберігає "хеш" – криптографічно захищену копію пароля.

### Як вигадати мастер-пароль?

Пароль до сховища паролів – це ваш майстер-пароль. Зручний та надійний майстер-пароль складається з чотирьох та більше не пов'язаних між собою слів. Для підсилення паролю, одне з цих слів можна написати у верхньому регістрі.

:bulb: Приклади сильних паролів, згенерованих програмою 1Password:

`hyping-BASKET-bouquet-outs`

`tinsel-dolt-INDIGENT-echo`

### Оновлення паролів

:bulb: "Правило буравчика": чим частіше ви використовуєте пароль, тим частіше він повинен змінюватись.

### Перевірити чи пароль не скомпрометовано

Витоки баз даних логінів та паролів відбуваються щодня. Перевірте, чи не скомпрометовано ваш пароль за допомогою вебсайту Троя Ханта [';--have i been pwned?](https://haveibeenpwned.com). Зареєструйтесь на вебсайті, щоб отримувати повідомлення про майбутні компрометації ваших облікових записів.

## Використовуйте двофакторну автентифікацію

### Увімкніть двофакторну автентифікацію

Всі сучасні онлайн-сервіси підтримують двофакторну автентифікацію. Увімкніть її за допомогою програмного токена Microsoft, Facebook, Twitter, Google, Authy тощо. Деякі парольні менеджери також мають цю функцію.

:wrench: Налаштування двофакторної автентифікації популярних сервісів:

- [Apple](https://support.apple.com/en-us/HT204915)
- [Google](https://myaccount.google.com/security/signinoptions/two-step-verification)
- [Facebook](https://www.facebook.com/settings?tab=security&section=approvals)
- [Twitter](https://twitter.com/settings/security)

:wrench: Решту сервісів ви знайдете на цьому вебсайті: https://twofactorauth.org

Найкращий другий фактор автентифікації – це ключ безпеки або токен. Найпопулярніші ключі безпеки:

- [Yubikey](https://www.yubico.com/)
- [Google Titan](https://cloud.google.com/titan-security-key)

:wrench: Зручні додатки для збереження другого фактору:

- [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2)
- [Authy](https://authy.com/download/)

### Уникайте SMS

Для двофакторної автентифікації, використовуйте `Google Authenticator`, інший додаток, або ключ безпеки. Уникайте використання одноразових паролів через SMS – це вкрай небезпечно.

## Використовуйте безпечні месенджери

Використовуйте надійне наскрізне шифрування (End-to-End Encryption, E2E) для передачі приватних та конфіденційних повідомлень. Наскрізне шифрування гарантує, що ніхто окрім вас і вашого співрозмовника не може отримати доступ до даних.

:wrench: Безпечні месенджери:

- Signal https://signal.org
- Threema https://threema.ch
- Wire https://wire.com
- Keybase https://keybase.io

:bulb: Порівняння безпеки месенджерів: https://www.securemessagingapps.com

## Використовуйте віртуальні приватні мережі (VPN)

Щоб захистити ваш мережевий трафік від прослуховування, використовуйте віртуальні приватні мережі (Virtual Private Networks, VPN). Найкращий спосіб зробити це – встановити свій власний VPN-сервер.

:bulb: Algo – розгорнути власний сервер VPN в будь-якому популярному хмарному сервісі: https://github.com/trailofbits/algo

:bulb: Outline – ще простіший спосіб налаштувати власний сервер VPN: https://getoutline.org/

Використання VPN-сервісів взагалі не рекомендується, але може бути допустимим, коли немає змоги скористатися власним VPN.

:wrench: Порівняльна таблиця VPN-сервісів: https://thatoneprivacysite.net/#simple-vpn-comparison

## Шифруйте дані

### Перевіряйте шифрування вебсайтів

Завжди переконуйтесь, що вебсайт, якому ви передаєте свої чутливі дані, використовує HTTPS. Це означає, що його адреса в адресному рядку браузера починається з `https://` та його сертифікат перевірений вашим браузером, отже він не робить вам попереджень безпеки.

Однак, наявності HTTPS не достатньо для повної довіри до вебсайту: будь-хто може згенерувати дійсний сертифікат для свого вебсервера. Потрібно звернути увагу та перевірити правильність доменного імені вебсайту, тому що його можна  підробити.

:exclamation: Ніколи, навіть для тимчасового використання, не приймайте недійсні сертифікати SSL.

### Шифруйте хмарні дані

Шифруйте дані перед завантаженням в хмару. Пам'ятайте: немає ніякої "хмари", це просто чийсь чужий комп'ютер. `Keybase` та `Boxcryptor` – це інструменти, які дозволяють шифрувати дані в автономному режимі, перш ніж завантажити їх у хмарне сховище. `Cryptomator` створює універсальний зашифрований логічний диск, який можна синхронізувати між вашими пристроями через хмарне сховище.

:wrench: Keybase: https://keybase.oi

:wrench: Cryptomator: https://cryptomator.org

:wrench: Boxcryptor: https://www.boxcryptor.com

### Шифруйте дані на диску

Використовуйте функцію `Full Disk Encryption` вашої операційної системи для захисту даних на ноутбуці або ПК від крадіжки або втрати. FDE це безплатна функція у Linux, MacOS та Windows Pro.

#### macOS

Увімкніть `File Vault` ([інструкція від Apple](https://support.apple.com/en-us/HT204837)). Ось і все, ви це зробили.

#### Linux

Використовуйте `LUKS` або інші засоби повного шифрування диску. В якості альтернативи, під час встановлення ОС зазвичай можна вибрати параметри шифрування диску або шифрування тільки вашого домашнього розділу. Ось це [достатньо детальна інструкція для Arch](https://wiki.archlinux.org/index.php/Dm-crypt/Encrypting_an_entire_system), але кожен популярний дистрибутив має аналогічний документ.

#### Windows

Ввімкніть `BitLocker`. Це швидко зробити та легко налаштувати та використовувати, тому що це "рідний" механізм ОС Windows. [Інструкція від Microsoft](http://www.howtogeek.com/234826/how-to-enable-full-disk-encryption-on-windows-10/).

У разі, якщо ваша версія ОС Windows поставляється без BitLocker, використовуйте "сторонні" рішення. Наприклад `VeraCrypt`, який є відгалуженням від TrueCrypt, :exclamation: який наразі припинив існування та не рекомендується для використання.

:wrench: VeraCrypt: https://veracrypt.codeplex.com

:bulb: Ви також можете шифрувати зовнішні диски або окремі файли.

## Операційна система та програми

Не запускайте програми з правами адміністратора. Завжди входьте в ОС з правами "звичайного" користувача та за потреби підвищуйте привілеї в меню програми `Run  As...` коли це потрібно.

:exclamation: Запускаючи програми з правами локального адміністратора, ви надаєте їм можливість перехоплювати доступ та дані інших користувачів, які зараз працюють на вашому комп'ютері або нещодавно заходили в нього. Таким чином зловмисник може перехопити реквізити доступу доменного адміністратора корпорації та повністю скомпрометувати домен `Active Directory`.

Не використовуйте піратські програми. Не запускайте та не встановлюйте програми, завантажені з ненадійних джерел, включаючи торенти та інші мережі обміну файлами. Це особливо стосується "кейгенів" та "крякалок", які зазвичай вимагають прав адміністратора для запуску.

### Windows

Увімкніть автооновлення (`Auto-Update`) в вашій ОС Windows. Для більш детального опису дій зверніться до [офіційної інструкції](https://support.microsoft.com/en-us/help/12373/windows-update-faq).

Переконайтеся в тому, що автооновлення Windows [налаштоване для перевірки оновлень для всіх продуктів Microsoft](https://www.winhelp.us/configure-automatic-updates-in-windows.html), включаючи MS Office.

Оновлюйте програмне забезпечення від "сторонніх" постачальників регулярно та автоматично.

### macOS

Увімкніть автооновлення в `AppStore` [як рекомендує Apple](https://support.apple.com/kb/PH25371). Увімкніть автооновлення MS Office в macOS [як рекомендує Microsoft](https://support.office.com/en-us/article/Check-for-Office-for-Mac-updates-automatically-bfd1e497-c24d-4754-92ab-910a4074d7c1). Увімкніть автооновлення всіх інших програм у системі.

### Linux

Сучасні дистрибутиви Linux дають змогу налаштувати автооновлення за допомогою засобів ОС, або ж регулярно оновлювати ПЗ вручну. Наприклад, в Ubuntu Linux оновлення ПЗ здійснюється за допомогою команди

```bash
apt update && apt -y upgrade
```

За подробицями щодо вашого дистрибутиву Linux зверніться до документації.

## Антивірус

### macOS та Linux

В Linux або macOS не користуйтеся антивірусом. Використання антивірусу в не-Windows системі становить більший ризик, ніж загроза інфікування вірусом. Якщо використання антивірусу не уникнути, встановіть Malwarebytes або BitDefender.

:wrench: Malwarebytes https://www.malwarebytes.com

:wrench: BitDefender https://www.bitdefender.de

### Windows

У Windows користуйтеся антивірусом. Увімкніть та не вимикайте вбудований Microsoft Defender.

## Фаєрвол

### macOS

Увімкніть та налаштуйте вбудований фаєрвол macOS у розділі `System Preferences -> Security & Privacy -> Firewall`. Розширені параметри `Firewall Options...` дозволяють більш детально його налаштовувати, наприклад, блокувати всі вхідні з'єднання, налаштовувати вхідні та вихідні фільтри для конкретних програм, а також дозволяти вхідні підключення до системних і підписаних програм. Увімкніть `Stealth Mode`, якщо ви хочете зробити ваш Mac недоступним для будь-якого іншого пристрою.

Встановіть та навчіться користуватися одним зі спеціалізованих клієнтських фаєрволів, таких як

:wrench: [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) (комерційний) або

:wrench: [LuLu](https://objective-see.com/products/lulu.html) (безкоштовний з відкритим кодом).

### Windows

TODO

### Linux

TODO

## Робіть резервні копії

### macOS

Використовуйте окремий зашифрований зовнішній жорсткий диск для резервного копіювання з допомогою `Time Machine`. Підключайте його кожного разу, коли працюєте над чимось важливим, резервні копії будуть створюватися автоматично. Рекомендований об'єм диску: щонайменше вдвічі більший за об'єм вашого внутрішнього носія. [Інструкція від Apple](https://support.apple.com/en-us/HT201250).

### Windows

У Windows 10 налаштування функції створення та відтворення з резервних копій дуже просте і може бути здійснене в меню  `Settings -> Update & Security -> Backup`. [Інструкція Microsoft](https://support.microsoft.com/en-us/help/17143/windows-10-back-up-your-files).

Для Windows 8.1 та 7 виконайте [ці рекомендації Microsoft](https://support.microsoft.com/en-us/help/17127/windows-back-up-restore) щодо роботи з резервними копіями даних та системи.

В якості альтернативи, оберіть та використовуйте [програмне забезпечення від стороннього постачальника](http://www.techradar.com/news/software/applications/best-free-backup-software-11-programs-we-recommend-1137924).

### Linux

Користувачі Linux мають доступ до різноманіття засобів створення резервних копій: від `tar` до `rsync` на мережеву файлову шару. Менш досвідчені користувачі можуть обрати [більш комфортний інструмент](http://www.nuxified.org/blog/easy-linux-backup-software-time-machine-functionality/).

Ви можете створювати резервні копії ваших даних автоматично, зберігаючи їх у хмарних носіях, таких як `Dropbox`, `iCloud Drive`, `OneDrive`, `Google Drive` тощо. Але не забувайте [шифрувати ваші дані](#Шифруйте-хмарні-дані) перед завантаженням їх у хмару.

## Мобільна безпека

Мобільна (стільникова) мережа є так само небезпечною, як публічні точки доступу Wi-Fi. Використовуйте ті ж криптографічні засоби у вашій мобільній мережі передачі даних. Не вважайте SMS або ваші голосові розмови приватними: замість цього використовуйте голосові виклики та повідомлення, які шифруються наскрізь.

Використовуйте `iOS`. Судячи з усього, мобільна безпека `Apple` та безпека їхньої екосистеми застосунків є набагато безпечнішою за рішення на базі ОС Android, які контролюються вашим оператором зв'язку або OEM-виробником (Samsung, LG, Sony тощо.)

Якщо `Android`, то `Google`. Тільки пряма підтримка операційної системи з боку виробника може гарантувати своєчасні оновлення безпеки. Будь-які додаткові кроки в ланцюжку постачання (OEM постачальники, стільникові оператори, корпоративні ІТ тощо) знижують рівень безпеки. У деяких випадках оновлення просто припиняють надходити до вашого пристрою через рік або два після початку його використання.

Не "рутайте" (`root`) свій смартфон. Використовуйте тільки дозволені репозиторії додатків, наприклад, `Google Play` та `AppStore`. Не завантажуйте та не встановлюйте "оновлення безпеки", які надходять з неавторизованих джерел програмного забезпечення.

## Фізична безпека

Тримайте ваші речі, де ви можете їх бачити або контролювати. Ваш комп'ютер і гаджети вимагають такого ж рівня фізичної безпеки, який ви забезпечуєте вашим кредитним карткам та ключам від квартири та автомобіля. Пам'ятайте: якщо зловмисник проведе навіть недовгий час наодинці з вашим комп'ютером, це вже буде не ваш комп'ютер, а його. Швидше за все, він зможе повністю скомпрометувати вашу систему. Блокування екрану допомагає, але існують сучасні атаки, від яких воно не захищає.

Отже, не залишайте ваш пристрій без нагляду, особливо коли він працює. Вимикайте його або відправляйте у режим гібернації кожного разу, коли ви залишаєте його без нагляду навіть на декілька хвилин. Налаштуйте повне шифрування диску та запит паролю кожного разу, коли він вмикається.

Здійснюйте чутливі та нечутливі операції з різних комп'ютерів. Якщо ви дозволяєте дітям грати в онлайн-ігри на комп'ютері, який ви використовуєте для онлайн-банкінгу – вас зламають. Якщо ви відвідуєте інтернет-крамниці з ПК в комп'ютерному клубі або інтернет-кафе – вас зламають. Якщо ви відправляєте ділові листи з ПК у відкритій зоні вашого готелю – вас зламають.

Використовуйте окремий комп'ютер для бізнесу та фінансових операцій та усіх дій, які вимагають приватності або конфіденційності. Використовуйте спеціальну віртуальну або фізичну машину для найбільш критичних операцій.

:exclamation: В деяких авторитарних країнах вас можуть *попросити* надати пароль до вашого зашифрованого носія інформації на кордоні та в аеропорті. Перетинаючи кордони таких держав, скористайтеся порадою: попросіть людину, якій ви довіряєте (бажано юриста) змінити ваш пароль перед від'їздом та надати його вам лише коли ви завершите подорож. Повторіть процедуру на зворотному шляху.

## Подяка

Цей посібник був би неможливий без допомоги багатьох фахівців галузі кібербезпеки в Україні та за кордоном. Щиро вдячний всім, хто зробив внесок у зміст цього документу та пропонував правки та оновлення під час та після його створення. Скомпільовано та підготовлено [Vlad Styran](https://fb.me/vstyran),, https://styran.com

Special thanks go to Boris "[@jadedsecurity](https://twitter.com/jadedsecurity)" Sverdlik for a great deal of inspiration and coining the "Don't click shit" slogan.

Взяти участь в розробці: https://github.com/sapran/dontclickshit/
