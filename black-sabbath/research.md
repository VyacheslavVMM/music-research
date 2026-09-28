# Black Sabbath — дослідження видань (дати + звукова репутація)

## Важливе застереження щодо методології

У цій сесії мережева політика (egress policy) блокує **весь** прямий доступ до зовнішніх сайтів — і через `curl`/Bash, і через інструмент `WebFetch` (перевірено на en.wikipedia.org, wikidata.org, discogs.com, Apple/Deezer/Qobuz, навіть на example.com — усюди `EGRESS_BLOCKED`). Працював лише інструмент `WebSearch` — серверний пошук, що повертає короткі сніпети/узагальнення, а не сирий вміст сторінки чи JSON API.

**За прямою вказівкою користувача** обсяг цього проходу звужено:
- ✅ Розділ A (дати релізу/запису) — зроблено, на основі `WebSearch`-сніпетів, які цитують інфобокс англійської Вікіпедії.
- ✅ Розділ D (звукова репутація по кожному виданню) — зроблено, на основі `WebSearch`-сніпетів з оглядів/форумів.
- ❌ Розділ B (обкладинки Apple/Deezer/Qobuz з виміром пікселів) — **пропущено навмисно**, робиться окремо.
- ❌ Розділ C (реальні видання/Discogs) — **пропущено навмисно**, робиться окремо.

Жодна дата чи факт нижче не підтверджені прямим HTTP-запитом до Wikipedia API чи інших API (це було неможливо в цій сесії) — усе базується на узагальненнях `WebSearch`. Числові значення DR (dr.loudness-war.info) відомі як існуючі, але сторінку не вдалося завантажити напряму, тож конкретних DR-цифр у звіті немає — це чесно позначено в кожному розділі, де це стосується.

---

## 1. Technical Ecstasy (1976)

**Дата релізу:** 25 вересня 1976 (за інфобоксом Вікіпедії, через WebSearch). Деякі вторинні джерела називають пізнішу дату для UK (8 жовтня 1976) — не підтверджено.
**Записано:** червень 1976, Criteria Studios, Маямі.

### Видання, які є в колекції

**«2013 Remaster», hi-res 24/96 digital**
- Оригінальне виробництво 1976 року вважається вже сильним; один з відгуків на Amazon зазначає, що якість продакшену «винятково хороша і взагалі не потребувала ремастерингу».
- Доступний у 24-біт/96кГц через ProStudioMasters/HighResAudio.
- Числових DR-показників знайти не вдалося (сайт dr.loudness-war.info недоступний для прямого фетчу в цій сесії).
- Джерела: [Amazon reviews](https://www.amazon.com/Technical-Ecstasy-Black-Sabbath/product-reviews/B00HRQ2EJK), [ProStudioMasters](https://www.prostudiomasters.com/album/page/105958)

**«2021 Remaster», hi-res 24/96 (2021 Super Deluxe)**
- Ремастер Енді Пірса та Метта Уортема оцінюють як «дуже вражаючий».
- У боксі є новий стерео-мікс Стівена Вілсона: частина оглядачів вважає його найкращим звучанням альбому за всю історію, інші — гіршим за оригінальний мікс. Думки реально розділилися.
- Раніше не виданий концертний LP 1977 року в боксі — найгірший за звуком диск набору: «бутлег-якість» на перших хвилинах, далі — пристойне розділення інструментів.
- Джерела: [SonicAbuse](https://sonicabuse.com/black-sabbath-technical-ecstasy-super-deluxe-edition-review/), [Get Ready to Rock](https://getreadytorock.me.uk/blog/2021/09/album-review-black-sabbath-technical-ecstasy-super-deluxe-5lp-vinyl-box-set/), [Metal Planet Music](https://metalplanetmusic.com/2021/09/album-review-black-sabbath-technical-ecstasy-super-deluxe/)

---

## 2. Never Say Die! (1978)

**Дата релізу:** 29 вересня 1978 (за інфобоксом Вікіпедії, через WebSearch).
**Записано:** 1978, Sounds Interchange, Торонто.

### «2013 Remaster», hi-res 24/96 digital
- Детального технічного аналізу знайти не вдалося; один відгук на Amazon називає ремастер «фантастичним» для запису 1978 року.
- Доступний у 24-біт/96кГц FLAC/AIFF через ProStudioMasters та Qobuz.
- Числових DR-даних не знайдено в цій сесії.
- Джерела: [ProStudioMasters](https://www.prostudiomasters.com/album/page/37607), [Qobuz](https://www.qobuz.com/us-en/album/never-say-die-black-sabbath/kzvdzmzzcdtkb), [Amazon](https://www.amazon.com/Never-Say-Remastered-Black-Sabbath/dp/B00HRS4FN6)

---

## 3. Heaven and Hell (1980)

**Дата релізу:** 18 квітня 1980 (за інфобоксом Вікіпедії — європейська дата). Деякі джерела (включно з постом гурту) називають 25 квітня 1980 як північноамериканську дату.
**Записано:** 1979–1980.

### «2008 Remaster» CD 16/44
- Явних коментарів про DR/гучність для саме цього видання знайти не вдалося; наявність підтверджена (Amazon, Deezer), але окремого відгуку про звук не знайдено — чесно позначаємо цю прогалину.
- Джерела: [Amazon](https://www.amazon.com/Heaven-and-Hell-Remastered-Version/dp/B001MCVN2Y), [Dynamic Range DB (сторінка існує, не вдалося завантажити)](https://dr.loudness-war.info/album/list?artist=black+sabbath&album=heaven+and+hell)

### «2014 Remaster» hi-res 24/192
- Розповсюджується через Rhino/Warner Studio Masters у 192кГц/24-біт та 96кГц/24-біт.
- Відгуки з форумів неоднозначні й залежать від продавця: один користувач Head-Fi писав, що ранні версії від Rhino/Sanctuary були «поганої якості», тоді як версія з HD Tracks — «значно краща».
- Джерела: [ProStudioMasters](https://www.prostudiomasters.com/album/page/35745), [Head-Fi forum](https://www.head-fi.org/threads/hi-res-albums-vs-mastered-for-itunes-or-apple-digital-master-albums-which-is-better.866861/page-5)

### «Deluxe Edition» (диск 1 — ремастер 24/96, диск 2 — бонус 24/44)
- Бонус-диск містить концертну рідкість, раніше не видану в Північній Америці: «Children of the Sea» та «Die Young» наживо з Hartford Civic Center (10 серпня 1980), а також «E5150»/«Neon Knights» наживо з Hammersmith Odeon (31 грудня 1981) — останні вперше з'явилися на бокс-сеті Rhino Handmade «Live at Hammersmith Odeon» 2007 року.
- Окремого технічного відгуку саме про звук бонус-диска не знайдено; той самий контент пізніше увійшов до перевидання 2021 року.
- Джерела: [Tower Records](https://towerrecords.com/collections/black-sabbath/products/black-sabbath-heaven-and-hell-deluxe-edition-2cd), [Everybody's Records](https://everybodysrecords.com/UPC/603497850709)

### «2021 Deluxe Edition, Remaster» 24/44 (19 треків)
- Ремастер описують як «сфокусованіший і потужніший» порівняно з попередніми CD-виданнями.
- Сам студійний альбом хвалять як улюбленець фанатів («ідеальні 10/10») — це стосується музики, а не безпосередньо мастерингу.
- Бонуси: живі B-сторони «Children of the Sea»/«Heaven and Hell» з сету Hammersmith Odeon 2007 року, моно радіо-едит «Lady Evil», а також раніше не видані живі треки з Hartford (10 серпня 1980) та Hammersmith Odeon (31 грудня 1981 — 2 січня 1982).
- Джерела: [MusicTAP](https://musictap.com/2021/03/26/review-heaven-and-hell-mob-rules-2cd-2021-black-sabbath-remasters/), [Renowned For Sound](https://renownedforsound.com/black-sabbath-heaven-and-hell-deluxe-edition/), [AllMusic](https://www.allmusic.com/album/release/heaven-and-hell-2021-deluxe-edition-mr0005336670)

### Японський SHM-SACD UIGY-9088 (2012)
- DSD, одношаровий 2-канальний SACD (не гібридний) — потрібен SACD-програвач; випущено 28 березня 2012.
- Відгуки позитивні: «чудове звучання, гарні верхи, середина, щільний і чіткий бас»; один рецензент зазначив легку «нестачу удару» порівняно з гучнішими мастерами, але не вважає це недоліком.
- Високо оцінюється колекціонерами — 4.46/5 у середньому на 26 оцінок на Discogs (на момент пошуку).
- Джерела: [Discogs](https://www.discogs.com/release/3536324-Black-Sabbath-Heaven-And-Hell), [CDJapan](https://www.cdjapan.co.jp/product/UIGY-9088)

---

## 4. Mob Rules (1981)

**Дата релізу:** 4 листопада 1981 (за інфобоксом Вікіпедії, через WebSearch).
**Записано:** 1981, Record Plant, Лос-Анджелес.

### «2008 Remaster» CD 16/44
- Ремастеровано в DigiPrep, випущено Rhino Entertainment.
- Оригінальне виробництво Мартіна Берча 1981 року вважається «потужним, динамічним»; конкретних DR-цифр у цій сесії не знайдено.
- Джерела: [Discogs](https://www.discogs.com/release/2382874-Black-Sabbath-Mob-Rules), [Tunebat](https://tunebat.com/Info/The-Mob-Rules-2008-Remaster-Black-Sabbath/2Cg5XzRsGO2VYbaUYN2j8i)

### «2013 Remaster» hi-res 24/192
- За описом продавця — трансфер 192кГц/24-біт з аналогових майстер-стрічок, без апскейлу з нижчої роздільності.
- Один користувач Discogs, порівнюючи цей hi-res-референс з вінілом, зазначив, що вініл «дуже конкурентоспроможний... з додатковим ударом» — тобто hi-res digital чистий і точний, але вініл може перевершувати його за «ударом» для деяких слухачів.
- Джерела: [Acoustic Sounds](https://store.acousticsounds.com/d/101848/Black_Sabbath-Mob_Rules-FLAC_192kHz24bit_Download), [Qobuz](https://www.qobuz.com/us-en/album/mob-rules-black-sabbath/g36n3l3bkg8tc)

### «2021 Deluxe Edition» 2CD 24/44
- Rhino випустив новий, «динамічніший» за словами рецензентів, ремастер, що замінює UK-делюкс-видання 2010 року.
- Бонусний матеріал включає раніше не видане повне концертне шоу 1982 року та B-сторони синглів.
- Metal Express Radio оцінило делюкс-перевидання на 9/10 — помітно вище за типові оцінки оригінального альбому (~7/10), значною мірою завдяки бонусному матеріалу.
- Джерела: [Metal Express Radio](https://www.metalexpressradio.com/2021/02/19/black-sabbath-heaven-and-hell-mob-rules-deluxe-editions-2021/), [Medium (Jason Ferguson)](https://jason-ferguson.medium.com/black-sabbath-mob-rules-2021-deluxe-edition-110c62e51d14), [Voices From The Darkside](https://www.voicesfromthedarkside.de/review/black-sabbath-mob-rules-2-cd-deluxe-edition/)

---

## 5. Live Evil (1982/1983)

**Дата релізу:** січень 1983 (за інфобоксом Вікіпедії вказано лише місяць і рік, точний день не знайдено).
**Записано:** 18 та 24 квітня, 12–13 травня 1982, у Сієтлі, Далласі та Сан-Антоніо, під час туру Mob Rules Tour.

### 40th Anniversary Edition 2023 (ремастер 2023 + рімікс 2023)
- Оригінальний мікс 1982 року широко критикують: вокал Діо та бас-гітара були зведені занадто тихо.
- Новий рімікс Вина Девіса (з оригінальних аналогових майстер-стрічок) рецензенти однозначно віддають перевагу над ремастерованим, але не переміксованим оригіналом — барабани винесені вперед, гітари/клавішні краще розділені, атмосфера залу посилена.
- Деякі рецензенти зазначають помітно вищу компресію/гучність на дисках з ремікс-версією, хоча загалом це вважається покращенням порівняно з міксом 1982 року.
- Джерела: [Metal Express Radio](https://www.metalexpressradio.com/2023/06/13/black-sabbath-live-evil-40th-anniversary-super-deluxe-edition/), [Tracking Angle](https://trackingangle.com/music/black-sabbath-rings-in-40-years-of-live-evil), [The Metal Pit](https://www.themetalpit.org/liveevil/)

### «2008 Remaster» CD 16/44
- Рецензенти описують його як явне покращення порівняно з оригінальним вінілом/CD, але «все ще не ідеальне».
- Бас Гізера Батлера, за відгуками, «плаває» по гучності протягом альбому — це радше вважають обмеженням вихідних записів, ніж помилкою ремастерингу.
- Самі концертні виконання оцінюються як «майже студійна якість», попри проблеми з міксом.
- Джерела: [mikeladano.com](https://mikeladano.com/2015/01/15/review-black-sabbath-live-evil-remastered-2-cd-version/), [Renowned For Sound](https://renownedforsound.com/black-sabbath-live-evil-deluxe-edition/)

---

## 6. Born Again (1983)

**Дата релізу:** 12 вересня 1983 (за інфобоксом Вікіпедії, через WebSearch).
**Записано:** травень–червень 1983, The Manor, Оксфордшир.

### «2004 Remaster» CD
- Оригінальний мікс 1983 року має погану репутацію через надлишок басу/«каші» у звуці; за автобіографією Тоні Айоммі, Ієн Гіллан нібито «спалив» твітери студійних моніторів під час зведення, і це залишилось непоміченим — часто наводиться як причина дивного звучання.
- Ремастер 2004 року описують як «збалансованіший», хоча бас «все ще занадто виступає на передньому плані».
- Частина слухацьких відгуків лишається різкою навіть після ремастеру (один відгук на Discogs: «Чудовий CD, але звук жахливий»).
- Вихідний матеріал — сильно компресована плівка 1/4 дюйма; ремастер намагався бути ближчим до оригінального вінілу, а не агресивно переегалізованим.
- Джерела: [black-sabbath.com](https://www.black-sabbath.com/2011/05/my-thoughts-on-the-born-again-remaster/), [Sea of Tranquility](https://www.seaoftranquility.org/reviews.php?op=showcontent&id=10881), [Discogs](https://www.discogs.com/master/6100-Black-Sabbath-Born-Again)

---

## 7. Seventh Star (1986)

**Дата релізу:** 20 січня 1986 (США), 17 лютого 1986 (Великобританія) — за інфобоксом Вікіпедії.
**Записано:** червень–серпень 1985, Cherokee Studios (Лос-Анджелес) та Cheshire Sound (Атланта).

### «2004 Remaster» CD
- Оцінюється як помірне покращення — «лише незначно краще» за попередній ремастер Castle 1996 року.
- Водночас «набагато краще» за оригінальний CD-реліз Warner Bros. 1987 року, за словами одного рецензента.
- Оригінальне виробництво 1986 року (особливо звук малого барабана, названий одним критиком «жахіттям») залишається обмеженням, яке ремастер не зміг повністю подолати.
- Джерела: [black-sabbath.com](https://www.black-sabbath.com/2010/10/7th_star_eternal_idol_deluxe_reviews/), [mikeladano.com](https://mikeladano.com/2012/06/19/review-black-sabbath-seventh-star-deluxe-edition/)

---

## 8. The Eternal Idol (1987)

**Дата релізу:** листопад 1987 (Великобританія, Vertigo — за інфобоксом вказано лише місяць і рік); 8 грудня 1987 (США, Warner Bros.).
**Записано:** дані про сесії запису в доступних сніпетах не знайдено.

### «2005 Remaster» CD
- Думки розділилися: один огляд на Metal Archives каже, що ремастер «звучить точнісінько як оригінальний реліз» (тобто покращення мінімальне), тоді як кілька відгуків покупців називають його «настільки гарною роботою з ремастерингу, наскільки це можливо».
- Сам мікс 1987 року — постійний предмет критики незалежно від ремастеру: один рецензент описує його як «більше схоже на чорновий мікс, ніж на фінальний».
- Джерела: [Metal Archives](https://www.metal-archives.com/reviews/Black_Sabbath/The_Eternal_Idol/521/), [Amazon](https://www.amazon.com/Eternal-Idol-Black-Sabbath/dp/B0012ELLBA)

---

## 9. Dehumanizer (1992)

**Дата релізу:** 22 червня 1992 (за інфобоксом Вікіпедії, через WebSearch).
**Записано:** кінець 1991 – початок 1992, Rockfield Studios, Уельс.

### «2008 Remaster» CD
- Прийом неоднозначний. Частина слухачів описує звук як «відкритий і гучний», з хорошим басом, і віддає йому перевагу над оригінальним CD 1992 року.
- Інші кажуть, що він «за звуком гірший за оригінальний CD 1992 року».
- Принаймні один рецензент вважає, що вихідний запис «ймовірно потребує ремікс», а не просто ремастеринг.
- Випущено 17 жовтня 2008 року лейблом Rhino Entertainment.
- Джерела: [Metal Archives](https://www.metal-archives.com/reviews/Black_Sabbath/Dehumanizer/529/), [Discogs](https://www.discogs.com/master/37616-Black-Sabbath-Dehumanizer), [PiercingMetal](https://www.piercingmetal.com/dehumanizer-remaster-by-black-sabbath/)

---

## 10. Cross Purposes (1994)

**Дата релізу:** 26 січня 1994 (Японія), 31 січня 1994 (Європа), 8 лютого 1994 (Північна Америка) — за інфобоксом Вікіпедії.
**Записано:** 1993, Monnow Valley Studios, Rockfield, Уельс.

### «2024 Remaster» 24/44 (з боксу «Anno Domini 1989–1995»)
- Це перше офіційне перевидання/ремастер альбому за всю історію; окремий ремастерований CD із бонус-треком вийшов 15 листопада 2024.
- Тоні Айоммі заявляв, що «ніколи не був задоволений звучанням гітари», а барабанщик Козі Пауелл нібито «ніколи не був задоволений звучанням барабанів» на оригіналі; ремастер зроблено спеціально, щоб винести ці елементи наперед — «щоб це звучало більше так, як люди очікують від Sabbath».
- Ранні відгуки слухачів дуже позитивні («звучить так добре, ніби отримуєш новий альбом Black Sabbath»), але незалежного технічного/DR-аналізу в цій сесії не знайдено.
- Джерела: [The Second Disc](https://theseconddisc.com/2024/03/25/black-sabbath-anno-domini-box-set/), [Blabbermouth](https://blabbermouth.net/news/watch-tony-iommi-and-tony-martin-discuss-black-sabbaths-cross-purposes-album-ahead-of-anno-domini-release), [black-sabbath.com](https://www.black-sabbath.com/2024/03/anno-domini-1989-1995/)

---

## 11. Reunion (1998)

**Дата релізу:** 19 жовтня 1998 (за інфобоксом Вікіпедії, через WebSearch).
**Записано:** 4–5 грудня 1997 (живі треки, NEC, Бірмінгем); квітень–травень 1998 (студійні треки, A&M Studios, Голлівуд).

### 25th Anniversary Expanded Edition (2023), 24/192
- Випущено 13 жовтня 2023 року, ремастеровано з оригінальних вихідних стрічок; два студійні бонус-треки 1998 року окремо переремастерував Денні Сейбер.
- Звук отримав широку похвалу: «відмінна якість», «чистий і охайний, але все ще явно живий».
- Відгуки на вінілове видання кажуть, що воно «звучить набагато краще за оригінальний CD», з чіткішим вокалом та більш присутніми басом/барабанами.
- Джерела: [Album of the Year](https://www.albumoftheyear.org/album/779274-black-sabbath-reunion-25th-anniversary-expanded-edition/user-reviews/), [Apple Music](https://music.apple.com/us/album/reunion-25th-anniversary-expanded-edition/1710661598), [Qobuz](https://www.qobuz.com/us-en/album/reunion-black-sabbath/nb6xm66sja8yb)

---

## 12. 13 (2013)

**Дата релізу:** 7 червня 2013 (за інфобоксом Вікіпедії, через WebSearch).
**Записано:** серпень 2012 – січень 2013.

### Deluxe Version (11 треків) та стандартне видання (8 треків)
- Обидва видання мають той самий мастеринг Ріка Рубіна/Ендрю Шепса, записаний/зведений у 96кГц/24-біт; делюкс-видання просто додає 3 бонус-треки, а не інший майстер.
- Альбом часто наводять як жертву «війни гучності» — надмірно стиснутий/обмежений динамічний діапазон відносно того, що міг би дати такий hi-res мастеринг-ланцюг; це стосується CD/цифрових майстерів обох видань однаково.
- Вінілове видання, за словами кількох слухачів, звучить помітно динамічніше/краще за CD або цифрові майстери.
- Джерела: [Sound on Sound](https://www.soundonsound.com/techniques/inside-track-black-sabbath-13), [Amazon](https://www.amazon.com/13-CD-Deluxe-Black-Sabbath/dp/B00BTHWFBK), [Discogs](https://www.discogs.com/release/4636781-Black-Sabbath-13)

---

## 13. The End (2017, live in Birmingham)

**Дата релізу:** 17 листопада 2017 (за інфобоксом Вікіпедії, через WebSearch; збігається з датою, вказаною в завданні).
**Записано:** 4 лютого 2017, Genting Arena, Бірмінгем, Англія (фінальний концерт The End Tour).

### 24/96 digital, 17 треків
- Рецензенти описують звук як «на найвищому рівні», з чутною атмосферою й ентузіазмом публіки протягом майже двогодинного сету.
- Доступний як hi-res цифровий реліз 24-біт/96кГц (ProStudioMasters) поряд із фізичними виданнями CD/DVD/Blu-ray/вініл.
- Окремого технічного (DR/гучність) розбору саме для 24/96 цифрового майстеру не знайдено.
- Джерела: [ProStudioMasters](https://www.prostudiomasters.com/album/page/16915), [SonicAbuse](https://sonicabuse.com/black-sabbath-the-end-dvd-review/)

---

## Підсумок обмежень цього проходу

1. **Дати** — усі отримані через `WebSearch`-сніпети, які посилаються на інфобокс Вікіпедії, а не через прямий виклик Wikipedia API (заблоковано мережевою політикою сесії). Там, де знайдено розбіжності між джерелами (Heaven and Hell, Live Evil — лише місяць/рік), це прямо позначено.
2. **Звукова репутація** — зібрана з доступних через пошук сніпетів оглядів/форумів/магазинів. Для кількох видань (2008 Heaven and Hell CD) якісних відгуків знайти не вдалося — це чесно позначено, а не заповнено вигаданими даними.
3. **DR-показники** (dr.loudness-war.info) — сайт існує, згадується в пошукових результатах, але сама сторінка не завантажилась напряму в цій сесії (WebFetch заблоковано), тож конкретних числових DR-значень у звіті немає.
4. **Обкладинки та Discogs-дані** — свідомо пропущені за проханням користувача; робляться окремо.
