# c\_prediction

## Functions

### predict

```lua
g_features.prediction:predict( 
    index: number,
    projectile_range: number,
    projectile_speed: number,
    projectile_width: number,
    delay: number,
    source_position: vec3
): prediction_result_t
```

### predict\_default

```lua
g_features.prediction:predict_default( 
    index: number,
    time: number
): vec3 | nil
```

### predict\_health

```lua
g_features.prediction:predict_health( 
    object: c_object,
    time: number
): number
```

### minion\_in\_line

```lua
g_features.prediction:minion_in_line( 
    start_pos: vec3,
    end_pos: vec3,
    projectile_width: number,
    ignored_network_id: number
): bool
```
