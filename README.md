# Talks

ارائه‌های [محمد پروین](https://mparvin.me) — میزبانی روی GitHub Pages.

**آدرس:** [talks.mparvin.me](https://talks.mparvin.me)

## ارائه‌ها

| مسیر | عنوان |
|------|--------|
| [`/vibe-coding`](https://talks.mparvin.me/vibe-coding/) | Open Source Tools for Vibe Coding |

## افزودن ارائهٔ جدید

1. یک پوشه در ریشه بسازید (مثلاً `pyday-2025/`).
2. اسلایدها را داخل همان پوشه بگذارید (`index.html` نقطهٔ ورود باشد).
3. کارت را در [`index.html`](index.html) ریشه اضافه کنید.

## DNS (ساب‌دامین)

در DNS دامنهٔ `mparvin.me` این رکورد را بگذارید:

| Type | Name | Value |
|------|------|--------|
| CNAME | `talks` | `mparvin.github.io` |

فایل [`CNAME`](CNAME) همین مقدار را به GitHub Pages اعلام می‌کند.

## پیش‌نمایش محلی

```bash
python3 -m http.server 8765
# http://localhost:8765
# http://localhost:8765/vibe-coding/
```
