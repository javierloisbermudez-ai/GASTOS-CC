# Expense Scanner — MVP

Android app prototype for:
- photographing an invoice
- OCR extraction
- manual review
- generating an Excel based on the user's INPUT/DATA workbook
- sharing the resulting XLSX through Android (WhatsApp, email, etc.)

## Build
Open this folder in Android Studio (Hedgehog/Koala or newer), let Gradle sync, then:
Build > Build Bundle(s) / APK(s) > Build APK(s)

The APK will normally be under:
app/build/outputs/apk/debug/app-debug.apk

## Important
This is the first MVP. OCR currently processes camera captures with the Latin ML Kit model.
PDF/multiple-file ingestion UI is present; batch OCR and multilingual normalization are the next development step.
The supplied Excel template is included under app/src/main/assets/.
