# turret range

{% code title="turret-range.lua" %}
```lua
local turrets = {}

cheat.register_callback("render", function()
    for i, v in ipairs(turrets) do
        if v ~= nil and not v:is_dead() and not v:is_invisible() then
            g_render:circle_3d(v.position, color:new(255, 255, 0), 850.0, 2, 90, 2)
        end
    end
end)

cheat.register_callback("feature", function()
    turrets = features.entity_list:get_enemy_turrets()
end)
```
{% endcode %}
