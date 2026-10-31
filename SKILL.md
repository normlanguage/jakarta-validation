# jakarta.validation Skill

Use this skill to work with Norm module `jakarta.validation` version 6. Use only declarations listed below.

## `jakarta.validation`

Source: `Valid.norm`

### `Valid`

```norm
annotation Valid implements FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention
```

## `jakarta.validation.constraints`

Source: `constraints/Email.norm`

### `Email`

```norm
annotation Email implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `regexp`

```norm
String regexp
```

Type: `String`

#### `Email`

```norm
Email(String? message, String? regexp)
```

Parameters:

- `message`: `String?`
- `regexp`: `String?`

## `jakarta.validation.constraints`

Source: `constraints/Future.norm`

### `Future`

```norm
annotation Future implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `Future`

```norm
Future(String? message)
```

Parameters:

- `message`: `String?`

## `jakarta.validation.constraints`

Source: `constraints/Max.norm`

### `Max`

```norm
annotation Max implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `value`

```norm
Long value
```

Type: `Long`

#### `Max`

```norm
Max(String? message, Long value)
```

Parameters:

- `message`: `String?`
- `value`: `Long`

## `jakarta.validation.constraints`

Source: `constraints/Min.norm`

### `Min`

```norm
annotation Min implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `value`

```norm
Long value
```

Type: `Long`

#### `Min`

```norm
Min(String? message, Long value)
```

Parameters:

- `message`: `String?`
- `value`: `Long`

## `jakarta.validation.constraints`

Source: `constraints/NotBlank.norm`

### `NotBlank`

```norm
annotation NotBlank implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `NotBlank`

```norm
NotBlank(String? message)
```

Parameters:

- `message`: `String?`

## `jakarta.validation.constraints`

Source: `constraints/NotEmpty.norm`

### `NotEmpty`

```norm
annotation NotEmpty implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `NotEmpty`

```norm
NotEmpty(String? message)
```

Parameters:

- `message`: `String?`

## `jakarta.validation.constraints`

Source: `constraints/NotNull.norm`

### `NotNull`

```norm
annotation NotNull implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `NotNull`

```norm
NotNull(String? message)
```

Parameters:

- `message`: `String?`

## `jakarta.validation.constraints`

Source: `constraints/Past.norm`

### `Past`

```norm
annotation Past implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `Past`

```norm
Past(String? message)
```

Parameters:

- `message`: `String?`

## `jakarta.validation.constraints`

Source: `constraints/Pattern.norm`

### `Pattern`

```norm
annotation Pattern implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `regexp`

```norm
String regexp
```

Type: `String`

#### `Pattern`

```norm
Pattern(String? message, String regexp)
```

Parameters:

- `message`: `String?`
- `regexp`: `String`

## `jakarta.validation.constraints`

Source: `constraints/Positive.norm`

### `Positive`

```norm
annotation Positive implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `Positive`

```norm
Positive(String? message)
```

Parameters:

- `message`: `String?`

## `jakarta.validation.constraints`

Source: `constraints/PositiveOrZero.norm`

### `PositiveOrZero`

```norm
annotation PositiveOrZero implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `message`

```norm
String message
```

Type: `String`

#### `PositiveOrZero`

```norm
PositiveOrZero(String? message)
```

Parameters:

- `message`: `String?`

## `jakarta.validation.constraints`

Source: `constraints/Size.norm`

### `Size`

```norm
annotation Size implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, RuntimeRetention, RepeatableAnnotation
```

#### `max`

```norm
Integer max
```

Type: `Integer`

#### `message`

```norm
String message
```

Type: `String`

#### `min`

```norm
Integer min
```

Type: `Integer`

#### `Size`

```norm
Size(Integer? max, String? message, Integer? min)
```

Parameters:

- `max`: `Integer?`
- `message`: `String?`
- `min`: `Integer?`

