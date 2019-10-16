
# w_qrcode

A Flutter plugin to scanning. Ready for Android


## 权限：
`<uses-permission android:name="android.permission.CAMERA" />`

`<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>`

`<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>`

## 安装

Add this to your package's pubspec.yaml file:

```yaml
dependencies:
 w_qrcode: ^0.1.1
```

## 使用方式
```dart
import 'package:w_qrcode/w_qrcode.dart' as scanner;

String barcode = await scanner.scan();

String photoScanResult = await scanner.scanPhoto();
```

## 许可

Distributed under the MIT license. See ``LICENSE`` for more information.

## 关于

Created by hookou.