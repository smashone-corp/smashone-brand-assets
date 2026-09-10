# og/ — карточки ссылок (Open Graph) страниц smashone.us

Класс заведён 10.09.2026. До этого дня og-картинки существовали **только** в репозитории кода —
в банке их не было ни одной, и это была дыра единого банка данных: ассет, который видит каждый,
кто делится ссылкой, не имел канонической копии.

## Что здесь лежит

Пути повторяют сайт один в один: `og/<то же имя>` = `web/public/assets/og/<то же имя>`.
Переименований нет, вложенность (`roles/`, `channels/`) сохранена.

Источник: `smashone-corp/SmashOne-US`, `origin/master` на `4613a8a1e`, ветка master.
Файлы взяты **байт в байт** (`git cat-file blob`), не пережаты и не сконвертированы.

## Правила класса

- Карточка обновляется **тем же именем** — старая заменяется, рядом ничего не копится.
- `sha256` ниже — прибор: расхождение банка и сайта ловится сверкой хэшей, а не глазами.
- Текст, напечатанный на карточке, живёт в ОДНОМ месте — `web/src/data/og-manifest.json`
  в репозитории сайта. Сюда он **не переписывается**: второй писатель по тому же факту
  завтра разъедется с первым.

## Проверка целостности

```bash
cd og && sha256sum -c SHA256SUMS.txt
```

## Опись — 29 карточек, 2037792 байт (1990.0 КБ)

| файл | пиксели | байт | sha256 |
|---|---|---|---|
| `channels/og-channel-facebook.jpg` | 1200×630 | 39556 | `76081ddf849fa842d052bb63a5cb6df5b1b5f64ce9db6d92568cce549ce3da60` |
| `channels/og-channel-google-business-profile.jpg` | 1200×630 | 55591 | `779bba36f0990e77d29cbc65cf00ccf6f608f14f5911954932922d4887b28309` |
| `channels/og-channel-instagram.jpg` | 1200×630 | 42734 | `2269f176ebb13084a4e13fd0212b0b443a3aa3716dc160f1a419ac16eeda3e54` |
| `channels/og-channel-telegram.jpg` | 1200×630 | 38494 | `c5de974164c6ab52956157b7e7f113114ead1e6ae79ee314af2bb40f19e05057` |
| `channels/og-channel-tiktok.jpg` | 1200×630 | 41347 | `3473f4a11af2da81912c6e96a6fa8b6ee1c2f820fa2d8f470dcff2bf253311d6` |
| `channels/og-channel-whatsapp-business.jpg` | 1200×630 | 52207 | `99163a38c8c7b65dbb04e05258e46529fc2abaa9e8eea814b6830f01d784dadd` |
| `channels/og-channel-youtube.jpg` | 1200×630 | 44755 | `3ab996676cf9b7fda46e7f5980fde8389bae0f32c7d0f829436c0335b47e67be` |
| `og-blog-ai-already-answers.jpg` | 1200×630 | 180233 | `f39e5d46371791749ad6e78104e4c43bd575d2cd60473613a84182bd2404cb1f` |
| `og-blog-bl1.jpg` | 1200×630 | 53778 | `58853631c319d6989e63601ccc6ba34509e28c54ffefa723a018027c2d681864` |
| `og-blog-first-employee.jpg` | 1200×630 | 80961 | `550797ab99ac20541247f8506b5cfad8132b1af0cb2f1669a17d8042bdb640e2` |
| `og-blog-who-was-watching.jpg` | 1200×630 | 124121 | `eb9a5d58dd2c69ce88e34ea0162b83e8e518e248eecebfc42a2f617e86b3b51d` |
| `og-business.jpg` | 1200×630 | 58145 | `2deb24ae0dd81a49f8a91d30a5be5ab21643725156d3b28feed72ac34cd5565f` |
| `og-easy-setup.jpg` | 1200×630 | 62543 | `8c9e0c96784229a890993079b40b8b090de207e1d2307dbee6d4acb14633caa4` |
| `og-home.jpg` | 1200×630 | 93435 | `6ae6e8ca6fcbb4cc38df258b87c7b27413b6d632f3b6937d341d019de7f0f891` |
| `og-partner.jpg` | 1200×630 | 40792 | `4aeef515dfd713aa4a100d0fc7197228e09620eb94ee2dcc90319e007b4a432a` |
| `og-pricing.jpg` | 1200×630 | 52201 | `1548c80e486dfa325af55f49c37bc8fac855b30cf698f02990a770685ebd879c` |
| `og-reading.jpg` | 1200×630 | 40246 | `2c6248483e84719e0f81b8ab82e4139fd4156f5863c01e873b1ef01ff45fd82d` |
| `og-share-1200x630.png` | 1200×630 | 475957 | `707d4cdda49369fb33e47e303ddc11116af66cccbbbed3611039562c5f5fb148` |
| `og-team.jpg` | 1200×630 | 90625 | `8770c2ee5ef1d595dd4baf7a648600369d8f2be733fa49a1a4a7ba3f4ac29f11` |
| `roles/og-role-administrator.jpg` | 1200×630 | 32022 | `135f09a76f2b8b0c9ce322954c397df649b6bf7f3c79bc5e2a606c1cb225aab6` |
| `roles/og-role-appointment-coordinator.jpg` | 1200×630 | 34112 | `cb6d2beaeec056a9c7967e0e9121bee8b577e89e1808443e0acc6488fe504907` |
| `roles/og-role-business-advisor.jpg` | 1200×630 | 41090 | `c0917ad567fd4c83a061c2f4d4ce681292f9b3872a331740452be7cc6f370b48` |
| `roles/og-role-customer-support-agent.jpg` | 1200×630 | 37433 | `501043599102de9c76a14f059447f5b477d201e57f515bd407b9a121f8865faf` |
| `roles/og-role-lead-qualifier.jpg` | 1200×630 | 42742 | `e6a06d7dccabc372a1a54b83dba4464999238e7eb582b4191aa93999a174e067` |
| `roles/og-role-marketing-assistant.jpg` | 1200×630 | 43972 | `f75858b638ba62b8df25ef00a66278323cdc3701a5930a97ceab6bf95d4835fe` |
| `roles/og-role-receptionist.jpg` | 1200×630 | 40578 | `f50c3b8b6bfd5800bb5a497e64ca29b9c8507f92553df0fab3b85f585be40a85` |
| `roles/og-role-sales-consultant.jpg` | 1200×630 | 32640 | `bc0cea79481b04faf01789a479bdb5020589d24b1b0f0404a57797d80729ce46` |
| `roles/og-role-smm-manager.jpg` | 1200×630 | 33538 | `ab1ab5dbd645d1893e72dfeac38e6a1b01d277ea1438597690988b550a784280` |
| `roles/og-role-video-maker.jpg` | 1200×630 | 31944 | `0d0b04111255cefc9e498dcbeb9786c61b5344617c2da061e3b74003df2cda15` |

🔴 **Все 29 карточек фактически 1200×630** — измерено из заголовков самих файлов 10.09.2026.
Формата 1200×628 в этом классе нет ни одного: 628 — это ленточный постер 1.91:1, другой предмет.

🔴 **Про «прод отдаёт другие байты».** Через CDN 17 из 29 карточек приходят меньшего размера,
чем лежат здесь. Это **не** расхождение банка с сайтом: origin отдаёт ровно эти байты
(сверено по `etag`, где вторая часть = размер файла на origin — совпал у 29 из 29),
а уменьшает их Cloudflare на выдаче (заголовок `cf-bgj: h2pri,imgq:100`).
Пиксели при этом не меняются — 1200×630 и на выдаче тоже.
Значит краулеры соцсетей забирают пережатую копию, и канон качества = файл здесь, а не в ленте.
