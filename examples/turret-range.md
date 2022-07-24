# Turret range

{% code title="turret-range.lua" %}
```lua
cheat.register_callback("render", function()
    local turrets = features.entity_list:get_enemy_turrets()
    for i, v in ipairs(turrets) do
        if v ~= nil and not v:is_dead() and not v:is_invisible() then
            g_render:circle_3d(v.position, color:new(255, 255, 0), 850.0, 2, 90, 2)
        end
    end
end)
```
{% endcode %}
