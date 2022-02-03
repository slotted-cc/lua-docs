# c\_prediction

## Functions1

### predict

| Argument          | Type                             | Required |
| ----------------- | -------------------------------- | -------- |
| index             | `number`                         | +        |
| projectile\_range | `number`                         | +        |
| projectile\_speed | `number`                         | +        |
| projectile\_width | `number`                         | +        |
| delay             | `number`                         | +        |
| source\_position  | ``[`vec3`](../structs/vec3.md)`` | +        |

```lua
features.prediction:predict( 
    index,
    projectile_range,
    projectile_speed,
    projectile_width,
    delay,
    source_position
): prediction_result_t
```

### predict\_default

| Argument | Type     | Required |
| -------- | -------- | -------- |
| index    | `number` | +        |
| time     | `number` | +        |

```lua
features.prediction:predict_default( 
    index,
    time
): vec3 | nil
```

### predict\_health

| Argument | Type                           | Required |
| -------- | ------------------------------ | -------- |
| object   | ``[`c_object`](c\_object.md)`` | +        |
| time     | `number`                       | +        |

```lua
features.prediction:predict_health( 
    object,
    time
): number
```

### minion\_in\_line

| Argument             | Type                             | Required |
| -------------------- | -------------------------------- | -------- |
| start\_pos           | ``[`vec3`](../structs/vec3.md)`` | +        |
| end\_pos             | ``[`vec3`](../structs/vec3.md)`` | +        |
| projectile\_width    | `number`                         | +        |
| ignored\_network\_id | `number`                         | +        |

```lua
features.prediction:minion_in_line( 
    start_pos,
    end_pos,
    projectile_width,
    ignored_network_id
): bool
```
