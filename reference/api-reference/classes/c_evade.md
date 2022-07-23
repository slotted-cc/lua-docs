# c\_evade

## Functions

### is\_position\_safe

| Argument       | Type                         | Required |
| -------------- | ---------------------------- | -------- |
| position       | [`vec3`](../structs/vec3.md) | +        |
| safe\_distance | `bool`                       | +        |

`features.evade:is_position_safe(position, safe_distance):` `bool`

### is\_active

`features.evade:is_active():` `bool`

### on\_pre\_call

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| callback | `function` | +        |

`features.evade:on_pre_call(callback):` `void`

### on\_post\_call

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| callback | `function` | +        |

`features.evade:on_post_call(callback):` `void`

### get\_safe\_position

`features.evade:get_safe_position():` `vec3 | nil`

### disable\_this\_tick

`features.evade:get_safe_position():` `nil`
