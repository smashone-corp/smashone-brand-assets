# `corp/linkedin/` — оформление страницы компании SmashOne в LinkedIn

Заведено 07.09.2026 (Мира, наряд GA: страница компании открывается по 100 контактам Дмитрия). Джей забирает файлы по наряду GA.

Raw-база: `https://raw.githubusercontent.com/smashone-corp/smashone-brand-assets/main/corp/linkedin/`

| Файл | Размер | Происхождение |
|---|---|---|
| `smashone-corp-linkedin-cover-1128x191.png` | 1128×191 (спецификация LinkedIn Company Page) | точный кроп центра принятого 03.09 баннера `channels/corp/smashone-corp-linkedin-banner-4200x700.png` (кит `SMM-Hub/design/scripts/corp-covers/`) до пропорции 1128:191 и даунскейл LANCZOS; смысл в центральной безопасной зоне, знак + «Hire an AI employee — before you hire a human.» + строка сервиса; слогана владельца («Hire an AI. Enjoy life.») НЕТ — юрпроверка знака не пройдена |
| `smashone-corp-linkedin-logo-400x400.png` | 400×400 | тот же знак, что на корпоративных аккаунтах: копия `logos/avatars-corp/avatar-400.png` — золотой знак `#b08930` на кремовом `#F7F6F2` (канон фавикона 25.08: чёрная плашка = дефект) |

🔴 Если понадобится баннер большего разрешения — LinkedIn принимает и `channels/corp/smashone-corp-linkedin-banner-4200x700.png` (6:1, показ ≈1128×191). Гейты речи: без цен, без дат, без числа ролей, без «MCP».

## Баннер ЛИЧНОГО профиля основателя — `founder-banner-nodate-1584x396.png` (08.09.2026, Мира; наряд GA 07.09 20:3x)
Замена живого баннера с публичной датой «Opening September 1, 2026» (канон 27.08: дат нигде). Язык принятых
корп-обложек 03.09 + обложки X без даты: крючок «Hire an AI employee — before you hire a human.», строка
«…and growing every month», ряд лиц ростера из `ai-employees/roster/` уходит за правый край — несчётный.
Text-safe: центральные 1344 px, не ниже 300 px; нижний левый угол под аватар профиля. sha256 `2aacf10d985e93a5…`.
Сборка: `SMM-Hub/design/scripts/corp-covers/build_founder.py` → `render_founder.py`.
raw: https://raw.githubusercontent.com/smashone-corp/smashone-brand-assets/main/corp/linkedin/founder-banner-nodate-1584x396.png
