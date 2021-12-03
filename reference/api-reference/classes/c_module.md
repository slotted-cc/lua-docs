# c\_module

## Members

* `priority_list: table<e_spell_flag>`

## Functions

### spell\_q

```lua
module:spell_q(): bool
```

### spell\_w

```
module:spell_w(): bool
```

### spell\_e

```
module:spell_e(): bool
```

### spell\_r

```
module:spell_r(): bool
```

### disable\_q\_on

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| func     | `function` | +        |

```lua
module:disable_q_on(func)

-- example usage
module:disable_q_on(function()
    -- always disable q
    return true
end)
```

### disable\_w\_on

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| func     | `function` | +        |

```lua
module:disable_w_on(func)
```

### disable\_e\_on

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| func     | `function` | +        |

```lua
module:disable_e_on(func)
```

### disable\_r\_on

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| func     | `function` | +        |

```lua
module:disable_r_on(func)
```

### get\_slot\_q

```
module:get_slot_q(): c_spell_slot
```

### get\_slot\_w

```
module:get_slot_w(): c_spell_slot
```

### get\_slot\_e

```
module:get_slot_e(): c_spell_slot
```

### get\_slot\_r

```
module:get_slot_r(): c_spell_slot
```
