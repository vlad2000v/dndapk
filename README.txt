ПОДЗЕМЕЛЬЯ И ДРАКОНЫ — Android-проект для сборки APK

1. Создайте репозиторий на GitHub (ветка main).
2. Загрузите в корень ВСЁ СОДЕРЖИМОЕ этой папки (включая .github), не саму папку.
3. Actions -> Build Android APK -> Run workflow.
4. Скачайте artifact DnD-debug-apk, распакуйте, установите app-debug.apk.

Приложению нужен интернет (Supabase). Библиотеки supabase.js и three.js
скачиваются во время сборки и встраиваются в APK.
