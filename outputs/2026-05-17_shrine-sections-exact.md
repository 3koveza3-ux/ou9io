# Nestli — Shrine Theme: Точные настройки каждой секции
> Формат: Название секции в Shrine → каждое поле → что вписать

---

## КАК ОТКРЫТЬ РЕДАКТОР

1. Shopify Admin → Online Store → Themes → Customize
2. Вверху в выпадающем списке выбрать: **Products → Default product**
3. Слева список секций. Под "Main product" жмёшь **+ Add section**

---

---

# СЕКЦИЯ 1 — ANNOUNCEMENT BAR

**Где:** Header (над всем сайтом)
**Shrine section name:** `Announcement bar`

### Как открыть:
Вверху редактора нажать `Header` → найти **Announcement bar** → включить toggle

### Поля:

| Поле | Что вписать |
|------|------------|
| **Text** | `🚚 FREE SHIPPING on orders ₴1500+ · 90-Day Returns · 2-Year Warranty` |
| **Link** | `/policies/shipping` |
| **Color scheme** | Custom → Background: `#7D9E82` · Text: `#FFFFFF` |

---

---

# СЕКЦИЯ 2 — MAIN PRODUCT (встроена, не добавляешь)

**Shrine section name:** `Main product`
Она уже стоит. Нажимаешь на неё и справа появляются настройки.

### Вкладка PRODUCT INFORMATION (правая панель):

Внутри "Main product" есть блоки которые можно добавлять/удалять.
Нажми на раздел и увидишь список активных блоков. Вот что должно быть:

---

### Блок: `Star rating` (рейтинг)
| Поле | Значение |
|------|---------|
| **Позиция** | Самый первый (над заголовком) |

---

### Блок: `Title` (название товара)
Заполняется автоматически из названия продукта в Shopify.
Название продукта: **`Nestli Embrace Sling Carrier`**

---

### Блок: `Price` (цена)
Заполняется автоматически. Убедись что в продукте заполнено:
- Price: `2490`
- Compare at price: `4150`

---

### Блок: `Text` (буллеты преимуществ)
| Поле | Что вписать |
|------|------------|
| **Text** | `✓ Ergonomic single-strap design — no back strain` |

Добавь **3 отдельных блока Text** (по одному на каждый буллет):
- `✓ Ergonomic single-strap design — no back strain`
- `✓ Breathable cotton-blend fabric — safe for sensitive skin`
- `✓ Adjustable fit for both moms and dads — chest 75–130 cm`

---

### Блок: `Variant picker` (выбор цвета)
Добавляется автоматически если у продукта есть варианты (Color).
Тип отображения: **Swatch** (не dropdown)

---

### Блок: `Buy buttons` (кнопка Add to Cart)
| Поле | Значение |
|------|---------|
| **Show dynamic checkout buttons** | OFF (убери галку — оставь только "Add to cart") |

---

### Блок: `Custom liquid` (trust line под кнопкой)
Нажми **+ Add block → Custom liquid**

Вставить:
```html
<p style="text-align:center; font-size:13px; color:#6B6B6B; margin-top:10px; font-family:'DM Sans', sans-serif;">
  90-Day Returns &nbsp;·&nbsp; 2-Year Warranty &nbsp;·&nbsp; Secure Checkout 🔒
</p>
```

---

### Блок: `Collapsible tab` (аккордеон 1 — Product Details)
| Поле | Что вписать |
|------|------------|
| **Heading** | `Product Details` |
| **Icon** | выбрать иконку (например: box или tag) |
| **Content** | см. ниже ↓ |

**Content (вставить как есть):**
```
The Nestli Embrace is made from a premium 80% cotton / 20% polyester blend — soft enough for newborn skin, durable enough for daily use.

WHAT'S INCLUDED
· Nestli Embrace Sling Carrier
· Newborn head support insert
· Compact carry pouch

MATERIALS
· Outer: 80% Cotton / 20% Polyester
· Shoulder pad: High-density foam
· Ring: Aircraft-grade aluminum

CARE
Machine wash 30°C gentle cycle. Air dry only.
```

---

### Блок: `Collapsible tab` (аккордеон 2 — Shipping & Returns)
| Поле | Что вписать |
|------|------------|
| **Heading** | `Shipping & Returns` |
| **Icon** | truck или package |
| **Content** | см. ниже ↓ |

**Content:**
```
SHIPPING
· Standard: 7–14 business days (FREE on orders ₴1500+)
· Express: 3–7 business days (₴350)
· All orders shipped within 24 hours

RETURNS
90-day return window — no questions asked.
Contact support@nestli.com to start your return.
Refund processed in 3–5 business days.
```

---

---

# СЕКЦИЯ 3 — IMAGE WITH TEXT (UGC видео / мама-одобрено)

**Shrine section name:** `Image with text`
**Добавить:** + Add section → Image with text

### Поля секции:

| Поле | Что вписать |
|------|------------|
| **Heading** | `MOM-TESTED, MOM-APPROVED` |
| **Heading size** | Large |
| **Text** | `Real moms. Real babies. Real results.` |
| **Image** | загрузить lifestyle фото (мама с ребёнком в слинге, 1:1) |
| **Image position** | Right (фото справа, текст слева) |
| **Color scheme** | Background: `#FAF6EF` |
| **Button label** | `Watch their stories` |
| **Button link** | `/collections/all` (или ссылка на TikTok) |
| **Button style** | Outline |

### Примечание про видео:
Shrine не встраивает TikTok нативно. Пока нет видео — использовать фото.
Когда будут видео — установить **Tolstoy** app и заменить этот блок их виджетом.

---

---

# СЕКЦИЯ 4 — MULTICOLUMN (Как надеть за 5 секунд)

**Shrine section name:** `Multicolumn`
**Добавить:** + Add section → Multicolumn

### Поля секции:

| Поле | Что вписать |
|------|------------|
| **Heading** | `CARRY THEM IN 5 SECONDS` |
| **Heading size** | Medium |
| **Columns on desktop** | 4 |
| **Columns on mobile** | 2 |
| **Image ratio** | Square |
| **Button label** | оставить пустым |
| **Color scheme** | Background: `#FFFFFF` |

### Внутри: 4 блока Column (по кнопке + Add column):

**Column 1:**
| Поле | Значение |
|------|---------|
| **Image** | фото "надеваем слинг через плечо" |
| **Heading** | `01 · Place It Around` |
| **Text** | `Loop the sling over one shoulder and let it fall across your body` |

**Column 2:**
| Поле | Значение |
|------|---------|
| **Image** | фото "кладём ребёнка в слинг" |
| **Heading** | `02 · Swoop Baby In` |
| **Text** | `Lift your baby and slide them into the pouch from below` |

**Column 3:**
| Поле | Значение |
|------|---------|
| **Image** | фото "затягиваем кольцо" |
| **Heading** | `03 · Adjust The Strap` |
| **Text** | `Pull through the ring to tighten until baby sits snug at chest height` |

**Column 4:**
| Поле | Значение |
|------|---------|
| **Image** | фото "мама улыбается, руки свободны" |
| **Heading** | `04 · Good To Go!` |
| **Text** | `Both hands free — you're ready for anything` |

---

---

# СЕКЦИЯ 5 — IMAGE WITH TEXT (Pain Points — "Time to Upgrade")

**Shrine section name:** `Image with text`
**Добавить:** + Add section → Image with text (вторая такая секция)

### Поля секции:

| Поле | Что вписать |
|------|------------|
| **Heading** | `IT'S TIME TO UPGRADE` |
| **Heading size** | Large |
| **Text** | `To a lighter, more comfortable way to carry your baby.` |
| **Image** | lifestyle фото: мама с ребёнком, outdoor, улыбается |
| **Image position** | Left (фото слева, текст справа) |
| **Color scheme** | Background: `#FAF6EF` |
| **Button label** | `Shop the Nestli Embrace` |
| **Button link** | `#main-product` (прокрутит наверх к форме) |
| **Button style** | Solid |

### Внутри — добавить 4 блока `Text`:

**Text блок 1:**
```
✓  Back & Hip Pain
Say goodbye to the discomfort of carrying your toddler all day.
```

**Text блок 2:**
```
✓  Arm Fatigue
No more tired arms — the carrier takes all the weight.
```

**Text блок 3:**
```
✓  Bulky Carriers
The Nestli Embrace folds into the size of your fist.
```

**Text блок 4:**
```
✓  Shoulder Pain
Our 8 cm padded strap spreads weight evenly — no pressure points.
```

---

---

# СЕКЦИЯ 6 — TESTIMONIALS (Карусель отзывов)

**Shrine section name:** `Testimonials`
**Добавить:** + Add section → Testimonials

### Поля секции:

| Поле | Что вписать |
|------|------------|
| **Heading** | `TRUSTED BY 50,000+ MOMS` |
| **Heading size** | Medium |
| **Color scheme** | Background: `#FFFFFF` |
| **Layout** | Carousel (не Grid) |
| **Auto-rotate** | OFF |

### Внутри — 4 блока `Testimonial`:

**Testimonial 1:**
| Поле | Значение |
|------|---------|
| **Quote** | `We flew across Europe with this carrier. It packs smaller than a water bottle and we used it the entire trip.` |
| **Author** | `Emma C.` |
| **Title / Location** | `California, US` |
| **Image** | фото покупателя или lifestyle фото (квадрат) |
| **Rating** | ★★★★★ (5) |

**Testimonial 2:**
| Поле | Значение |
|------|---------|
| **Quote** | `I have a very clingy baby and this lets me cook and clean while keeping him happy. This is our everyday essential.` |
| **Author** | `Stephanie K.` |
| **Title / Location** | `Oregon, US` |
| **Image** | фото |
| **Rating** | ★★★★★ (5) |

**Testimonial 3:**
| Поле | Значение |
|------|---------|
| **Quote** | `My husband refused every other carrier but loves this one. Says it's not complicated and doesn't look "girly".` |
| **Author** | `Rachel B.` |
| **Title / Location** | `Boston, US` |
| **Image** | фото |
| **Rating** | ★★★★★ (5) |

**Testimonial 4:**
| Поле | Значение |
|------|---------|
| **Quote** | `Went through 3 cheap knockoffs before getting this. Should have bought it first. The quality difference is night and day.` |
| **Author** | `Grace T.` |
| **Title / Location** | `Tampa, US` |
| **Image** | фото |
| **Rating** | ★★★★★ (5) |

---

---

# СЕКЦИЯ 7 — ICON BAR (Trust Badges)

**Shrine section name:** `Icon bar`  
*(в некоторых версиях Shrine называется `Feature bar` или `Icons with text`)*
**Добавить:** + Add section → Icon bar

### Поля секции:

| Поле | Что вписать |
|------|------------|
| **Color scheme** | Background: `#7D9E82` · Text: `#FFFFFF` |
| **Columns on desktop** | 3 |

### Внутри — 3 блока `Icon column`:

**Icon 1:**
| Поле | Значение |
|------|---------|
| **Icon** | выбрать `truck` или `package` из встроенных |
| **Heading** | `Fast Shipping` |
| **Text** | `Free on orders over ₴1500` |

**Icon 2:**
| Поле | Значение |
|------|---------|
| **Icon** | выбрать `heart` |
| **Heading** | `50,000+ Happy Moms` |
| **Text** | `And counting` |

**Icon 3:**
| Поле | Значение |
|------|---------|
| **Icon** | выбрать `return` или `refresh` |
| **Heading** | `90-Day Returns` |
| **Text** | `No questions asked` |

---

---

# СЕКЦИЯ 8 — COLLAPSIBLE CONTENT (FAQ)

**Shrine section name:** `Collapsible content`
**Добавить:** + Add section → Collapsible content

### Поля секции:

| Поле | Что вписать |
|------|------------|
| **Heading** | `Frequently Asked Questions` |
| **Color scheme** | Background: `#FFFFFF` |
| **Open first row by default** | ON (первый вопрос открыт) |

### Внутри — 6 блоков `Row`:

**Row 1:**
| Поле | Значение |
|------|---------|
| **Heading** | `How does the Nestli Embrace Carrier work?` |
| **Content** | `The Nestli Embrace is a ring sling. Loop it over one shoulder so it sits diagonally across your chest. Lift your baby and slide them into the fabric pouch. Pull the loose end through the ring to tighten until baby is snug at chest height. Takes under 10 seconds once you've done it once.` |

**Row 2:**
| Поле | Значение |
|------|---------|
| **Heading** | `What age and weight is it suitable for?` |
| **Content** | `The Nestli Embrace supports babies from newborn (0 months) through 4 years old, up to 20 kg (44 lbs). For newborns under 4 months, use the included head support insert.` |

**Row 3:**
| Поле | Значение |
|------|---------|
| **Heading** | `Will it fit my body type?` |
| **Content** | `Yes. The adjustable strap fits chest sizes 75–130 cm, covering XS through 3XL. Works equally for moms and dads. One carrier, every caregiver in the family.` |

**Row 4:**
| Поле | Значение |
|------|---------|
| **Heading** | `Will the strap hurt my shoulder or neck?` |
| **Content** | `The 8 cm wide padded strap distributes your baby's weight across your shoulder and upper back. Most parents report zero discomfort even after 2–3 hours of wear.` |

**Row 5:**
| Поле | Значение |
|------|---------|
| **Heading** | `How long does shipping take?` |
| **Content** | `Standard shipping: 7–14 business days (FREE on orders ₴1500+). Express: 3–7 business days (₴350). All orders ship within 24 hours of purchase.` |

**Row 6:**
| Поле | Значение |
|------|---------|
| **Heading** | `What is your refund and return policy?` |
| **Content** | `We offer a 90-day no-questions-asked return policy. Contact support@nestli.com and we'll arrange a full refund or free exchange. Refund processed within 3–5 business days.` |

---

---

# СЕКЦИЯ 9 — APP BLOCK (Отзывы Judge.me)

**Shrine section name:** добавляется автоматически после установки Judge.me
**Добавить:** + Add section → Apps → Judge.me Reviews

Если Judge.me не установлен:
1. Shopify Admin → Apps → Visit Shopify App Store
2. Найти: `Judge.me Product Reviews`
3. Install → Free plan
4. Вернуться в Customize → + Add section → Apps → Judge.me

### Настройки виджета в Judge.me (не в Shrine):
| Параметро | Значение |
|-----------|---------|
| **Primary color** | `#7D9E82` |
| **Font** | Inherit from theme |
| **Reviews per page** | 8 |
| **Show reviewer photos** | YES |
| **Default sort** | Most recent |
| **Header text** | `See What Other Moms Think` |

---

---

# СЕКЦИЯ 10 — FEATURED COLLECTION (You Might Also Love)

**Shrine section name:** `Featured collection`
**Добавить:** + Add section → Featured collection

### Поля секции:

| Поле | Что вписать |
|------|------------|
| **Heading** | `You Might Also Love` |
| **Collection** | выбрать коллекцию `Accessories` |
| **Products to show** | `3` |
| **Columns on desktop** | `3` |
| **Columns on mobile** | `2` |
| **Show secondary image on hover** | ON |
| **Enable quick add** | ON |
| **Color scheme** | Background: `#FAF6EF` |

---

---

# ИТОГОВЫЙ ПОРЯДОК СЕКЦИЙ В РЕДАКТОРЕ SHRINE

Вот как должен выглядеть левый сайдбар в Customize после того как всё добавишь:

```
📌 Header
   └── Announcement bar ✓

📦 Template — Product pages
   ├── Main product                    ← встроена
   │    ├── Star rating
   │    ├── Title
   │    ├── Price
   │    ├── Text (буллет 1)
   │    ├── Text (буллет 2)
   │    ├── Text (буллет 3)
   │    ├── Variant picker
   │    ├── Buy buttons
   │    ├── Custom liquid (trust line)
   │    ├── Collapsible tab (Product Details)
   │    └── Collapsible tab (Shipping & Returns)
   │
   ├── Image with text                 ← MOM-TESTED MOM-APPROVED
   ├── Multicolumn                     ← 5 секунд / 4 шага
   ├── Image with text                 ← Pain Points
   ├── Testimonials                    ← 4 отзыва-карточки
   ├── Icon bar                        ← 3 trust badge
   ├── Collapsible content             ← FAQ 6 вопросов
   ├── Apps → Judge.me                 ← полный блок отзывов
   └── Featured collection             ← You Might Also Love

🔻 Footer
```

---

# ЦВЕТА ДЛЯ THEME SETTINGS

**Где:** Customize → Theme settings (иконка шестерёнки) → Colors

| Слот | Название | Hex |
|------|---------|-----|
| Background | Primary | `#FFFFFF` |
| Background | Secondary | `#FAF6EF` |
| Button background | — | `#7D9E82` |
| Button text | — | `#FFFFFF` |
| Accent | — | `#D4A59A` |
| Heading text | — | `#1A1A1A` |
| Body text | — | `#1A1A1A` |
| Secondary text | — | `#6B6B6B` |

---

*Файл: 2026-05-17_shrine-sections-exact.md*
