# c\_orbwalker

## Functions

### send\_attack

| Argument    | Type     | Required |
| ----------- | -------- | -------- |
| network\_id | `number` | +        |

`features.orbwalker:send_attack(network_id):` `bool`

### is\_in\_attack

`features.orbwalker:is_in_attack():` `bool`

### send\_move\_input

| Argument | Type                         | Required |
| -------- | ---------------------------- | -------- |
| position | [`vec3`](../structs/vec3.md) | +        |
| force    | `bool`                       | +        |

`features.orbwalker:send_move_input(position, force):` `void`

### set\_cast\_time

| Argument | Type     | Required |
| -------- | -------- | -------- |
| time     | `number` | +        |

`features.orbwalker:set_cast_time(time):` `void`

### can\_move

`features.orbwalker:can_move():` `bool`

### is\_attackable

| Argument    | Type     | Required |
| ----------- | -------- | -------- |
| index       | `number` | +        |
| range       | `number` | +        |
| edge\_range | `bool`   | +        |

`features.orbwalker:is_attackable(index, range, edge_range):` `bool`

### get\_ping

`features.orbwalker:get_ping():` `number`

### get\_mode

`features.orbwalker:get_mode():` [`e_orbwalker_mode`](../enums/e\_orbwalker\_mode.md)

### reset\_aa\_timer

`features.orbwalker:reset_aa_timer():` `void`

### can\_attack

`features.orbwalker:can_attack():` `bool`

### should\_reset\_\_\_aa

`features.orbwalker:should_reset_aa():` `bool`

### on\_pre\_call

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| callback | `function` | +        |

`features.orbwalker:on_pre_call(callback):` `void`

### on\_post\_call

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| callback | `function` | +        |

`features.orbwalker:on_post_call(callback):` `void`
