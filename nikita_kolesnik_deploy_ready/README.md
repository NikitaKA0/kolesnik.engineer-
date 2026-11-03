# Nikita Kolesnik — bilingual academic and engineering website

Run locally by opening `index.html`; upload this folder's contents to a static web host (such as Netlify).

## Curated source-based engineering archive

All visuals are crops of files uploaded in this chat, **not generated stock photos**. Typography and matting around each excerpt were added for consistent presentation.

- Myograph PCB: `КП_КолесникНА.pdf`, p.19; extra original schematic p.18 and CAD enclosure p.14.
- EMD: `EMD_Колесник_МОБС_реферат_.pdf`, p.8 plus algorithm / source-code PDF excerpts.
- NMR: `ТР_ЭР-17-21_КолесникНА.pdf`, p.11 with PDF excerpts pp.8–12.
- EEG: `КолесникНА__отчёт_о_практике.pdf`, p.15; PDF excerpt pp.14–15. No patient source datasets are distributed.
- Cavitation: `Кавитация_отчет_01_10_2025.pdf`, p.49; PDF excerpt pp.41, 48–50. Literature-derived theory, not a novel experiment.
- Practice photo: `КолесникНА__отчёт_о_практике(1).pdf`, p.16; PDF excerpt pp.5–7,16. Photographer is not identified in report.

Publication, award and educational claims are in other sections; an engineering report excerpt is not a peer-reviewed publication.

## Deployment / custom domain

See `DOMAIN_SETUP.md` for the steps for `kolesnik.engineer`. The site contains no registrar credentials and changing local files does not modify real-world DNS records.


## Verified credentials added (2026-11-03)
- 2024-04-26: team 2nd place in “ПЛИС. Опережая сигналы”, VI Festival of Radioelectronics (photo supplied by user).
- 2025-07-04: MPEI professional retraining, “Алгоритмизация и разработка программ для предприятий ТЭК”, 252 hours, “Программист” (photo supplied by user).
- 2025-12-23: MPEI professional retraining, “Педагогика и психология в профессиональной деятельности”, 252 hours, “Преподаватель-ассистент” (photo supplied by user).
- For privacy, the website uses cropped diploma photographs showing identity, programme and qualification while omitting registration numbers and signatures. The team award photograph is included as supplied.


## Преподаватели и наставники (обновление 03.11.2026)

На сайте добавлен двуязычный раздел с 50 фамилиями преподавателей, указанными владельцем портфолио. Для 47 удалось сверить полные ФИО и сведения о должности, степени / звании по публичным страницам НИУ «МЭИ». У каждой карточки есть ссылка на использованный источник. Оставшиеся три фамилии (Ильин, Лебедева, Медовиков) представлены только как требующие уточнения; сведения об однофамильцах не подставлялись автоматически.

Академическое звание не следует смешивать с занимаемой должностью. При обновлениях университета степень / звание / должность могли измениться. Для новых проверок используйте оригинальные страницы МЭИ из карточек.


## Library ticker / Библиотечная лента

Список из 213 книг взят из `MyLibrary(4).xlsx` (лист Books, строки 2–214). Данные включены в `books-data.js`, отдельно загружать Excel на публичный сайт не требуется. Большинство строк оставлено в исходной транслитерации. Если автора нет или в книге содержится плейсхолдер, отображается «Автор не указан». Для строки №77 исправлено очевидное повреждение кодировки. Тематические символы приблизительно классифицируют по названию — в каталоге категория не была надёжно указана. Движение отключается при `prefers-reduced-motion`; есть кнопка паузы и остановка по наведению.

## Безопасность

См. [SECURITY.md](SECURITY.md). GitHub Pages не применяет `_headers`, но встроенный CSP действует в браузерах.
