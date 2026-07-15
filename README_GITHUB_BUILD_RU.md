# GhostNet Android APK — сборка через GitHub Actions

## Как собрать APK

1. Создай новый репозиторий на GitHub.
2. Распакуй этот архив.
3. Загрузи **содержимое папки** в корень репозитория.
4. GitHub Desktop → Commit → Push.
5. Открой GitHub → вкладка **Actions**.
6. Запусти workflow **Build Android APK**.
7. После завершения открой запуск workflow → **Artifacts** → скачай `GhostNet-Android-APK`.

## Что внутри

- Android VPN-клиент GhostNet на базе Hiddify core.
- Package ID: `ru.ghostnet.cybervpn`.
- Название: `GhostNet Cyber VPN`.
- Сервер «Белые списки» заменён на «Прага».
- Workflow уже настроен для сборки APK без ручных секретов.

## Важно

Это отдельный Android VPN-клиент. Основное приложение-кабинет GhostNet остаётся отдельным проектом.
