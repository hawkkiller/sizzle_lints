# sizzle_lints

Efficient lints for Dart and Flutter projects, combined together with love.

## Usage

To use these lints in your project, add the following to your `analysis_options.yaml`:

```yaml
include: package:sizzle_lints/lints.yaml
```

### Dart Code Metrics

To use the Dart Code Metrics lints in your project, add the following to your `analysis_options.yaml`:

```yaml
dart_code_metrics:
  extends:
    - package:sizzle_lints/dcm.yaml
```