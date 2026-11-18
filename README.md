# TEKSO

[Български по-долу](#bulgarian)

**One app for the documents you already have. Text, spreadsheets, presentations and PDF. No account, no cloud, no subscription pile.**

Office work should not mean a different app, a different bill and a different login for every file type. TEKSO opens the formats people already use (`.docx`, `.xlsx`, `.pptx`, PDF and OpenDocument) in one small desktop app. Your files stay on your computer. If you want an AI assistant to help, it can only propose changes, and you decide. Free during the beta. Later, about 5 to 7 EUR per year.

*Made by one person in Varna, Bulgaria.*

## Why TEKSO

- **One app, not a bundle of bills.** Text, spreadsheets, presentations and PDF live in one place. One small yearly price later, not separate apps with separate prices.
- **Your formats, not ours.** Open and save `.docx`, `.xlsx` and `.pptx`. Read `.odt`, `.ods` and `.odp`. Nothing to convert, nobody to ask.
- **Your files stay yours.** No account. No cloud. No telemetry. Not even automatic update checks. Files leave your computer only if you hand them to an AI of your choice.
- **AI that asks first.** Every change an AI makes is a proposal. You accept or reject it. Your passwords and PINs never reach the AI.
- **Serious PDF.** Edit, fill forms, produce PDF/A and accessible PDF/UA (both checked with veraPDF), and sign with a qualified electronic signature (QES/КЕП) on your smart card.

## What it does today

| You want to | TEKSO gives you |
|---|---|
| Write | Text documents: opens and saves `.docx` |
| Calculate | Spreadsheets: opens and saves `.xlsx`, with formulas and charts |
| Present | Presentations: opens and saves `.pptx` |
| Open other formats | Reads OpenDocument: `.odt`, `.ods`, `.odp` |
| Publish | Publications and books in our own `.opub` and `.obook` formats |
| Work with PDF | Editing and forms |
| Archive and accessibility | PDF/A and accessibility tagging (PDF/UA), both validated with veraPDF |
| Sign | Qualified electronic signature (QES/КЕП) on a smart card |
| Get help from AI | An assistant such as Claude works with your documents through MCP (the Model Context Protocol) |

Runs on macOS 12+ and Windows 10+ (64-bit).

## AI that asks first

Connect an AI assistant such as Claude and let it work on your documents through MCP. It reads, drafts and edits, but **every change is a proposal**. Nothing is applied until you accept it. Reject it and nothing happens.

- Passwords and PINs go only into TEKSO's own window. They never reach the AI.
- A standalone `tekso-mcp` server and a `.mcpb` package are available for Claude Desktop.
- AI suggestions can be wrong. Review them before accepting.

## Your files stay yours

- No account.
- No cloud.
- No telemetry.
- No automatic update checks.
- Files stay on your computer unless you give them to an AI assistant of your choice. They are then processed by that provider under its own terms.
- Downloading from GitHub is subject to GitHub's terms (for example, your IP address is visible to GitHub). GitHub counts file downloads.

## Coming next

These are plans, not promises, and they have no dates.

- **People:** store people and companies locally and insert their details while you type, with `/` or `@`, like code autocomplete. ID numbers never go to the AI.
- **Templates and mail merge.**
- **A deadline calendar.**
- **Helpers for Bulgarian institution filings:** TEKSO prepares the file, the human signs and submits.
- **A polished new interface** and the TEKSO visual identity.

## Beta and price, honestly

TEKSO is in **beta**. During the beta the app is **free**, and the beta has no end date.

Later it will cost about **5 to 7 EUR per year**. The price is not final. We will announce it at least **30 days** before it starts, and nothing will be charged without your explicit consent. An installed beta does not become paid retroactively. Details: [EULA](EULA.md), section 3.

Like any beta, the app may contain bugs. Keep backups of your important files. Compatibility with Microsoft Office is best effort, and complex documents may look different. For QES, the legal effect of a signature depends on your certificate provider, your card and the validity of your certificate. TEKSO is a tool, not legal advice.

## Not in the beta (yet)

- No real-time collaboration. This is by design: TEKSO is local.
- No macros. They are preserved in files, but not run.
- No live multi-monitor presenting.
- No screen-reader support yet.
- Arabic text in PDF/A is limited.

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

## Documentation

Install, first steps, AI setup, privacy and FAQ: [docs](docs/README.md).

## Feedback

Bugs and ideas: **Issues** tab. Do not post personal or confidential documents in public messages.

## Security

If you find a vulnerability, do not post it in Issues. Write to security@tekso.app.

## License

TEKSO is not open source software. Use is governed by the [EULA](EULA.md). The open-source components TEKSO uses, and their licenses, are listed in [THIRD-PARTY-LICENSES.md](THIRD-PARTY-LICENSES.md). This repository contains only installers, documentation and license texts. The source code is not public.

## Contact

hello@tekso.app · https://tekso.app

---

<a id="bulgarian"></a>

# TEKSO на български

[English above](#tekso)

**Едно приложение за документите, които вече имаш. Текст, таблици, презентации и PDF. Без акаунт, без облак, без купчина абонаменти.**

Офис работата не бива да значи различно приложение, различна сметка и различен вход за всеки вид файл. TEKSO отваря формати, които хората вече ползват (`.docx`, `.xlsx`, `.pptx`, PDF и OpenDocument), в едно малко приложение за компютъра. Файловете остават на твоя компютър. Ако искаш помощ от AI, той само предлага промени, а ти решаваш. Безплатно по време на бетата. По-късно, около 5 до 7 EUR годишно.

*Направено от един човек във Варна.*

## Защо TEKSO

- **Едно приложение, не пакет от сметки.** Текст, таблици, презентации и PDF на едно място. По-късно една малка годишна цена, а не отделни приложения с отделни цени.
- **Твоите формати, не нашите.** Отваряй и записвай `.docx`, `.xlsx` и `.pptx`. Чети `.odt`, `.ods` и `.odp`. Няма какво да се преобразува и никого не трябва да питаш.
- **Файловете остават твои.** Без акаунт. Без облак. Без телеметрия. Дори без автоматична проверка за нови версии. Файловете напускат компютъра само ако сам ги дадеш на AI по свой избор.
- **AI, който пита първо.** Всяка промяна от AI е предложение. Ти я приемаш или отхвърляш. Паролите и PIN кодовете ти никога не стигат до AI.
- **Сериозен PDF.** Редактиране, формуляри, PDF/A и достъпен PDF/UA (и двата проверени с veraPDF), и подпис с квалифициран електронен подпис (КЕП) от смарт карта.

## Какво прави днес

| Искаш да | TEKSO ти дава |
|---|---|
| Пишеш | Текстови документи: отваря и записва `.docx` |
| Смяташ | Таблици: отваря и записва `.xlsx`, с формули и диаграми |
| Представяш | Презентации: отваря и записва `.pptx` |
| Отвориш други формати | Чете OpenDocument: `.odt`, `.ods`, `.odp` |
| Издаваш | Публикации и книги в нашите формати `.opub` и `.obook` |
| Работиш с PDF | Редактиране и формуляри |
| Архив и достъпност | PDF/A и тагване за достъпност (PDF/UA), и двете валидирани с veraPDF |
| Подпишеш | Квалифициран електронен подпис (КЕП) от смарт карта |
| Ползваш AI | Асистент като Claude работи с документите ти през MCP (Model Context Protocol) |

Работи на macOS 12+ и Windows 10+ (64-битов).

## AI, който пита първо

Свържи AI асистент, например Claude, и му дай да работи по документите ти през MCP. Той чете, чернови и редактира, но **всяка промяна е предложение**. Нищо не се прилага, докато не го приемеш. Отхвърлиш ли го, нищо не се случва.

- Паролите и PIN кодовете се въвеждат само в собствения прозорец на TEKSO. Те никога не стигат до AI.
- Налични са самостоятелен сървър `tekso-mcp` и пакет `.mcpb` за Claude Desktop.
- AI предложенията може да са грешни. Прегледай ги, преди да ги приемеш.

## Файловете остават твои

- Без акаунт.
- Без облак.
- Без телеметрия.
- Без автоматична проверка за нови версии.
- Файловете остават на компютъра ти, освен ако сам не ги дадеш на AI асистент по твой избор. Тогава те се обработват от доставчика му по неговите условия.
- Изтеглянето от GitHub подлежи на условията на GitHub (например IP адресът ти е видим за GitHub). GitHub брои изтеглянията на файловете.

## Предстои

Това са планове, не обещания, и нямат срокове.

- **Хора:** пази локално хора и фирми и вмъквай данните им, докато пишеш, с `/` или `@`, като автодописване в код. ЕГН и номера на документи никога не отиват към AI.
- **Шаблони и сливане на кореспонденция.**
- **Календар на сроковете.**
- **Помощници за подаване към български институции:** TEKSO подготвя файла, човекът подписва и подава.
- **Изчистен нов интерфейс** и визуалната идентичност на TEKSO.

## Бета и цена, честно

TEKSO е в **бета**. По време на бетата приложението е **безплатно** и бетата няма крайна дата.

По-късно ще струва около **5 до 7 EUR годишно**. Цената не е окончателна. Ще я обявим най-малко **30 дни** преди да започне и няма да се таксува нищо без твоето изрично съгласие. Инсталирана бета версия не става платена със задна дата. Подробности: [EULA](EULA.md), т. 3.

Като всяка бета, приложението може да съдържа грешки. Прави си копия на важните файлове. Съвместимостта с Microsoft Office е по най-добро усилие и сложни документи може да изглеждат различно. При КЕП правната сила на подписа зависи от твоя удостоверител, картата и валидността на сертификата. TEKSO е инструмент, не правен съвет.

## Няма в бетата (още)

- Няма съвместна работа в реално време. Това е нарочно: TEKSO е локално.
- Няма макроси. Запазват се във файловете, но не се изпълняват.
- Няма презентиране на живо на няколко монитора.
- Още няма поддръжка за екранни четци.
- Арабският текст в PDF/A е ограничен.

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

## Документация

Инсталиране, първи стъпки, AI, поверителност и въпроси: [docs](docs/bg/README.md).

## Обратна връзка

Грешки и идеи: раздел **Issues**. Не публикувай лични или поверителни документи в публични съобщения.

## Сигурност

Откри ли уязвимост, не я публикувай в Issues. Пиши на security@tekso.app.

## Лиценз

TEKSO не е софтуер с отворен код. Ползването е по [EULA](EULA.md). Компонентите с отворен код, които TEKSO ползва, и техните лицензи са в [THIRD-PARTY-LICENSES.md](THIRD-PARTY-LICENSES.md). Това хранилище съдържа само инсталатори, документация и лицензни текстове. Изходният код не е публичен.

## Контакт

hello@tekso.app · https://tekso.app
