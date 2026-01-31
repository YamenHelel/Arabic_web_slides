# مرجع إعدادات الأسلوب المسبقة

أساليب بصرية منتقاة للعروض التقديمية الأمامية. كل إعداد مسبق يتضمن خيارات خط محددة، لوحات ألوان، ومناهج حركة لضمان تصاميم مميزة وغير عامة. جميع الإعدادات تدعم اللغة العربية واتجاه RTL.

---

## السمات الداكنة

### 1. سايبر نيون

**الأجواء:** مستقبلي، تقني، واثق، متطور

**الخطوط:**
- العرض: `Tajawal` (700) — جريء، هندسي، حديث
- النص: `Cairo` (400/500) — نظيف، تقني، قابل للقراءة

**الألوان:**
```css
:root {
    /* اتجاه RTL */
    direction: rtl;

    --bg-primary: #0a0f1c;
    --bg-secondary: #111827;
    --text-primary: #ffffff;
    --text-secondary: #94a3b8;
    --accent: #00ffcc;
    --accent-secondary: #ff00aa;
    --glow: rgba(0, 255, 204, 0.4);
}

html {
    direction: rtl;
}

body {
    text-align: right;
}
```

**العناصر المميزة:**
- نظام جسيمات للخلفية (canvas)
- توهج نيون على عناصر التمييز
- مؤشر مخصص مع ذيل
- تراكب نمط شبكة
- تأثير نص glitch على العناوين

**أسلوب الحركة:**
- سرعة متوسطة (0.5-0.8 ثانية)
- مداخل انزلاق للأعلى + ظهور
- ظهور متتابع

---

### 2. تنفيذي منتصف الليل

**الأجواء:** فاخر، جدير بالثقة، راقي، مؤسسي

**الخطوط:**
- العرض: `Noto Naskh Arabic` (700) — كلاسيكي، رسمي
- النص: `IBM Plex Sans Arabic` (400/600) — احترافي، قابل للقراءة بشكل عالي

**الألوان:**
```css
:root {
    direction: rtl;

    --bg-primary: #0f172a;
    --bg-secondary: #1e293b;
    --text-primary: #f8fafc;
    --text-secondary: #94a3b8;
    --accent: #3b82f6;
    --accent-secondary: #818cf8;
    --gold: #fbbf24;
}
```

**العناصر المميزة:**
- خلفيات تدرج دقيقة
- خطوط تمييز ذهبية رفيعة
- تصوير البيانات
- عناصر زخرفية قليلة
- التركيز على المسافات البيضاء

**أسلوب الحركة:**
- سريع، دقيق (0.3-0.5 ثانية)
- ظهور فقط، حركة قليلة
- ضبط احترافي

---

### 3. الفضاء العميق

**الأجواء:** ملهم، واسع، تأملي، رؤيوي

**الخطوط:**
- العرض: `Almarai` (700) — هندسي، عصر الفضاء
- النص: `Cairo` (400/500) — حديث، ودود

**الألوان:**
```css
:root {
    direction: rtl;

    --bg-primary: #030712;
    --bg-secondary: #111827;
    --text-primary: #f9fafb;
    --text-secondary: #6b7280;
    --accent: #818cf8;
    --accent-secondary: #c084fc;
    --stars: rgba(255, 255, 255, 0.1);
}
```

**العناصر المميزة:**
- خلفية حقل نجوم (CSS أو canvas)
- تأثيرات "أضواء كاشفة" تدرج شعاعي
- عناصر طافية
- خطوط كبيرة ومؤثرة
- تباعد رأسي سخي

**أسلوب الحركة:**
- بطيء، سينمائي (0.8-1.2 ثانية)
- مداخل تكبير + ظهور
- تمرير parallax

---

### 4. أخضر الطرفية

**الأجواء:** موجه للمطورين، جمالية الهاكر، تقني رجعي

**الخطوط:**
- العرض: `IBM Plex Mono` (700) — monospace، شبيه بالكود
- النص: `IBM Plex Mono` (400) — monospace متسق

**الألوان:**
```css
:root {
    direction: rtl;

    --bg-primary: #0d1117;
    --bg-secondary: #161b22;
    --text-primary: #c9d1d9;
    --text-secondary: #8b949e;
    --accent: #39d353;
    --accent-dim: rgba(57, 211, 83, 0.2);
    --border: #30363d;
}
```

**العناصر المميزة:**
- تأثير تراكب خط المسح
- مؤشر وامض
- كتل كود وتمييز النحو
- زخارف ASCII art
- حدود بأسلوب الطرفية

**أسلوب الحركة:**
- ظهور نص بالآلة الكاتبة
- انتقالات سريعة، حادة (0.2-0.3 ثانية)
- ظهور حرف بحرف

---

## السمات الفاتحة

### 5. ورق وحبر

**الأجواء:** تحريري، أدبي، مدروس، مصقول

**الخطوط:**
- العرض: `Amiri` (700) — أنيق، تحريري
- النص: `Scheherazade New` (400) — كلاسيكي، قابل للقراءة

**الألوان:**
```css
:root {
    direction: rtl;

    --bg-primary: #faf9f7;
    --bg-secondary: #f5f3ef;
    --text-primary: #1a1a1a;
    --text-secondary: #666666;
    --accent: #c41e3a;
    --border: #e5e2db;
}
```

**العناصر المميزة:**
- حروف كبيرة في بداية الفقرات
- اقتباسات مميزة
- نسيج ورق دقيق
- خطوط أفقية أنيقة
- تخطيطات أعمدة كلاسيكية

**أسلوب الحركة:**
- ظهور لطيف (0.4-0.6 ثانية)
- بدون حركات درامية
- مصقول، متحفظ

---

### 6. سويسري حديث

**الأجواء:** نظيف، دقيق، مستوحى من Bauhaus، هندسي

**الخطوط:**
- العرض: `Tajawal` (800) — قوي، هندسي
- النص: `Cairo` (400/600) — ودود، مدور

**الألوان:**
```css
:root {
    direction: rtl;

    --bg-primary: #ffffff;
    --bg-secondary: #f7f7f7;
    --text-primary: #000000;
    --text-secondary: #555555;
    --accent: #ff3300;
    --grid: rgba(0, 0, 0, 0.05);
}
```

**العناصر المميزة:**
- نظام شبكة مرئي
- تخطيطات غير متماثلة
- لون تمييز أحمر باعتدال
- خطوط سوداء جريئة
- أشكال هندسية

**أسلوب الحركة:**
- دقيق، آلي (0.3-0.4 ثانية)
- تسهيل خطي أو ease-out
- حركات محاذاة للشبكة

---

### 7. باستيل ناعم

**الأجواء:** ودود، متاح، إبداعي، مرح

**الخطوط:**
- العرض: `Cairo` (800) — مدور، دافئ
- النص: `Cairo` (400/500) — دفء متسق

**الألوان:**
```css
:root {
    direction: rtl;

    --bg-primary: #fef3f2;
    --bg-secondary: #fef9f5;
    --text-primary: #374151;
    --text-secondary: #6b7280;
    --accent: #f472b6;
    --accent-secondary: #a78bfa;
    --accent-tertiary: #34d399;
}
```

**العناصر المميزة:**
- زوايا دائرية في كل مكان
- أشكال blob في الخلفية
- ألوان تمييز باستيل متعددة
- ظلال ناعمة
- أيقونات مصورة

**أسلوب الحركة:**
- فيزياء زنبركية نطاطة
- تجاوزات مرحة
- عناصر طافية/متأرجحة

---

### 8. تحريري دافئ

**الأجواء:** إنساني، سرد قصصي، تصوير فوتوغرافي، مجلة

**الخطوط:**
- العرض: `Noto Kufi Arabic` (700) — أنيق، عناوين serif
- النص: `Tajawal` (400) — حديث، قابل للقراءة

**الألوان:**
```css
:root {
    direction: rtl;

    --bg-primary: #fffbf5;
    --bg-secondary: #f5efe6;
    --text-primary: #2d2a24;
    --text-secondary: #78716c;
    --accent: #b45309;
    --accent-secondary: #0369a1;
}
```

**العناصر المميزة:**
- صور hero كبيرة
- تراكبات صور مع نص
- تصوير دافئ
- اقتباسات مميزة بلون التمييز
- خطوط تمييز مكتوبة يدوياً

**أسلوب الحركة:**
- تلاشي متقاطع سينمائي
- تأثير Ken Burns على الصور
- انتقالات بطيئة، عاطفية (0.8-1 ثانية)

---

## سمات متخصصة

### 9. بروتاليست

**الأجواء:** خام، جريء، غير تقليدي، ملفت للانتباه

**الخطوط:**
- العرض: `Tajawal` (900) — ضخم، مضغوط
- النص: `IBM Plex Mono` (400) — صناعي

**الألوان:**
```css
:root {
    direction: rtl;

    --bg-primary: #ffffff;
    --text-primary: #000000;
    --accent: #ff0000;
    --border: #000000;
}
```

**العناصر المميزة:**
- حدود سوداء سميكة
- تخطيطات غير متماثلة، فوضوية
- خطوط ضخمة
- مظهر خام، غير مصقول
- تباين عالي

**أسلوب الحركة:**
- فوري أو سريع جداً
- قطع حادة، بدون تسهيل
- انتقالات مفاجئة

---

### 10. موجة التدرج

**الأجواء:** SaaS حديث، نشيط، تقني متاح

**الخطوط:**
- العرض: `Almarai` (800) — حديث، واثق
- النص: `Cairo` (400/500) — مسموح فقط لهذا الأسلوب

**الألوان:**
```css
:root {
    direction: rtl;

    --bg-primary: #0f0f1a;
    --gradient-1: #667eea;
    --gradient-2: #764ba2;
    --gradient-3: #f472b6;
    --text-primary: #ffffff;
    --text-secondary: #a1a1aa;
}
```

**العناصر المميزة:**
- شبكات تدرج متحركة
- أشكال blob مع ضبابية
- بطاقات glass-morphism
- كرات طافية
- منحنيات ناعمة

**أسلوب الحركة:**
- سلس، متدفق (0.5-0.7 ثانية)
- حركات دقيقة مستمرة
- ظهور عند التمرير

---

## مرجع سريع لتزاوج الخطوط العربية

| الأجواء | خط العرض | خط النص | المصدر |
|--------|----------|---------|--------|
| تقني/حديث | Tajawal (700) | Cairo (400) | Google |
| احترافي | Noto Naskh Arabic (700) | IBM Plex Sans Arabic (400) | Google |
| فضاء/مستقبل | Almarai (700) | Cairo (400) | Google |
| مطور | IBM Plex Mono | IBM Plex Mono | Google |
| تحريري | Amiri (700) | Scheherazade New (400) | Google |
| سويسري/بسيط | Tajawal (800) | Cairo (400) | Google |
| مرح | Cairo (800) | Cairo (400) | Google |
| مجلة | Noto Kufi Arabic (700) | Tajawal (400) | Google |
| بروتاليست | Tajawal (900) | IBM Plex Mono | Google |
| SaaS حديث | Almarai (800) | Cairo (400) | Google |

---

## مرجع تسهيل الحركة

```css
:root {
    /* منحنيات قياسية */
    --ease-out-expo: cubic-bezier(0.16, 1, 0.3, 1);
    --ease-out-quart: cubic-bezier(0.25, 1, 0.5, 1);
    --ease-out-cubic: cubic-bezier(0.33, 1, 0.68, 1);

    /* نطاط */
    --ease-bounce: cubic-bezier(0.34, 1.56, 0.64, 1);
    --ease-spring: cubic-bezier(0.175, 0.885, 0.32, 1.275);

    /* سلس */
    --ease-smooth: cubic-bezier(0.4, 0, 0.2, 1);

    /* حاد */
    --ease-snappy: cubic-bezier(0.68, -0.55, 0.265, 1.55);
}
```

---

## مقتطفات تأثيرات الخلفية

### حقل الجسيمات (Canvas)

```javascript
class ParticleSystem {
    constructor(canvas) {
        this.canvas = canvas;
        this.ctx = canvas.getContext('2d');
        this.particles = [];
        this.init();
    }

    init() {
        this.resize();
        for (let i = 0; i < 50; i++) {
            this.particles.push({
                x: Math.random() * this.canvas.width,
                y: Math.random() * this.canvas.height,
                vx: (Math.random() - 0.5) * 0.5,
                vy: (Math.random() - 0.5) * 0.5,
                radius: Math.random() * 2 + 1
            });
        }
        this.animate();
    }

    animate() {
        this.ctx.clearRect(0, 0, this.canvas.width, this.canvas.height);
        this.particles.forEach(p => {
            p.x += p.vx;
            p.y += p.vy;
            // الالتفاف حول الحواف
            if (p.x < 0) p.x = this.canvas.width;
            if (p.x > this.canvas.width) p.x = 0;
            if (p.y < 0) p.y = this.canvas.height;
            if (p.y > this.canvas.height) p.y = 0;
            // الرسم
            this.ctx.beginPath();
            this.ctx.arc(p.x, p.y, p.radius, 0, Math.PI * 2);
            this.ctx.fillStyle = 'rgba(0, 255, 204, 0.5)';
            this.ctx.fill();
        });
        requestAnimationFrame(() => this.animate());
    }
}
```

### شبكة التدرج (CSS)

```css
.gradient-mesh {
    background:
        radial-gradient(at 40% 20%, hsla(280, 100%, 70%, 0.3) 0px, transparent 50%),
        radial-gradient(at 80% 0%, hsla(200, 100%, 60%, 0.3) 0px, transparent 50%),
        radial-gradient(at 0% 50%, hsla(340, 100%, 70%, 0.3) 0px, transparent 50%),
        radial-gradient(at 80% 50%, hsla(180, 100%, 50%, 0.2) 0px, transparent 50%),
        radial-gradient(at 0% 100%, hsla(250, 100%, 60%, 0.3) 0px, transparent 50%),
        radial-gradient(at 80% 100%, hsla(20, 100%, 60%, 0.2) 0px, transparent 50%),
        var(--bg-primary);
}
```

### حقل نجوم متحرك (CSS)

```css
.starfield {
    background-image:
        radial-gradient(2px 2px at 20% 30%, white 0%, transparent 50%),
        radial-gradient(2px 2px at 40% 70%, white 0%, transparent 50%),
        radial-gradient(1px 1px at 50% 40%, white 0%, transparent 50%),
        radial-gradient(1px 1px at 60% 60%, white 0%, transparent 50%),
        radial-gradient(2px 2px at 90% 10%, white 0%, transparent 50%);
    background-size: 200% 200%;
    animation: twinkle 15s ease-in-out infinite;
}

@keyframes twinkle {
    0%, 100% { background-position: 0% 0%; }
    50% { background-position: 100% 100%; }
}
```

### نسيج التشويش (SVG Data URI)

```css
.noise {
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 400 400' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noiseFilter'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noiseFilter)'/%3E%3C/svg%3E");
    opacity: 0.05;
}
```

---

## أنماط RTL الخاصة

### تحويل الاتجاهات للـ RTL

```css
/* الانزلاق من اليمين (البداية في RTL) */
.reveal-start {
    opacity: 0;
    transform: translateX(-50px);
    transition: opacity 0.6s, transform 0.6s var(--ease-out-expo);
}

/* الانزلاق من اليسار (النهاية في RTL) */
.reveal-end {
    opacity: 0;
    transform: translateX(50px);
    transition: opacity 0.6s, transform 0.6s var(--ease-out-expo);
}

.visible .reveal-start,
.visible .reveal-end {
    opacity: 1;
    transform: translateX(0);
}
```

### خصائص منطقية CSS للـ RTL

```css
/* استخدم الخصائص المنطقية بدلاً من الفيزيائية */
.element {
    /* بدلاً من margin-left */
    margin-inline-start: 1rem;

    /* بدلاً من margin-right */
    margin-inline-end: 1rem;

    /* بدلاً من padding-left */
    padding-inline-start: 1rem;

    /* بدلاً من padding-right */
    padding-inline-end: 1rem;

    /* بدلاً من text-align: left */
    text-align: start;

    /* بدلاً من text-align: right */
    text-align: end;

    /* بدلاً من border-left */
    border-inline-start: 1px solid var(--border);

    /* بدلاً من left/right في positioning */
    inset-inline-start: 0;
    inset-inline-end: auto;
}
```

### نقاط التنقل للـ RTL

```css
/* نقاط التنقل على اليسار في RTL */
.nav-dots {
    position: fixed;
    left: 2rem;  /* على اليسار في RTL */
    right: auto;
    top: 50%;
    transform: translateY(-50%);
    z-index: 100;
}
```

### شريط التقدم للـ RTL

```css
/* شريط التقدم يبدأ من اليمين */
.progress-bar {
    position: fixed;
    top: 0;
    right: 0;  /* يبدأ من اليمين */
    left: auto;
    height: 3px;
    background: var(--accent);
    width: 0%;
    z-index: 101;
}
```

---

## لا تستخدم (أنماط AI العامة)

تجنب هذه الأنماط المفرطة الاستخدام التي تخلق "AI slop":

**الخطوط:**
- Inter (إلا في أسلوب موجة التدرج)
- Roboto
- Arial / Helvetica
- مجموعات خطوط النظام كخطوط عرض
- خطوط غير عربية للمحتوى العربي

**الألوان:**
- `#6366f1` (نيلي عام)
- تدرجات بنفسجية/violet على أبيض
- أزرار أساسية زرقاء عامة
- توزيع متساوي لألوان التمييز

**التخطيطات:**
- توسيط كل شيء
- hero عام مع نص يسار، صورة يمين (يجب أن يكون معكوساً للـ RTL)
- شبكة ميزات 3 أعمدة قياسية
- بطاقات مستطيلة مدورة مع ظلال

**الحركات:**
- توقيت متطابق على جميع العناصر
- بدون تأخير متتابع على العناصر الفرعية
- تسهيل خطي في كل مكان
- ارتداد مفرط

**التأثيرات:**
- ظلال سقوط بدون قصد
- glassmorphism مجاني
- ضبابيات لا تضيف معنى
- تدرجات بدون سبب
