# c\_input

### set\_cursor\_position

| Argument | Type   | Required |
| -------- | ------ | -------- |
| position | `vec3` | +        |

```lua
g_input:set_cursor_position(position)
```

### get\_cursor\_position

```
g_input:get_cursor_position(): vec2
```

### send\_key\_event

| Argument | Type          | Required |
| -------- | ------------- | -------- |
| key      | `e_key`       | +        |
| state    | `e_key_state` | +        |

```
g_input:send_key_event(key, state)
```

### send\_mouse\_key\_event

| Argument      | Type             | Required |
| ------------- | ---------------- | -------- |
| mouse\_button | e\_mouse\_button | +        |
| state         | e\_mouse\_state  | +        |

```
g_input:send_mouse_key_event(mouse_button, state)
```

### issue\_order\_move

| Argument | Type | Required |
| -------- | ---- | -------- |
| position | vec3 | +        |

```
g_input:issue_order_move(position)
```

### issue\_order\_attack

| Argument           | Type                 | Required |
| ------------------ | -------------------- | -------- |
| object/network\_id | `c_object \| number` | +        |

```
g_input:issue_order_attack(object/network_id)
```

### cast\_spell

| Argument                    | Type                         | Required |
| --------------------------- | ---------------------------- | -------- |
| slot                        | `e_spell_slot`               | +        |
| object/position/network\_id | `c_object \| vec3 \| number` | -        |

```
g_input:cast_spell(slot, object/position/network_id)
```

### release\_chargable

| Argument | Type           | Required |
| -------- | -------------- | -------- |
| slot     | `e_spell_slot` | +        |
| position | `vec3`         | +        |

```
g_input:release_chargable(slot, position)
```
