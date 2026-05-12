# דוח ביקורת SEO — אתר עו"ד צחי לביא (רשלנות רפואית)
**תאריך ביקורת:** 27 באפריל 2026  
**כלי:** ניתוח ידני של קבצי HTML + sitemap.xml + robots.txt  
**מתבדקות:** 22 עמודי HTML

---

## סיכום מנהלים

| קטגוריה | מצב | בעיות שנמצאו |
|---|---|---|
| תגי Title | ⚠️ חלקי | 12 עמודים ארוכים מ-60 תווים, 1 קצר מ-30 |
| Meta Description | ⚠️ חלקי | 2 קצרות, 1 ארוכה |
| מבנה H1 | ✅ תקין | כל העמודים עם H1 יחיד |
| Canonical Tags | 🔴 קריטי | אי-עקביות דומיין — GitHub vs lavia-adv.co.il |
| lang + dir | ✅ תקין | כל העמודים |
| Robots Meta | ⚠️ חסר | אף עמוד אינו מגדיר robots meta |
| Image Alt Text | ✅ תקין | אין תמונות עם alt ריק |
| Internal Linking | ⚠️ חלקי | 4 עמודים מבודדים, 3 קישורים שבורים |
| Schema Markup | ⚠️ חלקי | 6 עמודים ללא BreadcrumbList, accessibility ללא schema |
| Open Graph | ⚠️ חלקי | 8 עמודים עם שדות חסרים |
| sitemap.xml | 🔴 קריטי | 9 עמודים חסרים, דומיין שגוי |
| robots.txt | ✅ תקין | Allow: * + הפניה ל-sitemap |
| כותרות / תיאורים כפולים | ✅ תקין | אין כפילויות |

---

## 1. תגי Title — ניתוח מפורט

### בעיית אורך (מעל 60 תווים — ייחתכו בגוגל)

| עמוד | אורך | כותרת |
|---|---|---|
| article-car-accident-malpractice.html | **88** | נפגעת בתאונת דרכים ונגרם לך נזק בבית החולים? המלכודת המשפטית שחובה להכיר... |
| article-genetic-malpractice.html | **81** | רשלנות רפואית בבדיקות גנטיות: מתי קמה עילת תביעה ומתי מגיע פיצוי?... |
| article-family-doctor-referral-negligence.html | **77** | איחור בהפניה מרופא המשפחה: מתי קמה עילה לתביעת רשלנות רפואית?... |
| article-estate-malpractice.html | **73** | תביעת עיזבון ברשלנות רפואית – מי רשאי לתבוע ומה הפיצויים?... |
| article-birth-malpractice.html | **70** | רשלנות רפואית בלידה – מתי ניהול לידה הופך לעילת תביעה?... |
| article-pregnancy-malpractice.html | **70** | רשלנות רפואית בהיריון והולדה בעוולה – הזכות שנשללה מכם... |
| article-surgical-malpractice.html | **69** | רשלנות בכירורגיה בישראל — סוגים, אחריות ופיצוי [2026]... |
| article-informed-consent-surgery.html | **65** | הסכמה מדעת לניתוח — מה רופא חייב להסביר לך (2026)... |
| article-informed-consent-autonomy-damages.html | **65** | פגיעה באוטונומיה — גם אם הניתוח הצליח יש לך תביעה... |
| article-stroke-diagnosis.html | **65** | רשלנות רפואית בשבץ מוחי – כשאיחור של שעה שינה הכל... |
| article-cancer-diagnosis.html | **66** | איחור באבחון סרטן: כשהזמן הוא ההבדל בין חיים למוות... |
| article-informed-consent-case-law.html | **63** | תביעות הסכמה מדעת — 7 פסקי דין שמחייבים כל רופא... |
| article-malpractice-limitations.html | **63** | ילד שנפגע מרשלנות רפואית – יכול לתבוע עד גיל 25... |
| article-diagnosis-reassessment-failure.html | **62** | כשהרופא נעול על האבחנה — רשלנות באי הערכה מחדש... |
| article-informed-consent-special-cases.html | **61** | הסכמה מדעת בחירום, לקטין, ולשינוי באמצע ניתוח... |

### כותרת קצרה מדי (מתחת ל-30 תווים)

| עמוד | אורך | כותרת |
|---|---|---|
| accessibility.html | **28** | הצהרת נגישות \| עו״ד צחי לביא |

**המלצה:** קצר את הכותרות לבין 50–60 תווים. לדוגמה:  
`article-car-accident-malpractice.html` → `נזק בבית החולים אחרי תאונה? המלכודת המשפטית | עו"ד לביא`

---

## 2. Meta Description — ניתוח מפורט

### קצרות מדי (מתחת ל-120 תווים)

| עמוד | אורך | תיאור |
|---|---|---|
| accessibility.html | **89** | הצהרת נגישות של אתר עו״ד צחי לביא... |
| article-car-accident-malpractice.html | **102** | נפגעת בתאונת דרכים ונגרם לך נזק נוסף בבית החולים?... |

### ארוכות מדי (מעל 160 תווים)

| עמוד | אורך | הערה |
|---|---|---|
| article-pregnancy-malpractice.html | **161** | חורגת ב-1 תו — ייחתך בגוגל |

**המלצה:** כוונו לאורך בין 130–155 תווים. יש לקצר `article-pregnancy-malpractice.html` ולהרחיב `accessibility.html` ו-`article-car-accident-malpractice.html`.

---

## 3. מבנה כותרות H1 / H2 / H3

✅ **כל 22 עמודים** מכילים תג `<h1>` יחיד.  

### עמודים שראויים לבדיקת H1 מול Title

| עמוד | H1 | Title |
|---|---|---|
| index.html | `צחי לביא` (קצר מאוד, ללא מילות מפתח) | `עו״ד צחי לביא – עורך דין נזיקין ורשלנות רפואית` |
| article-car-accident-malpractice.html | תואם Title ✅ | — |

⚠️ **`index.html`**: ה-H1 הוא רק שם — `צחי לביא` — ללא מילות מפתח כגון "עורך דין" או "רשלנות רפואית". מומלץ להוסיף לפחות מילת מפתח אחת בתג H1 של דף הבית.

---

## 4. Canonical Tags — בעיה קריטית

### 🔴 אי-עקביות דומיין

הדומיין בתג canonical **שונה** בין קבוצות עמודים:

| עמוד | Canonical |
|---|---|
| index.html | `https://tzachilavi101-prog.github.io/tsachi-lavia-law/` |
| accessibility.html | `https://tzachilavi101-prog.github.io/tsachi-lavia-law/accessibility.html` |
| כל 20 מאמרי הרשלנות | `https://lavia-adv.co.il/article-*.html` |

**הבעיה:** המנוע מגוגל עשוי לאנדקס שני דומיינים שונים. sitemap.xml מצביע על `tzachilavi101-prog.github.io` בעוד שה-canonical של המאמרים מצביע על `lavia-adv.co.il`. זה יוצר **כפילות תוכן** בין שני דומיינים.

**המלצה:** יש להחליט על דומיין אחד (כנראה `lavia-adv.co.il`) ולאחד את כל ה-canonical וה-sitemap לאותו דומיין.

---

## 5. lang="he" ו-dir="rtl"

✅ **כל 22 עמודי HTML** פותחים עם `<html lang="he" dir="rtl">`.  
אין ליקויים בקטגוריה זו.

---

## 6. Robots Meta Tags

⚠️ **אף עמוד** באתר אינו מכיל `<meta name="robots">`.

- עבור עמוד `accessibility.html`: מומלץ להוסיף `<meta name="robots" content="noindex, follow">` כדי למנוע אינדוקס של עמוד שאינו תוכן ליבה.
- עבור שאר העמודים: הדפדפן ברירת המחדל הוא `index, follow` — אין צורך לציין זאת, אך כדאי להוסיף `noindex` ל-accessibility.

---

## 7. תיאור תמונות (Alt Text)

✅ **אין תמונות עם alt ריק** — כל תמונות ה-`<img>` שנמצאו כוללות טקסט alt.

### ⚠️ אי-התאמה בנתיב og:image לקבצים מקומיים

| עמוד | og:image מוגדר | קובץ בפועל |
|---|---|---|
| article-anesthesia-malpractice.html | `.../images/article-medical-malpractice-signs.png` | `article-medical-malpractice-signs.png` (בשורש) |
| article-delayed-emergency-surgery.html | `.../images/article-medical-malpractice-signs.png` | `article-medical-malpractice-signs.png` (בשורש) |
| article-missed-radiology-findings.html | `.../images/article-medical-malpractice-signs.png` | `article-medical-malpractice-signs.png` (בשורש) |
| article-pregnancy-malpractice.html | `.../article-pregnancy-malpractice.png` | `article-pregnancy-malpractice.webp` (פורמט שונה) |
| article-stroke-diagnosis.html | `.../article-stroke-diagnosis.png` | `article-stroke-diagnosis.webp` (פורמט שונה) |

**הבעיה:** 3 עמודים מצביעים לנתיב `/images/` שאינו קיים. 2 עמודים מצביעים על `.png` כשהקובץ הוא `.webp`.

---

## 8. קישוריות פנימית (Internal Linking)

### 🔴 קישורים שבורים

| עמוד | קישורים שבורים |
|---|---|
| article-anesthesia-malpractice.html | `article-orthopedic-malpractice.html` ❌ |
| article-anesthesia-malpractice.html | `article-vascular-malpractice.html` ❌ |
| article-anesthesia-malpractice.html | `article-urology-malpractice.html` ❌ |

3 קישורים מפנים לעמודים שאינם קיימים — יש להסיר אותם או להחליף אותם בעמודים קיימים.

### ⚠️ עמודים מבודדים (מעט קישורים יוצאים)

| עמוד | מספר קישורים פנימיים יוצאים | הערה |
|---|---|---|
| article-car-accident-malpractice.html | **1** (רק Homepage) | מנותק לחלוטין מרשת התוכן |
| article-estate-malpractice.html | **1** (רק Homepage) | מנותק לחלוטין |
| article-genetic-malpractice.html | **1** (רק Homepage) | מנותק לחלוטין |
| article-family-doctor-referral-negligence.html | **2** | נמוך מאוד |

**המלצה:** יש להוסיף לפחות 3–5 קישורים פנימיים רלוונטיים לכל עמוד. לדוגמה, `article-estate-malpractice.html` יכול לקשר ל-`article-malpractice-limitations.html`, `article-medical-malpractice-signs.html` ועוד.

### ✅ עמודים עם קישוריות פנימית טובה

- סדרת הסכמה מדעת (`informed-consent-*`) — כל 4 מאמרים מקושרים זה לזה ✅
- סדרת האבחון (`missed-surgical-diagnosis`, `missed-radiology-findings`, `diagnosis-reassessment-failure`, `delayed-emergency-surgery`) — מקושרים היטב ✅

---

## 9. Schema Markup

### ✅ סכמות קיימות לפי עמוד

| עמוד | LegalArticle | LegalService | BreadcrumbList | FAQPage |
|---|---|---|---|---|
| accessibility.html | ❌ | ❌ | ❌ | ❌ |
| index.html | ❌ | ✅ | ❌ | ❌ |
| article-anesthesia-malpractice.html | ✅ | ✅ | ❌ | ✅ |
| article-birth-malpractice.html | ✅ | ✅ | ✅ | ❌ |
| article-cancer-diagnosis.html | ✅ | ✅ | ✅ | ❌ |
| article-car-accident-malpractice.html | ✅ | ✅ | ❌ | ❌ |
| article-cerebral-palsy-malpractice.html | ✅ | ✅ | ✅ | ✅ |
| article-delayed-emergency-surgery.html | ✅ | ✅ | ✅ | ❌ |
| article-diagnosis-reassessment-failure.html | ✅ | ✅ | ✅ | ❌ |
| article-estate-malpractice.html | ✅ | ✅ | ❌ | ✅ |
| article-family-doctor-referral-negligence.html | ✅ | ✅ | ❌ | ❌ |
| article-genetic-malpractice.html | ✅ | ✅ | ❌ | ❌ |
| article-informed-consent-autonomy-damages.html | ✅ | ✅ | ✅ | ❌ |
| article-informed-consent-case-law.html | ✅ | ✅ | ✅ | ❌ |
| article-informed-consent-special-cases.html | ✅ | ✅ | ✅ | ❌ |
| article-informed-consent-surgery.html | ✅ | ✅ | ✅ | ✅ |
| article-malpractice-limitations.html | ✅ | ✅ | ❌ | ❌ |
| article-medical-malpractice-signs.html | ✅ | ✅ | ❌ | ❌ |
| article-missed-radiology-findings.html | ✅ | ✅ | ✅ | ❌ |
| article-missed-surgical-diagnosis.html | ✅ | ✅ | ✅ | ✅ |
| article-pregnancy-malpractice.html | ✅ | ✅ | ✅ | ✅ |
| article-stroke-diagnosis.html | ✅ | ✅ | ✅ | ✅ |
| article-surgical-malpractice.html | ✅ | ✅ | ✅ | ✅ |

### 🔴 בעיות ספציפיות בסכמות

1. **`accessibility.html`** — אין שום סכמה. יש להוסיף לפחות `WebPage`.

2. **`article-anesthesia-malpractice.html`** — משתמש בסכמה מסוג `Collection` (לא סכמת Schema.org תקנית). יש להחליף ב-`ItemList` אם המטרה היא רשימה של מאמרים.

3. **עמודים ללא `BreadcrumbList`** (6 עמודים): `article-car-accident-malpractice`, `article-estate-malpractice`, `article-family-doctor-referral-negligence`, `article-genetic-malpractice`, `article-malpractice-limitations`, `article-medical-malpractice-signs`, `article-anesthesia-malpractice` — הוספת Breadcrumb שיפרת תצוגת Rich Results בגוגל.

4. **עמודים ללא `FAQPage`** (12 עמודים): `article-birth-malpractice`, `article-cancer-diagnosis`, `article-car-accident-malpractice`, `article-delayed-emergency-surgery`, `article-diagnosis-reassessment-failure`, `article-estate-malpractice`, `article-family-doctor-referral-negligence`, `article-genetic-malpractice`, `article-informed-consent-autonomy-damages`, `article-informed-consent-case-law`, `article-informed-consent-special-cases`, `article-malpractice-limitations`, `article-medical-malpractice-signs`, `article-missed-radiology-findings` — מאמרים משפטיים ממירים היטב עם FAQPage.

5. **`article-delayed-emergency-surgery.html`** ו-`article-diagnosis-reassessment-failure.html` ו-`article-missed-radiology-findings.html` — מכילים סכמת `Article` (גנרי) לצד `LegalArticle`. מומלץ להסיר את `Article` ולהשתמש רק ב-`LegalArticle`.

---

## 10. Open Graph Tags

### בעיות לפי עמוד

| עמוד | חסר og:url | חסר og:locale | חסר og:site_name | חסר og:image |
|---|---|---|---|---|
| accessibility.html | ❌ | ❌ | ❌ | ❌ |
| index.html | — | — | — | ❌ |
| article-anesthesia-malpractice.html | — | ❌ | ❌ | — |
| article-birth-malpractice.html | ❌ | — | ❌ | — |
| article-cerebral-palsy-malpractice.html | ❌ | — | ❌ | — |
| article-estate-malpractice.html | — | — | — | ❌ |
| article-pregnancy-malpractice.html | ❌ | — | ❌ | — |
| article-stroke-diagnosis.html | ❌ | — | ❌ | — |

**סה"כ:** 8 עמודים עם שדות OG חסרים.

**תבנית מלאה מומלצת:**
```html
<meta property="og:title" content="..." />
<meta property="og:description" content="..." />
<meta property="og:type" content="article" />
<meta property="og:url" content="https://lavia-adv.co.il/[page].html" />
<meta property="og:image" content="https://lavia-adv.co.il/[image].png" />
<meta property="og:locale" content="he_IL" />
<meta property="og:site_name" content="עו״ד צחי לביא – נזיקין ורשלנות רפואית" />
```

---

## 11. sitemap.xml

### 🔴 בעיות קריטיות

**א. 9 עמודים חסרים מה-sitemap:**

| עמוד חסר |
|---|
| article-anesthesia-malpractice.html |
| article-birth-malpractice.html |
| article-cerebral-palsy-malpractice.html |
| article-estate-malpractice.html |
| article-family-doctor-referral-negligence.html |
| article-genetic-malpractice.html |
| article-pregnancy-malpractice.html |
| article-stroke-diagnosis.html |

**ב. אי-עקביות דומיין:**  
ה-sitemap משתמש ב-`https://tzachilavi101-prog.github.io/tsachi-lavia-law/` כדומיין בסיס, אבל ה-canonical של כל המאמרים מצביע על `https://lavia-adv.co.il/`. גוגל עשוי לא לאנדקס עמודים שה-sitemap שלהם לא תואם ל-canonical.

**המלצה:** יש לעדכן את sitemap.xml כך שכל ה-URL יצביעו לדומיין `lavia-adv.co.il`, ולהוסיף את כל 8 העמודים החסרים.

---

## 12. robots.txt

```
User-agent: *
Allow: /

Sitemap: https://tzachilavi101-prog.github.io/tsachi-lavia-law/sitemap.xml
```

✅ robots.txt קיים ותקין.  

⚠️ **הסיטמאפ מצביע לדומיין GitHub Pages** — יש לעדכן ל-`https://lavia-adv.co.il/sitemap.xml` לאחר אחוד הדומיין.

---

## 13. כפילויות בכותרות ותיאורים

✅ **אין כפילויות** — כל 22 עמודים כוללים כותרת ותיאור ייחודיים.

---

## רשימת עדיפויות לתיקון

### 🔴 עדיפות גבוהה (קריטי לאינדוקס)

1. **אחד את הדומיין** — כל canonical ו-sitemap.xml יצביעו ל-`lavia-adv.co.il` (לא GitHub Pages).
2. **עדכן sitemap.xml** — הוסף 8 עמודים חסרים ותקן את הדומיין.
3. **תקן קישורים שבורים** ב-`article-anesthesia-malpractice.html` (3 עמודים לא קיימים).

### ⚠️ עדיפות בינונית (שיפור נראות)

4. **קצר כותרות Title** ל-60 תווים מקסימום — 12 עמודים בצפייה.
5. **הרחב Meta Description** ב-`accessibility.html` (89 → 130 תווים) ו-`article-car-accident-malpractice.html` (102 → 130 תווים).
6. **הוסף `<meta name="robots" content="noindex, follow">`** ל-`accessibility.html`.
7. **תקן og:image paths** — 3 עמודים עם נתיב `/images/` שגוי, 2 עמודים עם סיומת `.png` שגויה (הקובץ `.webp`).
8. **הוסף og:url, og:site_name, og:locale** ל-8 עמודים חסרים.
9. **שפר H1 של index.html** — הוסף מילות מפתח ("עורך דין רשלנות רפואית") לתוך תג H1.

### 💡 עדיפות נמוכה (שיפורי Rich Results)

10. **הוסף BreadcrumbList** ל-7 עמודים שחסרים.
11. **הוסף FAQPage Schema** ל-12 עמודים שחסרים — ישפר CTR בחיפוש.
12. **הוסף קישורים פנימיים** ל-4 עמודים מבודדים (`article-car-accident-malpractice`, `article-estate-malpractice`, `article-genetic-malpractice`, `article-family-doctor-referral-negligence`).
13. **הוסף Schema ל-`accessibility.html`** — לפחות `WebPage` + `Organization`.
14. **הסר סכמת `Article` כפולה** מ-3 עמודים (שמור רק `LegalArticle`).
15. **הוסף og:image ל-`index.html`** ול-`article-estate-malpractice.html`.

---

*דוח זה הופק על ידי Claude Code בתאריך 27.04.2026*

---

# 🔄 נספח א' — עדכון סטטוס וסבב תיקונים (12 במאי 2026)

> **15 ימים לאחר האודיט המקורי.** סבב ראשון של תיקונים בוצע. נספח זה מסכם את ההתקדמות, מציג ניתוח חדש על עומק תוכן, ומציע מפת דרכים להעמקת מאמרים דקים. נכתב כ-handoff packet לסשנים עתידיים.

## א. סטטוס תיקונים מהאודיט המקורי

### ✅ הושלם במלואו

| # מקורי | פעולה | קבצים |
|---|---|---|
| 10 | הוספת `BreadcrumbList` schema | **7 קבצים** — anesthesia, car-accident, estate, family-doctor-referral-negligence, genetic, malpractice-limitations, medical-malpractice-signs |
| 11 | הוספת `FAQPage` content **גלוי** | **12 קבצים** — כל המאמרים שהיו עם schema-only ללא תוכן נראה |

עכשיו: **21/21 מאמרים** עם `BreadcrumbList` + `FAQPage` תוכן גלוי תואם schema.

### ✅ פעולות נוספות שבוצעו מעבר לאודיט המקורי

| פעולה | תיאור |
|---|---|
| **ריכוז CSS גלובלי** | `.faq-block` (7 שורות CSS) הועבר מ-inline ב-6 קבצים ל-`style.css` שורות 2085–2091. אפס שכפול. |
| **תיקון JavaScript באג קריטי** | `article-car-accident-malpractice.html` ו-`article-medical-malpractice-signs.html` קראו ל-`document.getElementById('hamburger')` שלא קיים → `TypeError` שעצר את ה-IntersectionObserver וגרם להסתרה מוחלטת של כל הטקסט עם `.reveal`. תוקן עם `if (hamburger && mobileMenu)`. |
| **איחוד מבנה FAQ ל-100%** | 3 מאמרים שהשתמשו במימוש ישן (`.faq-list` + `.faq-item` + JS `toggleFaq()`) הומרו ל-`.faq-block` עם `<details>/<summary>`. הוסרו: CSS מקומי + פונקציית JS. **כל 21 המאמרים על תבנית אחת.** |
| **איחוד טקסט כותרת FAQ** | `article-anesthesia-malpractice.html` הוסרה הסיומת "— רשלנות בהרדמה". כל 21 המאמרים עכשיו אומרים "שאלות נפוצות" בלבד. |

### 🔲 פתוח (מהאודיט המקורי — טרם בוצע)

קריטי:
- [1] איחוד דומיין canonical (חלק כבר עודכן ל-`lavia-adv.co.il` בסשן קודם, אבל לא הכל)
- [2] עדכון `sitemap.xml` — הוסף 8 עמודים חסרים
- [3] תיקון קישורים שבורים ב-`article-anesthesia-malpractice.html` (3 לינקים לעמודים שלא קיימים)

בינוני:
- [4] קיצור כותרות Title ל-60 תווים (12 עמודים)
- [5] הרחבת Meta Description ב-`accessibility.html` ו-`car-accident-malpractice.html`
- [6] הוספת `<meta name="robots" content="noindex, follow">` ל-`accessibility.html`
- [7] תיקון og:image paths
- [8] הוספת og:url, og:site_name, og:locale ל-8 עמודים
- [9] שיפור H1 של `index.html` (להוסיף מילות מפתח)

נמוך:
- [12] קישורים פנימיים ל-4 עמודים מבודדים
- [13] Schema ל-`accessibility.html`
- [14] הסרת `Article` כפול מ-3 עמודים
- [15] og:image ל-`index.html` ו-`estate-malpractice.html`

---

## ב. ניתוח עומק תוכן — מאמרים דקים (חדש)

מטריקות מדויקות לכל 21 המאמרים נכון ל-12.5.2026:

| H2 | מילים | מאמר | קטגוריה |
|---:|---:|---|---|
| 5 | 2,544 | `informed-consent-case-law` | תקין (מאמר פסיקה — לא חייב להיות רחב) |
| 7 | **1,921** | `car-accident-malpractice` | 🔴 **הדק ביותר** |
| 7 | **1,989** | `informed-consent-special-cases` | 🟡 דק |
| 7 | 2,159 | `diagnosis-reassessment-failure` | תקין |
| 7 | 2,390 | `missed-surgical-diagnosis` | תקין |
| 7 | 2,730 | `estate-malpractice` | טוב |
| 8 | 2,135 | `medical-malpractice-signs` | 🟡 דק (אבל זה מאמר Hub-Intro) |
| 8 | 2,144 | `family-doctor-referral-negligence` | תקין |
| 8 | 2,273 | `missed-radiology-findings` | תקין |
| 8 | 2,306 | `informed-consent-autonomy-damages` | תקין |
| 8 | 2,379 | `delayed-emergency-surgery` | תקין |
| 8 | 2,664 | `birth-malpractice` | טוב |
| 8 | 2,802 | `cancer-diagnosis` | טוב |
| 8 | 3,421 | `informed-consent-surgery` | טוב מאוד |
| 9 | **2,007** | `malpractice-limitations` | 🟡 דק (H2 רבים, מילים מעטות לכל H2) |
| 9 | **2,103** | `genetic-malpractice` | 🟡 דק |
| 10 | 3,551 | `cerebral-palsy-malpractice` | פילר |
| 10 | 3,625 | `stroke-diagnosis` | פילר |
| 11 | 3,876 | `anesthesia-malpractice` | פילר |
| 11 | 5,469 | `surgical-malpractice` | פילר עמוק |
| 14 | 4,030 | `pregnancy-malpractice` | פילר עמוק |

**טווח:** 1,921 → 5,469 מילים (פער של פי 2.8). חציון: 8 H2 / 2,379 מילים.

### דפוס "Pillar" שמופיע בעשירים

3 המאמרים הכי עמוקים (stroke, pregnancy, surgical) חולקים מבנה אחיד:

```
1. מבוא/Hook
2. רקע רפואי או הסבר מקצועי
3. הלכה/מסגרת נורמטיבית
4. ניתוח פסיקה (3+ פסקי דין)
5. יסודות משפטיים / קשר סיבתי
6. גובה הפיצויים (טבלה / טווחים)
7. צ׳קליסט
8. צעדים מעשיים (3-4 צעדים)
9. שאלות נפוצות
```

המאמרים הדקים חסרים בדרך כלל את **גובה פיצויים**, **צ׳קליסט**, **צעדים מעשיים**, ולעיתים גם **ניתוח פסיקה מובנה**.

---

## ג. מפת דרכים — Outlines למאמרים לעיבוי

### 🔴 עדיפות 1: `article-car-accident-malpractice.html`
**יעד:** 1,921 → ~3,800 מילים. 7 → 12 H2.

5 סקציות חדשות + 1 H2 קיים שעובה:

| # | H2 חדש/קיים | תוכן | Format |
|---|---|---|---|
| 1 | קיים — הטעות שעולה לנפגעי תאונות דרכים הון | להשאיר | פסקאות |
| 2 | 🔵 **תשובה מהירה: מה זה ייחוד עילה ולמה זה משנה?** | 3-4 שורות תקציר ל-Google Snippet | Highlight box |
| 3 | קיים — הרקע המשפטי: חוק הפלת״ד וייחוד העילה | להעמיק | פסקאות + הגדרה מוסגרת |
| 4 | 🔵 **מתי הנזק בבית החולים נכלל בפלת״ד ומתי לא?** | הבחנות עם דוגמאות | טבלת השוואה / תרשים זרימה |
| 5 | קיים — סיפור מקרה: CRPS לאחר ארטרוסקופיה | להשאיר | case-study card |
| 6 | 🔵 **פסיקה ישראלית: פסקי דין מובילים** | 3 פס״ד ⚠️ ציטוטים לאישור עו"ד | 3 case cards |
| 7 | קיים — למה חייבים עו"ד שמבין גם ברשלנות רפואית? | להשאיר | פסקאות |
| 8 | 🔵 **טבלת פיצויים** | ראשי נזק + טווחים | טבלה |
| 9 | 🔵 **צ׳קליסט: 5 שאלות לזהות "נזק שני"** | רשימת שאלות | רשימה עם checkboxes |
| 10 | 🔵 **4 צעדים מעשיים אחרי תאונה ופציעה רפואית** | (1) מסמכים (2) תיעוד (3) חוות דעת (4) פנייה לעו״ד | רשימה ממוספרת |
| 11 | קיים — אל תפקירו את התיק שלכם | להשאיר | פסקאות |
| 12 | קיים — שאלות נפוצות | להוסיף 2-3 שאלות חדשות | faq-block |

### 🟡 עדיפות 2: `article-genetic-malpractice.html`
**יעד:** 2,103 → ~3,400 מילים.

3 סקציות חדשות + עיבוי קיימים:
- 🔵 "תשובה מהירה: מתי קמה עילת תביעה גנטית?"
- 🔵 "פסיקה ישראלית נוספת: 3-4 פס״ד על הולדה בעוולה" ⚠️
- 🔵 "טבלת פיצויים בתביעות גנטיות"
- 🔵 "צ׳קליסט: 6 סימנים שייעוץ גנטי היה רשלני"
- עיבוי: "מה ניתן לתבוע?" → טבלת ראשי נזק
- עיבוי: "מה עליכם לעשות עכשיו?" → 4 צעדים מפורטים

### 🟡 עדיפות 3: `article-malpractice-limitations.html`
**יעד:** 2,007 → ~3,500 מילים. **אסטרטגיה שונה — עיבוי קיימים במקום הוספת H2.**

לכל חריג (גילוי מאוחר / הסתרה / אוטונומיה / רשלנות מתמשכת) — הוסף 3 רכיבים סטנדרטיים:
1. דוגמה ממשית
2. פסיקה ישראלית ⚠️
3. טיפ מעשי (highlight box)

3 H2 חדשים בסוף:
- 🔵 "טבלת התיישנות: סקירה מהירה"
- 🔵 "צ׳קליסט: איך לחשב את ההתיישנות שלך"
- 🔵 "3 צעדים אם אתה קרוב לקצה ההתיישנות"

---

## ד. החלטות מבניות + אילוצים שנקבעו בסבב הזה

**חשוב לידע בסשנים עתידיים:**

1. **`.faq-block` היא התבנית האחידה.** כל מאמר חדש או עדכון חייב להשתמש בה (HTML5 `<details>/<summary>/<p>` בתוך `<section class="faq-block reveal" aria-labelledby="...">`). CSS מרוכז ב-`style.css` שורות 2085–2091 — **אל תכניס CSS של `.faq-block` בקובץ HTML.**

2. **`BreadcrumbList` משובץ בתוך ה-LegalArticle schema** כשדה `breadcrumb` (לא כ-`<script>` JSON-LD נפרד). תבנית 3 רמות סטנדרטית — דף הבית / מאמרים / שם המאמר (position 3 ללא URL כי זה העמוד הנוכחי).

3. **3 המאמרי "Pillar-style" הם המודל לחיקוי**: `stroke-diagnosis`, `pregnancy-malpractice`, `surgical-malpractice`. כשכותבים תוכן חדש או מעמיקים מאמר דק — תסתכל עליהם כ-reference template.

4. **אסור להמציא פסיקה ישראלית.** Claude יכול **להציע** פסקי דין מוכרים (כמו "הלכת דעקה", "הלכת קימחי", "הלכת אבילפזוב", "הלכת המר") עם הערה שצריך לאמת — אבל **ציטוטים מדויקים (מספר תיק, שנה, שופט)** חייבים להגיע מעו"ד צחי לביא ולא מ-Claude.

5. **כתיבת תוכן דורשת קריאת `.claude/brand-voice-guidelines.md` ו-`.claude/about-me.md`** לפני כל מילה — לפי הוראה ב-CLAUDE.md. בסבב הזה לא ערכנו כתיבת תוכן ממשית (רק structure), ולכן הקבצים האלה לא נטענו.

6. **3 commits נדחפו ל-main** בעקבות הסבב:
   - `8955453` — Add FAQ sections and centralize FAQ CSS across articles
   - `4f676ac` — Pre-existing edits from prior sessions: canonical migration, branding, pillar pages
   - Commit נוסף שהמשתמש דחף מקומית (BreadcrumbList ל-7 + איחוד כותרת FAQ + איחוד 3 חריגים ל-`.faq-block`)

---

*נספח א' נכתב על ידי Claude (Cowork) ב-12 במאי 2026.*

