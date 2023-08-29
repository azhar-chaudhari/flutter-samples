# direct dependency

## Add a package as a direct dependency:
```bash
flutter pub add <package-name>
```

## example direct dependency:
```bash
flutter pub add http
```

## Add a package as a direct dependency:
```bash
dart pub add <package-name>
```

## example direct dependency:
```bash
dart pub add http
```

# dev dependency

## Add a package as a dev-dependency:
```bash
flutter pub add dev:<package-name>
```

## example dev-dependency:
```bash
flutter pub add dev:foo
```

## Add a package as a dev-dependency:
```bash
dart pub add dev:<package-name>
```

## example dev-dependency:
```bash
dart pub add dev:foo
```

## result dev-dependency:
```bash
dependency_overrides:
  foo: 1.0.0
```

## Remove a package:
```bash
flutter pub remove <package-name>
```