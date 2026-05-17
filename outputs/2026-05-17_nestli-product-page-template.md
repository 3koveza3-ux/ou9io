# Nestli — Product Page Template & Font System
> Shrine Theme | Hero Product: Nestli Embrace Sling Carrier
> Based on Senarah competitor page analysis

---

## ШРИФТЫ

### Рекомендация: Комбинация A — "Elegant DTC"

| Роль | Шрифт | Стиль | Где использовать |
|------|--------|-------|-----------------|
| **Заголовки H1–H2** | `DM Serif Display` | Regular, Italic | Название продукта, секционные заголовки |
| **Тело / подзаголовки** | `DM Sans` | 300–500 | Описание, буллеты, FAQ, цена |
| **Акцент / quotes** | `DM Serif Display Italic` | Italic | Цитаты отзывов, слоган |

**Почему DM Serif Display + DM Sans:**
- DM Serif — мягкий, женственный серифный шрифт. Не кричащий, не детский
- DM Sans — его "сестринский" гротеск. Они созданы парой — идеальная читабельность
- Оба бесплатны на Google Fonts
- Сочетание Serif заголовок + Sans тело = стандарт для premium DTC брендов (Allbirds, Mejuri, Baboon To The Moon)

**Как добавить в Shrine:**
1. Shopify Admin → Online Store → Themes → Customize
2. Theme settings (иконка шестерёнки) → Typography
3. Heading font: `DM Serif Display`
4. Body font: `DM Sans`
5. Base font size: 16px

**Размеры шрифтов (CSS переменные Shrine):**
```
H1 product title: 32–40px, weight 400 (Regular)
H2 section title: 26–32px, uppercase + letter-spacing 0.08em
H3 subheading: 18–22px
Body text: 15–16px, weight 300–400, line-height 1.6
Price: 22–26px, weight 500 (DM Sans Medium)
CTA button text: 14–15px, weight 500, uppercase, letter-spacing 0.06em
```

---

## СТРУКТУРА СТРАНИЦЫ ПРОДУКТА

Полная структура в том же порядке что у Senarah — адаптирована под Nestli.
Всего **11 блоков** сверху вниз.

---

### БЛОК 0 — Announcement Bar (Шапка-полоска)

```
🎀 FREE SHIPPING on orders over ₴1500 · 90-Day Returns · 2-Year Warranty
```
**Shrine:** Theme settings → Announcement bar
**Цвет фона:** `#7D9E82` (Sage Green)
**Цвет текста:** `#FFFFFF`
**Шрифт:** DM Sans, 13px, weight 500, uppercase

---

### БЛОК 1 — Product Section (Основная секция, above the fold)

**Левая колонка — галерея:**
- Основное изображение: слинг на белом фоне (4:5 ratio, мин 1200×1500px)
- 5 миниатюр снизу:
  1. Слинг на белом фоне (главное)
  2. Мама с ребёнком в слинге — lifestyle front view
  3. Lifestyle side view (видно как сидит ребёнок)
  4. Крупный план застёжки/ремня
  5. Слинг в сумке/компактно сложен

**Правая колонка — форма:**

```
⭐⭐⭐⭐⭐  [3,429 reviews]          ← Stars (цвет #D4A59A / Blush)

NESTLI EMBRACE SLING CARRIER       ← H1, DM Serif Display, 36px

₴2,490.00  ~~₴4,150.00~~  SAVE 40% ← Price, badge зелёный #7D9E82

[For 0–4 yrs]  [Up to 20 kg]       ← Feature pills (outlined, #7D9E82)

✓  Ergonomic single-strap design   ← Feature bullets
✓  Breathable, soft cotton-blend fabric
✓  Adjustable for both parents

COLOR                               ← Color section label
● ○ ○ ○  [Black] [Cream] [Sage] [Blush]  ← Color swatches

┌─────────────────────────────────────────┐
│  🎁  Buy 1 Get 1 at 50% OFF             │  ← Promo banner
│  Discount auto-applied at checkout.     │  цвет фона #FAF6EF
└─────────────────────────────────────────┘

[  Add to Cart — ₴2,490  ]          ← CTA button, полная ширина
                                      фон #7D9E82, текст белый
                                      hover: #5C7A61

90-Day Returns  ·  2-Year Warranty  ← Микро-доверие под кнопкой

▼ Product Details                   ← Аккордеон
▼ Shipping & Returns

──────────────────────────────────

UPGRADE YOUR CARRY COMFORT          ← In-page upsell секция
Built-in extras for every outing.

┌────────────────────────────────────┐
│ [img]  Shoulder Cushion Pad        │  ← Upsell 1
│        ₴583.00   [Color ▼]  [Add+] │
└────────────────────────────────────┘
┌────────────────────────────────────┐
│ [img]  Mini Storage Bag            │  ← Upsell 2
│        ₴872.00   [Color ▼]  [Add+] │
└────────────────────────────────────┘
```

**Shrine настройки:**
- Section: `Main product` (встроенная секция)
- Включить: Product media, Product form, upsell block (через app или метаполя)
- Media aspect ratio: Portrait (4:5)

---

### БЛОК 2 — UGC Video Row "MOM-APPROVED"

```
                MOM-TESTED
              MOM-APPROVED 🤍

[▶ Video 1]  [▶ Video 2]  [▶ Video 3]  [▶ Video 4]
"Best thing   "Tried 3     "Baby loves  "My go-to
 I bought     carriers,    it instantly"  for grocery
 this year"   this won"               runs"
```

**Shrine block:** `Image with text` или кастомный `Video row`
**Заголовок:** DM Serif Display, 28px, center, letter-spacing 0.1em, UPPERCASE
**Видео:** TikTok/Reels UGC — embed через Tolstoy или MBC Reviews app
**Фон блока:** `#FAF6EF` (Cream)
**Соотношение сторон видео:** 9:16 (вертикальное), 4 в ряд

---

### БЛОК 3 — How It Works "5 SECONDS TO CARRY"

```
         CARRY THEM IN 5 SECONDS ⏱

[Photo 1]      [Photo 2]      [Photo 3]      [Photo 4]
Place around   Swoop baby in  Adjust strap   Good to go!
your body      gently         to your fit
```

**Shrine block:** `Image with text` × 4 или `Multicolumn`
**Фон:** белый `#FFFFFF`
**Заголовок:** H2, uppercase, letter-spacing 0.1em
**Подписи:** DM Sans 14px, weight 400, center

---

### БЛОК 4 — Pain Points "TIME TO UPGRADE"

```
              IT'S TIME TO UPGRADE
         To a lighter, more comfortable carrier.

[Lifestyle photo    ]   ○  Back & Hip Pain
[мама с ребёнком в  ]      Say goodbye to the pain of carrying toddlers
[слинге, outdoor    ]
                        ○  Arm Fatigue
                           Say goodbye to tired arms

                        ○  Bulky Carriers
                           Ditch carriers that weigh you down

                        ○  Shoulder Pain
                           Our strap design spreads weight evenly
```

**Shrine block:** `Image with text` (image left, content right)
**Иконки:** ✓ или кружки (можно unicode ○ / ◉)
**Цвет иконок:** `#7D9E82`
**Фон:** `#FAF6EF`

---

### БЛОК 5 — Social Proof Counter "TRUSTED BY"

```
        TRUSTED BY 50,000+ MOMS

[Photo]  ⭐⭐⭐⭐⭐   [Photo]  ⭐⭐⭐⭐⭐   [Photo]  ⭐⭐⭐⭐⭐   [Photo]  ⭐⭐⭐⭐⭐
"Travel    "This is my   "Dad         "Worth
Essential" toddler must  Approved"    The Money"
           have"

           [← · · · · →]   ← dots navigation (mobile)
```

**Shrine block:** `Testimonials` carousel
**Фото:** квадратные 1:1, реальные фото покупателей из UGC
**Фон:** белый
**Заголовок:** H2, center, uppercase

---

### БЛОК 6 — Trust Badges (3 иконки)

```
🚚 Fast Shipping        💛 50,000+ Happy Moms      ↩ 90-Day Returns
  & Easy Returns           Worldwide                  Money-Back
```

**Shrine block:** `Image with text` (multicolumn, 3 колонки)
**Фон:** `#7D9E82` (Sage Green) или `#FAF6EF`
**Текст на зелёном:** белый
**Иконки:** SVG или emoji

---

### БЛОК 7 — FAQ (5 вопросов)

```
        FREQUENTLY ASKED QUESTIONS

▼  How does the Nestli Embrace Carrier work?
▼  What age / weight is it suitable for?
▼  Will it fit my body type?
▼  Will the strap hurt my shoulder or neck?
▼  How long does shipping take?
▼  What is your refund and return policy?
```

**Shrine block:** `Collapsible content` (FAQs)
**Фон:** белый
**Текст вопроса:** DM Sans, 16px, weight 500
**Текст ответа:** DM Sans, 15px, weight 300, line-height 1.7

**Готовые ответы для FAQ:**

**Q: How does the Nestli Embrace Carrier work?**
A: Simply loop the sling over one shoulder, place your baby in the pouch, and adjust the strap using the sliding ring. Baby sits in a natural M-position facing you. Takes under 10 seconds once you've done it once.

**Q: What age / weight is it suitable for?**
A: The Nestli Embrace is designed for babies 0 months to 4 years old, supporting up to 20 kg (44 lbs). For newborns under 4 months, always use the included head support insert.

**Q: Will it fit my body type?**
A: Yes. The adjustable strap fits chest sizes 75–130 cm. Works for both moms and dads. One size fits all caregivers.

**Q: Will the strap hurt my shoulder or neck?**
A: The wide padded strap distributes weight evenly across your shoulder and back. Most parents report zero shoulder pain even after 2–3 hours of carry.

**Q: How long does shipping take?**
A: Standard shipping: 7–14 business days. Express: 3–7 business days. Free standard shipping on all orders over ₴1500.

**Q: What is your refund and return policy?**
A: We offer a 90-day no-questions-asked return policy. If you're not happy with your carrier for any reason, contact us and we'll arrange a full refund or exchange.

---

### БЛОК 8 — Reviews Section

```
         SEE WHAT OTHER MOMS THINK

★★★★☆  4.6 out of 5    [3,429 reviews]    [Write a review ▷]

[Only with Photos ▼]

[Avatar J]  Janice L.           ★★★★★   2024-08-30
            "My husband doesn't like girly carriers, but he's
            more than happy to use this one :)"
            [Photo of dad using the sling]

[Avatar D]  Diana M.            ★★★★★   2024-08-03
            "We went on a family trip and this was our saviour —
            we could easily switch between wearers without hurting our backs"
            [Outdoor lifestyle photo]

... (показывать 6–8 отзывов, затем [Load more])
```

**App для отзывов:** Loox или Judge.me (импорт отзывов с AliExpress через DSers)
**Shrine block:** встраивается через Loox/Judge.me виджет
**Фон:** `#FFFFFF`

---

### БЛОК 9 — You May Also Like (Cross-sell)

```
         YOU MIGHT ALSO LOVE

[Shoulder Pad]      [Storage Bag]      [Baby Bib Set]
Shoulder Cushion    Mini Carrier Bag   Organic Cotton Bibs
₴583.00            ₴872.00            ₴490.00
[Add to Cart]      [Add to Cart]      [Add to Cart]
```

**Shrine block:** `Featured collection` или `Product recommendations`
**Коллекция:** "Accessories" — 3 продукта

---

### БЛОК 10 — Footer Strip

```
[Nestli logo]

Shop          Help           Follow
Sling Carrier   FAQ          Instagram
Accessories     Shipping     TikTok
                Returns
                Contact Us

© 2026 Nestli. All rights reserved.
```

---

## ЦВЕТА ДЛЯ PRODUCT PAGE (повтор для удобства)

| Элемент | Hex | Применение |
|---------|-----|-----------|
| Primary (Sage) | `#7D9E82` | CTA кнопка, иконки, badge, announcement bar |
| Cream | `#FAF6EF` | Фон чередующихся секций, promo banner |
| Blush | `#D4A59A` | Звёзды рейтинга, акцентные детали |
| Dark text | `#1A1A1A` | Заголовки, основной текст |
| Light text | `#6B6B6B` | Подписи, мета-текст |
| White | `#FFFFFF` | Фон основных секций, текст на тёмном |

---

## ПОРЯДОК ДОБАВЛЕНИЯ БЛОКОВ В SHRINE

1. Shopify Admin → Online Store → Themes → Customize
2. Выбрать страницу продукта (Product pages)
3. Нажать "Add block" / "Add section" под основной секцией продукта
4. Добавлять в порядке:

```
[ВСТРОЕНО]  Main product section
[+]         Rich text / Image with text  →  UGC Video Row (Блок 2)
[+]         Multicolumn                 →  How It Works (Блок 3)
[+]         Image with text             →  Pain Points (Блок 4)
[+]         Testimonials                →  Social Proof (Блок 5)
[+]         Multicolumn                 →  Trust Badges (Блок 6)
[+]         Collapsible content         →  FAQ (Блок 7)
[APP]       Loox / Judge.me widget      →  Reviews (Блок 8)
[+]         Featured collection         →  You May Also Like (Блок 9)
```

---

## ТЕКСТ ДЛЯ ОСНОВНОГО ОПИСАНИЯ ПРОДУКТА (Product Details аккордеон)

```
Meet the Nestli Embrace — the softest, most compact baby sling
for moms who want to stay close without sacrificing comfort.

Designed for one-handed on/off in under 10 seconds, the Embrace
fits babies from newborn through 4 years old (up to 20 kg).

WHAT'S INCLUDED:
· Nestli Embrace Sling Carrier
· Newborn head support insert
· Compact carry pouch

MATERIALS:
· Outer: 80% Cotton / 20% Polyester blend
· Padding: High-density foam shoulder pad
· Hardware: Aircraft-grade aluminum ring

DIMENSIONS:
· Adjustable strap: 75–130 cm chest circumference
· Machine washable: 30°C gentle cycle
```

---

## НАЗВАНИЕ ПРОДУКТА (для Shopify)

**Product title:** `Nestli Embrace — Baby Sling Carrier`
**Product subtitle (metafield):** `For Newborns to 4 Years · Up to 20 kg · Ships in 24h`
**SEO title:** `Nestli Embrace Baby Sling Carrier | Free Shipping`
**SEO description:** `The Nestli Embrace sling carrier holds your baby close while keeping both hands free. Ergonomic, adjustable, newborn-safe. 90-day returns. Shop now.`

---

*Файл создан: 2026-05-17*
*Для темы: Shrine (Shopify)*
*Конкурент для сравнения: senarah.com*
