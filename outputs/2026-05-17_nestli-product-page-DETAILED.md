# Nestli Embrace — Детальный шаблон страницы продукта
> Shrine Theme | Каждая секция подробно
> Дата: 2026-05-17

---

# БЛОК 0 — ANNOUNCEMENT BAR (Полоска-шапка)

## Что это
Узкая полоска над навигацией. Работает 24/7 как постоянный триггер срочности или доверия.

## Визуальный вид
```
┌────────────────────────────────────────────────────────────────┐
│  🎀  FREE SHIPPING on orders ₴1500+  ·  90-Day Returns  ·  2-Year Warranty  │
└────────────────────────────────────────────────────────────────┘
```

## Точный текст (3 варианта, меняй каждые 2 недели)

**Вариант 1 — Доставка:**
```
🚚  FREE SHIPPING on orders over ₴1500  ·  Ships within 24 hours
```

**Вариант 2 — Срочность:**
```
⏰  MOTHER'S DAY SALE — 40% OFF ends Sunday  ·  Use code MOM40
```

**Вариант 3 — Доверие:**
```
🤍  Trusted by 50,000+ moms  ·  90-Day Returns  ·  2-Year Warranty
```

## Настройки в Shrine
- **Где:** Online Store → Themes → Customize → Theme settings → Announcement bar
- **Background color:** `#7D9E82` (Sage Green)
- **Text color:** `#FFFFFF` (White)
- **Font:** DM Sans, 12–13px, weight 500, letter-spacing 0.05em
- **Высота:** 36–40px
- **Показывать на:** All pages (включая product page)
- **Ссылка:** можно поставить на /policies/shipping

---

# БЛОК 1A — NAVIGATION (Навигация)

## Визуальный вид
```
┌──────────────────────────────────────────────────────────────────────────┐
│  nestli          Sling Carrier    Accessories ▼    FAQ    Track Order    🛒 │
│                                                    [SHOP ALL PRODUCTS]      │
└──────────────────────────────────────────────────────────────────────────┘
```

## Меню — точная структура

| Пункт | Куда ведёт | Тип |
|-------|-----------|-----|
| Sling Carrier | /products/nestli-embrace | Прямая ссылка |
| Accessories | выпадающий список | Dropdown |
| → Shoulder Cushion Pad | /products/shoulder-pad | — |
| → Mini Storage Bag | /products/storage-bag | — |
| FAQ | /pages/faq | Страница |
| Track Order | /apps/track (или AfterShip) | Внешнее |
| [SHOP ALL PRODUCTS] | /collections/all | Кнопка-CTA |

## Настройки в Shrine
- **Логотип:** SVG или PNG с прозрачным фоном, размер 120–160px ширина
- **Nav background:** `#FFFFFF`
- **Nav text color:** `#1A1A1A`
- **CTA кнопка:** фон `#7D9E82`, текст белый, border-radius 4px
- **Sticky nav:** включить (залипает при скролле)
- **Cart icon:** показывать счётчик товаров

---

# БЛОК 1B — MAIN PRODUCT SECTION (Основная секция продукта)

## Это самый важный блок. Всё происходит здесь.

## Визуальный вид (desktop, split 50/50)

```
┌─────────────────────────────┬──────────────────────────────────────────┐
│                             │  ⭐⭐⭐⭐⭐  3,429 reviews ↓              │
│  [THUMBNAIL 1]              │                                          │
│  [THUMBNAIL 2]              │  NESTLI EMBRACE                         │
│  [THUMBNAIL 3]    [MAIN     │  SLING CARRIER                          │
│  [THUMBNAIL 4]     IMAGE]   │                                          │
│  [THUMBNAIL 5]              │  ₴2,490  ~~₴4,150~~  [SAVE 40%]         │
│                             │                                          │
│              [🔍 Expand]    │  [For 0–4 yrs]  [Up to 20 kg]           │
│                             │                                          │
│                             │  ✓ Ergonomic single-strap design         │
│                             │  ✓ Breathable cotton-blend fabric        │
│                             │  ✓ Adjustable for moms and dads          │
│                             │                                          │
│                             │  COLOR                                   │
│                             │  ● ○ ○ ○                                │
│                             │  Black  Cream  Sage  Blush               │
│                             │                                          │
│                             │ ┌─────────────────────────────────────┐  │
│                             │ │ 🎁 Buy 1 Get 1 at 50% OFF           │  │
│                             │ │    Auto-applied at checkout.        │  │
│                             │ └─────────────────────────────────────┘  │
│                             │                                          │
│                             │ [     Add to Cart — ₴2,490.00      ]    │
│                             │                                          │
│                             │  90-Day Returns  ·  2-Year Warranty      │
│                             │                                          │
│                             │ ▼ Product Details                        │
│                             │ ▼ Shipping & Returns                     │
└─────────────────────────────┴──────────────────────────────────────────┘
```

---

## 1B-i: ГАЛЕРЕЯ (левая колонка)

### Какие фото нужны (5 штук):

| № | Описание | Ракурс | Фон |
|---|---------|--------|-----|
| 1 | Слинг лежит/висит | Студийное фото | Белый |
| 2 | Мама несёт ребёнка спереди | Lifestyle, дома | Светлый интерьер |
| 3 | Боковой вид — видно как сидит ребёнок | Lifestyle, улица | Природа/парк |
| 4 | Крупный план кольца/застёжки | Детально | Белый |
| 5 | Слинг сложен компактно (рядом с бутылкой воды для масштаба) | Студийное | Белый |

### Настройки в Shrine:
- **Media aspect ratio:** Portrait (4:5) — идеально для мобайла
- **Thumbnail position:** Left (вертикальный ряд миниатюр)
- **Enable image zoom:** YES
- **Video:** можно добавить 15-секундное видео как первый медиа-элемент

---

## 1B-ii: ЗАГОЛОВОК и РЕЙТИНГ

### Точный текст:
```
Название: NESTLI EMBRACE SLING CARRIER
Подзаголовок (если тема поддерживает): For newborns to toddlers · Hands-free comfort
```

### Рейтинг (через Loox или Judge.me):
- Показывать: ★★★★☆ 4.6  |  3,429 reviews
- Клик → скроллит к секции отзывов
- Цвет звёзд: `#D4A59A` (Blush)

### Настройки шрифта:
- **H1 (название):** DM Serif Display, 36px desktop / 28px mobile, Regular
- **Рейтинг текст:** DM Sans, 13px, `#6B6B6B`

---

## 1B-iii: ЦЕНА

### Отображение:
```
₴2,490.00    ~~₴4,150.00~~    [SAVE 40%]
```

### Настройки:
- **Актуальная цена:** DM Sans, 26px, weight 600, `#1A1A1A`
- **Перечёркнутая цена:** DM Sans, 18px, weight 400, `#9B9B9B`, strikethrough
- **Badge "SAVE 40%":** фон `#7D9E82`, текст белый, 12px, uppercase, border-radius 4px
- **Сравнительная цена** устанавливается в Shopify через поле "Compare at price"

---

## 1B-iv: FEATURE PILLS (Таблетки-характеристики)

### Вид:
```
[ For 0–4 yrs ]   [ Up to 20 kg ]
```

### Как сделать в Shrine:
- Если тема не поддерживает — добавить через Custom HTML block или metafields
- CSS стиль: border 1px solid `#7D9E82`, color `#7D9E82`, border-radius 20px, padding 6px 14px, DM Sans 13px

---

## 1B-v: FEATURE BULLETS (Буллеты преимуществ)

### Точный текст:
```
✓  Ergonomic single-strap design — no back strain
✓  Breathable cotton-blend fabric — safe for sensitive skin
✓  Adjustable for both parents — fits chest 75–130 cm
```

### Настройки:
- **Иконка ✓:** цвет `#7D9E82`
- **Текст:** DM Sans, 14–15px, weight 400, `#1A1A1A`
- **Жирное слово** перед тире — weight 600

---

## 1B-vi: COLOR SWATCHES (Выбор цвета)

### Варианты:
| Название | Hex цвета кружка |
|----------|-----------------|
| Black | `#1A1A1A` |
| Cream | `#FAF6EF` (с border `#D4A59A`) |
| Sage | `#7D9E82` |
| Blush | `#D4A59A` |

### Настройки в Shopify:
- Создать Product variants → Option: "Color"
- В Shrine: включить Color swatches в Product form settings
- Размер кружка: 28×28px, border-radius 50%
- Active state: border 2px solid `#1A1A1A`

---

## 1B-vii: PROMO BANNER (внутри формы)

### Вид:
```
┌─────────────────────────────────────────────────────────┐
│  🎁  Buy 1 Get 1 at 50% OFF                             │
│       Discount auto-applied at checkout.                │
└─────────────────────────────────────────────────────────┘
```

### Настройки:
- **Фон:** `#FAF6EF` (Cream)
- **Border:** 1px solid `#D4A59A` (Blush)
- **Иконка 🎁:** 20px
- **Заголовок:** DM Sans, 14px, weight 600, `#1A1A1A`
- **Подпись:** DM Sans, 13px, weight 300, `#6B6B6B`
- **Реализация:** через Shrine "Product badges" или Custom HTML в описании

---

## 1B-viii: CTA КНОПКА

### Вид:
```
[        Add to Cart — ₴2,490.00        ]
```

### Настройки:
- **Фон:** `#7D9E82` (Sage Green)
- **Текст:** `#FFFFFF`, DM Sans, 15px, weight 600, uppercase, letter-spacing 0.08em
- **Высота:** 52–56px (крупная, уверенная)
- **Border-radius:** 6px
- **Hover:** фон темнее `#5C7A61`, transition 0.2s ease
- **Ширина:** 100% (полная ширина правой колонки)
- **Динамическая цена:** обновляется при смене варианта

---

## 1B-ix: TRUST LINE (под кнопкой)

### Вид:
```
90-Day Returns  ·  2-Year Warranty  ·  Secure Checkout 🔒
```

### Настройки:
- **Текст:** DM Sans, 12px, weight 400, `#6B6B6B`, center
- **Отступ сверху:** 10px от кнопки

---

## 1B-x: АККОРДЕОНЫ

### Аккордеон 1 — "Product Details"

**Заголовок:** `Product Details`

**Содержимое:**
```
The Nestli Embrace is made from a premium 80% cotton / 20% polyester blend —
soft enough for newborn skin, durable enough for daily use.

WHAT'S INCLUDED:
· Nestli Embrace Sling Carrier
· Newborn head support insert
· Compact carry pouch

MATERIALS:
· Outer shell: 80% Cotton / 20% Polyester
· Shoulder pad: High-density foam
· Ring: Aircraft-grade aluminum

CARE INSTRUCTIONS:
Machine washable — 30°C gentle cycle. Air dry.
Do not tumble dry.
```

### Аккордеон 2 — "Shipping & Returns"

**Заголовок:** `Shipping & Returns`

**Содержимое:**
```
SHIPPING:
· Standard: 7–14 business days (FREE on orders ₴1500+)
· Express: 3–7 business days (₴350)
· All orders shipped within 24 hours of purchase

RETURNS:
· 90-day return window — no questions asked
· Item must be in original condition
· Contact: support@nestli.com to start your return
· Refund processed within 3–5 business days
```

### Настройки аккордеонов в Shrine:
- **Где:** Main product → Product information → Collapsible tab (×2)
- **Border:** 1px solid `#E8E1D8`
- **Иконка раскрытия:** шеврон ↓, цвет `#7D9E82`
- **Заголовок:** DM Sans, 15px, weight 500
- **Текст внутри:** DM Sans, 14px, weight 300, line-height 1.7

---

# БЛОК 1C — IN-PAGE UPSELLS (Апсейлы внутри страницы продукта)

## Что это
Секция прямо под аккордеонами. Предлагает 2 дополнения к слингу перед тем как покупатель уйдёт к корзине.

## Визуальный вид
```
──────────────────────────────────────────────
UPGRADE YOUR CARRY COMFORT
Built-in extras that make every outing easier.

┌────────────────────────────────────────────┐
│ [IMG]   Shoulder Cushion Pad               │
│         ₴583.00                            │
│         Color: [Black ▼]       [  Add+ ]   │
└────────────────────────────────────────────┘

┌────────────────────────────────────────────┐
│ [IMG]   Mini Storage Bag                   │
│         ₴872.00                            │
│         Color: [Black ▼]       [  Add+ ]   │
└────────────────────────────────────────────┘
──────────────────────────────────────────────
```

## Точный текст заголовка:
```
Заголовок: UPGRADE YOUR CARRY COMFORT
Подзаголовок: Built-in extras that make every outing easier.
```

## Настройки:
- **Заголовок:** DM Sans, 16px, weight 600, uppercase, letter-spacing 0.08em
- **Подзаголовок:** DM Sans, 14px, weight 300, `#6B6B6B`
- **Карточка апсейла:** белый фон, border 1px solid `#E8E1D8`, border-radius 8px, padding 16px
- **Фото товара:** 64×64px, border-radius 6px
- **Кнопка [Add+]:** фон `#FAF6EF`, border 1px solid `#7D9E82`, цвет `#7D9E82`, hover → заполняется зелёным

## Как реализовать:
**Вариант A (проще):** Shopify app "Frequently Bought Together" или "Candy Rack"
**Вариант B (нативно):** Shrine поддерживает "Product upsell" block — добавить в Main product section
**Вариант C:** Custom Liquid через metafields (для разработчика)

---

# БЛОК 2 — UGC VIDEO ROW "MOM-TESTED MOM-APPROVED"

## Что это
Горизонтальный ряд из 4 вертикальных видео (9:16) с UGC — реальные мамы используют слинг. Снято в TikTok/Reels стиле. Самый конвертирующий блок после основной секции.

## Визуальный вид
```
╔══════════════════════════════════════════════════════════════════╗
║                   MOM-TESTED                                    ║
║                 MOM-APPROVED 🤍                                  ║
║                                                                  ║
║  ┌──────┐   ┌──────┐   ┌──────┐   ┌──────┐                     ║
║  │  ▶   │   │  ▶   │   │  ▶   │   │  ▶   │                     ║
║  │      │   │      │   │      │   │      │                     ║
║  │      │   │      │   │      │   │      │                     ║
║  └──────┘   └──────┘   └──────┘   └──────┘                     ║
║  "Best thing  "Tried 3   "Baby loved   "My go-to                ║
║   I bought    carriers,   it from      for grocery              ║
║   this year"  this won"   day one"     runs"                    ║
╚══════════════════════════════════════════════════════════════════╝
```
**Фон блока:** `#FAF6EF` (Cream)

## Точный текст заголовка:
```
Строка 1: MOM-TESTED
Строка 2: MOM-APPROVED 🤍
```
**Шрифт:** DM Serif Display, 32–38px, center, цвет `#1A1A1A`
**Эмодзи:** оставить, добавляет тепло (единственный раз на странице)

## Подписи под видео (4 штуки):
```
Видео 1: "Best thing I bought this year"
Видео 2: "Tried 3 carriers — this won"
Видео 3: "Baby loved it from day one"
Видео 4: "My go-to for grocery runs"
```
**Шрифт подписей:** DM Serif Display Italic, 15px, `#6B6B6B`, center

## Какие видео нужны (TikTok/Reels контент):
| # | Сценарий | Хук (первые 2 сек) |
|---|---------|-------------------|
| 1 | Мама надевает слинг за 5 секунд | "Watch how fast this goes on..." |
| 2 | Ребёнок засыпает в слинге | "He ONLY sleeps in this thing now" |
| 3 | Руки свободны — мама готовит еду | "Hands free finally 🙌" |
| 4 | Папа в слинге с ребёнком | "Even dad approved" |

## Как реализовать в Shrine:
**Вариант A — Tolstoy app (рекомендую):**
- Устанавливается за 5 минут
- Встраивает TikTok-style видео прямо на страницу
- Shopify App Store → "Tolstoy Shoppable Video"
- Вставить виджет через Shrine Custom HTML section

**Вариант B — вручную через Shrine:**
- Section: `Image with text` (4 колонки)
- Вместо изображений — вставить embed YouTube/TikTok
- Под каждым видео — текстовый блок с подписью

**Вариант C — просто фото с overlay ▶:**
- Пока нет видео — сделать lifestyle фото с кнопкой ▶ сверху
- Клик открывает TikTok/YouTube в новой вкладке

## Мобайл:
- Desktop: 4 колонки в ряд
- Mobile: горизонтальный скролл (swiper) 1.5 видео видно

---

# БЛОК 3 — HOW IT WORKS "CARRY THEM IN 5 SECONDS"

## Что это
4-шаговая инструкция с фото. Снимает главное возражение: "это сложно надеть". Показывает что слинг надевается за секунды.

## Визуальный вид
```
╔══════════════════════════════════════════════════════════════════╗
║               CARRY THEM IN 5 SECONDS ⏱                        ║
║                                                                  ║
║  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐        ║
║  │          │  │          │  │          │  │          │        ║
║  │  [Фото]  │  │  [Фото]  │  │  [Фото]  │  │  [Фото]  │        ║
║  │          │  │          │  │          │  │          │        ║
║  └──────────┘  └──────────┘  └──────────┘  └──────────┘        ║
║       1             2             3             4               ║
║  Place it       Swoop baby    Adjust the     Good to go!        ║
║  around your    in gently     strap to       You're both        ║
║  body           from below    your fit       free               ║
╚══════════════════════════════════════════════════════════════════╝
```
**Фон блока:** `#FFFFFF`

## Точный текст:

**Заголовок:**
```
CARRY THEM IN 5 SECONDS ⏱
```
DM Sans, 28–32px, uppercase, letter-spacing 0.1em, center, weight 500

**4 шага:**

| Шаг | Номер | Заголовок | Описание |
|-----|-------|-----------|---------|
| 1 | `01` | Place It Around | Loop the sling over one shoulder and let it fall across your body |
| 2 | `02` | Swoop Baby In | Lift your baby and slide them into the pouch from below |
| 3 | `03` | Adjust The Strap | Pull the ring to tighten until baby sits snug at your chest |
| 4 | `04` | Good To Go! | Both hands free — ready to go anywhere |

## Стиль текста:
- **Номер `01`:** DM Serif Display, 40px, `#D4A59A` (Blush), — декоративный
- **Заголовок шага:** DM Sans, 16px, weight 600, `#1A1A1A`
- **Описание:** DM Sans, 14px, weight 300, `#6B6B6B`, line-height 1.6

## Фотографии для 4 шагов:
- Квадратный формат 1:1, светлый фон (белый или cream)
- Единый стиль обработки: нейтральные тёплые тона
- Можно взять с AliExpress у того же поставщика или снять самому

## Настройки в Shrine:
- **Section:** `Multicolumn` — 4 колонки
- **Image aspect ratio:** Square (1:1)
- **Alignment:** Center
- **Номера шагов:** добавить через Custom liquid или Caption field
- **Mobile:** 2×2 сетка (не горизонтальный скролл)

---

# БЛОК 4 — PAIN POINTS "IT'S TIME TO UPGRADE"

## Что это
Секция "до/после" без явного упоминания конкурентов. Называет боли которые покупатель уже чувствовал с другими слингами/носителями — и показывает что Nestli решает каждую.

## Визуальный вид
```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║                   IT'S TIME TO UPGRADE                          ║
║          To a lighter, more comfortable way to carry.           ║
║                                                                  ║
║  ┌────────────────────┐   ○  Back & Hip Pain                    ║
║  │                    │      Say goodbye to the discomfort of   ║
║  │    [Lifestyle      │      carrying your toddler all day.     ║
║  │     photo:         │                                          ║
║  │     мама с         │   ○  Arm Fatigue                        ║
║  │     ребёнком,      │      Say goodbye to tired arms from     ║
║  │     на улице,      │      extended carrying sessions.        ║
║  │     улыбается]     │                                          ║
║  │                    │   ○  Bulky Carriers                     ║
║  │                    │      Ditch carriers that weigh you      ║
║  │                    │      down and take up half your bag.    ║
║  │                    │                                          ║
║  └────────────────────┘   ○  Shoulder Pain                     ║
║                              Our wide strap spreads your        ║
║                              child's weight evenly.             ║
╚══════════════════════════════════════════════════════════════════╝
```
**Фон блока:** `#FAF6EF` (Cream)

## Точный текст:

**Заголовок:**
```
IT'S TIME TO UPGRADE
```
DM Serif Display, 34px, center, `#1A1A1A`

**Подзаголовок:**
```
To a lighter, more comfortable way to carry.
```
DM Sans, 16px, weight 300, `#6B6B6B`, center

**4 боли (справа):**

```
БОЛЬ 1:
Заголовок: Back & Hip Pain
Текст: Say goodbye to the discomfort of carrying your toddler 
       all day. Our ergonomic strap distributes weight evenly 
       so your back stays happy.

БОЛЬ 2:
Заголовок: Arm Fatigue
Текст: No more tired, aching arms. The Nestli Embrace sits 
       on your shoulder — not in your hands.

БОЛЬ 3:
Заголовок: Bulky Carriers
Текст: Ditch the carriers that weigh you down. The Nestli 
       Embrace folds into a compact pouch the size of your fist.

БОЛЬ 4:
Заголовок: Shoulder Pain
Текст: Our 8cm wide padded strap spreads your child's weight 
       across your shoulder — not just one point.
```

**Иконки:** кружки ○ (пустые) которые становятся ◉ при hover, или checkmarks ✓
**Цвет иконок:** `#7D9E82` (Sage Green)
**Заголовок боли:** DM Sans, 16px, weight 600, `#1A1A1A`
**Текст боли:** DM Sans, 14px, weight 300, `#6B6B6B`, line-height 1.7

## Фото (левая сторона):
- Вертикальное 3:4 или квадрат 1:1
- Мама с ребёнком в слинге — outdoor, natural light
- Улыбается, руки делают что-то полезное (кофе, телефон, сумка)
- Тёплые нейтральные тона

## Настройки в Shrine:
- **Section:** `Image with text`
- **Image position:** Left (фото слева, текст справа)
- **Desktop layout:** 50/50
- **Контент блоки (×4):** добавить через "Text with icon" или list items

---

# БЛОК 5 — SOCIAL PROOF "TRUSTED BY 50,000+ MOMS"

## Что это
Карусель из 4 отзывов с фото покупателей. Самый мощный доверительный блок. Показывает реальных людей, реальные истории.

## Визуальный вид
```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║             TRUSTED BY 50,000+ MOMS                             ║
║                                                                  ║
║  ┌──────────────┐ ┌──────────────┐ ┌──────────────┐ ┌────────┐  ║
║  │ [Фото мамы  ]│ │[Фото семьи  ]│ │[Фото папы   ]│ │[Фото  ]│  ║
║  │  с ребёнком ]│ │  на природе ]│ │  с ребёнком ]│ │  мамы ]│  ║
║  │              │ │              │ │              │ │        │  ║
║  │ ⭐⭐⭐⭐⭐     │ │ ⭐⭐⭐⭐⭐     │ │ ⭐⭐⭐⭐⭐     │ │⭐⭐⭐⭐⭐│  ║
║  │ "Travel      │ │ "This is my  │ │ "Dad         │ │"Worth  │  ║
║  │  Essential"  │ │  toddler     │ │  Approved"   │ │ The    │  ║
║  │              │ │  must-have"  │ │              │ │ Money" │  ║
║  │ Sarah M.     │ │ Stephanie K. │ │ Rachel B.    │ │Grace T.│  ║
║  │ California   │ │ Oregon       │ │ Boston       │ │Tampa   │  ║
║  └──────────────┘ └──────────────┘ └──────────────┘ └────────┘  ║
║                                                                  ║
║                    ← · · · · →                                   ║
╚══════════════════════════════════════════════════════════════════╝
```
**Фон блока:** `#FFFFFF`

## Точный текст заголовка:
```
TRUSTED BY 50,000+ MOMS
```
DM Sans, 28px, uppercase, letter-spacing 0.1em, center, weight 500

## 4 карточки отзывов (готовый текст):

**Карточка 1:**
```
Заголовок: "Travel Essential"
Отзыв: "We flew across Europe and used this the whole trip.
        It packs smaller than a water bottle — and we used it 
        the entire time."
Имя: Emma C.
Город: California, US
```

**Карточка 2:**
```
Заголовок: "Velcro Baby Approved"
Отзыв: "I cling-er here and my son adores it. It lets me cook 
        and clean while keeping him happy on my hip. This is 
        our everyday essential now."
Имя: Stephanie K.
Город: Oregon, US
```

**Карточка 3:**
```
Заголовок: "Dad Approved"
Отзыв: "My husband refused all our other carriers but loves 
        this one. Says it's not girly and not complicated. 
        He even packed it for our last weekend trip."
Имя: Rachel B.
Город: Boston, US
```

**Карточка 4:**
```
Заголовок: "Worth The Money"
Отзыв: "Went through 3 cheap knockoffs before getting this. 
        Should have bought it first. The quality difference 
        is night and day."
Имя: Grace T.
Город: Tampa, US
```

## Настройки карточек:
- **Фото:** квадрат 1:1, 280×280px minimum, реальные lifestyle фото
- **Звёзды:** `#D4A59A` (Blush), 16px
- **Заголовок карточки:** DM Serif Display Italic, 18px, `#1A1A1A`
- **Текст отзыва:** DM Sans, 14px, weight 300, `#6B6B6B`, line-height 1.6, в кавычках ""
- **Имя:** DM Sans, 13px, weight 500, `#1A1A1A`
- **Город:** DM Sans, 12px, `#9B9B9B`
- **Фон карточки:** `#FFFFFF`
- **Border:** 1px solid `#E8E1D8`
- **Border-radius:** 12px

## Навигация карусели:
- Стрелки ← → : цвет `#7D9E82`
- Точки-индикаторы: активная `#7D9E82`, неактивная `#E8E1D8`
- Auto-play: НЕТ (пусть пользователь сам листает)

## Настройки в Shrine:
- **Section:** `Testimonials`
- **Layout:** Carousel / Grid (4 в ряд на desktop, 1 на mobile)
- **Enable image:** YES (фото покупателя)
- **Rating:** YES

---

# БЛОК 6 — TRUST BADGES (3 иконки)

## Что это
Горизонтальная полоска из 3 иконок с подписями. Снимает последние возражения перед скроллом к FAQ и отзывам.

## Визуальный вид
```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║    🚚                      🤍                      ↩            ║
║    Fast Shipping       50,000+ Happy           90-Day           ║
║    & Easy Returns      Moms Worldwide       Money-Back          ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```
**Фон блока:** `#7D9E82` (Sage Green)
**Все тексты:** `#FFFFFF` (White)

## Точный текст:

| Иконка | Заголовок | Подпись |
|--------|-----------|---------|
| 🚚 (или SVG грузовик) | Fast Shipping & Easy Returns | Free on orders over ₴1500 |
| 🤍 (или SVG сердце) | 50,000+ Happy Moms | Worldwide |
| ↩ (или SVG стрелка) | 90-Day Money-Back | No questions asked |

## Настройки текста:
- **Иконка:** 32–40px, белая (SVG лучше emoji)
- **Заголовок:** DM Sans, 16px, weight 600, `#FFFFFF`, uppercase
- **Подпись:** DM Sans, 13px, weight 300, `rgba(255,255,255,0.8)`
- **Отступ между колонками:** равный

## Настройки в Shrine:
- **Section:** `Multicolumn` — 3 колонки
- **Фон секции:** `#7D9E82`
- **Иконки:** добавить как image (SVG) или использовать built-in icon picker Shrine
- **Выравнивание:** Center (по центру)
- **Padding:** 40px top/bottom

## SVG иконки (вставить в Custom HTML):
```html
<!-- Грузовик -->
<svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="white" viewBox="0 0 24 24">
  <path d="M20 8h-3V4H3c-1.1 0-2 .9-2 2v11h2c0 1.66 1.34 3 3 3s3-1.34 3-3h4c0 1.66 1.34 3 3 3s3-1.34 3-3h2v-5l-3-4zm-.5 1.5l1.96 2.5H17V9.5h2.5zM6 18c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1zm11 0c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1z"/>
</svg>

<!-- Сердце -->
<svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="white" viewBox="0 0 24 24">
  <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/>
</svg>

<!-- Возврат -->
<svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="white" viewBox="0 0 24 24">
  <path d="M12 5V1L7 6l5 5V7c3.31 0 6 2.69 6 6s-2.69 6-6 6-6-2.69-6-6H4c0 4.42 3.58 8 8 8s8-3.58 8-8-3.58-8-8-8z"/>
</svg>
```

---

# БЛОК 7 — FAQ (Часто задаваемые вопросы)

## Что это
6 аккордеонов с вопросами которые покупатель задаёт ДО покупки. Снимает возражения у тех кто почти решился.

## Визуальный вид
```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║              FREQUENTLY ASKED QUESTIONS                         ║
║                                                                  ║
║  ┌──────────────────────────────────────────────────────────┐   ║
║  │  How does the Nestli Embrace Carrier work?            ↓  │   ║
║  └──────────────────────────────────────────────────────────┘   ║
║  ┌──────────────────────────────────────────────────────────┐   ║
║  │  What age and weight is it suitable for?              ↓  │   ║
║  └──────────────────────────────────────────────────────────┘   ║
║  ┌──────────────────────────────────────────────────────────┐   ║
║  │  Will it fit my body type?                            ↓  │   ║
║  └──────────────────────────────────────────────────────────┘   ║
║  ┌──────────────────────────────────────────────────────────┐   ║
║  │  Will the strap hurt my shoulder or neck?             ↓  │   ║
║  └──────────────────────────────────────────────────────────┘   ║
║  ┌──────────────────────────────────────────────────────────┐   ║
║  │  How long does shipping take?                         ↓  │   ║
║  └──────────────────────────────────────────────────────────┘   ║
║  ┌──────────────────────────────────────────────────────────┐   ║
║  │  What is your refund and return policy?               ↓  │   ║
║  └──────────────────────────────────────────────────────────┘   ║
╚══════════════════════════════════════════════════════════════════╝
```
**Фон блока:** `#FFFFFF`

## Полные тексты всех 6 FAQ:

---

**Q1: How does the Nestli Embrace Carrier work?**

A: The Nestli Embrace is a ring sling carrier. Simply loop it over one shoulder so it sits diagonally across your chest. Lift your baby and slide them into the fabric pouch. Pull the loose end of the strap through the ring to tighten until baby is snug and upright at your chest level. That's it — takes under 10 seconds once you've done it once.

---

**Q2: What age and weight is it suitable for?**

A: The Nestli Embrace supports babies from newborn (0 months) through 4 years old, up to 20 kg (44 lbs). For newborns under 4 months, use the included head support insert to keep baby's head properly supported. Always ensure baby's chin is off their chest and airway is clear.

---

**Q3: Will it fit my body type?**

A: Yes. The adjustable strap fits chest sizes from 75 cm to 130 cm, covering XS through 3XL. It works equally well for moms and dads. One carrier — every caregiver in the family. If you're between sizes, size up and tighten with the ring.

---

**Q4: Will the strap hurt my shoulder or neck?**

A: The Nestli Embrace is designed with an 8 cm wide padded shoulder strap that distributes your baby's weight across your shoulder and upper back — not just one point. Most parents report zero discomfort even after 2–3 hours of continuous wear. If you feel strain, the carrier likely needs adjustment — check that baby sits at chest height, not stomach level.

---

**Q5: How long does shipping take?**

A: We ship all orders within 24 hours of purchase.

· **Standard shipping:** 7–14 business days (FREE on orders ₴1500+)
· **Express shipping:** 3–7 business days (₴350)

You'll receive a tracking number by email as soon as your order ships. Track your order anytime at [Track My Order link].

---

**Q6: What is your refund and return policy?**

A: We offer a **90-day no-questions-asked return policy**. If you're not 100% happy with your Nestli Embrace for any reason — the fit, the color, anything — contact us at support@nestli.com and we'll arrange a full refund or free exchange.

Items must be returned in original condition. Refund is processed within 3–5 business days of receiving your return.

---

## Настройки в Shrine:
- **Section:** `Collapsible content`
- **Заголовок секции:** "FREQUENTLY ASKED QUESTIONS", DM Sans, 26px, uppercase, center
- **Стиль аккордеона:** Row (каждый вопрос — отдельная строка)
- **Иконка открытия:** шеврон ↓ → ↑, цвет `#7D9E82`
- **Текст вопроса:** DM Sans, 16px, weight 500, `#1A1A1A`
- **Текст ответа:** DM Sans, 14–15px, weight 300, `#6B6B6B`, line-height 1.75
- **Border между вопросами:** 1px solid `#E8E1D8`
- **Открыт по умолчанию:** Q1 (How does it work)

---

# БЛОК 8 — REVIEWS SECTION (Полный блок отзывов)

## Что это
Полная секция с реальными отзывами покупателей, звёздами и фотографиями. Реализуется через приложение Loox или Judge.me.

## Визуальный вид
```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║             SEE WHAT OTHER MOMS THINK                           ║
║                                                                  ║
║  ★★★★☆  4.6 out of 5    |    3,429 reviews    [Write a Review]  ║
║                                                                  ║
║  [Only with Photos ▼]                                           ║
║                                                                  ║
║  ┌────────────────────────────────────────────────────────┐     ║
║  │ [J]  Janice L.           ★★★★★          2024-08-30     │     ║
║  │      "My husband doesn't like the usual chest carriers │     ║
║  │       but he's more than happy to use this one :)"     │     ║
║  │      [Фото: папа с ребёнком в слинге на улице]         │     ║
║  └────────────────────────────────────────────────────────┘     ║
║                                                                  ║
║  ┌────────────────────────────────────────────────────────┐     ║
║  │ [D]  Diana M.            ★★★★★          2024-08-03     │     ║
║  │      "We went on a family trip and this carrier was    │     ║
║  │       our saviour — we could switch between wearers"   │     ║
║  │      [Lifestyle фото]                                  │     ║
║  └────────────────────────────────────────────────────────┘     ║
║                                                                  ║
║                    [ Load more reviews ]                         ║
╚══════════════════════════════════════════════════════════════════╝
```
**Фон блока:** `#FAFAFA`

## Заголовок:
```
SEE WHAT OTHER MOMS THINK
```
DM Serif Display, 32px, center, `#1A1A1A`

## Настройки стиля:
- **Звёзды (общий рейтинг):** `#D4A59A` (Blush), 22px
- **Кнопка "Write a Review":** outlined, border `#7D9E82`, text `#7D9E82`, hover → заполняется
- **Аватар покупателя:** круглый, 44px, фон `#FAF6EF`, инициал `#7D9E82`
- **Имя покупателя:** DM Sans, 15px, weight 600
- **Текст отзыва:** DM Sans, 14px, weight 300, line-height 1.7, `#1A1A1A`
- **Дата:** DM Sans, 12px, `#9B9B9B`
- **Фото к отзыву:** квадрат 80×80px, border-radius 8px, клик → увеличивается

## Как настроить:

**Шаг 1 — Установить приложение:**
- Shopify App Store → Judge.me Product Reviews (бесплатно) или Loox ($9.99/мес)
- Judge.me лучше для старта — бесплатный план имеет все нужные функции

**Шаг 2 — Импортировать отзывы с AliExpress:**
- В Judge.me: Reviews → Import → AliExpress
- Вставить URL товара с AliExpress
- Выбрать: только отзывы с фото, минимум 4 звезды
- Перевести с китайского (приложение делает автоматически)

**Шаг 3 — Настроить виджет:**
- Judge.me → Settings → Widget
- Primary color: `#7D9E82`
- Font: inherit (подхватит DM Sans из темы)
- Review count to show: 8 (потом "Load more")
- Show reviewer photos: YES
- Sort default: Most recent

**Шаг 4 — Добавить на страницу:**
- Shrine → Product page → Add section → Apps → Judge.me
- Или вставить через Custom Liquid: `{% render 'judgeme_widgets', ... %}`

---

# БЛОК 9 — YOU MIGHT ALSO LOVE (Перекрёстные продажи)

## Что это
Секция с 3 дополнительными товарами в самом низу страницы — для тех кто долистал. Последний шанс добавить что-то в корзину.

## Визуальный вид
```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║                  YOU MIGHT ALSO LOVE                            ║
║                                                                  ║
║  ┌───────────────┐   ┌───────────────┐   ┌───────────────┐      ║
║  │               │   │               │   │               │      ║
║  │  [Фото        │   │  [Фото        │   │  [Фото        │      ║
║  │   Shoulder    │   │   Storage     │   │   Baby        │      ║
║  │   Cushion]    │   │   Bag]        │   │   Bib Set]    │      ║
║  │               │   │               │   │               │      ║
║  │ Shoulder      │   │ Mini Storage  │   │ Organic Bib   │      ║
║  │ Cushion Pad   │   │ Bag           │   │ Set (3-pack)  │      ║
║  │               │   │               │   │               │      ║
║  │ ₴583.00       │   │ ₴872.00       │   │ ₴490.00       │      ║
║  │ [Add to Cart] │   │ [Add to Cart] │   │ [Add to Cart] │      ║
║  └───────────────┘   └───────────────┘   └───────────────┘      ║
╚══════════════════════════════════════════════════════════════════╝
```
**Фон блока:** `#FAF6EF` (Cream)

## Точный текст заголовка:
```
YOU MIGHT ALSO LOVE
```
DM Serif Display, 30px, center, `#1A1A1A`

## 3 товара для этой секции:

| Товар | Цена | AliExpress | Назначение |
|-------|------|-----------|-----------|
| Shoulder Cushion Pad | ₴583 | Накладка для ремня | Comfort upsell |
| Mini Storage Bag | ₴872 | Сумочка-органайзер | Convenience upsell |
| Organic Baby Bib Set (3шт) | ₴490 | Набор слюнявчиков | Baby care cross-sell |

## Настройки карточек товаров:
- **Фото:** квадрат 1:1, светлый фон
- **Имя товара:** DM Sans, 15px, weight 500, `#1A1A1A`
- **Цена:** DM Sans, 16px, weight 600, `#1A1A1A`
- **Кнопка "Add to Cart":** полная ширина карточки, фон `#7D9E82`, текст белый
- **Hover на карточке:** лёгкая тень `box-shadow: 0 4px 16px rgba(0,0,0,0.08)`

## Настройки в Shrine:
- **Section:** `Featured collection` или `Product recommendations`
- **Коллекция:** создать коллекцию "Accessories" и добавить туда 3 товара
- **Products to show:** 3
- **Columns desktop:** 3
- **Columns mobile:** 2 (с горизонтальным скроллом)
- **Enable quick add:** YES (кнопка Add to Cart прямо из карточки)

---

# ИТОГОВЫЙ ПОРЯДОК БЛОКОВ (чеклист для Shrine)

```
☐  БЛОК 0   Announcement Bar           — Theme settings → Announcement bar
☐  БЛОК 1A  Navigation                 — Header (настроить меню)
☐  БЛОК 1B  Main Product Section       — Встроено в Shrine (Media + Form)
☐  БЛОК 1C  In-page Upsells            — App: Candy Rack / Shrine upsell block
☐  БЛОК 2   UGC Video Row              — App: Tolstoy / Custom HTML
☐  БЛОК 3   How It Works (4 шага)      — Section: Multicolumn
☐  БЛОК 4   Pain Points                — Section: Image with text
☐  БЛОК 5   Testimonials Carousel      — Section: Testimonials
☐  БЛОК 6   Trust Badges               — Section: Multicolumn (зелёный фон)
☐  БЛОК 7   FAQ (6 вопросов)           — Section: Collapsible content
☐  БЛОК 8   Full Reviews               — App: Judge.me / Loox widget
☐  БЛОК 9   You Might Also Love        — Section: Featured collection
```

---

# ПРИЛОЖЕНИЯ (Apps) которые нужны

| App | Цена | Для чего |
|-----|------|---------|
| Judge.me | Бесплатно | Отзывы с фото, импорт с AliExpress |
| Tolstoy | Бесплатно (до 2 видео) | UGC видео на странице |
| Candy Rack | $29.99/мес | In-page upsells (Блок 1C) |
| AfterShip | Бесплатно | Track My Order страница |

*Candy Rack можно заменить бесплатным "Frequently Bought Together" от Tikfoo — менее красиво но работает.*

---

*Файл создан: 2026-05-17*
*Тема: Shrine (Shopify)*
*Конкурент-референс: senarah.com*
