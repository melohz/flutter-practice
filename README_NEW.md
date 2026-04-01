# flutter-practice

Flutter の学習用リポジトリです。

現在は、Flutter のデフォルトのカウンターアプリが含まれています。`FloatingActionButton` を押すと、画面中央のカウントが 1 ずつ増えます。

## 構成

- `lib/main.dart`: アプリ本体。MaterialApp とカウンター画面を定義
- `pubspec.yaml`: プロジェクト設定と依存関係

## 使用技術

- Flutter
- Dart
- Material Design

## セットアップ

```bash
flutter pub get
flutter run
```

## 現在の内容

- `MyApp` で `MaterialApp` を初期化
- `MyHomePage` で状態を持つカウンター画面を表示
- `FloatingActionButton` で `_incrementCounter()` を実行

## 補足

`pubspec.yaml` ではプロジェクト名が `hello_world` になっています。
README のリポジトリ名とは異なるため、必要に応じて今後そろえると分かりやすくなります.
