# NMedia

Исправленная версия ДЗ 1.1.

## Что изменено
- проект переведён на обычный шаблон **Empty Views Activity**
- `MainActivity` теперь использует `AppCompatActivity`
- интерфейс вынесен в `activity_main.xml`
- на экране показывается `NMedia!`
- обновлены версии AGP/Gradle для CI

## Параметры
- `applicationId`: `ru.netology.nmedia`
- `versionName`: `1.0`
- `minSdk`: `24`

## GitHub Actions
Workflow собирает `debug APK` и прикладывает его как artifact.
