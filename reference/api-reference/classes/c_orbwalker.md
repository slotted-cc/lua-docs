# c\_orbwalker

## Functions

### send\_attack

| Argument    | Type     | Required |
| ----------- | -------- | -------- |
| network\_id | `number` | +        |

```lua
features.orbwalker:send_attack(network_id): bool
```

### is\_in\_attack

```
features.orbwalker:is_in_attack(): bool
```

### send\_move\_input

| Argument | Type   | Required |
| -------- | ------ | -------- |
| position | `vec3` | +        |
| force    | `bool` | +        |

```
features.orbwalker:send_move_input(position, force)
```

### set\_cast\_time

| Argument | Type     | Required |
| -------- | -------- | -------- |
| time     | `number` | +        |

```
features.orbwalker:set_cast_time(time)
```

### can\_move

```
features.orbwalker:can_move(): bool
```

### is\_attackable

| Argument    | Type     | Required |
| ----------- | -------- | -------- |
| index       | `number` | +        |
| range       | `number` | +        |
| edge\_range | `bool`   | +        |

```
features.orbwalker:is_attackable(index, range, edge_range): bool
```

### get\_ping

```
features.orbwalker:get_ping(): number
```

### get\_mode

```
features.orbwalker:get_mode(): e_orbwalker_mode
```

### reset\_aa\_timer

```
features.orbwalker:reset_aa_timer()
```

### can\_attack

```
features.orbwalker:can_attack(): bool
```

### should\_reset_\__aa

```lua
features.orbwalker:should_reset_aa(): bool
```
