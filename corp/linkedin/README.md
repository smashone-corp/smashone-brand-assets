# `corp/linkedin/` — оформление страницы компании SmashOne в LinkedIn

Заведено 07.09.2026 (Мира, наряд GA: страница компании открывается по 100 контактам Дмитрия). Джей забирает файлы по наряду GA.

Raw-база: `https://raw.githubusercontent.com/smashone-corp/smashone-brand-assets/main/corp/linkedin/`

| Файл | Размер | Происхождение |
|---|---|---|
| `smashone-corp-linkedin-cover-1512x256.png` | 1512×256 (минимум и рекомендация LinkedIn для Company Page, справка LinkedIn 2026) | 🆕 12.09.2026 — **загружать этот файл.** Кит `SMM-Hub/design/scripts/channel-covers-v3/` (мастер @2x `out/linkedin-cover-3024x512.png`), лица Слоан и Блейк из ростера банка теми же байтами. Текстовый блок сдвинут вправо по слову владельца 12.09 («надпись на шапке нужно немного правее сместить»): знак с 31.1 %, текст с 35.6 % ширины; на живой геометрии страницы без логина квадрат логотипа занимает до 19.8 % (десктоп) и 29.1 % (телефон, веб) — в его зоне 0 глифов. sha256 `6045cb5743ab402d9c1b8f035db01af259447aa9993acfc8a9d912d9c87e0d6d`. Замеры: `SMM-Hub/design/reports/2026-09-12-linkedin-company-cover/` |
| `smashone-corp-linkedin-cover-1128x191.png` | 1128×191 | 🔄 12.09.2026 — та же композиция, что 1512×256, уменьшенная (ниже спецификации LinkedIn, держится для совместимости). ⚰️ Прежнее содержимое «кроп центра баннера 03.09» снято: живой была шапка из кита v3, а не этот кроп. sha256 `f7df87684090a21588d79fe61881e25e2501d3376c50e89bc734abce465b8d37` |
| `smashone-corp-linkedin-logo-400x400.png` | 400×400 | тот же знак, что на корпоративных аккаунтах: копия `logos/avatars-corp/avatar-400.png` — золотой знак `#b08930` на кремовом `#F7F6F2` (канон фавикона 25.08: чёрная плашка = дефект) |

🔴 Если понадобится баннер большего разрешения — LinkedIn принимает и `channels/corp/smashone-corp-linkedin-banner-4200x700.png` (6:1, показ ≈1128×191). Гейты речи: без цен, без дат, без числа ролей, без «MCP».

## Баннер ЛИЧНОГО профиля основателя — `founder-banner-nodate-1584x396.png` (08.09.2026, Мира; наряд GA 07.09 20:3x)
Замена живого баннера с публичной датой «Opening September 1, 2026» (канон 27.08: дат нигде). Язык принятых
корп-обложек 03.09 + обложки X без даты: крючок «Hire an AI employee — before you hire a human.», строка
«…and growing every month», ряд лиц ростера из `ai-employees/roster/` уходит за правый край — несчётный.
Text-safe: центральные 1344 px, не ниже 300 px; нижний левый угол под аватар профиля. sha256 `2aacf10d985e93a5…`.
Сборка: `SMM-Hub/design/scripts/corp-covers/build_founder.py` → `render_founder.py`.
raw: https://raw.githubusercontent.com/smashone-corp/smashone-brand-assets/main/corp/linkedin/founder-banner-nodate-1584x396.png
