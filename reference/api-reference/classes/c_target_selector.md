# c\_target\_selector

## Functions

### get\_default\_target

```lua
features.target_selector:get_default_target(): c_object | nil
```

### get\_orbwalker\_default\_target

```lua
features.target_selector:get_orbwalker_default_target(): c_object | nil
```

### get\_forced\_target

```lua
features.target_selector:get_forced_target(): c_object | nil
```

### is\_forced

```lua
features.target_selector:is_forced(): bool
```

### is\_bad\_target

| Argument | Type   | Required |
| -------- | ------ | -------- |
| index    | number | +        |

```lua
features.target_selector:is_bad_target(index): bool
```

### force\_target

| Argument | Type                | Required |
| -------- | ------------------- | -------- |
| object   | number \| c\_object | +        |

```lua
features.target_selector:force_target(object): bool
-- To reset forced target call force_target with nil or -1 as object argument
```
