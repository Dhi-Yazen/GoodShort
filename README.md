# GoodShort

مستودع توزيع نسخ أندرويد من تطبيق **GoodShort**. تُنشر ملفات الـ APK كأصول (assets) على صفحات الإصدارات في GitHub، لأن حد GitHub لحجم الملف داخل git هو 100 MiB بينما حجم الحزمة هنا أكبر من ذلك.

This repository publishes Android build artifacts for **GoodShort**. APK files are attached as GitHub Release assets (they exceed git's 100 MiB per-file limit); the git tree itself holds no binaries.

## التنزيل / Download

آخر إصدار متاح من تبويب Releases: [أحدث إصدار](../../releases/latest) — الملف `GoodShort_3.2.2.2122.apk`.

Get the current build from the [latest release](../../releases/latest): `GoodShort_3.2.2.2122.apk`.

## بيانات الحزمة / Build metadata

| الحقل / Field | القيمة / Value |
|---|---|
| Application ID | `com.newreading.goodreels` |
| versionName | `3.2.2.2122` |
| versionCode | `3222122` |
| minSdkVersion | `23` (Android 6.0) |
| targetSdkVersion | `35` (Android 15) |
| حجم الملف / Size | `175381922` bytes (167.26 MiB) |
| SHA-256 | `576c58e91c9c1f1f90a8a1674b4c2235b80ee4b68156006134f81e228afaaf96` |

تحقّق من سلامة الملف بعد التنزيل وقبل التثبيت:

Verify the download before installing it:

```sh
sha256sum GoodShort_3.2.2.2122.apk
```

## ملاحظات / Notes

- هذا المستودع للتوزيع فقط؛ لا تتضمن أي شيفرة مصدرية.
- يتطلب التثبيت الجانبي (sideload) تمكين «التثبيت من مصادر غير معروفة» على الجهاز.
- Releases here are distribution artifacts only — no source code is published.
