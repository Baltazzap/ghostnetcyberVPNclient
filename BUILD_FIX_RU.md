# Исправление сборки

Ошибка вида:

```text
IconData can't be extended outside of its library because it's a final class
```

появлялась потому, что GitHub Actions ставил самый новый Flutter `stable`.
Для этой версии Hiddify нужен Flutter `3.38.5`, поэтому workflows теперь закреплены на:

```yaml
flutter-version: "3.38.5"
channel: stable
```

Собирать нужно обычными workflows:

- Build Android APK
- Build Windows EXE
