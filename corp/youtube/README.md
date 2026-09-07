# `corp/youtube/` — обложки пяти плейлистов канала `@SmashOneUS` (07.09.2026, Мира; наряд GA 19:3x)

🔴 **Факт площадки:** у плейлиста YouTube нет собственного постера — в списке плейлистов показывается
обложка ПЕРВОГО видео. Поэтому каждый файл здесь — обложка первого ролика полосы, собранная по
шаблону этой полосы так, чтобы имя плейлиста читалось киккером. Ставится как thumbnail первого
видео плейлиста (Custom thumbnail в YouTube Studio); если у первого ролика есть своя обложка —
выбор за публикатором, оба файла лежат у него.

Шаблоны полос приняты владельцем 04.09 (канвас «youtube-lane-thumbnails», кит канала —
`channels/youtube/corp/`: баннер 2560×1440, аватар 800×800, шаблоны обложек). Тексты — только из
документов GA: паспорт канала §5 (первый урок, персона Слоан, Tampa) и
`Jay/tasks/_FROM_GA-2026-09-07-linkedin-page-texts-and-playlist-texts.md` (описания полос 4 и 5,
дословные фрагменты). Сборка детерминированная: `SMM-Hub/design/scripts/youtube-kit/build_playlists.py`
→ `render_playlists.py`. Лицо Слоан — референс Дона `heroes/sloane/reference/sloane-photo-reference-v1.jpeg`.

Raw-база: `https://raw.githubusercontent.com/smashone-corp/smashone-brand-assets/main/corp/youtube/`

| # | Плейлист | Файл | Шаблон полосы |
|---|---|---|---|
| 1 | Lessons | `playlist-01-lessons-1280x720.png` | урок 01 «Hire your first employee from your own chat» · имена ассистентов текстом |
| 2 | Meet the staff | `playlist-02-meet-the-staff-1280x720.png` | персона Слоан (референс Дона), чип «AI-generated presenter» |
| 3 | Demo businesses | `playlist-03-demo-businesses-1280x720.png` | Tampa Pasta House — в кадре блюдо, людей нет (рамка 31.08), плашка честности |
| 4 | AI at work for small business | `playlist-04-ai-at-work-for-small-business-1280x720.png` | вариант A (типографика), нижняя строка — «Each card names its source.» |
| 5 | SmashOne updates | `playlist-05-smashone-updates-1280x720.png` | шаблон статьи с киккером полосы |

Гейты речи на всех пяти: без цен, без дат, без числа ролей, без слова «MCP», чужих логотипов нет.
Мобильная проверка: крючок читается на 168×94.
## sha256 (первые 16)
- 64064a80ec3e14a3 *playlist-01-lessons-1280x720.png
- a7ea6b543b6bbc02 *playlist-02-meet-the-staff-1280x720.png
- faaa85ef93142beb *playlist-03-demo-businesses-1280x720.png
- 4b1a605fc0b71a97 *playlist-04-ai-at-work-for-small-business-1280x720.png
- 05ae4f4247b67954 *playlist-05-smashone-updates-1280x720.png
