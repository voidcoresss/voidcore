# Dolphy — проект для Android Studio

Это исходный проект Dolphy-App из предоставленного архива, подготовленный для открытия в Android Studio.

## Как открыть
1. Распакуйте архив в обычную папку (не открывайте проект прямо внутри ZIP).
2. Запустите Android Studio и выберите **Open**.
3. Укажите папку `Dolphy-AndroidStudio` (внутри должны быть `settings.gradle.kts`, `build.gradle.kts` и папка `app`).
4. Дождитесь Gradle Sync. При первом запуске потребуется интернет для загрузки Gradle и зависимостей.
5. Используйте JDK 17 в **Settings → Build, Execution, Deployment → Build Tools → Gradle → Gradle JDK**.
6. Установите Android SDK Platform 36 через SDK Manager, если Android Studio попросит.
7. Чтобы собрать APK: **Build → Build Bundle(s) / APK(s) → Build APK(s)**. Обычно debug APK появится в `app/build/outputs/apk/debug/`.

## Важно
- Я добавил отсутствующий в архиве Unix-скрипт `gradlew`; Windows-скрипт `gradlew.bat` и Gradle Wrapper уже были в проекте.
- Сборка здесь не запускалась: в среде подготовки нет установленного Android SDK/эмулятора. Поэтому совместимость и успешную компиляцию нужно подтвердить через Gradle Sync/Build в Android Studio.
- Проект требует Android SDK 36, JDK 17 и подключения к интернету для загрузки зависимостей.
- Исходники и лицензия проекта сохранены; проверьте `LICENSE` перед распространением или публикацией изменённой версии.
