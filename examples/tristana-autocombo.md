# Tristana autocombo

{% code title="combo-example.lua" %}
```lua
cheat.register_module({
    champion_name = "Tristana",
    spell_q = function(data)
        if features.buff_cache:get_buff(g_local.index, "TristanaW") ~= nil or not features.orbwalker:should_reset_aa() then
            return false
        end

        return g_input:cast_spell(e_spell_slot.q, nil)
    end,
    spell_e = function(data)
        local target = features.target_selector:get_default_target()

        if target == nil or not features.orbwalker:is_attackable(target.index, 0.0, true) then
            return false
        end

        if features.buff_cache:get_buff(target.index, "tristanaecharge") ~= nil then
            return false
        end

        if g_input:cast_spell(e_spell_slot.q, nil) then
            features.orbwalker:set_cast_time(features.orbwalker:get_attack_cast_delay())
            return true
        end

        return false
    end,
    initialize = function()
        print("initializing module")
        -- setup menu here
    end,
    get_priorities = function()
        return {
            "spell_e",
            "spell_q"
        }
    end
})
```
{% endcode %}
