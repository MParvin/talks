<!-- .slide: class="title-slide" -->

# Open Source Tools for Vibe Coding

<p class="subtitle">توسعهٔ هدایت‌شده با AI بدون دردسر</p>

<hr class="brand-line" />

<p class="presenter"><strong>محمد پروین</strong> · بنیانگذار پارس آپس و PaaS2</p>

<div class="contacts">
  <a href="https://t.me/mdparvin" target="_blank" rel="noopener"><i class="fab fa-telegram"></i> @mdparvin</a>
  <a href="https://github.com/mparvin" target="_blank" rel="noopener"><i class="fab fa-github"></i> mparvin</a>
</div>

---

## Vibe Coding چیست؟

- جابه‌جایی از **نوشتن سینتکس** به **هدایت معماری**
- مفهومی که <span class="latin">Andrej Karpathy</span> مطرح کرد
- زبان طبیعی = رابط اصلی توسعه <!-- .element: class="fragment" -->

<div class="callout fragment">
  <p>نقش شما: <strong>مدیر پرامپت</strong> + <strong>بازبین سیستم</strong> — نه فقط کدنویس خط‌به‌خط</p>
</div>

---

## انقلاب Cursor

- ادغام عوامل LLM داخل ادیتور
- جریان کاری جدید: گفتگو → کد → بازبینی

<div class="callout catch fragment">
  <p><strong>اما…</strong> وابستگی به وندور · اشتراک ماهانه · نگرانی حریم خصوصی · کمتر بودن کنترل روی مدل و داده</p>
</div>

- جامعه به‌سمت **جایگزین‌های متن‌باز** می‌رود <!-- .element: class="fragment" -->

---

## چرا متن‌باز برای Vibe Coding؟

- **حریم خصوصی:** با مدل محلی، کد و کانتکست روی ماشین شما می‌ماند
- **BYOK:** هارنس متن‌باز + مدل دلخواه — حتی مدل اختصاصی مثل <span class="latin">Claude</span>
- <span class="latin">OpenRouter</span> / API ابری: انعطاف بیشتر، ولی کانتکست به provider می‌رود <!-- .element: class="fragment" -->
- **شفافیت:** کنترل پرامپت، ابزارها و جریان اجرا <!-- .element: class="fragment" -->

<div class="callout success fragment">
  <p>IP فقط وقتی کاملاً محلی است که مدل هم محلی باشد (مثل <span class="latin">Ollama</span>)</p>
</div>

---

## افزونه‌های IDE و ایجنت‌های ترمینال

<div class="cols">
<div class="col">

### Cline & Roo Code

- افزونهٔ VS Code با Human-in-the-loop
- Cline: حالت Plan / Act
- Roo: Architect و حالت‌های نقش

</div>
<div class="col">

### Aider & OpenCode

- ابزارهای CLI ترمینال‌محور
- Aider: auto-commit روی Git
- OpenCode: ایجنت ترمینال / TUI

</div>
</div>

---

## اجرای محلی و سطح سیستم‌عامل

<div class="cols">
<div class="col">

### Open Interpreter

- کنترل OS با زبان طبیعی
- اجرای اسکریپت‌ها
- پردازش فایل‌های محلی

</div>
<div class="col">

### Dyad

- اپلیکیشن دسکتاپ native
- ساخت اپ محلی
- بازبینی امنیتی آزمایشی با AI

</div>
</div>

<div class="callout fragment">
  <p>از کدنویسی در ادیتور تا <strong>اجرای واقعی روی ماشین</strong> — مدل می‌تواند محلی یا ابری باشد</p>
</div>

---

## معرفی Hermes Agent

<span class="tag">Nous Research</span>

- harness پایدار و متن‌باز برای ایجنت‌های خودمختار
- حافظهٔ **خودبهبود** بین نشست‌ها
- ساخت و نگه‌داری **مهارت** در طول زمان <!-- .element: class="fragment" -->
- کنترل کامل ابزارها و CLI <!-- .element: class="fragment" -->

<div class="callout fragment">
  <p>نه فقط یک چت — یک <strong>هارنس ایجنت</strong> که یاد می‌گیرد و ماندگار می‌ماند</p>
</div>

---

## Hermes فراتر از Vibe Coding

- ایجنت **همه‌منظوره** — نه فقط copilot یا افزونهٔ IDE
- کاربردها: زیرساخت · پژوهش خودکار · کارهای OS <!-- .element: class="fragment" -->
- یکپارچگی چندکاناله: بات‌های Telegram / Discord <!-- .element: class="fragment" -->

<div class="callout success fragment">
  <p><strong>Local First:</strong> اجرا روی ماشین یا VPS شما — بدون تلمتری اجباری به سازنده؛ مدل می‌تواند محلی یا ابری باشد</p>
</div>

---

## پروژهٔ ویژه: AI-Awesome

- مجموعهٔ curated از ابزارها، فریمورک‌ها و منابع AI / ML / DL
- نقطهٔ شروع عالی برای چیدن stack وایب‌کدینگ شما

<p style="margin: 1em 0; font-size: 0.85em;">
  <a class="latin" href="https://github.com/MParvin/AI-Awesome" target="_blank" rel="noopener">
    <i class="fab fa-github"></i> github.com/MParvin/AI-Awesome
  </a>
</p>

<div class="callout success fragment">
  <p>⭐ ستاره بزنید · مشارکت کنید · برای setup بعدی‌تان کاوش کنید</p>
</div>

---

## جمع‌بندی و پرسش

<div class="quote">
  Vibe Coding جایگزین دولوپرها نیست — آن‌ها را به <strong>معمار سیستم</strong> تبدیل می‌کند.
</div>

### سپاس از توجه شما

<div class="contacts">
  <a href="https://t.me/mdparvin" target="_blank" rel="noopener"><i class="fab fa-telegram"></i> @mdparvin</a>
  <a href="https://github.com/mparvin" target="_blank" rel="noopener"><i class="fab fa-github"></i> mparvin</a>
</div>

<p class="subtitle" style="margin-top: 1.2em;">سوالی دارید؟</p>
