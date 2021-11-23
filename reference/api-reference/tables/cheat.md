# cheat

### register\_callback

| Argument | Type       | Required |
| -------- | ---------- | -------- |
| name     | `string`   | +        |
| callback | `function` | +        |

```lua
cheat.register_callback( name, callback )

-- usage example
cheat.register_callback("render", function()
    print("hello from render callback")    
end)
```

#### Available callbacks

* `feature`
* `render`
* `pre_feature`
