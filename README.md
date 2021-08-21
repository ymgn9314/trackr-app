![text_logo](https://user-images.githubusercontent.com/35668159/130312182-c8c7ebc3-f06b-47d4-8424-37e17e1dcba2.png)

# Grinder
## Grinderのインストール
```shell
pub global activate grinder
```

## build_runnerの実行
```shell
grind
```

## アプリ起動
### debug-dev
```shell
flutter run --debug --flavor dev --dart-define=FLAVOR=dev -t lib/main-dev.dart
```

### release-prod
```shell
flutter run --release --flavor prod --dart-define=FLAVOR=prod -t lib/main-prod.dart
```

# Flavor生成
```shell
./flavorizr/flavorizr.sh
```

# スプラッシュ画像の生成
```shell
./native_splash/native_splash.sh
```

# アプリアイコンの生成
```shell
flutter pub run flutter_launcher_icons:main -f flutter_launcher_icons-dev.yaml
```

