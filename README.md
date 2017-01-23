# Як не стати кібер-жертвою

Постійна адреса: https://github.com/sapran/dontclickshit/

Оригінальна майнд-мапа (оновлюється):
- [Українською](http://www.xmind.net/m/DNRY)
- [Англійською](http://www.xmind.net/m/raQ4)

## Зміст

1. [Не натискайте каку](#Не-натискайте-каку)
2. [Використовуйте пасфрази замість паролів](#Використовуйте-пасфрази-замість-паролів)
3. [Використовуйте двохфакторну автентифікацію](#Використовуйте-двохфакторну-автентифікацію)
4. [Операційна система та програмне забезпечення](#Операційна-система-та-програмне-забезпечення)
5. [Антивірус](#Антивірус)
6. [Робіть резервні копії даних](#Робіть-резервні-копії-даних)
7. [Використовуйте криптографію](#Використовуйте-криптографію)
8. [Мобільна безпека](#Мобільна-безпека)
9. [Фізична безпека](#Фізична-безпека)
10. [Зворотній зв'язок](#Бережіться)

## Не натискайте каку

### Що мається на увазі?

Не відкривайте, не натискайте, та не запускайте **підозрілі файли, посилання та програми**.

Основне правило: якщо ви на це (лист, файл, посилання тощо) не чекали, це підозріло.

### Підозрілі файли

Не відкривайте підозрілі файли, вкладення електронної пошти, або архівні документи, якщо ви не довіряєте джерелу, з якого вони надійшли. Відправляйте небажані листи в папку для спаму перед прочитанням – файли або посилання від людей, яких ви не знаєте, повинні розцінюватися як шкідливі за замовчуванням.

Перевіряйте отримані файли іншим шляхом, ніж той, який використовувався для їх передачі. Наприклад, якщо ви отримали документ MS Word по електронній пошті, зв'яжіться з відправником за допомогою програми обміну миттєвими повідомленнями (месенджера) або по телефону та спитайте в нього мету відправки файлу та взагалі, чи він вам його відправив.

:exclamation: Найбільш ризиковані типи файлів:
- Будь-які виконувані файли: `EXE`, `COM`, `CMD`, `BAT`, `PS1`, `SWF`, `JAR` тощо.
- Документи MS Office, особливо з макросами: `DOC/DOCX/DOCM`, `XLS/XSLX/XLSM` тощо.
- PDF документи: `PDF`.
- Файли векторної графіки з вбудованим кодом: `SVG`.
- Архіви файлів, особливо захищені паролем.

Іноді, особливо під тиском часу, буває важко відрізнити шкідливі файли від легітимних. Користуйтеся сервісом VirusTotal для перевірки підозрілих файлів шляхом їх одночасного сканування більш ніж 50 антивірусами. Це набагато ефективніше, ніж сканування файлів антивірусом в автономному режимі, але :exclamation:враховуйте той факт, що завантажуючи файли на VirusTotal ви надаєте доступ до нього третій стороні.

:wrench: VirusTotal: https://virustotal.com

### Підозрілі посилання

Не відкривайте підозрілі посилання (URL), особливо ті, що вказують на веб-сайти, які ви зазвичай не відвідуєте. Завжди перевіряйте **доменні імена веб-сайтів**, перш ніж натиснути на посилання: зловмисники можуть замаскувати доменне ім'я, щоб воно виглядало знайомим (`facelook.com`, `gooogle.com` тощо) Використовуйте HTTPS та перевіряйте SSL-сертифікат веб-сайту, щоб переконатися, що він не клонований або підроблений.

Шкідливі URL-адреси **можуть "маскуватися" за довільним текстом** в HTML-файлах, документах та електронних листах. У веб-браузері або поштовій програмі наведіть курсор миші на посилання (але не натискайте) і почекайте деякий час (1-2 сек), поки не "спливе" реальний URL. Можна також клацнути правою кнопкою миші на посиланні та скопіювати його в текстовий редактор, щоб побачити його фактичну адресу. Використовуйте [VirusTotal](https://virustotal.com) для перевірки підозрілих посилань так само, як для сканування файлів.

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

Не підключайте флешки та зовнішні диски, не вставляйте CD та DVD тощо у ваш комп'ютер якщо ви не довіряєте повністю їхньому джерелу. Існують техніки зламу комп'ютера ще до того, як ви відкриєте файл на флешці і задовго до того, як ваш антивірус його просканує. Якщо ви знайшли пристрій всередині офісу або на вулиці, якщо ви отримали його по пошті або з доставкою, якщо незнайомець дав вам його з проханням роздрукувати документ або просто відкрити та перевірити його вміст – є великі шанси, що пристрій є зловмисним. Довіряйте лише власним пристроям та будьте обережні з пристроями, які отримуєте від інших людей по роботі або в інших цілях.

## Використовуйте пасфрази замість паролів

### Що таке пасфраза?

Використовуйте пасфрази замість паролів щоб уникнути проблем зі слабкими паролями. Паролі, які засновані на відомих словах з словника, легко підібрати.

Натомість, оберіть фразу, яку ви не зможете легко забути в наступні 2-3 дні: рядок з вірша або пісні, прислів'я, гасло тощо. Потім трансформуйте цю фразу у єдине "слово" видаливши пробіли та замінивши деякі літери схожими на них цифрами або спецсимволами: `A->4`, `B->8`, `C->(`, `E->3`, `I->1`, `L->7`, `S->5`, `T->7` тощо. Додавання цифр та спецсимволів, а також переведення деяких букв у верхній регістр, зроблять пасфразу ще сильнішою.

### Як створити сильну пасфразу?

Використовуйте рецепти створення сильних, унікальних пасфраз. Рецепт – це алгоритм, який використовується для формування різних пасфраз для різних систем на спільній основі. Наприклад:

1. Виберіть міцну основу, скажімо, пасфразу `w3llD0nem8'`

2. Придумайте спосіб прив'язки ключової фрази до сервісу. Наприклад, просте додавання імені сервера в кінці:

	`w3llD0nem8'google`

	Або розщеплення імені сервісу навпіл і додавання на початку та в кінці фрази:

	`goow3llD0nem8'gle`

	`glew3llD0nem8'goo`

3. Не забудьте трохи "перекрутити" отриману фразу, скажімо, змінивши останню букву імені сервісу на цифру, якщо це можливо, і додавши знак оклику або інший спецсимвол.

	`goow3llD0nem8'gl3!`

### Тримайте пасфрази в секреті

Ніхто крім вас не повинен знати ваші пасфрази. Не розказуйте їх нікому, включаючи вашого боса, вашого сисадміна або службу підтримки, вашу дружину, ваших батьків, ваших дітей тощо. В них **немає ніяких логічних або законних підстав для отримання ваших пасфраз**. З технічної точки зору, навіть система, в якій ви використовуєте пасфразу, не має доступу до неї в її первісному вигляді. Замість цього система зберігає "хеш" – її криптографічно захищену копію.

Ніколи не записуйте ваші пасфрази на папері або в незашифрованому файлі. Захищений паролем файл Excel – це не шифрування. Архів, захищений паролем – не є належним шифруванням. Використовуйте тільки надійні [парольні менеджери](#Парольні-менеджери) для зберігання пасфраз, якщо це необхідно.

### Оновлення пасфраз

Змінюйте пасфрази на регулярній основі та **принаймні один раз на рік**. Ваші корпоративні пасфрази та пасфрази, які ви використовуєте найчастіше (наприклад, кілька разів на день), повинні змінюватися принаймні щомісячно або раз на два місяці. 

:bulb: "Правило буравчика": чим частіше ви використовуєте пасфразу, тим частіше вона повинна змінюватись.

### Парольні менеджери

Використовуйте програмне забезпечення для збереження та захисту паролів – парольні менеджери – та виконуйте ці правила:

0. Генеруйте сильні, випадкові паролі довжиною від 20 символів.
1. Переконайтеся, що ваш майстер-пароль, яким ви захищаєте решту паролів, є сильною пасфразою.
2. Використовуйте парольний менеджер, який шифрує базу даних перед зберіганням її в хмарі або синхронізації між пристроями по мережі.
3. Частіше, бажано автоматично, робіть резервні копії бази даних паролів.

:wrench: Прикладами хороших парольних менеджерів є:
- 1Pasword https://1password.com
- KeePass http://keepass.info
- Password Safe https://pwsafe.org

### Все ще хочете використовувати паролі?

Надійні паролі довгі, складні та унікальні. Це означає, що вони повинні бути довше 12 символів, містити різні типи символів (літери, цифри, спеціальні символи), та бути різними для кожної служби, веб-сайту або системи. Паролі не повинні бути засновані на простих словах, які можна знайти в словниках. Паролі не повинні бути когнітивними, це означає, що вони не повинні бути засновані на даних про користувача або систему. В противному випадку, інформація, що стосується користувача або системи, допоможе зловмисникові вгадати пароль.

## Використовуйте двохфакторну автентифікацію

### Увімкніть двохфакторну автентифікацію

Більшість поважних онлайн-сервісів підтримують двохфакторну автентифікацію. Увімкніть її за допомогою програмного токена (доступний у Facebook, Twitter, Google тощо) або за допомогою одноразового пароля з доставкою по SMS.

:wrench: URL-адреси для налаштування багатофакторної автентифікації популярних веб-сайтів:
- Apple https://support.apple.com/en-us/HT204915
- Google https://myaccount.google.com/security/signinoptions/two-step-verification
- Facebook https://www.facebook.com/settings?tab=security&section=approvals
- Twitter https://twitter.com/settings/security
- Dropbox https://www.dropbox.com/account/#security

:wrench: Широка підбірка сервісів, які підтримують двохфакторну автентифікацію: https://twofactorauth.org

### Уникайте SMS

Надавайте перевагу використанню `Google Authenticator`, фізичного токена, або перевірці за допомогою мобільного додатку. Уникайте використання одноразових паролів через SMS коли це можливо.

## Операційна система та програмне забезпечення

Не використовуйте піратське програмне забезпечення. Не запускайте та не встановлюйте програмне забезпечення, завантажене з ненадійних джерел, включаючи торенти та інші peer-to-peer мережі обміну файлами. Це особливо стосується "кейгенів" та "крякалок", які зазвичай вимагають права адміністратора для запуску.

Мораль або етика не мають з цим нічого спільного: це просто абсолютно небезпечно. По-перше, зараження дистрибутиву програми Троянцем та "безкоштовна" публікація його в Інтернеті – це відомий спосіб зараження систем, і це відбувається набагато частіше, ніж хотілося б. По-друге, на піратське програмне забезпечення рідко можна своєчасно встановлювати оновлення безпеки, які просто не надходять до вашої системи. "Активації" та повторні активації згають ваш час, а ризики не оновлення програмного забезпечення є неприйнятними.

### Windows

Увімкніть авто-оновлення (`Auto-Update`) в вашій ОС Windows. Для більш детального опису дій зверніться до [офіційної інструкції](https://support.microsoft.com/en-us/help/12373/windows-update-faq).

Переконайтеся в тому, що авто-оновлення Windows [налаштоване для перевірки оновлень для всіх продуктів Microsoft](https://www.winhelp.us/configure-automatic-updates-in-windows.html), включаючи MS Office.

Оновлюйте програмне забезпечення від "сторонніх" постачальників регулярно та автоматично. Для цього використовуйте `Flexera` (раніше відома як Secunia) PSI або еквівалентне рішення, яке перевіряє наявність оновлень для вашого ПЗ та дозволяє вам встановлювати їх автоматично.

:wrench: Flexra PSI: http://www.flexerasoftware.com/enterprise/products/software-vulnerability-management/personal-software-inspector/

### macOS

Увімкніть авто-оновлення в `AppStore` [як рекомендує Apple](https://support.apple.com/kb/PH25371).

Увімкніть авто-оновлення MS Office в macOS [як рекомендує Microsoft](https://support.office.com/en-us/article/Check-for-Office-for-Mac-updates-automatically-bfd1e497-c24d-4754-92ab-910a4074d7c1).

Використовуйте Homebrew для оновлення вашого стороннього ПЗ. Ви можете легко знайти багато програм, які вже використовуєте, у Homebrew:

```bash
brew search vlc
brew search wireshark
brew search gpgtools
```

Щоб встановити Homebrew, ознайомтеся з офіційною інструкцією: http://brew.sh 

В якості альтернативи, щоб тримати сторонні програми в актуальному стані, використовуйте MacInformer або еквівалентний інструмент. :exclamation: ПОПЕРЕДЖЕННЯ: хоча це й безпечніше, ніж не використовувати жоден механізм оновлення, такого роду програмне забезпечення може бути "рекламно-агресивним" та звісно ж не таким безпечним, як Homebrew. Отже, URL на продукт тут немає.

### Linux

Сучасні дистрибутиви Linux дають змогу налаштувати авто-оновлення за допомогою засобів ОС, або ж регулярно оновлювати ПЗ вручну. Наприклад, у Ubuntu Linux оновлення ПЗ здійснюється за допомогою команди

```bash
apt update && apt -y upgrade
```

За подробицями щодо вашого дистрибутиву Linux зверніться до документації.

## Антивірус

### macOS та Linux

В Linux або macOS **не користуйтеся** антивірусом. Серйозно. Рішення з безпеки також містять вразливості, вони не є безпечнішими за будь-який інший програмний продукт. При цьому, з метою ефективності, антивіруси зазвичай вимагають підвищених привілеїв в ОС. Це становить більший ризик, ніж загроза інфікування вірусом або троянцем на порівняно більш безпечній та менш популярній платформі. Якщо ви слідуєте іншим рекомендаціям з цієї інструкції , ви можете встановити антивірус, який не буде постійно моніторити вашу ОС, та періодично сканувати вашу систему з його допомогою. 

:wrench: Один з таких варіантів це Malwarebytes: https://www.malwarebytes.com

### Windows

В Windows **користуйтеся** антивірусом. Але не забувайте, що антивіруси дуже неефективні проти сучасних онлайн-загроз. Ви можете уявити собі ефективність антивірусів десь між 15% та 30%, в більшості випадків це буде правдою.

Вибрати антивірус нелегко: "незалежні" тести більш прихильні до антивірусних вендорів, які в решті решт фінансують ці тестування. Існують, щоправда, більш-менш об'єктивні ревю та результати тестувань.

- AV-Test.org https://www.av-test.org/en/antivirus/home-windows
- Результати тестування NSS Labs, якщо ви можете їх знайти.

## Робіть резервні копії даних

### macOS

Використовуйте окремий зашифрований зовнішній жорсткий диск для резервного копіювання з допомогою `Time Machine`. Підключайте його кожного разу, коли працюєте над чимось важливим, резервні копії будуть створюватися автоматично. Рекомендований об'єм диску: щонайменше вдвічі більший за об'єм вашого внутрішнього носія. [Інструкція від Apple](https://support.apple.com/en-us/HT201250).

### Windows

У Windows 10 налаштування функції створення та відтворення з резервних копій дуже просте і може бути здійснене в меню  `Settings -> Update & Security -> Backup`. [Інструкція Micrsoft](https://support.microsoft.com/en-us/help/17143/windows-10-back-up-your-files).

Для Windows 8.1 та 7 виконайте [ці рекомендації Microsoft](https://support.microsoft.com/en-us/help/17127/windows-back-up-restore) щодо роботи з резервними копіями даних та системи.

В якості альтернативи, оберіть та використовуйте [програмне забезпечення від стороннього постачальника](http://www.techradar.com/news/software/applications/best-free-backup-software-11-programs-we-recommend-1137924).

### Linux

Користувачі Linux мають доступ до різноманіття засобів створення резервних копій: від `tar` до `rsync` на мережеву файлову шару. Менш досвідчені користувачі можуть обрати [більш комфортний інструмент](http://www.nuxified.org/blog/easy-linux-backup-software-time-machine-functionality/).

Ви можете створювати резервні копії ваших даних автоматично, зберігаючи їх у хмарних носіях, таких як `Dropbox`, `iCloud Drive`, `OneDrive`, `Google Drive` тощо. Але не забувайте [шифрувати ваші дані](#Шифруйте-хмарні-дані) перед завантаженням їх у хмару.

## Використовуйте криптографію

### Перевіряйте шифрування веб-сайтів

Завжди переконуйтесь, що веб-сайт, якому ви передаєте свої чутливі дані, використовує HTTPS. Це означає, що його адреса в адресному рядку браузера починається з `https://` та його сертифікат перевірений вашим браузером, отже він не робить вам попереджень безпеки.

Зверніть увагу, що наявності HTTPS не достатньо для виникнення довіри до веб-сайту: будь-хто може згенерувати дійсний сертифікат для свого веб-сервера. Потрібно звернути увагу та перевірити правильність доменного імені веб-сайту, тому що воно може бути легко підроблене, а веб-сайт – клонований.

:exclamation: Ніколи, навіть для тимчасового використання, не приймайте недійсні сертифікати.

### Шифруйте дані

Ви можете використовувати функцію `Full Disk Encryption` вашої операційної системи для захисту даних на вашому ноутбуці або ПК від крадіжки або втрати. FDE це безкоштовна функція у Linux, MacOS та Windows Pro.

#### macOS

Увімкніть `File Vault`. Ось і все, ви це зробили. [Інструкція від Apple](https://support.apple.com/en-us/HT204837).

#### Linux

Використовуйте `LUKS` або інші засоби повного шифрування диску. В якості альтернативи, під час встановлення ОС зазвичай можна вибрати параметри шифрування диску або шифрування тільки вашого домашнього розділу. Ось це [достатньо детальна інструкція для Arch](https://wiki.archlinux.org/index.php/Dm-crypt/Encrypting_an_entire_system), але кожен популярний дистрибутив має аналогічний документ.

#### Windows

Ввімкніть `BitLocker`. Це швидко зробити та легко налаштувати та використовувати, тому що це "рідний" механізм ОС Windows. [Інструкція від Microsoft](http://www.howtogeek.com/234826/how-to-enable-full-disk-encryption-on-windows-10/).

У разі, якщо ваша версія ОС Windows поставляється без BitLocker, використовуйте "сторонні" рішення. Наприклад `VeraCrypt`, який є відгалуженням від TrueCrypt, :exclamation: який у свою чергу припинив існування та не рекомендується для використання.

:wrench: VeraCrypt: https://veracrypt.codeplex.com

:bulb: Ви також можете шифрувати зовнішні диски або окремі файли.

### Шифруйте канали зв'язку

Використовуйте надійне шифрування "з кінця в кінець" для передачі приватних та конфіденційних даних. Шифрування "з кінця в кінець" гарантує, що ніхто, крім вас і вашого одержувача не може отримати доступ до розмови. Засобами шифрування електронної пошти "з кінця в кінець" є `PGP/GPG`, та `S/MIME`. Програми обміну миттєвими повідомленнями, які здійснюють шифрування "з кінця в кінець":  `Signal`, `WhatsApp`, `iMessage`, `Viber`, `Threema`. В `Facebook Messenger`, `Google Allo`, і `Telegram` є "секретні чати", які можна розглядати як більш безпечний режим, ніж чати за замовчуванням.

:wrench: Шифрування електронної пошти

- GPGTools для Apple Mail та macOS: https://gpgtools.org/
- OpenPGP у Microsoft Outlook 2016/2013/2010/2007: https://www.encryptomatic.com/openpgp/
- S/MIME в Outlook Web App: https://support.office.com/en-us/article/Encrypt-messages-by-using-S-MIME-in-Outlook-Web-App-2e57e4bd-4cc2-4531-9a39-426e7c873e26

:wrench: Месенджери, які здійснюють шифрування "з кінця в кінець" за замовчуванням:

- Signal https://whispersystems.org
- WhatsApp (uses Signal protocol) https://www.whatsapp.com
- Viber https://www.viber.com
- Threema https://threema.ch

:wrench: Месенджери з підтримкою посиленої анонімності:
	
- Ricochet https://ricochet.im
- Retroshare http://retroshare.net

Інструкція з безпечного обміну миттєвими повідомленнями та порівняння рівня безпеки сучасних месенджерів від EFF: https://www.eff.org/secure-messaging-scorecard

### Шифруйте хмарні дані

Шифруйте дані перед завантаженням в хмару. Пам'ятайте: немає ніякої "хмари", це просто чужий комп'ютер. `Boxcryptor` є інструментом, який дозволяє шифрувати дані в автономному режимі, перш ніж покласти їх у хмарний диск. Використовуйте його безкоштовно для одного хмарного диску.

:wrench: Boxcryptor: https://www.boxcryptor.com

### Користуйтеся VPN

Для того, щоб захистити ваші мережеві дані та метадані від прослуховування, використовуйте VPN (віртуальна приватна мережа). Ви можете вибрати один з багатьох провайдерів послуг VPN, таких як proXPN або PrivateTunnel. Ви можете встановити і підтримувати свій власний VPN-сервер. Під час віддаленої роботи з бізнес-даними, завжди використовуйте корпоративну VPN.
	
:wrench: Персональні VPN:

- PrivateTunnel https://www.privatetunnel.com
- proXPN https://secure.proxpn.com

:bulb: Як налаштувати свій власний VPN-сервер: https://www.digitalocean.com/community/tutorials/openvpn-access-server-centos

## Мобільна безпека

Мобільна (стільникова) мережа є так само небезпечною, як публічні точки доступу Wi-Fi. Використовуйте ті ж криптографічні засоби у вашій мобільній мережі передачі даних. Не вважайте SMS або ваші голосові розмови приватними: замість цього використовуйте голосові виклики та повідомлення, які шифруються "з кінця в кінець".

Використовуйте `iOS`. Судячи з усього, мобільна безпека `Apple` та безпека їхньої екосистеми застосунків є набагато безпечнішою за рішення на базі ОС Android, які контролюються вашим оператором зв'язку або OEM-виробником (Samsung, LG, Sony тощо.)

Якщо `Android`, то `Google`. Тільки пряма підтримка операційної системи з боку виробника може гарантувати своєчасні оновлення безпеки. Будь-які додаткові кроки в ланцюжку поставок (OEM постачальники, стільникові оператори, корпоративні ІТ тощо) знижують рівень безпеки. У деяких випадках оновлення просто припиняють надходити до вашого пристрою через рік або два після початку його використання.

Не "рутайте" (`root`) свій смартфон. Використовуйте тільки дозволені репозиторії додатків, наприклад, `Google Play` та `AppStore`. Не завантажуйте та не встановлюйте "оновлення безпеки", які надходять з неавторизованих джерел програмного забезпечення.

## Фізична безпека

Тримайте ваші речі, де ви можете їх бачити або контролювати. Ваш комп'ютер і гаджети вимагають такого ж рівня фізичної безпеки, який ви забезпечуєте вашим кредитним карткам та ключам від квартири або автомобіля. Пам'ятайте: якщо зловмисник проведе навіть недовгий час наодинці з вашим комп'ютером, це вже буде не ваш комп'ютер, а його. Швидше за все, він зможе повністю скомпрометувати вашу систему не доклавши суттєвих зусиль. Блокування сесії користувача може допомогти, але існують сучасні атаки, від яких воно не захищає.

Отже, не залишайте ваш пристрій без нагляду, особливо коли він працює. Вимикайте його або відправляйте у режим гібернації кожного разу, коли ви залишаєте його без нагляду навіть на декілька хвилин. Налаштуйте запит паролю кожного разу, коли він вмикається.

Здійснюйте чутливі та нечутливі операції з різних комп'ютерів. Якщо ви дозволяєте дітям грати в онлайн-ігри на комп'ютері, який ви використовуєте для онлайн-банкінгу – вас зламають. Якщо ви відвідуєте Інтернет-крамниці з ПК в комп'ютерному клубі або Інтернет-кафе – вас зламають. Якщо ви відправляєте ділові листи з ПК у відкритій зоні вашого готелю – вас зламають.

Використовуйте окремий комп'ютер для бізнес- та фінансових операцій та усіх дій, які вимагають приватності або конфіденційності. Використовуйте спеціальну віртуальну або фізичну машину для найбільш критичних операцій.

:bulb: В деяких авторитарних країнах вас можуть *попросити* надати пароль до вашого зашифрованого носія інформації на кордоні та в аеропорті. Перетинаючи кордони таких держав, скористайтеся порадою: попросіть людину, якій ви довіряєте (бажано юриста) змінити ваш пароль перед від'їздом та надати його вам лише коли ви завершите подорож. Повторіть процедуру на зворотньому шляху. 

## Бережіться!

Дякую, що приділяєте увагу власній кібер-безпеці. Поділіться цією пам'яткою з близькими, друзями та колегами, щоб зробити світ трохи безпечнішим.

Ця пам'ятка – результат роботи спеціалістів з кібер-безпеки, які мають багаторічний досвід побудови, перевірки та етичного зламу комп'ютерних систем, додатків та мереж.

Ви можете поширювати цю пам'ятку, використовувати її у бізнесі, та змінювати на власний розсуд. Це безкоштовно. Посилання на оригінал та автора вітаються.

Якщо у вас є що додати або ви знайшли в тексті помилку, напишіть на :email: sapran@protonmail.com або [створіть issue](https://github.com/sapran/dontclickshit/issues/new).

Скомпільовано та підготовлено by Vlad Styran, [Berezha Security](https://berezhasecurity.com), https://blog.styran.com
