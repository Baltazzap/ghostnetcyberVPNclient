GhostNet Cyber VPN — брендированная версия на базе Hiddify App

Что уже изменено:
- Название приложения: GhostNet Cyber VPN
- Android applicationId: ru.ghostnet.cybervpn
- Основной цвет интерфейса: оранжевый #FF7A00
- Иконки Android / Windows / Web / Tray заменены на GhostNet
- Логотип assets/images/logo.svg заменён
- Ссылка Telegram в Constants заменена на https://t.me/ghostnetv_bot
- Windows title/exe metadata заменены

Команды сборки Android:
flutter clean
flutter pub get
flutter build apk --release

APK будет тут:
build/app/outputs/flutter-apk/app-release.apk

Команды сборки Windows:
flutter clean
flutter pub get
flutter config --enable-windows-desktop
flutter build windows --release

Windows build будет тут:
build/windows/x64/runner/Release

Важно:
Я оставил внутреннее имя Flutter-пакета `hiddify`, чтобы не ломать тысячи import-ов вида package:hiddify/...
Это нормально для сборки. Пользователь увидит GhostNet Cyber VPN.

Лицензия:
Проект основан на Hiddify App. Проверь LICENSE.md перед публичной публикацией и сохрани требования лицензии.
