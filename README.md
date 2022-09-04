# Metro Icons Flutter

This package includes 700 icons from [Metro UI Icon](https://metroui.org.ua/icons.html) set. The naming convention is the same as the CSS names in camelCase.

## Instalation
Include `metro_icons` in your `pubspec.yaml` file:

```yaml
dependencies:
  flutter:
    sdk: flutter
  metro_icons: version
```

## Usage

To use this package, just import it into your file and enjoy it.

```dart
import 'package:metro_icons/metro_icons.dart';

...

Icon(MetroIcon.chatBubble)
Icon(MetroIcon.comment, size: 48)
Icon(MetroIcon.reply, size: 48, color: Colors.blue,)
...
```