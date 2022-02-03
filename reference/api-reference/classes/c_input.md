# c\_input

### set\_cursor\_position

| Argument | Type                         | Required |
| -------- | ---------------------------- | -------- |
| position | [`vec3`](../structs/vec3.md) | +        |

`g_input:set_cursor_position(position):` `void`

### get\_cursor\_position

`g_input:get_cursor_position():` [`vec2`](../structs/vec2.md)`3`

### send\_key\_event

| Argument | Type                                       | Required |
| -------- | ------------------------------------------ | -------- |
| key      | [`e_key`](../enums/e\_key.md)              | +        |
| state    | [`e_key_state`](../enums/e\_key\_state.md) | +        |

`g_input:send_key_event(key, state):` `void`

### send\_mouse\_key\_event

| Argument      | Type                                             | Required |
| ------------- | ------------------------------------------------ | -------- |
| mouse\_button | [`e_mouse_button`](../enums/e\_mouse\_button.md) | +        |
| state         | [`e_key_state`](../enums/e\_key\_state.md)       | +        |

`g_input:send_mouse_key_event(mouse_button, state):` `void`

### issue\_order\_move

| Argument | Type                         | Required |
| -------- | ---------------------------- | -------- |
| position | [`vec3`](../structs/vec3.md) | +        |

`g_input:issue_order_move(position):` `void`

### issue\_order\_attack

| Argument           | Type                                   | Required |
| ------------------ | -------------------------------------- | -------- |
| object/network\_id | [`c_object`](c\_object.md) \| `number` | +        |

`g_input:issue_order_attack(object/network_id):` `void`

### cast\_spell

| Argument                    | Type                                                                   | Required |
| --------------------------- | ---------------------------------------------------------------------- | -------- |
| slot                        | [`e_spell_slot`](../enums/e\_spell\_slot.md)                           | +        |
| object/position/network\_id | [`c_object`](c\_object.md) \| [`vec3`](../structs/vec3.md) \| `number` | -        |

`g_input:cast_spell(slot, object/position/network_id):` `void`

### release\_chargable

| Argument | Type                                         | Required |
| -------- | -------------------------------------------- | -------- |
| slot     | [`e_spell_slot`](../enums/e\_spell\_slot.md) | +        |
| position | [`vec3`](../structs/vec3.md)                 | +        |

`g_input:release_chargable(slot, position):` `void`
