# Ночная вахта — Android

**Вариант 1 (без установки ничего): GitHub**
1. Создайте репозиторий на github.com и загрузите в него все файлы этой папки (включая скрытую `.github`).
2. Вкладка Actions → "Build APK" → дождитесь зелёной галочки (~3 мин).
3. Внутри запуска скачайте артефакт `nochnaya-vahta-apk` → внутри `app-debug.apk`.

**Вариант 2: Android Studio**
File → Open → эта папка → Build → Build APK(s).

Игра лежит в `app/src/main/assets/index.html` — заменяйте её и пересобирайте.
