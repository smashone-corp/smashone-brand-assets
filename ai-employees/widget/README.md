# Лица для виджета на сайте клиента — без значка «AI» (Мира, 25.09.2026)

> Наряд `DISP-MIRA-2026-09-25-2231-WIDGET-FACES-BADGE-FREE-VARIANTS-DISCLOSURE-BY-LABEL-1`, решение GA 25.09 22:31 МСК: на виджете клиента раскрытие = одна подпись под именем (§71, `product-facts.yml` `disclosure.widget_header`: «{name} · AI assistant»), значок на лице — второе раскрытие, снимается. **В кабинете и на нашем сайте значок остаётся** (файлы `../ai-office/*-avatar-*`).

**Как сделано:** квадрат по голове из канонического аватара персоны `../ai-office/<persona>-avatar-512.webp` (у Джордан — `june-avatar-512.webp`, имя файла историческое), нижний край — на 6 px выше плашки значка; кроп до масштабирования совпадает с оригиналом пиксель в пиксель (проверено), ретуши нет — лицо то же; затем масштаб до , webp q92; на виджете показывается кругом 40 px.
**Значок вшит только у семи персон** (Jordan, Sloane, Sage, Avery, Blake, Ruby, Miles). У Reese (lead qualifier), Rene (appointment coordinator), Piper (marketing assistant) лицо = портрет ростера `../roster/role-*.webp` — значка там нет, отдельный файл не нужен.

| Файл | sha8 |
|---|---|
| `avery-widget-384.webp` | 44c5b80d |
| `blake-widget-384.webp` | 103b5021 |
| `jordan-widget-384.webp` | a62211d1 |
| `miles-widget-384.webp` | 8b1ac6e5 |
| `ruby-widget-384.webp` | f5fd6a3b |
| `sage-widget-384.webp` | 33a314fe |
| `sloane-widget-384.webp` | 36a3f2f8 |
