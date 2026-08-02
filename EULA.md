# Lithium 7 — Условия использования / Terms of use

**Редакция (revision): 2**  
**Программа / Program:** Lithium 7 («Программа» / “the Program”)  
**Характер:** безвозмездно, AS IS, закрытый исходный код (proprietary)

Этот файл — **публичная копия** обязательных условий доступа к Программе. Тот же смысл зафиксирован внутри приложения (GUI-пластина и `lithium eula`). При существенном изменении текста автор может поднять номер редакции и запросить повторное согласие.

Начиная использовать Программу (включая выражение согласия в GUI или CLI), вы подтверждаете, что **прочитали, поняли и приняли** эти условия целиком. Если вы не согласны — **не используйте** Программу и закройте её.

By using the Program (including expressing consent in the GUI or CLI), you confirm that you have **read, understood, and accepted** these terms in full. If you do not agree — **do not use** the Program and close it.

---

## Как принимается согласие / How consent is recorded

| Канал | Действие |
|-------|----------|
| **GUI** | Прочитать текст; согласие — **правый клик** по элементу принятия (тихая подсказка в UI). |
| **CLI** | `lithium eula [ru\|en]`, затем ввести точно: **`ПРИНИМАЮ`** (не `y`, не один Enter). |
| **Хранение** | `HKCU\Software\Lithium` — `EulaAccepted`, `EulaVersion` |

Фраза CLI всегда **`ПРИНИМАЮ`**, даже если тело соглашения на английском.

---

# Русский текст (канон для RU-локали)

## 1. Безвозмездность и характер распространения

Программа предоставляется бесплатно, «как есть» (**AS IS**), без каких-либо гарантий — явных, подразумеваемых или предусмотренных законом, в той мере, в какой отказ от гарантий допустим. Автор не обещает пригодности для конкретной цели, бесперебойной работы, совместимости с вашей системой или отсутствия ошибок.

Программа поставляется **одним исполняемым файлом без инсталлятора** и не обязывает автора поддерживать какое-либо конкретное окружение, путь запуска или способ доставки. Отсутствие инсталлятора не означает отсутствия следа в системе: Программа создаёт записи в реестре Windows и локальный журнал (см. §7).

**Заявленная среда первого публичного релиза:** Windows 11 **25H2 Pro** и новее (в перспективе — **26H2**), UI на **Microsoft Edge WebView2**. Иные редакции и версии ОС могут не поддерживаться.

## 2. Закрытый исходный код

Программа распространяется как закрытый (**proprietary**) продукт. Исходный код не предоставляется. Запрещены (в объёме, допустимом применимым правом): обратная разработка, декомпиляция, дизассемблирование, извлечение компонентов, снятие защиты, а также создание производных работ, если иное прямо не разрешено автором в письменной форме.

## 3. Ваша ответственность — полная и исключительная

Всё, что вы делаете с помощью Программы с момента согласия, лежит **строго на вас**. Вы самостоятельно оцениваете риски, последствия, законность и уместность любых действий: изменение параметров Windows, реестра, служб, сетевых настроек, файловых ассоциаций, очистки, обновлений, снимков состояния и любых иных операций, доступных в Программе сейчас или в будущем.

Автор **не несёт ответственности** за любой ущерб — прямой, косвенный, случайный, последующий, штрафной или иной — включая, без ограничения: потерю данных, простой, сбои оборудования или ПО, потерю прибыли, репутационный вред, нарушение лицензий третьих лиц, претензии работодателя или администратора сети, административные или уголовные последствия, а также любые «непредвиденные» результаты ваших действий.

Вы соглашаетесь, что используете Программу **на свой страх и риск**, и что вы обладаете достаточными правами и компетенцией для изменения конфигурации системы, на которой запускаете Программу.

## 4. Нет обязанности поддержки

Автор не обязан оказывать поддержку, отвечать на обращения, выпускать обновления, исправлять ошибки или сохранять совместимость с будущими версиями Windows. Любая помощь, если она случается, — жест доброй воли, а не обязательство.

## 5. Неофициальные, крякнутые и изменённые сборки

Использование неофициальной, взломанной («крякнутой»), пересобранной, перекодированной, пропатченной, заражённой, урезанной или иным образом изменённой копии Программы **не создаёт** обязанностей и **не влечёт** ответственности автора. Автор не контролирует и не ручается за происхождение таких копий, их содержимое, встроенный код третьих лиц, трояны, майнеры, кейлоггеры и любые иные «сюрпризы».

Претензии, связанные с такими копиями, адресуются исключительно тому, кто их собрал, распространил или вам передал — **не** автору оригинальной Программы.

## 6. Целостность, подмена и обман

Если интерфейс, текст, поведение или цифровая подпись (если применимо) не совпадают с официальной поставкой — считайте экземпляр **скомпрометированным**. Автор не отвечает за ущерб от подмены, репаков, «тихих» установщиков и сборок «с твиками от автора YouTube».

Скачивайте Программу только из **официального** канала автора (релизы данного репозитория / страница, указанная автором).

Официальная поставка **не имеет цифровой подписи издателя**. Единственный механизм проверки подлинности экземпляра — **SHA256**, опубликованный на странице того же релиза. Экземпляр, чей хеш расходится с опубликованным, считается изменённым: на него распространяется §5, и ни одно положение настоящих условий, касающееся оригинальной Программы, к нему не применяется.

## 7. Данные, журналы и следы

Программа может создавать **локальные** файлы (в том числе журнал рядом с исполняемым файлом) и записи в реестре Windows (в том числе служебные отметки согласия и состояния). Вы понимаете и принимаете это. Автор **не** собирает ваши данные «в облако» через эту Программу как часть обязательной телеметрии продукта; однако сам Windows, антивирусы, корпоративные агенты и сеть, в которой вы работаете, могут фиксировать активность **независимо** от автора.

## 8. Запрещённое и рискованное использование

Вы обязуетесь **не** использовать Программу для нарушения закона, обхода мер безопасности без полномочий, повреждения чужих систем, сокрытия противоправной деятельности или иных целей, на которые у вас нет права. Любое такое использование — исключительно ваша вина и ваш риск; автор дистанцируется от него полностью.

## 9. Возмещение и защита интересов автора

В пределах, допускаемых правом, вы соглашаетесь оградить автора от претензий третьих лиц, штрафов, издержек и расходов (включая разумные юридические), возникших из-за вашего использования Программы, нарушения этих условий или ваших действий на затронутых системах.

## 10. Ограничение ответственности — потолок

В максимальной степени, допустимой применимым правом, совокупная ответственность автора по любым требованиям, связанным с Программой, **не превышает** сумму, фактически уплаченную вами автору за Программу. Поскольку Программа бесплатна, эта сумма равна **нулю**.

## 11. Автономность положений

Если какое-либо положение признают недействительным, остальные сохраняют силу. Бездействие автора при нарушении условий не означает отказа от прав.

## 12. Изменения

Автор может обновлять условия в новых версиях Программы. При существенном изменении может потребоваться **повторное** согласие. Продолжение использования после такого запроса означает принятие новой редакции.

## 13. Принятие

Выражая согласие, вы подтверждаете, что вам есть **18 лет** (или вы действуете с согласия законного представителя там, где это требуется), что вы понимаете риски изменения системы, и что принимаете на себя **полную** ответственность за последствия.

## 14. Автор, применимое право и язык текста

«Автор» — правообладатель Программы, указанный на официальной странице релизов; там же приводится единственный канал связи с ним (ROST/rost).

К настоящим условиям применяется право Российской Федерации в части, не противоречащей императивным нормам страны вашего постоянного проживания.

Русский и английский тексты имеют равную силу. При расхождении толкований преимущество имеет **русский** текст.

Ничто в настоящих условиях не ограничивает права, прямо предоставленные вам императивными нормами закона, включая право на изучение и адаптацию программы для достижения совместимости в объёме, гарантированном законом (в частности, ст. 1280 ГК РФ, ст. 6 Директивы 2009/24/EC).

## 15. Компоненты третьих лиц

Интерфейс Программы работает поверх **Microsoft Edge WebView2 Runtime** — продукта Microsoft, поставляемого на условиях Microsoft. Автор не является его правообладателем и не отвечает за его работу.

Отдельные данные, включённые в поставку (списки доменов, наборы значений конфигурации и подобное), могут происходить из открытых источников с собственными лицензиями. Их перечень и условия приводятся на официальной странице релизов.

---

# English text (canon for EN locale)

## 1. Gratis nature and distribution

The Program is provided free of charge, **“as is” (AS IS)**, without any warranties — express, implied, or statutory — to the extent a disclaimer is permitted. The author does not promise fitness for a particular purpose, uninterrupted operation, compatibility with your system, or freedom from errors.

The Program ships as **a single executable with no installer** and does not obligate the author to support any particular environment, launch path, or delivery method. The absence of an installer does not mean the absence of a trace: the Program creates Windows registry entries and a local journal (see §7).

**Stated environment for the first public release:** Windows 11 **25H2 Pro** or newer (with **26H2** expected), UI on **Microsoft Edge WebView2**. Other editions and OS versions may be unsupported.

## 2. Closed source

The Program is distributed as a closed (**proprietary**) product. Source code is not provided. Reverse engineering, decompilation, disassembly, extraction of components, circumvention of protection, and creation of derivative works are prohibited (to the extent allowed by applicable law), unless the author expressly permits otherwise in writing.

## 3. Your responsibility — full and exclusive

Everything you do with the Program from the moment of consent is **strictly on you**. You alone assess risks, consequences, legality, and appropriateness of any actions: changing Windows settings, the registry, services, network configuration, file associations, cleanup, updates, state snapshots, and any other operations available in the Program now or in the future.

The author is **not liable** for any damage — direct, indirect, incidental, consequential, punitive, or otherwise — including without limitation: data loss, downtime, hardware or software failures, lost profits, reputational harm, third-party license violations, claims by an employer or network administrator, administrative or criminal consequences, and any “unforeseen” results of your actions.

You agree that you use the Program **at your own risk**, and that you have sufficient rights and competence to change the configuration of the system on which you run the Program.

## 4. No support obligation

The author is not obliged to provide support, answer requests, ship updates, fix bugs, or maintain compatibility with future Windows versions. Any help, if it happens, is a gesture of goodwill, not an obligation.

## 5. Unofficial, cracked, and modified builds

Using an unofficial, cracked, rebuilt, re-encoded, patched, infected, stripped, or otherwise modified copy of the Program creates **no** duties and **no** liability for the author. The author does not control and does not vouch for the origin of such copies, their contents, embedded third-party code, trojans, miners, keyloggers, or any other “surprises”.

Claims related to such copies are addressed solely to whoever built, distributed, or handed them to you — **not** to the author of the original Program.

## 6. Integrity, substitution, and fraud

If the interface, text, behavior, or digital signature (if applicable) does not match the official distribution — treat the copy as **compromised**. The author is not responsible for damage from substitution, repacks, “silent” installers, or builds “with YouTube-author tweaks”.

Download the Program only from the author’s **official** channel (releases of this repository / a page designated by the author).

The official distribution carries **no publisher code signature**. The only authenticity check is the **SHA256** published on the same release page. A copy whose hash differs from the published one is deemed modified: §5 applies to it, and no provision of these terms concerning the original Program applies to it.

## 7. Data, logs, and traces

The Program may create **local** files (including a journal next to the executable) and Windows registry entries (including service marks of consent and state). You understand and accept this. The author does **not** collect your data “to the cloud” through this Program as mandatory product telemetry; however Windows itself, antivirus software, corporate agents, and the network you work on may record activity **independently** of the author.

## 8. Prohibited and high-risk use

You agree **not** to use the Program to violate the law, bypass security measures without authority, damage others’ systems, conceal unlawful activity, or other purposes you have no right to pursue. Any such use is solely your fault and your risk; the author fully distances from it.

## 9. Indemnity and protection of the author

To the extent permitted by law, you agree to hold the author harmless from third-party claims, fines, costs, and expenses (including reasonable legal fees) arising from your use of the Program, breach of these terms, or your actions on affected systems.

## 10. Limitation of liability — ceiling

To the maximum extent permitted by applicable law, the author’s aggregate liability for any claims related to the Program shall **not exceed** the amount you actually paid the author for the Program. Because the Program is free, that amount is **zero**.

## 11. Severability

If any provision is held invalid, the remainder remains in force. The author’s failure to act on a breach does not waive rights.

## 12. Changes

The author may update these terms in new versions of the Program. A material change may require **renewed** consent. Continued use after such a request means acceptance of the new revision.

## 13. Acceptance

By expressing consent, you confirm that you are at least **18** years old (or act with a legal guardian’s consent where required), that you understand the risks of changing the system, and that you accept **full** responsibility for the consequences.

## 14. Author, governing law, and language

“The author” means the rightsholder of the Program named on the official releases page, which also lists the only contact channel (ROST/rost).

These terms are governed by the law of the Russian Federation, to the extent this does not conflict with mandatory rules of your country of habitual residence.

The Russian and English texts are equally valid. In case of divergent interpretation, the **Russian** text prevails.

Nothing in these terms limits rights granted to you by mandatory provisions of law, including the right to study and adapt the program to achieve interoperability to the extent guaranteed by law (in particular Art. 1280 of the Civil Code of the Russian Federation and Art. 6 of Directive 2009/24/EC).

## 15. Third-party components

The Program’s interface runs on top of **Microsoft Edge WebView2 Runtime**, a Microsoft product supplied under Microsoft’s own terms. The author is not its rightsholder and is not responsible for its operation.

Certain data bundled with the Program (domain lists, configuration value sets, and similar) may originate from open sources under their own licenses. Their list and terms are published on the official releases page.

---

*Lithium 7 · EULA revision 1 · free · proprietary · AS IS*
