# Compass WebView (Android)

Тестовое приложение компаса на базе Android WebView.
Данные ориентации устройства считываются через аппаратные сенсоры (`SensorManager`, `TYPE_ROTATION_VECTOR` / `TYPE_ACCELEROMETER` + `TYPE_MAGNETIC_FIELD`) и в реальном времени транслируются в HTML5/Canvas/CSS циферблат.

## Сборка и Nightly релизы
Сборка и публикация APK происходят автоматически через GitHub Actions workflow `.github/workflows/nightly.yml` при каждом коммите в ветку `main`.
APK доступен в разделе Releases репозитория под тегом `nightly`.
