# TEKSO (beta)

[Български по-долу](#bulgarian)

**A desktop office suite: text, spreadsheets, presentations and PDF in one app. Your files stay on your computer.**

## Status

TEKSO is in **beta**. During the beta the app is **free**. The beta has no fixed end date.

TEKSO will become paid later, at roughly 5 to 7 EUR per year as an indication. We say so up front to avoid surprises. The price is not final: we will announce it at least 30 days before it starts and nothing will be charged without your explicit consent. An installed beta does not become paid retroactively. Details: [EULA](EULA.md), section 3.

Like any beta, the app may contain bugs. Keep backups of your important files.

## What it does

- **Text:** opens and saves `.docx`.
- **Spreadsheets:** opens and saves `.xlsx`, with formulas and charts.
- **Presentations:** opens and saves `.pptx`.
- **PDF:** editing, forms, PDF/A, signing with a qualified electronic signature (QES) on a smart card.
- **Optional AI:** an AI assistant (for example Claude) can work with your documents through MCP. The AI only **proposes** changes and you accept them. Passwords and PINs are entered only in the app window and are not passed to the AI.

## What we do not promise

- Compatibility with Microsoft Office is best effort. Complex documents may look different.
- QES: the legal effect of a signature depends on your certificate provider, your card and the validity of your certificate. TEKSO is a tool, not legal advice.
- AI suggestions can be wrong. Review them before accepting.

## Privacy

- No account, no cloud.
- The app does not send data about you, does not collect usage statistics and does not check for updates on its own.
- Your files do not leave your computer unless you give them to an AI assistant of your choice. They are then processed by that provider under its own terms.
- Downloading from GitHub is subject to GitHub's terms (for example, your IP address is visible to GitHub). GitHub counts file downloads.

## Download and install

Installers (Windows and macOS) are in the **Releases** section of this page.

- System requirements: Windows 10 or later (64-bit), macOS 12 or later.
- Checksums (SHA-256): published with each release.
- Beta installers are **not code-signed**. Windows SmartScreen and macOS Gatekeeper may show a warning on first launch.

### First launch of an unsigned beta

Code signing will come with the paid version. Until then, your system asks once:

- **macOS:** open TEKSO; when macOS says it cannot verify the developer, click **Done**. Then open **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to TEKSO. Confirm once more. From then on it opens normally.
- **Windows:** when the blue **Windows protected your PC** window appears, click **More info**, then **Run anyway**.

Download only from the **Releases** page of this repository and compare the SHA-256 checksum published with the release.

## Feedback

Bugs and ideas: **Issues** tab. Do not post personal or confidential documents in public messages.

## Security

If you find a vulnerability, do not post it in Issues. Write to security@tekso.app.

## License

TEKSO is not open source software. Use is governed by the [EULA](EULA.md). The open-source components TEKSO uses, and their licenses, are listed in [THIRD-PARTY-LICENSES.md](THIRD-PARTY-LICENSES.md). This repository contains only installers, documentation and license texts. The source code is not public.

## Contact

hello@tekso.app

---

<a id="bulgarian"></a>

# TEKSO (бета), на български

**Офис пакет за компютъра: текст, таблици, презентации и PDF в едно приложение. Файловете остават на твоя компютър.**

## Статус

TEKSO е в **бета**. По време на бетата приложението е **безплатно**. Бетата няма определена крайна дата.

По-късно TEKSO ще стане платено, за ориентир около 5 до 7 EUR годишно. Обявяваме го още сега, за да няма изненади. Цената не е окончателна: ще я обявим най-малко 30 дни преди да се въведе и няма да се таксува нищо без твоето изрично съгласие. Инсталирана бета версия не става платена със задна дата. Подробности: [EULA](EULA.md), т. 3.

Като всяка бета, приложението може да съдържа грешки. Прави си копия на важните файлове.

## Какво прави

- **Текст:** отваря и записва `.docx`.
- **Таблици:** отваря и записва `.xlsx`, с формули и диаграми.
- **Презентации:** отваря и записва `.pptx`.
- **PDF:** редактиране, формуляри, PDF/A, подписване с квалифициран електронен подпис (КЕП) на карта.
- **AI по избор:** AI асистент (например Claude) може да работи с документите през MCP. AI само **предлага** промени, ти ги приемаш. Паролите и PIN кодовете се въвеждат само в прозореца на приложението и не се подават към AI.

## Какво не обещаваме

- Съвместимостта с Microsoft Office е по най-добро усилие. Сложни документи може да изглеждат различно.
- КЕП: правната сила на подписа зависи от твоя удостоверител, картата и валидността на сертификата. TEKSO е инструмент, не правен съвет.
- AI предложенията може да са грешни. Прегледай ги, преди да ги приемеш.

## Поверителност

- Без акаунт, без облак.
- Приложението не изпраща данни за теб, не събира статистика за използване и не проверява само за нови версии.
- Файловете ти не напускат компютъра, освен ако сам не ги дадеш на AI асистент по твой избор. Тогава те се обработват от доставчика му по неговите условия.
- Изтеглянето от GitHub подлежи на условията на GitHub (например IP адресът ти е видим за GitHub). GitHub брои изтеглянията на файловете.

## Изтегляне и инсталиране

Инсталаторите (Windows и macOS) са в раздела **Releases** на тази страница.

- Системни изисквания: Windows 10 или по-нов (64-битов), macOS 12 или по-нов.
- Контролни суми (SHA-256): публикуват се към всяко издание.
- Инсталаторите на бетата **не са подписани** със сертификат. Windows SmartScreen и macOS Gatekeeper може да покажат предупреждение при първото отваряне.

### Първо отваряне на неподписаната бета

Подписът ще дойде с платената версия. Дотогава системата пита веднъж:

- **macOS:** отвори TEKSO; когато macOS каже, че не може да провери разработчика, натисни **Done**. После отвори **System Settings → Privacy & Security**, слез надолу и натисни **Open Anyway** до TEKSO. Потвърди още веднъж. След това се отваря нормално.
- **Windows:** когато се появи синият прозорец **Windows protected your PC**, натисни **More info**, после **Run anyway**.

Теглете само от раздела **Releases** на това хранилище и сравнете контролната сума SHA-256, публикувана към изданието.

## Обратна връзка

Грешки и идеи: раздел **Issues**. Не публикувай лични или поверителни документи в публични съобщения.

## Сигурност

Откри ли уязвимост, не я публикувай в Issues. Пиши на security@tekso.app.

## Лиценз

TEKSO не е софтуер с отворен код. Ползването е по [EULA](EULA.md). Компонентите с отворен код, които TEKSO ползва, и техните лицензи са в [THIRD-PARTY-LICENSES.md](THIRD-PARTY-LICENSES.md). Това хранилище съдържа само инсталатори, документация и лицензни текстове. Изходният код не е публичен.

## Контакт

hello@tekso.app
