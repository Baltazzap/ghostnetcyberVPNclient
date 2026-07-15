# GhostNet Cyber VPN — отдельный VPN-клиент

Это отдельный VPN-клиент на базе Hiddify, брендированный под GhostNet Cyber VPN.

## Что внутри

- Android APK сборка через GitHub Actions
- Windows x64 portable ZIP сборка через GitHub Actions
- Название приложения: GhostNet Cyber VPN
- Android package: `ru.ghostnet.cybervpn`
- Брендинг/иконки GhostNet уже применены
- Сервер «Белые списки» заменён на «Прага» в брендированном варианте

## Как собрать Android APK

1. Создай новый GitHub-репозиторий.
2. Распакуй архив в корень репозитория.
3. Сделай Commit → Push.
4. Открой GitHub → Actions.
5. Запусти `Build Android APK`.
6. Готовый APK будет в Artifacts: `GhostNet-Android-APK`.

## Как собрать Windows

1. Открой GitHub → Actions.
2. Запусти `Build Windows EXE`.
3. Готовый архив будет в Artifacts: `GhostNet-Windows-x64`.

## Важно

Этот проект основан на Hiddify и использует hiddify-core. Лицензию и упоминание исходного проекта не удаляй.
