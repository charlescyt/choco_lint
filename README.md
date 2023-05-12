# Choco Lint

Custom lint rules for Dart and Flutter.

## Usage

Add `choco_lint` to the dev dependency of your `pubspec.yaml`:

```yaml
dev_dependencies:
  choco_lint:
    git:
      url: git@github.com:charlescyt/choco_lint.git
      ref: 1.0.0 # specify version here
```

For app, include `choco_lint/analysis_options.yaml` in your project's `analysis_options.yaml`:

```yaml
include: package:choco_lint/analysis_options.yaml
```

For package, use `choco_lint/analysis_options_package` instead.

```yaml
include: package:choco_lint/analysis_options_package.yaml
```
