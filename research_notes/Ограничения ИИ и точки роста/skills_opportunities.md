# Спрос на людей и продукты в ИИ-индустрии (ноябрь 2026): навыки, роли, ниши, закрывающие ограничения ИИ

> **Методическая оговорка (важно для автора отчёта).** Дата сбора: 2026-11-26. В этой сессии инструмент прямой загрузки страниц (WebFetch) был заблокирован сетевым allowlist: все 8 попыток открыть первоисточники (pwc.com, fortune.com, stackoverflow.blog, news.crunchbase.com, ycombinator.com, aljazeera.com, valueaddvc.com, hiringlab.org) завершились ошибкой DNS. Поэтому **все факты ниже получены через веб-поиск (сводки поисковой выдачи по указанным URL), а не через чтение полного текста страниц**. Цифры переданы так, как их вернул поиск; там, где поиск сам отметил расхождения или вторичность источника, это указано. Перед публикацией ключевые цифры (PwC, Menlo, Crunchbase, YC RFS) желательно сверить с первоисточником. Пометки: **[перв.]** — URL первоисточника; **[втор.]** — пересказ/агрегатор; **[ист.]** — данные старше 2026 г. (исторический контекст).

---

## 1. Какие ИИ-роли и навыки растут быстрее всего в 2026 г.

### Takeaway
Спрос концентрируется не в «обучении моделей», а во внедрении и надёжности: forward-deployed инженеры (+1000% вакансий г/г по Lightcast), AI/agent-инженеры, агентные навыки (+280% за год), ИИ-безопасность и governance. Премия за ИИ-навыки высокая (PwC: 62% в среднем по миру), но рынок сдвигается в сторону сеньоров — входные позиции сокращаются.

### Cited Findings

**Общая картина спроса (данные)**
- PwC 2026 Global AI Jobs Barometer (пресс-релиз, ~15.06.2026; >1 млрд объявлений о вакансиях, 27 стран): вакансии, требующие ИИ-навыков, растут намного быстрее рынка в целом — 69% против 9%; средняя зарплатная премия за ИИ-навыки выросла до 62%. Заголовок отчёта: ИИ «делит рынок труда на два пути, вознаграждая человеческие навыки» — [PwC press release, перв.](https://www.pwc.com/gx/en/news-room/press-releases/2026/pwc-2026-ai-jobs-barometer.html); [зеркало Cision/AAP 15.06.2026](https://www.aap.com.au/aapreleases/cision20260615ae78182/)
- PwC, Великобритания: премия за ИИ-навыки утроилась за год — 34,2% в 2025 против 11% в 2024 (ниже среднемировой) — [PwC UK, перв.](https://pwc.co.uk/press-room/press-releases/research-commentary/2026/ai-jobs-barometer-2026.html). Финансовый сектор: премия 53% в 2025 — [PwC FS report, перв.](https://www.pwc.com/gx/en/issues/artificial-intelligence/job-barometer/2026/pwc-aijb-2026-financial-services-report.pdf)
- Stanford AI Index 2026 (данные Lightcast, апрель 2026): в США 2,5% всех вакансий упоминают ИИ-навыки — +55% к прошлому году, +72% к 2022, почти +300% за десятилетие; большинство ИИ-вакансий — вне ИТ-ролей, и эта доля растёт. Python — самый востребованный специализированный навык в ИИ-вакансиях США: 258 674 объявления в 2025 (+~30% к 2024). На Кремниевую долину приходится 13% всех ИИ-вакансий — [Lightcast: Four Takeaways from the 2026 Stanford AI Index, перв.](https://lightcast.io/resources/blog/stanford-ai-2026); [Stanford AI Index 2026, гл. 4 «Economy», перв.](https://hai.stanford.edu/assets/files/ai_index_report_2026_chapter_4_economy.pdf)
- Агентный ИИ как кластер навыков (Lightcast, для AI Index 2026): доля вакансий с агентными навыками выросла с 0,06% (2024) до 0,23% (2025) — рост >280% за год, ~86–90 тыс. вакансий в США. Медианная зарплата в объявлениях с agentic AI — $153 тыс. против $141 тыс. по ИИ-вакансиям в целом и $125 тыс. по ИТ-вакансиям (сравнение медиан по категориям, не «чистая» премия) — [Lightcast: Tracking the Agentic AI Explosion in Jobs, перв.](https://lightcast.io/blog/tracking-the-agentic-ai-explosion-in-jobs)
- Lightcast «Beyond the Buzz» **[ист., июль 2025]**: ИИ-навыки дают +28% (~$18 тыс./год) к объявленной зарплате; анализ >1,3 млрд вакансий. В сентябре 2026 цифра 28% повторно представлялась на вебинаре Randstad (вероятно, не новые данные) — [Lightcast press release](https://lightcast.io/resources/blog/beyond-the-buzz-press-release-2025-07-23); [HCAMag](https://www.hcamag.com/us/specialization/transformation/ai-skills-carry-a-nearly-18000-premium-but-pay-bands-arent-budging/594128)
- Контраргумент по премии — Payscale 2026: 58% работодателей платят или планируют платить премию за ИИ-навыки, но 23% тех, кто раньше платил, теперь считают ИИ-грамотность базовым требованием; 19% не меняют структуру оплаты — [Payscale press release 2026, перв.](https://www.payscale.com/press-releases/2026-ai-workforce-impact-preview)
- LinkedIn Jobs on the Rise 2026 (январь 2026; роли, начатые 01.01.2023–31.07.2025): №1 — AI engineer; AI consultants / strategists — в верхней части списка. За 2023–2025 LinkedIn зафиксировал 639 тыс. ИИ-вакансий в США, из них 75 тыс. — AI engineer — [Dice о списке LinkedIn, втор.](https://www.dice.com/career-advice/ai-related-jobs-top-linkedins-fastest-growing-roles-list-for-2026); [CBS News](https://www.cbsnews.com/news/artificial-intelligence-entry-level-role-linkedin-study/)
- WEF (январь 2026, по данным LinkedIn): мировая экономика добавила 1,3 млн новых ИИ-связанных рабочих мест за два года — [WEF, перв.](https://weforum.org/stories/2026/01/ai-has-already-added-1-3-million-new-jobs-according-to-linkedin-data/)
- WEF Future of Jobs Report **[ист., январь 2025; издания 2026 г. поиск не нашёл]**: самые быстрорастущие навыки — AI и big data, затем сети и кибербезопасность, технологическая грамотность; самые быстрорастущие роли в % — big data specialists, fintech engineers, AI/ML specialists; к 2030: 170 млн новых ролей, 92 млн вытеснено — [WEF, перв.](https://www.weforum.org/publications/the-future-of-jobs-report-2025/?so=1)

**Forward-deployed engineering (FDE)**
- Fortune (03.09.2026, данные Lightcast): вакансии «forward-deployed» инженеров выросли более чем на 1000% за январь–август 2026 к тому же периоду 2025 и более чем на 4600% к 2023. Медианная объявленная зарплата FDE — >$188 тыс. против ~$145 тыс. у обычных software engineers — [Fortune, перв.](https://fortune.com/2026/09/03/forward-deployed-engineers-fast-growing-six-figure-silicon-valley-job-integrate-ai-with-customers-tech-careers-palantir/); также [PYMNTS](https://www.pymnts.com/artificial-intelligence-2/2026/forward-deployed-engineers-emerge-as-one-of-ais-fastest-growing-jobs/)
- Ранее Financial Times (в пересказе Fast Company): вакансии FDE выросли >800% с начала 2025 по сентябрь 2025 **[ист.]**; периоды разные, напрямую не сравнивать; база мала — [Fast Company](https://www.fastcompany.com/91435680/postings-for-this-ai-job-are-up-800)

**Разработчики и агенты (Stack Overflow)**
- Stack Overflow Developer Survey 2026 (результаты 06.10.2026): 73% тех, кто пользуется ИИ-ассистентами/агентами, используют их ежедневно; среди ИИ-пользователей чаще всего — coding agents (66%) и чат-боты (63%); популярные агенты — Claude Code (66%) и GitHub Copilot (59%). «Автоматизированные агентные workflow» использовали 26,2%; 17,2% не используют ИИ-инструменты. CEO: скепсис — критический предохранитель по мере роста автономности агентов — [Stack Overflow blog, перв.](https://stackoverflow.blog/2026/10/06/the-results-of-the-2026-developer-survey-are-here/); [IT Brief](https://itbrief.com.au/story/stack-overflow-survey-shows-developers-trust-ai-with-caveats); [DevOps Digest](https://devopsdigest.com/developers-positive-about-ai-trust-remains-conditional)
- Stack Overflow pulse-опрос (27.05.2026): использование агентов почти удвоилось — 59% против 31% в 2025; 69% используют одного агента, 17% — несколько специализированных, 16% — несколько координируемых; 63% редко или никогда не дают агентам работать на «автопилоте»; главные опасения — точность и безопасность — [Stack Overflow blog, перв.](https://stackoverflow.blog/2026/05/27/agents-on-a-leash-agentic-ai-remains-mostly-monitored-at-work)

**ИИ-безопасность и кибербезопасность**
- AI Workforce Consortium (блог Cisco, 2026): доля вакансий по кибербезопасности в странах G7, требующих ИИ-навыков, выросла до 28,5% (октябрь 2025 – март 2026) с 14,2% годом ранее — [Cisco blog, перв.](https://blogs.cisco.com/our-corporate-purpose/ai-workforce-consortium-building-a-cybersecurity-workforce-ready-for-whats-next)
- SANS | GIAC 2026: 6 из 10 организаций называют дефицит навыков (а не людей) главным кадровым вызовом (+20 п.п. за год); 27% пострадали от инцидентов из-за пробелов в компетенциях; спрос на специалистов в новых ролях (AI/ML security specialist, AI security engineer, AI governance analyst) более чем удвоился за год; только 20% организаций обучают весь персонал ИИ-безопасности — [SANS, перв.](https://www.sans.org/press/announcements/sans-research-cybersecurity-talent-shortage-narrative-wrong-real-crisis-what-your-team-doesnt-know-starting-ai); [Barracuda, 21.10.2026](https://blog.barracuda.com/2026/10/21/ai-cybersecurity-skills-gap)
- Accenture (Axios, 02.06.2026): «это уже не дефицит, а несоответствие» навыков — [Axios](https://www.axios.com/2026/06/02/accenture-ai-cybersecurity-workforce-report)

**AI governance / compliance**
- Axipro, 2026 (3 519 вакансий в ЕС): европейские компании нанимают ~7 специалистов по созданию ИИ на 1 по управлению им; большинство governance-вакансий — у фирм >5000 сотрудников, две трети — финансы и ИТ-консалтинг — [Technology Magazine / GlobeNewswire](https://technologymagazine.com/globenewswire/3326317)
- IAPP Salary and Jobs Report 2025-26 **[ист., август 2025; >1600 респондентов, 60+ стран]**: средняя базовая зарплата AI governance (legal/compliance) — $190 тыс.; медиана технических AI-governance ролей в техсекторе — $221 тыс. — [IAPP, перв.](https://iapp.org/resources/article/salary-survey)
- Hays (Il Sole 24 Ore, 2026): за первые 4 месяца 2026 поиск специалистов сосредоточен на AI Engineer, Data Engineer, Generative AI Specialist, а также AI Governance / Compliance Specialist — [Il Sole 24 Ore](https://en.ilsole24ore.com/art/professional-demand-grows-40-per-cent-AI7G27kC)
- Регуляторный драйвер: обязательства прозрачности по ст. 50 EU AI Act применяются со 2 августа 2026; Digital Omnibus отложил требования к high-risk системам до декабря 2027 — [Stacker, втор.](https://stacker.com/stories/ai/ai-governance-confidence-gap-why-trust-ai-running-ahead-capacity-govern-it)
- Нишевость: в Великобритании постоянных вакансий с упоминанием «EU AI Act» — 8 за полгода до 20.09.2025 **[ист.]** — [ITJobsWatch](https://www.itjobswatch.co.uk/jobs/uk/eu%20ai%20act.do?p=6)

**Сдвиг к сеньорам (Indeed Hiring Lab)**
- Indeed Hiring Lab (23.07.2026, «The labor market is tilting toward seniority»): вакансии в разработке ПО выросли почти на 15% с февраля 2025 при падении общего числа вакансий на 7%, но остаются на ~27,5% ниже уровня февраля 2020. 71% прироста (май 2025 – май 2026) — сеньорные роли; 37% — вакансии с «AI» в названии. Entry-level вакансии: −7,5% г/г на май 2026; senior: +14,7% — [Indeed Hiring Lab, перв.](https://www.hiringlab.org/2026/07/23/the-labor-market-is-tilting-toward-seniority/)
- Indeed (январь 2026): вакансии с упоминанием ИИ растут на фоне общей слабости найма — [Hiring Lab, 22.01.2026](https://www.hiringlab.org/2026/01/22/january-labor-market-update-jobs-mentioning-ai-are-growing-amid-broader-hiring-weakness)
- В начале 2026 только 4,5% вакансий в разработке ПО были entry-level; на тот момент вакансии разработчиков были на 29% ниже допандемийного ориентира Indeed (по сводке поиска; источник в выдаче — материал Fortune об «experience creep») — [Fortune, 03.04.2026](https://fortune.com/2026/04/03/experience-creep-jobs-ai-entry-level/)
- Индия — контрпример: вакансии в разработке ПО упали на 12,3% за три месяца — [People Matters / Indeed](https://www.peoplematters.in/news/recruiting-and-onboarding/software-job-postings-fall-123percent-as-ai-reshapes-tech-hiring-in-india-indeed-50486)

**Зарплаты AI engineer (разброс источников)**
- Оценки средней базовой зарплаты AI engineer в США в 2026: $140–185 тыс., одна широко цитируемая — ~$206 тыс.; Salary.com — $113 тыс. (июнь 2026, иное определение роли). Levels.fyi **[ист., Q3 2025]**: премия ИИ-специалистов уровня Staff — 18,7% — [dev.to-обзор, втор.](https://dev.to/rishi_kora/ai-engineer-pay-in-2026-what-the-salary-data-really-says-721); [Salary.com](https://www.salary.com/research/salary/hiring/artificial-intelligence-engineer-salary)

### Inferences
- Самый быстрый рост — у ролей «последней мили»: FDE, AI-консультанты, агентная инженерия. Это роли, где ценность — в доведении модели до работающего процесса у клиента, что совпадает с главным ограничением ИИ 2026 г. (надёжность и интеграция, а не «сырой интеллект»). Профиль читателя (Node.js, автоматизация) ближе всего именно к этому кластеру.
- Проценты роста FDE и agentic AI считаются от малой базы (0,23% вакансий); абсолютный объём рынка — десятки тысяч вакансий в США, а не миллионы.
- Премия за ИИ-навыки размывается: по Payscale четверть бывших «плательщиков премии» уже считают ИИ-грамотность нормой. Премию удерживают специализированные навыки (агенты, evals, безопасность), а не «умение пользоваться ИИ».
- Governance — реальный, но узкий и корпоративный рынок (крупные фирмы, финансы); соотношение 7:1 говорит о недоукомплектованности, но входной барьер — юридический/комплаенс-бэкграунд.

### Gaps
- Не найдено данных о вакансиях/зарплатах отдельно для «evals engineer», «inference optimization engineer», «ML infrastructure» и «AI product manager» за 2026 г.
- Отчёт ISC2 Workforce Study 2026 поиском не найден (есть только издание 2025 г.).
- Полный текст PwC Barometer и Stack Overflow Survey открыть не удалось — детали (скорость изменения навыков, конкретные профессии «двух путей», доверие к ИИ в %) не извлечены.
- Данных о робототехнических вакансиях (спрос на инженеров) за 2026 г. не найдено — только финансирование (см. раздел 3).

---

## 2. Какие навыки теряют ценность

### Takeaway
Обесцениваются товарные, легко формализуемые задачи: массовый контент и копирайтинг (−54…−63% заказов на Upwork за 18 месяцев по стороннему анализу), начальное программирование (разрыв занятости молодых в ИИ-экспонированных профессиях вырос до 19%), «prompt engineer» как отдельная должность. Навык не исчезает, а встраивается в более широкие роли.

### Cited Findings
- Stanford Digital Economy Lab, обновление «Canaries» (12.08.2026): разрыв в занятости работников 22–25 лет в ИИ-экспонированных профессиях вырос до 19%; у опытных работников сопоставимого провала нет; массового вытеснения по экономике в целом исследователи не видят — [Stanford DEL, перв.](https://digitaleconomy.stanford.edu/news/canariesaug26/); [GCN](https://gcn.com/ai-hiring-gap-workers-ages-widens/20887/)
- Бриньолфссон оценивает спад занятости начинающих разработчиков (22–26 лет) примерно в 20% — [Fortune, 27.06.2026](https://fortune.com/2026/06/27/what-is-ai-impact-entry-level-jobs-stanford-adp-canaries-brynjolfsson-richardson/); [IEEE Spectrum](https://spectrum.ieee.org/ai-impact-on-job-market)
- Оговорка Stanford SIEPR: спад у начинающих не заметен до 2024 г., поэтому снижение найма в 2022 г. правдоподобно объясняется не ИИ — [SIEPR policy brief, перв.](https://siepr.stanford.edu/publications/policy-brief/what-really-happening-jobs-separating-ai-hype-reality)
- UpHunt (сторонний блог-агрегатор, 2026; 3,25 млн объявлений Upwork, январь 2025 – июнь 2026): заказы на writing упали ~на 54% (с 8 002 до 3 698 в месяц) против ~34% по платформе; content writing −63,3% (4 733 → 1 737), sales/marketing copywriting ~−58%. **Не рецензируемое исследование** — [UpHunt](https://uphunt.io/blog/did-ai-kill-upwork-writing-jobs-2026-data)
- Ранний анализ ~5 млн объявлений Upwork **[ист., 01.11.2022 – 14.02.2024]**: writing −33%, перевод −19%, клиентская поддержка −16% — [пересказ Bloomberry, втор.](https://skool.com/chatgpt/good-news-for-chatbot-agencies)
- Противоположный сигнал по переводу — Upwork **[ист., сентябрь 2025]**: спрос на translation & localization вырос на 29%, т.к. бизнес платит за человеческий контроль над ИИ-«workslop» — [Upwork Monthly Hiring Report](https://www.upwork.com/research/monthly-hiring-report-september-2025)
- OpenAI + Upwork (ноябрь 2026, 63 категории работ): в 43 из 63 категорий задачи, часто выполняемые в ChatGPT, теряют долю, редкие — набирают; «само по себе использование ChatGPT не объясняет изменения спроса»; ИИ-связанные фриланс-проекты имеют на 52% более высокие бюджеты и сочетают техническое внедрение, креатив и бизнес-процессы — [OpenAI, перв.](https://openai.com/index/ai-effect-on-freelance-work/); [People Matters](https://sea.peoplemattersglobal.com/news/ai-and-emerging-tech/ai-related-freelance-projects-command-52percent-higher-budgets-as-demand-shifts-to-specialised-skills-openai-report-53273)
- Prompt engineer как должность **[ист., 2025]**: экономист Indeed Allison Shrivastava — должность «не взлетела», работа влилась в роли ML-инженера и automation architect; вакансий «минимум» — [Fortune, 07.05.2025](https://fortune.com/2025/05/07/prompt-engineering-200k-six-figure-role-now-obsolete-thanks-to-ai/); [Fast Company](https://www.fastcompany.com/91327911/prompt-engineering-going-extinct). Исследование 20 662 вакансий LinkedIn: prompt engineering — <0,5% выборки — [arXiv 2506.00058](https://arxiv.org/html/2506.00058v2)
- Трафик для контент-сайтов (прямо касается SEO-опыта читателя): Chartbeat 2026 Publisher Playbook — рефералы из Google Search на новостные/медиа-сайты упали на 40,2% (июль 2025 → июль 2026); малые издатели −60%, средние −47%, крупные −22% — [Android Headlines, октябрь 2026](https://androidheadlines.com/2026/10/google-search-publisher-traffic-declines-40-percent.html); [Neowin](https://www.neowin.net/news/report-ai-overviews-are-crushing-small-publishers-as-google-search-traffic-drops-60)
- Рефералы от чат-ботов — <1% просмотров страниц издателей, хотя доля выросла >200% (декабрь 2024 → декабрь 2025); Scrunch: ИИ-рефералы — ~1,1% визитов на новостные сайты — [9to5Google, 18.03.2026](https://9to5google.com/2026/03/18/google-search-traffic-publishers-report/); [Search Engine Land](https://searchengineland.com/news-publisher-visits-from-ai-study-484851)
- Pew Research: когда вверху выдачи есть AI Overview, по ссылкам внутри него кликает ~1% пользователей — [AdExchanger](https://www.adexchanger.com/publishers/the-ai-search-reckoning-is-dismantling-open-web-traffic-and-publishers-may-never-recover)
- Позиция Google (оспаривается): глава поиска Liz Reid — объём кликов «относительно стабилен», отчёты о падении основаны на некорректных методиках — [Search Engine Journal](https://www.searchenginejournal.com/google-ai-overviews-impact-on-publishers-how-to-adapt-into-2026/556843/)
- Мнение (Karpathy, в пересказах): агенты писали ~80% его кода; «расплачиваются джуниоры» — [Yahoo Tech, втор.](https://tech.yahoo.com/ai/chatgpt/articles/ai-agents-wrote-80-karpathys-175030864.html)

### Inferences
- Для владельца контент-сайтов модель «SEO-трафик → монетизация» под прямым давлением: малые издатели теряют больше всех (−60%), а ИИ-рефералы (~1%) потерю не компенсируют. Это аргумент за смену позиции — от производителя контента к поставщику инструментов/услуг видимости в ИИ-поиске (см. раздел 5).
- Обесценивается не «код» и не «текст» как таковые, а их товарная часть без ответственности за результат; растёт цена проверки, спецификации, интеграции.
- Данные по фрилансу измеряют число объявлений, не заработки; окна и методики разные — цифры спада стоит подавать как диапазон (−30…−63%), а не точную величину.

### Gaps
- Нет надёжных данных 2026 г. о падении числа вакансий «prompt engineer» (цифры −30%, −79%, «78% вакансий» приходят из маркетинговых блогов без проверяемого источника — в заметки как факты не включены).
- Не найдено данных 2026 г. по Центральной Азии о влиянии ИИ на фриланс/аутсорс-разработку.
- Не удалось проверить по первоисточнику цифру «20%» по разработчикам (приводится во вторичных пересказах).

---

## 3. Куда течёт венчурное финансирование в 2026 г.; переполненные и недообслуженные категории; запросы YC и тезисы инвесторов

### Takeaway
ИИ забирает ~64% мирового венчура (Q3 2026: $102 млрд из $159 млрд по Crunchbase), но деньги сверхконцентрированы: мегараунды в моделях/инфраструктуре/чипах/дата-центрах и рекордная робототехника. По расходам предприятий 69% уходит трём лабораториям. Открытыми проблемами инвесторы называют уже не модели, а физические узкие места (энергия, дата-центры, финансирование железа), безопасность агентов, evals/надёжность и продажу «результата вместо инструмента».

### Cited Findings

**Общие объёмы**
- Crunchbase, Q3 2026: мировое венчурное финансирование — $159 млрд (−25% к Q2, +53% г/г); ИИ-стартапы — $102 млрд, 64% (на 14 п.п. выше Q3 2025, но ниже двух предыдущих кварталов); рекордные 27 компаний привлекли по $1 млрд+ (16 в Q2, 14 в Q1). Сев. Америка: $92 млрд, из них ~$61 млрд в ИИ. Определение «AI-driven» в отчёте не раскрыто — [Crunchbase News, перв.](https://news.crunchbase.com/?p=92594); пересказы: [AI Weekly](https://aiweekly.co/alerts/crunchbase-logs-27-billion-dollar-rounds-in-q3-2026-as-ai-grabs-102b-or-64-of), [IBTimes](https://www.ibtimes.com/ai-startups-global-venture-funding-q3-2026-3809588)
- Расхождение: CB Insights оценивает мировой венчур Q3 2026 в $187,2 млрд (иная методика) — [Let's Data Science, втор.](https://letsdatascience.com/news/cb-insights-reports-q3-2026-vc-funding-surge-driven-by-ai-ed964a42)

**Расходы предприятий (Menlo Ventures, «2026: The State of Enterprise AI», 03.11.2026; ~400 лиц, принимающих решения в США)**
- Годовой темп расходов предприятий на ИИ — $176,8 млрд к сентябрю 2026 против $33 млрд в 2025 (×5,4) — [Menlo PDF, перв.](https://menlovc.com/wp-content/uploads/2026/11/menlo_ventures_enterprise_ai_report-2026-110326.pdf); [HPCwire, 03.11.2026](https://www.hpcwire.com/aiwire/2026/11/03/menlo-venturest-enterprise-ai-spending-hits-177b-up-5-4x-in-one-year-as-agents-take-over/)
- Разбивка (только во вторичном пересказе графика, не сверено с PDF): foundation models и инференс $12,5 млрд → $94,2 млрд; ИИ-инфраструктура $1,5 → $5,3 млрд; ассистенты/продуктивность $8,4 → $25,0 млрд; coding $4,4 → $34,0 млрд; итого инфраструктура $99,5 млрд, приложения $77,3 млрд — [FourWeekMBA, втор.](https://fourweekmba.com/ai-enterprise-ai-spend-hit-177b-up-5-4x-in-a-year-menlo-says/)
- ИИ-лаборатории (Anthropic, OpenAI, Google) получают 69% расходов; решает способность модели, а не цена. Доля предприятий, платящих за ИИ: 55% → 65%. Инкумбенты удержали или нарастили долю почти в половине категорий (ServiceNow — 91% ИИ-расходов в ИТ, Workday — 68% в HR). Только 22% ИИ-расходов пришло из софтверных бюджетов. **Menlo — инвестор Anthropic (конфликт интересов)** — [Campus Technology, 09.11.2026](https://campustechnology.com/articles/2026/11/09/report-enterprise-ai-spending-outpaces-adoption-growth.aspx); [SaaStr](https://www.saastr.com/ai-spend-hit-177-billion-this-year-only-22-of-it-came-out-of-software-budgets/)
- McKinsey «The state of AI in 2026: On the road to ROI»: 40% респондентов из крупных организаций (выручка >$1 млрд) масштабируют ИИ-агентов (27% годом ранее); только 37% сообщают о положительном вкладе ИИ в EBIT — практически без изменений к 2025 — [McKinsey, перв.](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai)

**ИИ-безопасность (растущая, быстро заполняется)**
- Crunchbase (2026): ИИ-ориентированные киберстартапы привлекли $855 млн в 150+ seed-раундах с начала года — темп на исторический рекорд; примеры: Cylake — $45 млн seed (март), JetStream Security — $34 млн seed (март) — [Crunchbase News, перв.](https://news.crunchbase.com/cybersecurity/seed-trends-ai-security-startup-funding-2026/)
- DataTribe Q2 2026 (Help Net Security, 31.07.2026): ИИ-безопасность — крупнейшая категория кибер-seed, почти четверть сделок; все компании кроме одной — про защиту агентных систем — [Help Net Security](https://helpnetsecurity.com/2026/07/31/ai-agents-cybersecurity-seed-funding)
- HiddenLayer привлёк $100 млн (TechCrunch, 02.09.2026) под Agentic Runtime Security; Straiker — $64 млн; red teaming: Mindgard $30 млн, Dreadnode $14 млн, Promptfoo $18,4 млн Series A (даты трёх последних раундов поиском не подтверждены) — [TechCrunch](https://techcrunch.com/2026/09/02/hiddenlayer-nabs-100m-as-enterprises-rush-to-secure-their-ai-deployments/); [SecurityWeek: Straiker](https://www.securityweek.com/straiker-raises-64-million-for-ai-security-platform/amp/); [Mindgard](https://www.securityweek.com/mindgard-raises-30-million-to-protect-ai-systems/amp/); [Dreadnode](https://www.securityweek.com/offensive-ai-startup-dreadnode-secures-14m-to-stress-test-ai-systems/amp/); [Promptfoo](https://www.securityweek.com/promptfoo-raises-18-4-million-for-ai-security-platform/amp/)

**Evals / observability (относительно небольшая категория)**
- Braintrust: $80 млн Series B (17.02.2026), лид Iconiq, оценка $800 млн post-money — [Axios](https://www.axios.com/pro/enterprise-software-deals/2026/02/17/ai-observability-braintrust-80-million-800-million); [SiliconANGLE](https://siliconangle.com/2026/02/17/braintrust-breaks-80m-series-b-funding-round-become-observability-layer-ai/)
- Vals AI (evals): $40 млн Series A 13.08.2026, лид a16z (единственный источник — агрегатор) — [Sacra](https://sacra.com/c/vals-ai); Respan: $5 млн (18.03.2026, Gradient, YC) — [GlobeNewswire](https://www.globenewswire.com/news-release/2026/03/18/3258291/0/en/Respan-Announces-5M-in-Funding-from-Gradient-Y-Combinator-and-others-Launches-First-Proactive-AI-Observability-Platform.html); OpenObserve: $10 млн Series A (28.04.2026) — [OpenObserve](https://openobserve.ai/whats-new/2026-04-28-series-a-announcement.md)
- Один агрегатор насчитывает 43 стартапа AI observability с суммарным финансированием $1,1 млрд (слабый источник) — [Neuronfeed](https://neuronfeed.com/category/ai-observability)

**Робототехника / physical AI**
- Crunchbase: финансирование робототехники в 2026 уже превысило рекордный 2025; крупнейшая сделка года — Saronic (автономные суда); Mind Robotics — $500 млн Series A (март) — [Crunchbase News, перв.](https://news.crunchbase.com/robotics/startup-venture-funding-surges-2026-data/)
- $18,8 млрд с начала 2026 против $15 млрд за весь 2025 (дата среза неясна) — [Cryptorank, втор.](https://cryptorank.io/news/feed/a790e-startup-venture-funding-surges-2026-data)
- Dealroom (брифинг 06.10.2026): гуманоидные стартапы — $11 млрд венчура с начала 2026, более чем вдвое выше рекорда всего 2025; на Китай приходится ~2/3 финансирования гуманоидов — [Dealroom briefing](https://dealroom.co/briefing/2026-10-06/); [Dealroom chart](https://dealroom.co/charts/humanoid-robotics)
- Humanoid (Великобритания): $152 млн Series A при оценке $1,35 млрд (21.07.2026) — [Tech.eu](https://tech.eu/2026/07/21/uk-robotics-startup-humanoid-hits-135b-valuation-with-152m-series-a/)

**Compute / инференс / энергия**
- Dealroom (через CNBC): ИИ-чиповые стартапы привлекли $8,3 млрд в 2026 — [TechStartups, втор.](https://techstartups.com/?p=133250)
- Стартапы ИИ-дата-центров в США: $33,5 млрд с начала 2026, почти вдвое быстрее прошлого года (краткая новостная сводка) — [NewsBytes, втор.](https://www.newsbytesapp.com/news/business/us-ai-data-center-startups-raise-335-billion-in-2026/tldr)
- Gimlet Labs: $300 млн Series B при оценке $3 млрд («перестроить инференс»); энергопотребление ИИ-дата-центров ~18 ГВт в 2025 с ожиданием утроения к 2030 — [Dealroom](https://dealroom.co/news/148837-gimlet-labs-raises-300m-series-b-at-3b-valuation-to-rebuild-ai-inference/). Stanford AI Index 2026 даёт другую цифру: ИИ-дата-центры мира могут потреблять 29,6 ГВт — [MIT Technology Review, 13.04.2026](https://www.technologyreview.com/2026/04/13/1135675/want-to-understand-the-current-state-of-AI-check-out-these-charts)
- Deepinfra: $107 млн (май 2026) на инференс-облако для open-source моделей — [SiliconANGLE](https://siliconangle.com/?p=746725); Emerald AI — ПО гибкости энергопотребления дата-центров, работало в мультимегаваттном масштабе на август 2026 (сумма раунда «$150M» видна только в URL источника, текстом не подтверждена) — [Under30CEO, втор.](https://www.under30ceo.com/data-center-power-emerald-ai-150m/)

**Вертикальный ИИ**
- Harvey (юриспруденция): ~$190 млн ARR на конец 2025 → ~$300 млн к маю 2026 (оценка Sacra); оценка компании $11 млрд (март) → $15,5 млрд (сентябрь 2026) по вторичным источникам — [Sacra](https://sacra.com/research/harvey-at-195m-arr/); [Enterprise DNA, втор.](https://enterprisedna.co/resources/ai-map/company/harvey)
- OpenEvidence: ~$300 млн годовой выручки к середине 2026 (в основном реклама фармы), оценка $12 млрд; Sierra: $100 млн ARR за 7 кварталов, >$150 млн к февралю 2026; Legora: >$100 млн в апреле 2026 — оценки третьих сторон — [Enterprise DNA](https://enterprisedna.co/resources/ai-map/company/openevidence); [Tomasz Tunguz](https://tomtunguz.com/ai-harness-arr-multiples/)
- Tunguz: рынок оценил Harvey, Legora и Sierra в 50×, 56× и 100× ARR соответственно — [tomtunguz.com](https://tomtunguz.com/ai-harness-arr-multiples/)
- Один анализ: если убрать 12 сделок свыше $1 млрд, вертикальные стартапы получили 51% оставшихся денег (источник вторичный, первичный отчёт не найден) — [AI to ROI substack](https://ai2roi.substack.com/p/ai-to-roi-big-story-the-power-of)

**Y Combinator Requests for Startups**
- Winter 2027 (страница впервые зафиксирована в Wayback 27.10.2026): 11 идей; вступление — «самые большие узкие места ИИ смещаются за пределы моделей». Темы: цепочки поставок для дата-центров, финансирование роботов и GPU-кластеров, модели, принадлежащие компании (company-owned/специализированные модели — 4 из 11 запросов), ИИ для городских разрешений (permits); 7 из 11 — про железо, финансирование, госсектор и труд (группировка аналитика, не YC) — [YC RFS, перв.](https://ycombinator.com/rfs); [FourWeekMBA, втор.](https://fourweekmba.com/ai-yc-names-11-startup-ideas-as-ai-bottlenecks-move-past-models/); [Runtimewire](https://runtimewire.com/article/y-combinator-winter-2027-ai-bottlenecks); [Beinsure](https://beinsure.com/news/y-combinators-winter-2027-startup-priorities/)
- Fall 2026 (опубликован ~23.07.2026; дедлайн был 27 июля): 13 идей под тезисом «ИИ выходит в физический мир» — образование, здравоохранение, оборона, финансы, инфраструктура, труд. Подтверждённые названия: «The Primer» (ИИ-репетитор каждому ребёнку), «Self-Maintaining APIs» / «API Change Agents» (Harsha Gaddipati; агенты, применяющие breaking changes API как pull request'ы в кодовых базах клиентов), «Compute at Sea» (Francois Chaubard), multiplayer agents, «A cloud for small software»; впервые — запрос от министра армии США Daniel P. Driscoll (дешёвые оборонные технологии массового производства) — [IBTimes](https://www.ibtimes.sg/A000Ncu); [Startup Fortune, 23.07.2026](https://startupfortune.com/y-combinators-fall-2026-wish-list-puts-a-sitting-army-secretary-in-the-founder-pitch-room/); [explainx.ai](https://explainx.ai/blog/yc-requests-for-startups-fall-2026); [Superframeworks: «5 plays indie hackers can ship»](https://superframeworks.com/articles/yc-fall-2026-rfs-indie-hacker-plays)
- Summer 2026: 15 пунктов с уклоном в hard tech (агророботы, анти-дроны, чипы для инференса в космосе, цепочка поставок полупроводников); Spring 2026 — 8 категорий — [The Next Web](https://thenextweb.com/news/yc-summer-2026-rfs-hard-tech-pivot)
- YC оговаривает: это лишь часть того, что фонд финансирует; работать над этими идеями для заявки не обязательно — [YC RFS](https://ycombinator.com/rfs)

**Тезисы инвесторов (мнения)**
- Sequoia, AI Ascent 2026 (конец апреля 2026): ставка на long-horizon агентов, работающих часами/днями и выдающих законченный результат; тезис Julien Bek — «services over software»: «копилоты» продают инструмент профессионалам, «автопилоты» продают результат напрямую покупателю; прогноз — задержки строительства дата-центров при ускорении потребительского принятия — [Sequoia, перв.](https://www.sequoiacap.com/article/ai-ascent-2026); [Dealroom feed](https://app.dealroom.co/news/feed/sequoia-ai-will-replace-software-tools-by-executing-work-not-assisting-humans)
- a16z «Big Ideas 2026» **[ист., декабрь 2025]**: агентный трафик выглядит для legacy-систем как DDoS → нужно перестраивать control plane под агентов; «смерть prompt box» (меньше промптинга, встроенная память); переход от изолированных копилотов к координируемым мультиагентным системам → новые роли и слои ПО для координации, governance и надёжности — [a16z Big Ideas, part 1](https://a16z.com/newsletter/big-ideas-2026-part-1/); [a16z podcast](https://a16z.com/podcast/big-ideas-2026-the-enterprise-orchestration-layer/)

### Inferences
- **Переполнено / недоступно соло-строителю:** foundation models, чипы, дата-центры, гуманоиды, общий coding-ассистент (капиталоёмко; 69% расходов забирают три лаборатории; инкумбенты удерживают горизонтальные категории).
- **Быстро заполняется, но ещё открыто:** безопасность агентов (150+ seed-раундов за год — конкуренция высокая, зато явный платёжеспособный спрос), GEO/AEO (см. раздел 5).
- **Относительно недофинансировано относительно боли:** evals/observability (Braintrust $800 млн — крупнейший игрок; категория ~$1,1 млрд против $94 млрд расходов на модели) при том, что только 37% компаний видят вклад ИИ в EBIT и 63% разработчиков не доверяют агентам автопилот. Разрыв между расходами и доказанной отдачей — сама по себе рыночная ниша (измерение, надёжность, внедрение).
- Сдвиг YC от «моделей» к физическим и институциональным узким местам (permits, финансирование, API-совместимость) показывает: открытые проблемы — в стыках ИИ с реальным миром. «Self-Maintaining APIs», «cloud for small software», ИИ для разрешений — посильны малой команде с веб-бэкграундом.
- Тезис Sequoia «продавать результат, а не инструмент» прямо применим к агентству/сервису для МСБ.

### Gaps
- State of AI Report 2026 (Air Street / Nathan Benaich) поиском не найден — неизвестно, вышел ли и что в нём.
- Не найдены отчёты PitchBook/CB Insights 2026 с разбивкой ИИ-финансирования по категориям в едином формате; цифры по категориям собраны из разных источников с разными срезами и несопоставимы напрямую.
- Полные списки YC Fall 2026 (13) и Winter 2027 (11) с авторами и формулировками получить не удалось (ycombinator.com недоступен из сессии).
- Не найдены тезисы a16z/Sequoia, датированные второй половиной 2026 г.; Bessemer State of AI 2026 не найден.

---

## 4. Что рекомендуют практики и исследователи (атрибутированные мнения)

### Takeaway
Консенсус практиков 2026 г.: ценность смещается от написания кода к построению систем вокруг агентов — спецификации, проверка, evals, «петли» обратной связи, продуктовое суждение. Рекомендация для обучения — довести один проект end-to-end с набором evals. Это мнения, а не данные; большинство найдено за апрель–август 2026, свежих высказываний за сентябрь–ноябрь найдено мало.

### Cited Findings (все пункты — мнения, с атрибуцией)
- **Andrew Ng / DeepLearning.AI — «AI Engineering Skills Map» (август 2026).** Основана на анализе >10 000 вакансий, десятках структурированных интервью с экспертами, нанимающими менеджерами и рекрутёрами, и опросах. Четыре столпа: (1) создание и развёртывание ИИ-приложений, (2) основы software engineering, (3) работа с coding-агентами, (4) «shaping the build» (продуктовое суждение — что строить). 20 навыков в 4 группах; тестирование — в центре. Ng предпочитает говорить о «навыках AI-инженерии», а не о должности «AI Engineer». Оговорка: методика кластеризации и окно выборки не опубликованы; DeepLearning.AI продаёт курсы — [The Batch, перв.](https://www.deeplearning.ai/the-batch/the-ai-engineering-skills-map); [Skills Map](https://www.deeplearning.ai/resources/ai-engineering-skills); [explainx.ai, август 2026](https://explainx.ai/blog/andrew-ng-ai-engineering-skills-map-august-2026)
- Ng (в пересказе, не проверено по первоисточнику): построить одно законченное ИИ-приложение с нуля, развернуть, создать набор evals и изучить, где оно ошибается; «писать код дешевеет, а решать, какую проблему стоит решать — нет» — [dev.to, втор.](https://dev.to/decisive1/andrew-ng-on-the-future-of-ai-what-engineers-should-really-focus-on-3kch)
- **Andrej Karpathy — «From Vibe Coding to Agentic Engineering»** (беседа со Stephanie Zhan, Sequoia AI Ascent, конец апреля 2026; пересказы до 31.07.2026): vibe coding поднимает «пол» для всех, agentic engineering сохраняет профессиональную планку качества — агенты как основной исполнитель при тех же гарантиях безопасности и корректности. Больше всего выигрывают те, кто освоил проектирование спецификаций, ревью диффов, eval-петли и надзор за безопасностью; автоматизированная оценка — самый недоразвитый навык даже у опытных инженеров. Цитата: «You can outsource your thinking, but you can't outsource your understanding». Точные формулировки по видео не сверены; источники расходятся в деталях (про «10x») — [стенограмма, Singju Post](https://singjupost.com/andrej-karpathy-from-vibe-coding-to-agentic-engineering-w-stephanie-zhan-transcript/); [StartupHub, 31.07.2026](https://www.startuphub.ai/news/figure-andrej-karpathy-agentic-engineering-sequoia-2026-07-31); [MindStudio](https://www.mindstudio.ai/blog/karpathy-sequoia-talk-5-predictions-agentic-engineering)
- **Latent Space (swyx и соавт.) — «5 trends» по итогам AI Engineer World's Fair 2026:** сдвиг от «строить с агентами» к «строить системы вокруг агентов»; термин «loop engineering» — ответственность инженера-человека строить петли (внешняя петля: сигналы обратной связи, evals, человеческий ввод). Addy Osmani: «агенты могут вести гораздо большую часть внутренней петли исполнения, но внешняя петля — всё ещё инженерия». Среди тем дня — forward deployed engineers и «software factories» — [Latent Space, перв.](https://latent.space/p/aiewf26trends); [dev.to-зеркало](https://dev.to/latentspace/5-trends-that-defined-ai-engineering-at-worlds-fair-2026-5dj6); [Daily Dispatch](https://www.latent.space/p/aiewf-daily-dispatch-loops?open=false)
- Финальный keynote AIEWF 2026 был посвящён «harness engineering» (Mike Krieger, Anthropic Labs) — по вторичному вендорскому блогу — [TrueFoundry](https://www.truefoundry.com/blog/aiewf-2026-loops-harness-engineering)
- **Hamel Husain (март 2026):** «Evals Skills for Coding Agents» — как научить coding-агента запускать продуктовые evals; его курс AI Evals (с Shreya Shankar) прошли >5 000 студентов из 500+ компаний — [hamel.dev, перв.](https://hamel.dev/blog/posts/evals-skills/)
- **Armin Ronacher (через Simon Willison) [ист., ноябрь 2025]:** тестирование и evals остаются самой трудной проблемой AI-инженерии — [simonwillison.net, tag evals](https://simonwillison.net/tags/evals/)
- **Chip Huyen (в пересказе):** «неважно, что вы строите, если делаете это end-to-end», плюс системное мышление — [Yahoo Tech, втор.](https://tech.yahoo.com/ai/articles/want-upskill-ai-former-nvidia-171247655.html)
- **Sequoia (Julien Bek, 2026):** строить «автопилоты», продающие результат, а не «копилоты», продающие инструмент — [Dealroom feed](https://app.dealroom.co/news/feed/sequoia-ai-will-replace-software-tools-by-executing-work-not-assisting-humans)
- **Y Combinator (октябрь 2026):** «самые большие узкие места ИИ смещаются за пределы моделей» — [YC RFS](https://ycombinator.com/rfs)

### Inferences
- Сходящиеся рекомендации независимых практиков (Ng, Karpathy, Husain, Latent Space) указывают на один и тот же дефицитный навык: **оценка и верификация** (evals, спецификации, петли обратной связи). Это совпадает с данными раздела 1 (63% не доверяют агентам автопилот) и раздела 3 (evals недофинансированы).
- Для прикладного строителя без ML-PhD путь «agentic engineering + evals + продуктовое суждение» реалистичнее, чем обучение моделей: все четыре столпа карты Ng — инженерные и продуктовые, не исследовательские.
- У большинства цитируемых есть коммерческий интерес (курсы, фонды, медиа) — рекомендации стоит подавать как мнения заинтересованных экспертов.

### Gaps
- Мало найдено высказываний строго из периода сентябрь–ноябрь 2026; основная масса — апрель–август 2026.
- Не найдено рекомендаций исследователей фундаментального уровня (interpretability, inference optimization, data-centric AI) с конкретными советами для практиков.
- Полный список пяти трендов Latent Space и 20 навыков карты Ng не получен (страницы не открывались).

---

## 5. Возможности для соло-строителей и малых команд; доказательства реальной выручки

### Takeaway
Наиболее документированная выручкой ниша, близкая к SEO-опыту читателя, — GEO/AEO: ~$604 млн финансирования в 10 стартапах, Peec AI — $10 млн ARR за 16 месяцев, рынок оценивается в $390 млн (2025) с CAGR 41%. Услуги внедрения ИИ для МСБ подтверждены спросом (84% готовы доверить внедрение внешнему консультанту), но не данными о выручке агентств. Истории «миллион в одиночку» существуют, но плохо верифицированы.

### Cited Findings

**GEO / AEO (оптимизация под ИИ-поиск)**
- Value Add VC (16.10.2026): ~$604 млн раскрытого финансирования в 10 GEO/AEO-стартапах; на Profound приходится ~55% ($335 млн после Series D $180 млн при оценке $1,8 млрд) — [Value Add VC](https://valueaddvc.com/blog/ai-search-optimization-startups-2026-geo-aeo-funding-investors); Dealroom: ~$472 млн по 7 компаниям (сумма раундов, не размер рынка) — [Dealroom](https://dealroom.co/charts/generative-engine-optimization-startups)
- Profound: $96 млн Series C (Fortune, 24.02.2026), оценка $1 млрд, всего $155 млн на тот момент; далее Series D $180 млн при оценке $1,8 млрд (сентябрь 2026). Официальный ARR не раскрыт; оценка Fortune — ~$6,8 млн/год за 2025; компания заявляла утроение выручки за 6 месяцев до сентября 2026 — [Fortune](https://fortune.com/2026/02/24/exclusive-as-ai-threatens-search-profound-raises-96-million-to-help-brands-stay-visible/); [Sacra](https://sacra.com/c/profound)
- Peec AI (Берлин): компания сама подтвердила $10 млн ARR через 16 месяцев после запуска (пресс-релиз 28.05.2026); оценки Sacra — $11,5 млн (июнь 2026) и $20 млн (конец октября 2026, не подтверждено). Рост выручки на клиента связан с переходом к агентствам и enterprise; агентства, стандартизирующиеся на Peec, становятся мультиаккаунтными источниками выручки — [One News Page (пресс-релиз)](https://www.onenewspage.com/n/Press+Releases/1ztfis6jxj/Peec-AI-hits-10M-ARR-16-months-after.htm); [Sacra: Peec vs Profound](https://sacra.com/research/peec-vs-profound/)
- AthenaHQ: ~$990 тыс. выручки — оценка Latka по сводке поиска; низкая достоверность, точный URL страницы AthenaHQ не получен (в выдаче была только страница Latka о Profound) — [Latka](https://getlatka.com/companies/tryprofound)
- MarketsandMarkets: рынок GEO — ~$390 млн в 2025, прогноз ~$4,25 млрд к 2032, CAGR 41% (2026–2032) — [MarketsandMarkets](https://www.marketsandmarkets.com/Market-Reports/generative-engine-optimization-geo-market-265868816.html)
- Предостережение Sacra: категория в зачаточной стадии; неясно, достигнет ли ИИ-поиск масштаба и стабильности, достаточных для большой экосистемы инструментов оптимизации — [Sacra](https://sacra.com/research/profound)
- Инкумбенты отвечают: Ahrefs, Semrush и Conductor выпускают свои GEO-функции на фоне сотен миллионов у «чистых» GEO-игроков — [Everything PR](https://everything-pr.com/ahrefs-semrush-and-conductor-push-back-as-geo-pure-plays-raise-hundreds-of-millions/)
- Контекст спроса: Gartner прогнозировал падение традиционного поиска на 25% к концу 2026; eMarketer — 31,3% населения США используют генеративный ИИ-поиск в 2026 (вторичный пересказ, не проверено) — [AgentMarketCap, втор.](https://agentmarketcap.ai/blog/2026/04/17/profound-96m-series-c-generative-engine-optimization-unicorn)

**Услуги внедрения ИИ для МСБ**
- Pax8 Pulse (24.03.2026; 400 руководителей малого бизнеса США): 84% доверили бы внедрение ИИ внешнему технологическому консультанту; риски — фрагментированные инструменты и сбои интеграции — [Pax8 via AOL](https://lite.aol.com/tech/story/0022/20260324/9677293.htm)
- IDC (30.06.2026): безопасное внедрение новых технологий — главный вызов МСБ, впереди бюджета и нехватки ИТ-персонала — [IDC blog](https://www.idc.com/resource-center/blog/from-wait-and-see-to-all-in-how-smbs-are-rewriting-their-ai-story/)
- SAS/IDC (апрель 2026; 1 600 руководителей МСБ): большинство МСБ — на ранних стадиях ИИ-зрелости, трудности с исполнением — [SAS press release](https://www.sas.com/da_dk/news/press-releases/2026/april/majority-of-smbs-remain-in-early-stages-of-ai-maturity--study-sa.html)
- Bluehost: 87% малых бизнесов используют хотя бы один ИИ-инструмент, 47% — первый год — [Bluehost](https://www.bluehost.com/state-of-small-business-ai-confidence/ai-confidence-divide)
- Upwork (Q1 2026; 195 руководителей МСБ): пилотов ИИ-агентов больше, чем фирм, не рассматривающих их; прирост продуктивности пока инкрементальный; барьеры — безопасность данных/комплаенс и неопределённость ROI — [Upwork](https://www.upwork.com/resources/state-of-ai-in-smbs)
- Clutch (август 2026; 600 малых бизнесов США): пробелы в стратегии, готовности данных и governance — [Clutch](https://clutch.co/press-releases/SMB-ai-maturity-report)
- OpenAI + Upwork (ноябрь 2026): ИИ-связанные фриланс-проекты — на 52% более высокие бюджеты — [People Matters](https://sea.peoplemattersglobal.com/news/ai-and-emerging-tech/ai-related-freelance-projects-command-52percent-higher-budgets-as-demand-shifts-to-specialised-skills-openai-report-53273)

**Соло-основатели и малые команды**
- Carta (через PYMNTS): доля новых стартапов с единственным основателем выросла с 23,7% (2019) до 36,3% (H1 2025) **[ист.]** — [PYMNTS](https://www.pymnts.com/startups/2026/weekender-honey-i-shrunk-unicorn/)
- Base44 (соло-основатель Maor Shlomo) продан Wix за $80 млн в июне 2025 **[ист.]**; ~300 тыс. пользователей и $3,5 млн ARR до продажи (по блог-пересказу) — [Fortune, 18.05.2026](https://fortune.com/2026/05/18/solo-founders-ai-automation-entire-teams-entrepreneurs/)
- Заявления о выручке одиночек (Nick Dobos ~$8,8 млн ARR; Pieter Levels $1 млн+ ARR на Photo AI) происходят из блогов/рассылок и **не верифицированы**; на Indie Hackers пользователи сами просят фактчекинг — [Indie Hackers](https://www.indiehackers.com/post/11-solo-indie-hackers-making-1m-in-annual-revenue-NRq6hCm3La6N6UliFRfE); [We Are Founders, втор.](https://www.wearefounders.uk/the-30-highest-valued-solo-startups-of-2026/)
- Скепсис: оценка Everest Group — ~70–80% корпоративных инициатив с агентным ИИ в 2026 не вышли из proof-of-concept (вторичный пересказ, не проверено) — [dev.to, втор.](https://dev.to/nishilbhave/the-one-person-billion-dollar-company-ai-makes-it-real-23ja)

**Evals и надёжность как продукт**
- См. раздел 3: Braintrust ($800 млн оценка), Vals AI ($40 млн), Respan ($5 млн от YC/Gradient) — раунды 2026 г. показывают, что малые команды получают финансирование в этой нише — [Axios](https://www.axios.com/pro/enterprise-software-deals/2026/02/17/ai-observability-braintrust-80-million-800-million); [GlobeNewswire](https://www.globenewswire.com/news-release/2026/03/18/3258291/0/en/Respan-Announces-5M-in-Funding-from-Gradient-Y-Combinator-and-others-Launches-First-Proactive-AI-Observability-Platform.html)

**Провенанс контента**
- Обязательства прозрачности ст. 50 EU AI Act применяются со 2 августа 2026: синтетический контент должен маркироваться в машиночитаемой форме; Кодекс практики по маркировке ИИ-контента опубликован Еврокомиссией 10.06.2026 и описывает многослойный подход — видимые раскрытия, машиночитаемые манифесты метаданных (слой, куда относят C2PA), невидимые водяные знаки, фингерпринтинг. Сам регламент C2PA не называет — [IPTC, июнь 2026](https://iptc.org/news/eu-ai-transparency-code-of-practice-june-2026/); [SSL.com, вендор](https://www.ssl.com/article/eu-ai-act-article-50/); [CEPIC](https://www.cepic.org/post/the-transparency-obligations-of-the-ai-act-take-effect-on-2-august-2026-what-cepic-members-should-consider)
- Cloud Security Alliance (29.07.2026): состояние технологий водяных знаков не дотягивает до требования обнаружимости — [CSA research note](https://labs.cloudsecurityalliance.org/wp-content/uploads/2026/07/CSA_research_note_eu_ai_act_article_50_transparency_20260729-csa-styled-1.pdf)

**Локализация / переводы**
- Upwork **[ист., сентябрь 2025]**: спрос на translation & localization +29% за счёт человеческого контроля над ИИ-выводом — [Upwork](https://www.upwork.com/research/monthly-hiring-report-september-2025)

### Inferences
- **GEO/AEO — самое прямое продолжение SEO-компетенции читателя** и единственная из перечисленных ниш с подтверждённой самой компанией выручкой ($10 млн ARR у Peec за 16 мес.). Но продуктовый слой уже занят хорошо финансируемыми игроками и инкумбентами (Ahrefs, Semrush). Для соло-строителя реалистичнее **сервисный слой** (GEO-агентство/консалтинг на базе чужих инструментов) и **региональные/языковые ниши** (русско- и казахоязычный рынок, локальные ИИ-ассистенты), куда глобальные игроки не дошли. Это вывод, прямых данных о выручке GEO-агентств нет.
- Разрыв «87% МСБ используют ИИ / большинство на ранней стадии / 84% хотят внешнего консультанта» описывает спрос на интеграторов. Навыки Node.js + автоматизация покрывают именно этот слой. Главные барьеры покупателя (безопасность данных, неясный ROI) подсказывают формат: измеримый результат и фиксированный объём, а не «внедрение ИИ вообще».
- Провенанс: регуляторный спрос появился (август 2026), но технология незрелая и рынок стандартов контролируют крупные игроки; для одиночки скорее консалтинг по соответствию/интеграция, чем собственный продукт.
- Истории «миллион в одиночку» лучше использовать как иллюстрацию возможности, а не как базовую ставку: источники — блоги, выборка смещена на выживших.

### Gaps
- **Нет данных о выручке** GEO-агентств, AI-automation-агентств для МСБ и соло-строителей вертикальных агентов — только спросовые опросы и данные о финансируемых стартапах.
- Не найдено размера рынка услуг внедрения ИИ для МСБ за 2026 г.
- Не найдено данных о выручке в нише локализации/региональных данных для ИИ (разметка, датасеты на малоресурсных языках).
- Не найдено ни одного источника, отслеживающего именно соло-стартапы вертикальных агентов.

---

## 6. Развивающиеся рынки: Казахстан и Центральная Азия

### Takeaway
Казахстан — региональный лидер с заметным отрывом: закон об ИИ в силе с 18.01.2026, профильное министерство, суперкомпьютер из TOP500, национальные LLM, 100+ ИИ-стартапов и $73 млн ИИ-венчура (×5 за два года). При этом массовое использование ИИ низкое (15,9% населения, 70-е место из 147), а у компаний региона чёткая ИИ-стратегия есть только у 34% против 76% в мире — разрыв между государственной амбицией и реальным внедрением и есть рыночная возможность.

### Cited Findings

**Регулирование и институты**
- Закон РК № 230-VIII «Об искусственном интеллекте» подписан президентом 17.11.2025, вступил в силу 18.01.2026; системы ИИ классифицируются по уровню риска (минимальный, средний, высокий), для высокорисковых — более строгий режим. Chambers называет его первым специализированным законодательным актом в этой сфере на пространстве ЕАЭС — [gov.kz (МИИЦР), перв.](https://www.gov.kz/memleket/entities/maidd/press/news/details/1143060?lang=ru); [EY](https://www.ey.com/en_kz/technical/tax-alerts/2025/12/law-on-artificial-intelligence-kazakhstan); [Chambers](https://chambers.com/articles/current-issues-in-artificial-intelligence-regulation-in-kazakhstan); [Tengrinews](https://en.tengrinews.kz/kazakhstan_news/new-law-comes-into-force-in-kazakhstan-270729)
- Министерство искусственного интеллекта и цифрового развития создано в 2025 г., уполномоченный орган по ИИ — [Mondaq](https://webiis10.mondaq.com/new-technology/1747632/ai-regulation-and-the-ministry-of-artificial-intelligence-in-kazakhstan)
- Al Jazeera (21.09.2026): Казахстан в 2025 стал второй юрисдикцией после ЕС, принявшей закон об ИИ; критика — правоприменение пока неясно и может не включать серьёзного общественного контроля — [Al Jazeera](https://www.aljazeera.com/news/2026/9/21/inside-kazakhstans-push-to-become-a-regional-ai-centre)
- Президент объявил 2026 год годом ИИ; на рассмотрении более широкий Цифровой кодекс и мера о запрете ИИ для социального профилирования — [Intellinews](https://www.intellinews.com/central-asia-lagging-in-ai-diffusion-report-442712/); [Eurasianet](https://eurasianet.org/ai-in-kazakhstan-lifting-off-toward-the-cognitive-economy)

**Инфраструктура и модели**
- Национальный суперкомпьютер Alem.Cloud (Астана): №104 в TOP500, ~20,48 ПФлоп/с, NVIDIA H200 (страница национального ИИ-агентства). Запущен в июле 2025; Euronews тогда сообщал «~2 экзафлопс» — расхождение с TOP500; партнёр по строительству — Presight (ОАЭ) — [NITEC AI ecosystem](https://ai.nitec.kz/en/ecosystem); [Euronews, 20.07.2025, ист.](https://www.euronews.com/next/2025/07/20/the-most-powerful-supercomputer-in-central-asia-launches-in-kazakhstanin-bid-for-ai-boost)
- По оценке из поста об AI Country Report, локальную разработку обеспечивают ~2 000 GPU NVIDIA (LinkedIn-пост, слабый источник) — [LinkedIn](https://ru.linkedin.com/in/alina-kokosadze)
- KazLLM: представлена ISSAI (Назарбаев Университет) в декабре 2024 **[ист.]**; 70 млрд параметров, архитектура Llama 3.1; разработана ISSAI, QazCode и Astana Hub, обучена на >150 млрд токенов на казахском, русском, английском и турецком. Alem LLM — 246 млрд параметров — [NITEC](https://ai.nitec.kz/en/ecosystem); [Astana Hub blog](https://astanahub.com/en/blog/ot-kazllm-k-urdullm-kak-kazakhstanskii-ai-opyt-stal-eksportnym-produktom)
- Экспорт опыта: в феврале 2026 Beeline Kazakhstan и QazCode подписали меморандум с JazzWorld (крупнейший оператор Пакистана) — «от KazLLM к UrduLLM» — [Astana Hub blog](https://astanahub.com/en/blog/ot-kazllm-k-urdullm-kak-kazakhstanskii-ai-opyt-stal-eksportnym-produktom)
- Международный ИИ-центр Alem.ai: открытие анонсировано президентом Токаевым в октябре 2025 на Digital Bridge — [Al Jazeera](https://www.aljazeera.com/news/2026/9/21/inside-kazakhstans-push-to-become-a-regional-ai-centre)
- Казахстан выразил готовность участвовать в разработке тюркской LLM — [oq.gov.kz](https://oq.gov.kz/en/qazalemnews/1281)

**Экосистема и деньги**
- Первый Kazakhstan AI Country Report (январь 2026): венчурное финансирование ИИ-проектов выросло с ~$14 млн (2023) до $73 млн (2025); ИИ — более половины всего венчура страны; >100 ИИ-стартапов; среди мер — поддержка казахоязычных LLM. Intellinews приводит «более $75 млн» — [gov.kz, перв.](https://www.gov.kz/memleket/entities/maidd/press/news/details/1149605?lang=en); [Astana Times, февраль 2026](https://astanatimes.com/2026/02/venture-investment-in-ai-rises-fivefold-in-two-years-says-latest-report/); [Daryo, 29.01.2026](https://daryo.uz/en/2026/01/29/kazakhstans-ai-startup-ecosystem-grows-to-100-startups-with-73mn-in-venture-investment/); [Intellinews](https://www.intellinews.com/government-report-highlights-artificial-intelligence-gains-in-kazakhstan-423547/)
- Astana Hub, итоги 2025 (отчёт февраля 2026): экспорт ИТ-услуг резидентов — $633,8 млн, совокупная выручка >$1,7 млрд, >32 тыс. рабочих мест. Gulf News: $634,6 млн из $1 млрд ИТ-экспорта Казахстана. На главной странице хаба — «$2 млрд экспортной выручки» (вероятно, накопленным итогом) — [Astana Hub](https://astanahub.com/en/article/ot-talantov-do-globalnykh-proektov-kak-astana-hub-razvivaet-ai-ekosistemu-kazakhstana); [Gulf News](https://gulfnews.com/amp/story/gn-focus%2Fkazakhstan-emerges-as-central-eurasias-tech-powerhouse-bridging-gulf-and-global-markets-1.500524748)
- Акселератор AI'preneurs (с 2024, открыт набор шестого потока): стартапы участников сгенерировали 153 млн тенге продаж и предпродаж в 2025; две команды получили soft-commitments на $75 тыс. от Astana Hub Ventures. Astana Hub Ventures инвестировал $500 тыс. в Higgsfield — [DKNews](https://dknews.kz/en/articles-in-english/399591-astana-hub-opens-applications-for-sixth-ai-preneurs)
- Поддержать ИИ-инициативы Казахстана намерены Telegram, Google и inDrive — [Orda.kz](https://en.orda.kz/telegram-google-and-indrive-to-support-kazakhstans-artificial-intelligence-push-6143/)

**Принятие ИИ в регионе**
- Microsoft Global AI Diffusion Report (публикации 01.06.2026): Казахстан — 70-е место из 147, 15,9% населения регулярно используют ИИ (в одном источнике 15,8%); Кыргызстан — 116-е (9,5%); Узбекистан — 142-е; Афганистан — 144-е; Таджикистан — 145-е; Туркменистан — 146-е. Казахстан, Кыргызстан и Узбекистан — среди самых быстрорастущих по принятию ИИ с июня 2025 — [Daryo, 01.06.2026](https://daryo.uz/en/2026/06/01/uzbekistan-ranks-142nd-globally-in-ai-use-as-kazakhstan-leads-central-asia/); [Kun.uz, 01.06.2026](https://kun.uz/en/news/2026/06/01/kazakhstan-leads-central-asia-in-ai-adoption-as-uzbekistan-struggles-with-low-usage-rates-0fddc4); [Fergana](https://en.fergana.agency/news/146961/)
- Узбекистан: использование генеративного ИИ среди работающих выросло с 5,7% (H1 2025) до 7,2% (Q1 2026) — [Kursiv, 12.05.2026](https://uz.kursiv.media/en/2026-05-12/generative-ai-usage-reaches-7-2-among-uzbekistans-workforce/)
- KPMG Tech Report 2026 (май 2026, регион): только 34% компаний имеют чёткую ИИ-стратегию против 76% в мире — [KPMG Kazakhstan](https://kpmg.com/kz/en/media/press-releases/2026/05/tech-report.html)
- Лидеры Кыргызстана, Таджикистана и Узбекистана заявляли о планах создать ИТ/ИИ-хабы — [Intellinews](https://www.intellinews.com/central-asia-lagging-in-ai-diffusion-report-442712/)
- Глобальный контекст — Deloitte State of AI 2026: 77% называют место разработки ИИ ключевым фактором при выборе новых технологий (суверенность) — [Deloitte](https://www.deloitte.com/content/dam/assets-shared/docs/about/2025/state-of-ai-2026-global.pdf)

**Языковой разрыв**
- KazMMLU **[ист., февраль 2025]** — первый MMLU-подобный датасет для казахского (национальные экзамены, учебники, профсертификации) — [arXiv 2502.12829](https://arxiv.org/abs/2502.12829v2)
- KazBench-KK **[ист., 2025]**: 7 111 вопросов в 17 культурно значимых доменах; оценка KazLLM (ISSAI) ранее опиралась в основном на машинно переведённые датасеты; TUMLU покрывает тюркские языки, но без казахстанского контекста — по сводке поиска из обзоров связанных работ в [arXiv 2502.12829](https://arxiv.org/html/2502.12829v2) и мартовских препринтах 2026 г. (точный arXiv-ID самого KazBench-KK не получен)
- Два препринта марта 2026 (соответствие названий и ID поиском не подтверждено — в выдаче были ID [2603.20854](https://arxiv.org/html/2603.20854v1) и [2603.21036](https://arxiv.org/html/2603.21036v1)): «Left Behind» — контролируемый бенчмарк: 2 000 ответов, 8 LLM, 50 вручную составленных вопросов с параллельными версиями на английском, казахском и монгольском; «SozKZ» — обучение эффективных малых языковых моделей для казахского с нуля
- Sherkala-Chat (8B) **[ист., 2025]**: на базе LLaMA-3.1-8B, 45,3 млрд токенов на казахском, английском, русском и турецком — [arXiv 2503.01493](https://arxiv.org/html/2503.01493v2)

### Inferences
- Сочетание «сильное государство-заказчик + слабое массовое принятие (15,9%) + только 34% компаний со стратегией» означает, что спрос в регионе смещён к **внедрению и адаптации**, а не к созданию базовых технологий. Это рынок интеграторов, обучения и локализованных вертикальных продуктов.
- Языковая ниша реальна и подтверждена академически (оценка моделей на казахском опиралась на машинный перевод; название работы «Left Behind» говорит само за себя). Практические продукты поверх этого разрыва: казахо-/русскоязычные evals и тестовые наборы, локальные данные, GEO для казахоязычных и русскоязычных запросов, голос/поддержка на казахском. Это вывод; данных о выручке таких продуктов не найдено.
- Экспорт KazLLM-опыта в Пакистан показывает модель «региональная экспертиза по малоресурсным языкам → экспортный продукт» — применимо и к малым командам (тюркские языки, урду и т.п.).
- Новый закон об ИИ с риск-классификацией создаёт локальный спрос на комплаенс-компетенции, которых на рынке почти нет (закон в силе менее года).
- Низкая стоимость жизни + экспортная модель Astana Hub ($634 млн ИТ-экспорта) + зарплатная премия за ИИ-навыки на глобальном рынке (раздел 1) делают удалённую работу/услуги на внешние рынки экономически привлекательнее чисто локального рынка.

### Gaps
- Не найдено данных о рынке труда ИИ-специалистов в Казахстане/ЦА (вакансии, зарплаты, дефицит) за 2026 г.
- Не найдено данных о выручке казахстанских ИИ-стартапов (кроме 153 млн тенге у участников AI'preneurs) и разбивки выручки Astana Hub на ИИ/не-ИИ.
- Не найдено информации о работах по узбекским, кыргызским, таджикским, туркменским LLM и речевым датасетам; также о казахских ASR-датасетах.
- Статья Al Jazeera не открывалась — детали (программы обучения, объёмы инвестиций, цитаты критиков) извлечены частично.
- Налоговые/визовые режимы Astana Hub для резидентов в 2026 г. не исследовались.

---

## 7. Пути обучения: ресурсы, сертификации, типы проектов

### Takeaway
В 2026 г. работодатели проверяют проекты, а не значки: сертификации помогают пройти первичный отсев (особенно облачные вендорские), но решает законченный, развёрнутый проект с набором evals. Самые цитируемые структурированные ориентиры — карта навыков Andrew Ng и материалы по evals Hamel Husain.

### Cited Findings
- InfoWorld (2026, мнение колумниста): ИИ-сертификации всё ещё имеют смысл, но по более узким причинам, для более конкретных ролей и с более коротким сроком годности — [InfoWorld](https://infoworld.com/article/4242723/are-ai-certifications-still-worth-it-what-changed-in-2026.html)
- Несколько источников сходятся: большинство ИИ-сертификаций не окупаются; нанимают кандидатов с меньшим числом сертификатов и большим production-опытом; рекрутёры смотрят GitHub, портфолио, технические кейсы — [KDnuggets](https://kdnuggets.com/5-ai-certifications-worth-paying-for-in-2026-and-which-to-skip); [dev.to](https://dev.to/georgiaweston/how-hiring-managers-validate-ai-certifications-a-playbook-4k2p)
- Противоречивые непроверенные цифры: «73% нанимающих менеджеров ценят продемонстрированные ИИ-проекты выше сертификатов» (со ссылкой на LinkedIn) и «только 23% активно отсеивают по ИИ-сертификатам»; Resume Genius: 82% считают, что сертификации могут быть так же ценны, как бакалавриат — первоисточники не проверены — [Rework, втор.](https://resources.rework.com/news/ai-jobs-skills/ai-certification-market-2026-what-matters); [Millersville, втор.](https://techprogram.millersville.edu/blog/is-ai-certification-worth-it-2026/)
- Вендорские сертификации (AWS, Google Cloud, Microsoft Azure) дольше сохраняют признание работодателей, чем платформенно-нейтральные; чаще всего называют Google Professional ML Engineer и AWS Certified ML – Specialty; экзамен Microsoft AI-102 обновляется на конец 2026 (источник показателей узнаваемости неясен) — [Dataquest](https://www.dataquest.io/blog/best-ai-certifications/); [eWeek](https://www.eweek.com/news/best-ai-certifications-2026/)
- Barclay Simpson 2026 (governance): работодатели хотят «практические ИИ-компетенции и знакомство с EU AI Act» — [Barclay Simpson](https://www.barclaysimpson.com/?p=82558)
- Ресурсы, названные практиками: DeepLearning.AI AI Engineering Skills Map (4 столпа, 20 навыков; август 2026) — [DeepLearning.AI](https://www.deeplearning.ai/resources/ai-engineering-skills); серия разборов «Skills Map in detail» — [The Batch](https://www.deeplearning.ai/the-batch/he-ai-engineering-skills-map-in-detail-building-and-deploying-ai-applications); Hamel Husain — evals-навыки для coding-агентов (март 2026) и курс AI Evals (>5 000 студентов из 500+ компаний) — [hamel.dev](https://hamel.dev/blog/posts/evals-skills/); FAQ по AI evals (Husain и Shankar) **[ист., июль 2025]** — [simonwillison.net](https://feeds.simonwillison.net/2025/Jul/3/faqs-about-ai-evals/); длинные объяснения Karpathy о том, как работают LLM — [Louis Bouchard](https://www.louisbouchard.ai/learn-ai-engineering/)
- Тип проекта (мнения): Ng — одно законченное приложение, развёрнутое, с набором evals и разбором ошибок (пересказ); Chip Huyen — «неважно что, главное end-to-end» — [dev.to, втор.](https://dev.to/decisive1/andrew-ng-on-the-future-of-ai-what-engineers-should-really-focus-on-3kch); [Yahoo Tech, втор.](https://tech.yahoo.com/ai/articles/want-upskill-ai-former-nvidia-171247655.html)
- Локальная точка входа: акселератор AI'preneurs (Astana Hub), шестой поток — [DKNews](https://dknews.kz/en/articles-in-english/399591-astana-hub-opens-applications-for-sixth-ai-preneurs)
- Инструментальный ориентир: по Stack Overflow 2026 самые используемые coding-агенты — Claude Code (66%) и GitHub Copilot (59%) — [Stack Overflow blog](https://stackoverflow.blog/2026/10/06/the-results-of-the-2026-developer-survey-are-here/)

### Inferences
- Для прикладного строителя с Node.js наиболее «кредитный» артефакт в 2026 — публичный законченный агентный продукт (или кейс внедрения у клиента) с документированными evals, метриками надёжности и разбором отказов; он одновременно закрывает три столпа карты Ng и отвечает на главный дефицит рынка (верификация).
- Сертификации стоит рассматривать точечно: облачная вендорская — если цель найм/FDE-роли у западных работодателей; governance (тип AIGP) — если цель комплаенс-ниша. Для собственного продукта или агентства их ценность мала.
- Реалистичные входные требования по путям (синтез разделов 1–6, не прямые данные): (а) agentic/AI engineering и FDE — сильная общая инженерия + опыт внедрения у клиента, ML-степень не требуется; (б) evals/надёжность — инженерия + дисциплина измерений, порог входа низкий, дефицит высокий; (в) ИИ-безопасность агентов — нужен бэкграунд в security, порог средний; (г) inference optimization / ML-инфраструктура / робототехника — глубокий технический порог и капиталоёмкость, для одиночки без ML-подготовки наименее доступны; (д) governance — юридический/комплаенс-порог.

### Gaps
- Не найдено достоверных сведений о сертификациях, специфичных для агентной инженерии (вендорские программы от ИИ-лабораторий, NVIDIA и др.) и их признании работодателями в 2026 г.
- Нет данных о том, какие сертификации/проекты реально повышают шансы найма для кандидатов из развивающихся рынков, работающих удалённо.
- Содержание 20 навыков карты Ng и программы курса AI Evals не извлечено (страницы не открывались).
- Нет количественных данных о сроках и стоимости перехода веб-разработчика в AI-инженерию.
