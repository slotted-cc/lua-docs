# c\_buff\_cache

## Functions

### get\_buff

| Argument      | Type     | Required |
| ------------- | -------- | -------- |
| object\_index | `number` | +        |
| name          | `string` | +        |

`features.buff_cache:get_buff(object_name, name):` [`buff_cache_t`](../structs/buff\_cache\_t.md)``

### has\_buff\_of\_typ**e**

| Argument      | Type                                   | Required |
| ------------- | -------------------------------------- | -------- |
| object\_index | `number`                               | +        |
| type          | ``[`e_buff_type`](c\_buff\_cache.md)`` | +        |

`features.buff_cache:get_buff(object_index, type):` `bool`

### has\_hard\_cc

| Argument      | Type     | Required |
| ------------- | -------- | -------- |
| object\_index | `number` | +        |

`features.buff_cache:has_hard_cc(object_index):` `bool`

### is\_immobile

| Argument      | Type     | Required |
| ------------- | -------- | -------- |
| object\_index | `number` | +        |

`features.buff_cache:is_immobile(object_index):` `bool`

### can\_cast

| Argument      | Type     | Required |
| ------------- | -------- | -------- |
| object\_index | `number` | +        |

`features.buff_cache:can_cast(object_index):` `bool`

### get\_all\_buffs

| Argument      | Type     | Required |
| ------------- | -------- | -------- |
| object\_index | `number` | +        |

`features.buff_cache:get_all_buffs(object_index):` [`table<buff_cache_t>`](../structs/buff\_cache\_t.md)``
