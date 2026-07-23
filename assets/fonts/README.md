# فونت لوکال — AppPrimary

فایل‌های فونت در این پوشه قرار دارند. **فعلاً فایل‌های placeholder (Vazirmatn) برای تست هستند** — با فونت خودتان جایگزین کنید.

## فایل‌های مورد انتظار

| فایل | وزن |
|------|-----|
| `AppPrimary-Regular.woff2` | 400 |
| `AppPrimary-Medium.woff2` | 500 |
| `AppPrimary-SemiBold.woff2` | 600 |
| `AppPrimary-Bold.woff2` | 700 |
| `AppPrimary-ExtraBold.woff2` | 800 |

## تنظیمات

1. فایل‌های woff2 فونت خود را اینجا کپی کنید (همان نام‌ها)
2. در صورت تغییر نام فونت:
   - [`src/styles/fonts.css`](../styles/fonts.css) → `font-family`
   - [`src/app/core/config/font.config.ts`](../../app/core/config/font.config.ts) → `APP_FONT_FAMILY`

## تبدیل فونت

فونت `.ttf` / `.otf` را با [transfonter.org](https://transfonter.org/) به woff2 تبدیل کنید.
