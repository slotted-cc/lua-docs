# c\_target\_selector

## Functions

### get\_default\_target

`features.target_selector:get_default_target():` [`c_object`](c\_object.md) | `nil`

### get\_orbwalker\_default\_target

`features.target_selector:get_orbwalker_default_target():` [`c_object`](c\_object.md) | `nil`

### get\_forced\_target

`features.target_selector:get_forced_target():` [`c_object`](c\_object.md) | `nil`

### is\_forced

`features.target_selector:is_forced():` `bool`

### is\_bad\_target

| Argument | Type     | Required |
| -------- | -------- | -------- |
| index    | `number` | +        |

`features.target_selector:is_bad_target(index):` `bool`

### force\_target

| Argument | Type                                     | Required |
| -------- | ---------------------------------------- | -------- |
| object   | `number` \| [`c_object`](c\_object.md)`` | +        |

To reset forced target call force\_target with nil or -1 as object argument

`features.target_selector:force_target(object):` `bool`

``
