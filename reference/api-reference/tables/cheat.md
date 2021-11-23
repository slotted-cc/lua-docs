# cheat

### register\_callback

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| name     | `string`   | +        |
| callback | `function` | +        |

```lua
cheat.register_callback(name, callback)

-- usage example
cheat.register_callback("render", function()
    print("hello from render callback")    
end)
```

#### Available callbacks

* `feature`
* `render`
* `pre_feature`

### register\_module

| Argument | Type    | Required |
| -------- | ------- | -------- |
| module   | `table` | +        |

| Key            | Type       | Return type | Required |
| -------------- | ---------- | ----------- | -------- |
| champion\_name | `string`   | -           | +        |
| on\_draw       | `function` | -           | -        |
| spell\_q       | `function` | bool        | -        |
| spell\_w       | `function` | bool        | -        |
| spell\_e       | `function` | bool        | -        |
| spell\_r       | `function` | bool        | -        |
| initialize     | `function` | -           | -        |

Data passed to all spell\_\* functions is of type [champion\_module\_spell\_data\_t](../structs/champion\_module\_spell\_data\_t.md).

Functions for spells will only be called when the slot is ready.

```lua
-- example usage 
local registered = cheat.register_module({
    "champion_name" = "Ezreal",
    "spell_q" = function(data)
        return false
    end
})
```
