
# 二维码扫描插件

A Flutter plugin 🛠 to scanning. Ready for Android 🚀


## 权限：
`<uses-permission android:name="android.permission.CAMERA" />`
`<uses-permission android:name="android.permission.VIBRATE"/>`

## 安装

Add this to your package's pubspec.yaml file:

```yaml
dependencies:
 w_qrcode: ^0.1.0
```

## 使用方式
```dart
import 'package:w_qrcode/w_qrcode.dart' as scanner;

String barcode = await scanner.scan();

String photoScanResult = await scanner.scanPhoto();
```