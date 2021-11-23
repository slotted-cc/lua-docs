# c\_orbwalker

## Functions

### send\_attack

| Argument    | Type     | Required |
| ----------- | -------- | -------- |
| network\_id | `number` | +        |

```lua
g_features.orbwalker:send_attack( network_id ): bool
```

### is\_in\_attack

```
g_features.orbwalker:is_in_attack(): bool
```

### send\_move\_input

| Argument | Type   | Required |
| -------- | ------ | -------- |
| position | `vec3` | +        |
| force    | `bool` | +        |

```
g_features.orbwalker:send_move_input( position, force )
```

### set\_cast\_time

| Argument | Type     | Required |
| -------- | -------- | -------- |
| time     | `number` | +        |

```
g_features.orbwalker:set_cast_time( time )
```

### can\_move

```
g_features.orbwalker:can_move(): bool
```

### is\_attackable

| Argument    | Type     | Required |
| ----------- | -------- | -------- |
| index       | `number` | +        |
| range       | `number` | +        |
| edge\_range | `bool`   | +        |

```
g_features.orbwalker:is_attackable( index, range, edge_range ): bool
```

### get\_ping

```
g_features.orbwalker:get_ping(): number
```

### get\_mode

```
g_features.orbwalker:get_mode(): e_orbwalker_mode
```

### reset\_aa\_timer

```
g_features.orbwalker:reset_aa_timer()
```

### can\_attack

```
g_features.orbwalker:can_attack(): bool
```

### should\_rest_\__aa

```lua
g_features.orbwalker:should_rest_aa(): bool
```
