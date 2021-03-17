# Як не стати кібер-жертвою

## Зміст

1. [Не натискайте каку](#user-content-не-натискайте-каку)
1. [Використовуйте парольні менеджери](#user-content-використовуйте-парольні-менеджери)
1. [Використовуйте двофакторну автентифікацію](#user-content-використовуйте-двофакторну-автентифікацію)
1. [Використовуйте безпечні месенджери](#user-content-використовуйте-безпечні-месенджери)
1. [Використовуйте віртуальні приватні мережі](#user-content-використовуйте-віртуальні-приватні-мережі)
1. [Шифруйте дані](#user-content-шифруйте-дані)
1. [Операційна система та програмне забезпечення](#user-content-операційна-система-та-програмне-забезпечення)
1. [Антивірус](#user-content-антивірус)
1. [Фаєрвол](#user-content-фаєрвол)
1. [Робіть резервні копії даних](#user-content-робіть-резервні-копії-даних)
1. [Мобільна безпека](#user-content-мобільна-безпека)
1. [Фізична безпека](#user-content-фізична-безпека)
1. [Зворотній зв'язок](#user-content-бережіться)


## Не натискайте каку

### Що мається на увазі?

Не відкривайте, не натискайте, та не запускайте **підозрілі файли, посилання та програми**.

Основне правило: якщо ви на це (лист, файл, посилання тощо) не чекали, це підозріло.

### Підозрілі файли

Не відкривайте підозрілі файли, вкладення електронної пошти, або архівні документи, якщо ви не довіряєте джерелу, з якого вони надійшли. Відправляйте небажані листи в директорію для спаму перед прочитанням – файли або посилання від людей, яких ви не знаєте, повинні розцінюватися як шкідливі за замовчуванням.

Перевіряйте отримані файли іншим шляхом, ніж той, який використовувався для їх передачі. Наприклад, якщо ви отримали документ MS Word електронною поштою, зв'яжіться з відправником за допомогою програми обміну миттєвими повідомленнями (месенджера) або телефоном та спитайте в нього мету відправки файлу та взагалі, чи він вам його відправив.

:exclamation: Найбільш ризиковані типи файлів:
- Будь-які виконувані файли: `EXE`, `COM`, `CMD`, `BAT`, `PS1`, `SWF`, `JAR`, `JS`, `VBS` тощо.
- Документи MS Office, особливо з макросами: `DOC/DOCX/DOCM`, `XLS/XSLX/XLSM` тощо.
- PDF документи: `PDF`.
- Файли векторної графіки з вбудованим кодом: `SVG`.
- Архіви файлів, особливо захищені паролем.

Іноді, особливо під тиском часу, буває важко відрізнити шкідливі файли від легітимних. Користуйтеся сервісом VirusTotal для перевірки підозрілих файлів шляхом їх одночасного сканування більш ніж 50 антивірусами. Це набагато ефективніше, ніж сканування файлів антивірусом в автономному режимі, але :exclamation:враховуйте той факт, що завантажуючи файли на VirusTotal ви надаєте доступ до нього третій стороні.

:wrench: VirusTotal: https://virustotal.com

### Підозрілі посилання

Не відкривайте підозрілі посилання (URL), особливо ті, що вказують на веб-сайти, які ви зазвичай не відвідуєте. Завжди перевіряйте **доменні імена веб-сайтів**, перш ніж натиснути на посилання: зловмисники можуть замаскувати доменне ім'я, щоб воно виглядало знайомим (`facelook.com`, `gooogle.com` тощо) Використовуйте HTTPS та перевіряйте SSL-сертифікат веб-сайту, щоб переконатися, що він не клонований або підроблений.

Шкідливі URL-адреси **можуть "маскуватися" за довільним текстом** в HTML-файлах, документах та електронних листах. У веб-браузері або поштовій програмі наведіть курсор миші на посилання (але не натискайте) і почекайте деякий час (1-2 сек), поки не "спливе" реальний URL. Можна також клацнути правою кнопкою миші на посиланні та скопіювати його в текстовий редактор, щоб побачити його фактичну адресу. Використовуйте [VirusTotal](https://virustotal.com) для перевірки підозрілих посилань так само як для сканування файлів.

Шкідливі URL-адреси можуть бути закодовані в вигляді QR-кодів та/або роздруковані на папері, в тому числі в формі скорочених URL, згенерованих спеціальними сервісами на кшталт `tinyurl.com`, `bit.ly`, `ow.ly` тощо. Не вводьте ці посилання в браузер та не скануйте QR-коди вашим смартфоном якщо ви не впевнені у їхньому вмісті та їхньому походженні.

:wrench: Ви можете розгорнути скорочені URL перед відкриттям за допомогою цих веб-сайтів:
- http://checkshorturl.com/
- http://www.expandurl.net/

:wrench: Ці додатки до популярних браузерів здійснюють таке розгортання автоматично:
- Google Chrome, [URL Unshortener](https://chrome.google.com/webstore/detail/url-unshortener/hciiopljaekhmopgaghflgfnhhbbaclm)
- Mozilla Firefox, [Long URL Please Mod](https://addons.mozilla.org/en-US/firefox/addon/long-url-please-mod/)

### Підозрілі спливаючі вікна

Будьте обережні щодо спливаючих вікон та повідомлень у вашому браузері, програмах, операційній системі та мобільному пристрої. Завжди читайте вміст спливаючих вікон та **не "схвалюйте" або "приймайте" нічого похапцем**.

Спливаючі вікна можуть становити небезпеку у різні способи: деякі дозволяють зловмисникам встановити у вашій системі підробні SSL-сертифікати, які допоможуть їм перехоплювати ваш мережевий трафік; деякі можуть встановлювати зловмисні програми на ваш комп'ютер та смартфон або перенаправляти ваш браузер на зловмисні веб-сайти, які заражають комп'ютери вірусами та іншими зловмисними програмами.

### Підозрілі пристрої

Не підключайте флешки та зовнішні диски, не вставляйте CD та DVD тощо у ваш комп'ютер якщо ви не довіряєте повністю їхньому джерелу. Існують техніки зламу комп'ютера ще до того, як ви відкриєте файл на флешці та задовго до того, як ваш антивірус його просканує. Якщо ви знайшли пристрій всередині офісу або на вулиці, якщо ви отримали його поштою або з доставкою, якщо незнайомець дав вам його з проханням роздрукувати документ або просто відкрити та перевірити його вміст – є великі шанси, що пристрій є зловмисним. Довіряйте лише власним пристроям та будьте обережні з пристроями, які отримуєте від інших людей по роботі або в інших цілях.

## Використовуйте парольні менеджери

Використовуйте програмне забезпечення для збереження та захисту паролів – парольні менеджери – та виконуйте такі правила:

1. Генеруйте довгі, випадкові паролі довжиною від 20 символів.
1. Переконайтеся, що ваш майстер-пароль, яким ви захищаєте решту паролів, є сильним паролем.
1. Використовуйте парольний менеджер, який шифрує базу даних перед зберіганням її в хмарі або синхронізацією між пристроями по мережі.
1. Частіше, бажано автоматично, робіть резервні копії бази даних паролів.

:wrench: Прикладами хороших парольних менеджерів є:
- 1Password https://1password.com (non-free)
- Bitwarden https://bitwarden.com (free & opensource)
- Dashlane https://www.dashlane.com/ (free with limitations or non-free premium)
- KeePassXC https://keepassxc.org/ (free & opensource, DIY cloud sync)

### Тримайте паролі в секреті

Ніхто крім вас не повинен знати ваші паролі. Не розказуйте їх нікому, включаючи вашого боса, вашого сисадміна або службу підтримки, вашу дружину, ваших батьків, ваших дітей тощо. В них **немає ніяких логічних або законних підстав для отримання ваших паролів**. З технічної точки зору, навіть система, в якій ви використовуєте пароль, не має доступу до паролів в первісному вигляді. Замість цього система зберігає "хеш" – криптографічно захищену копію пароля.

Ніколи не записуйте ваші паролі на папері або в незашифрованому файлі. Захищений паролем файл Excel – це не шифрування. Архів, захищений паролем – не є належним шифруванням.

### Як вигадати мастер-пароль?

Пароль до сховища паролів – це ваш мастер-пароль. Зручний та надійний мастер-пароль складається з чотирьох та більше не пов'язаних між собою слів. Для підсилення паролю, одне з цих слів можна написати у верхньому регістрі.

:bulb: Приклади сильних паролів, згенерованих програмою 1Password:

```hyping-BASKET-bouquet-outs```
```tinsel-dolt-INDIGENT-echo```

### Оновлення паролів

:bulb: "Правило буравчика": чим частіше ви використовуєте пароль, тим частіше вона повинна змінюватись.

## Використовуйте двофакторну автентифікацію

### Увімкніть двофакторну автентифікацію

Більшість сучасних онлайн-сервісів підтримують двофакторну автентифікацію. Увімкніть її за допомогою програмного токена (доступний у Facebook, Twitter, Google тощо) або за допомогою одноразового пароля з доставкою по SMS.

:wrench: URL-адреси для налаштування багатофакторної автентифікації популярних веб-сайтів:

- Apple https://support.apple.com/en-us/HT204915
- Google https://myaccount.google.com/security/signinoptions/two-step-verification
- Facebook https://www.facebook.com/settings?tab=security&section=approvals
- Twitter https://twitter.com/settings/security
- Dropbox https://www.dropbox.com/account/#security

:wrench: Широка підбірка сервісів, які підтримують двофакторну автентифікацію: https://twofactorauth.org

### Уникайте SMS

Надавайте перевагу використанню `Google Authenticator`, фізичного токена, або перевірці за допомогою мобільного додатку. Уникайте використання одноразових паролів через SMS.

## Використовуйте безпечні месенджери

Використовуйте надійне наскрізне шифрування (End-to-End Encryption, E2E) для передачі приватних та конфіденційних даних. Наскрізне шифрування гарантує, що ніхто окрім вас і вашого співрозмовника не може отримати доступ до вмісту повідомлень.

:wrench: Безпечні месенджери, які здійснюють шифрування "з кінця в кінець" за замовчуванням:

- Signal https://signal.org
- Threema https://threema.ch
- Wire https://wire.com
- Keybase https://keybase.io

:bulb: Інструкція з безпечного обміну миттєвими повідомленнями та порівняння рівня безпеки сучасних месенджерів: https://www.securemessagingapps.com

:wrench: Шифрування електронної пошти

- GPGTools для Apple Mail та macOS: https://gpgtools.org/
- OpenPGP у Microsoft Outlook 2016/2013/2010/2007: https://www.encryptomatic.com/openpgp/
- S/MIME в Outlook Web App: https://support.office.com/en-us/article/Encrypt-messages-by-using-S-MIME-in-Outlook-Web-App-2e57e4bd-4cc2-4531-9a39-426e7c873e26

## Використовуйте віртуальні приватні мережі

Для того, щоб захистити ваші мережеві дані та метадані від прослуховування, використовуйте віртуальні приватні мережі (Virtual Private Networks, VPN). Найкращий  спосіб зробити це – встановити свій власний VPN-сервер.

:bulb: Algo – розгорнути власний сервер VPN в будь-якому популярному хмарному сервісі: https://github.com/trailofbits/algo

:bulb: Outline – ще простіший спосіб налаштувати власний сервер VPN: https://getoutline.org/

Використання VPN-сервісів взагалі не рекомендується, але може бути допустимим, коли немає змоги скористатися власним VPN.

:wrench: Порівняльна таблиця VPN-сервісів: https://thatoneprivacysite.net/#simple-vpn-comparison

## Шифруйте дані

### Перевіряйте шифрування веб-сайтів

Завжди переконуйтесь, що веб-сайт, якому ви передаєте свої чутливі дані, використовує HTTPS. Це означає, що його адреса в адресному рядку браузера починається з `https://` та його сертифікат перевірений вашим браузером, отже він не робить вам попереджень безпеки.

Зверніть увагу, що наявності HTTPS не достатньо для виникнення довіри до веб-сайту: будь-хто може згенерувати дійсний сертифікат для свого веб-сервера. Потрібно звернути увагу та перевірити правильність доменного імені веб-сайту, тому що воно може бути легко підроблене, а веб-сайт – клонований.

:exclamation: Ніколи, навіть для тимчасового використання, не приймайте недійсні сертифікати.

### Шифруйте хмарні дані

Шифруйте дані перед завантаженням в хмару. Пам'ятайте: немає ніякої "хмари", це просто чужий комп'ютер. `Boxcryptor` та `Cryptomator` – це інструменти, які дозволяють шифрувати дані в автономному режимі, перш ніж завантажити їх у хмарне сховище. `Boxcryptor` можна використовувати безкоштовно для одного хмарного диска, `Cryptomator` – безкоштовна програма з відкритим кодом.

:wrench: Boxcryptor: https://www.boxcryptor.com
:wrench: Cryptomator: https://cryptomator.org

### Шифруйте дані на диску

Ви можете використовувати функцію `Full Disk Encryption` вашої операційної системи для захисту даних на вашому ноутбуці або ПК від крадіжки або втрати. FDE це безкоштовна функція у Linux, MacOS та Windows Pro.

#### macOS

Увімкніть `File Vault`. Ось і все, ви це зробили. [Інструкція від Apple](https://support.apple.com/en-us/HT204837).

#### Linux

Використовуйте `LUKS` або інші засоби повного шифрування диску. В якості альтернативи, під час встановлення ОС зазвичай можна вибрати параметри шифрування диску або шифрування тільки вашого домашнього розділу. Ось це [достатньо детальна інструкція для Arch](https://wiki.archlinux.org/index.php/Dm-crypt/Encrypting_an_entire_system), але кожен популярний дистрибутив має аналогічний документ.

#### Windows

Ввімкніть `BitLocker`. Це швидко зробити та легко налаштувати та використовувати, тому що це "рідний" механізм ОС Windows. [Інструкція від Microsoft](http://www.howtogeek.com/234826/how-to-enable-full-disk-encryption-on-windows-10/).

У разі, якщо ваша версія ОС Windows поставляється без BitLocker, використовуйте "сторонні" рішення. Наприклад `VeraCrypt`, який є відгалуженням від TrueCrypt, :exclamation: який наразі припинив існування та не рекомендується для використання.

:wrench: VeraCrypt: https://veracrypt.codeplex.com

:bulb: Ви також можете шифрувати зовнішні диски або окремі файли.

## Операційна система та програмне забезпечення

Не запускайте клієнтське програмне забезпечення із правами адміністратора. Завжди здійснюйте інтерактивний вхід в ОС з правами "звичайного" користувача та за потреби підвищуйте привілеї в меню програми `Run As...` коли вимагається встановити чи запустити легітимні програми. Ніколи не запускайте, особливо з правами адміністратора, програми на `Java`, `Flash`, сценарії `PowerShell` та `cmd` тощо та будь-який інший "мобільний" код.

:exclamation: ПОПЕРЕДЖЕННЯ: Запускаючи програми з правами локального адміністратора, ви надаєте їм можливість перехоплювати реквізити доступу та поточні сесії інших користувачів, які зараз працюють на вашому комп'ютері або нещодавно заходили в нього. Таким чином зловмисник може перехопити реквізити доступу доменного адміністратора корпорації та повністю скомпрометувати домен `Active Directory`.

Не використовуйте піратське програмне забезпечення. Не запускайте та не встановлюйте програмне забезпечення, завантажене з ненадійних джерел, включаючи торенти та інші peer-to-peer мережі обміну файлами. Це особливо стосується "кейгенів" та "крякалок", які зазвичай вимагають права адміністратора для запуску.

Мораль або етика не мають з цим нічого спільного: це просто абсолютно небезпечно. По-перше, зараження дистрибутиву програми Троянцем та "безкоштовна" публікація його в Інтернеті – це відомий спосіб зараження систем, і це відбувається набагато частіше, ніж хотілося б. По-друге, на піратське програмне забезпечення рідко можна своєчасно встановлювати оновлення безпеки, які просто не надходять до вашої системи. "Активації" та повторні активації згають ваш час, а ризики не оновлення програмного забезпечення є неприйнятними.

### Windows

Увімкніть автооновлення (`Auto-Update`) в вашій ОС Windows. Для більш детального опису дій зверніться до [офіційної інструкції](https://support.microsoft.com/en-us/help/12373/windows-update-faq).

Переконайтеся в тому, що автооновлення Windows [налаштоване для перевірки оновлень для всіх продуктів Microsoft](https://www.winhelp.us/configure-automatic-updates-in-windows.html), включаючи MS Office.

Оновлюйте програмне забезпечення від "сторонніх" постачальників регулярно та автоматично. Для цього використовуйте `Flexera` (раніше відома як Secunia) PSI або еквівалентне рішення, яке перевіряє наявність оновлень для вашого ПЗ та дозволяє вам встановлювати їх автоматично.

:wrench: Flexra PSI: http://www.flexerasoftware.com/enterprise/products/software-vulnerability-management/personal-software-inspector/

### macOS

Увімкніть автооновлення в `AppStore` [як рекомендує Apple](https://support.apple.com/kb/PH25371).

Увімкніть автооновлення MS Office в macOS [як рекомендує Microsoft](https://support.office.com/en-us/article/Check-for-Office-for-Mac-updates-automatically-bfd1e497-c24d-4754-92ab-910a4074d7c1).

Використовуйте Homebrew для оновлення вашого стороннього ПЗ. Ви можете легко знайти багато програм, які вже використовуєте, у Homebrew:

```bash
brew search vlc
brew search wireshark
brew search gpgtools
```

Щоб встановити Homebrew, ознайомтеся з офіційною інструкцією: http://brew.sh

В якості альтернативи, щоб тримати сторонні програми в актуальному стані, використовуйте MacInformer або еквівалентний інструмент. :exclamation: ПОПЕРЕДЖЕННЯ: хоча це й безпечніше, ніж не використовувати жоден механізм оновлення, такого роду програмне забезпечення може бути "рекламно-агресивним" та звісно ж не таким безпечним, як Homebrew. Отже, URL на продукт тут немає.

### Linux

Сучасні дистрибутиви Linux дають змогу налаштувати автооновлення за допомогою засобів ОС, або ж регулярно оновлювати ПЗ вручну. Наприклад, в Ubuntu Linux оновлення ПЗ здійснюється за допомогою команди

```bash
apt update && apt -y upgrade
```

За подробицями щодо вашого дистрибутиву Linux зверніться до документації.

## Антивірус

### macOS та Linux

В Linux або macOS **не користуйтеся** антивірусом. Серйозно. Рішення з безпеки також містять вразливості, вони не є безпечнішими за будь-який інший програмний продукт. При цьому, з метою ефективності, антивіруси зазвичай вимагають підвищених привілеїв в ОС. Це становить більший ризик, ніж загроза інфікування вірусом або троянцем на порівняно більш безпечній та менш популярній платформі. Якщо ви слідуєте іншим рекомендаціям з цієї інструкції, ви можете встановити антивірус, який не буде постійно моніторити вашу ОС, та періодично сканувати вашу систему з його допомогою. Один з таких антивірусів виробляє Malwarebytes, інший, більш прискіпливий варіант, – це BitDefender.

:wrench: Malwarebytes https://www.malwarebytes.com

:wrench: BitDefender https://www.bitdefender.de

### Windows

У Windows **користуйтеся** антивірусом. Але не забувайте, що антивіруси дуже неефективні проти сучасних онлайн-загроз. Ви можете уявити собі ефективність антивірусів десь між 15% та 30%, в більшості випадків це буде правдою.

Вибрати антивірус нелегко: "незалежні" тести більш прихильні до антивірусних постачальників, які в решті решт фінансують ці тестування. Існують, щоправда, більш-менш об'єктивні ревю та результати тестувань.

- AV-Test.org https://www.av-test.org/en/antivirus/home-windows
- Результати тестування NSS Labs, якщо ви можете їх знайти.

## Фаєрвол

### macOS

Увімкніть та налаштуйте вбудований фаєрвол macOS у розділі `System Preferences -> Security & Privacy -> Firewall`. Розширені параметри `Firewall Options...` дозволяють більш детально його налаштовувати, наприклад, блокувати всі вхідні з'єднання, налаштовувати вхідні та вихідні фільтри для конкретних програм, а також дозволяти вхідні підключення до системних і підписаних програм. Увімкніть `stealth mode`, якщо ви хочете зробити ваш Mac недоступним для будь-якого іншого мережевого клієнта (наприклад, для запобігання [віддаленій атаці за протоколом ICMP](https://lgtm.com/blog/apple_xnu_icmp_error_CVE-2018-4407)).

Встановіть та навчіться користуватися одним зі спеціалізованих клієнтських фаєрволів, таких як

:wrench: [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) (комерційний) або

:wrench: [LuLu](https://objective-see.com/products/lulu.html) (безкоштовний з відкритим кодом).

### Windows

TODO

### Linux

TODO

## Робіть резервні копії даних

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

Мобільна (стільникова) мережа є так само небезпечною, як публічні точки доступу Wi-Fi. Використовуйте ті ж криптографічні засоби у вашій мобільній мережі передачі даних. Не вважайте SMS або ваші голосові розмови приватними: замість цього використовуйте голосові виклики та повідомлення, які шифруються "з кінця в кінець".

Використовуйте `iOS`. Судячи з усього, мобільна безпека `Apple` та безпека їхньої екосистеми застосунків є набагато безпечнішою за рішення на базі ОС Android, які контролюються вашим оператором зв'язку або OEM-виробником (Samsung, LG, Sony тощо.)

Якщо `Android`, то `Google`. Тільки пряма підтримка операційної системи з боку виробника може гарантувати своєчасні оновлення безпеки. Будь-які додаткові кроки в ланцюжку постачання (OEM постачальники, стільникові оператори, корпоративні ІТ тощо) знижують рівень безпеки. У деяких випадках оновлення просто припиняють надходити до вашого пристрою через рік або два після початку його використання.

Не "рутайте" (`root`) свій смартфон. Використовуйте тільки дозволені репозиторії додатків, наприклад, `Google Play` та `AppStore`. Не завантажуйте та не встановлюйте "оновлення безпеки", які надходять з неавторизованих джерел програмного забезпечення.

## Фізична безпека

Тримайте ваші речі, де ви можете їх бачити або контролювати. Ваш комп'ютер і гаджети вимагають такого ж рівня фізичної безпеки, який ви забезпечуєте вашим кредитним карткам та ключам від квартири або автомобіля. Пам'ятайте: якщо зловмисник проведе навіть недовгий час наодинці з вашим комп'ютером, це вже буде не ваш комп'ютер, а його. Швидше за все, він зможе повністю скомпрометувати вашу систему не доклавши суттєвих зусиль. Блокування сесії користувача може допомогти, але існують сучасні атаки, від яких воно не захищає.

Отже, не залишайте ваш пристрій без нагляду, особливо коли він працює. Вимикайте його або відправляйте у режим гібернації кожного разу, коли ви залишаєте його без нагляду навіть на декілька хвилин. Налаштуйте запит паролю кожного разу, коли він вмикається.

Здійснюйте чутливі та нечутливі операції з різних комп'ютерів. Якщо ви дозволяєте дітям грати в онлайн-ігри на комп'ютері, який ви використовуєте для онлайн-банкінгу – вас зламають. Якщо ви відвідуєте інтернет-крамниці з ПК в комп'ютерному клубі або інтернет-кафе – вас зламають. Якщо ви відправляєте ділові листи з ПК у відкритій зоні вашого готелю – вас зламають.

Використовуйте окремий комп'ютер для бізнес- та фінансових операцій та усіх дій, які вимагають приватності або конфіденційності. Використовуйте спеціальну віртуальну або фізичну машину для найбільш критичних операцій.

:bulb: В деяких авторитарних країнах вас можуть *попросити* надати пароль до вашого зашифрованого носія інформації на кордоні та в аеропорті. Перетинаючи кордони таких держав, скористайтеся порадою: попросіть людину, якій ви довіряєте (бажано юриста) змінити ваш пароль перед від'їздом та надати його вам лише коли ви завершите подорож. Повторіть процедуру на зворотному шляху.

## Бережіться!

Дякую, що приділяєте увагу власній кібербезпеці. Поділіться цією пам'яткою з близькими, друзями та колегами, щоб зробити світ трохи безпечнішим.

Ця пам'ятка – результат роботи спеціалістів з кібербезпеки, які мають багаторічний досвід побудови, перевірки та етичного зламу комп'ютерних систем, додатків та мереж. Ці настанови надаються "як є", автор(и) не несуть відповідальності за ваші дії або бездіяльність.

Ви можете поширювати цю пам'ятку, використовувати її у бізнесі, та змінювати на власний розсуд. Це безкоштовно. Посилання на оригінал та автора вітаються.

Якщо у вас є що додати або ви знайшли в тексті помилку, напишіть на :email: sapran@protonmail.com або [створіть issue](https://github.com/sapran/dontclickshit/issues/new).

## Credits

Цей посібник був би неможливий без допомоги багатьох фахівців галузі кібербезпеки в Україні та за кордоном. Щиро вдячний всім, хто зробив внесок у зміст цього документу та пропонував правки та оновлення під час та після його створення. Скомпільовано та підготовлено [Vlad Styran](https://fb.me/vstyran), [Berezha Security](https://berezhasecurity.com), https://styran.com

Special thanks go to Boris "[@jadedsecurity](https://twitter.com/jadedsecurity)" Sverdlik for a great deal of inspiration and coining the "Don't click shit" slogan.

[English version (out of date)](https://github.com/sapran/dontclickshit/blob/master/README_EN.md)

Постійна адреса: https://github.com/sapran/dontclickshit/

Оригінальна майнд-мапа (оновлюється):
- [Українською](http://www.xmind.net/m/DNRY)
- [Англійською](http://www.xmind.net/m/raQ4)
