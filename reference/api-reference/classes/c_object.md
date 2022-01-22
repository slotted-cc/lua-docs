# c\_object

## Members

* `index: number`
* `next_object_index: number`
* `team: number`
* `network_id: number`
* `framecount: number`
* `position: vec3`
* `mana: number`
* `max_mana: number`
* `mana_enabled: number`
* `physical_damage_percentage_modifier: number`
* `magical_damage_percentage_modifier: number`
* `health: number`
* `max_health: number`
* `bonus_attack: number`
* `bonus_attack_speed: number`
* `life_steal: number`
* `attack_speed: number`
* `base_attack: number`
* `crit_chance: number`
* `toal_armor: number`
* `bonus_armor: number`
* `total_mr: number`
* `base_health_regen: number`
* `total_health_regen: number`
* `movement_speed: number`
* `attack_range: number`
* `gold: number`
* `total_gold: number`
* `min_gold: number`
* `max_gold: number`
* `champion_name: lstring`
* `level: number`

## Functions

### is\_recalling

```lua
object:is_recalling(): bool
```

### is\_local

```
object:is_local(): bool
```

### is\_game\_object

```
object:is_game_object(): bool
```

### is\_dead\_object

```
object:is_dead_object(): bool
```

### is\_invalid\_object

```
object:is_invalid_object(): bool
```

### is\_neutral\_camp

```
object:is_neutral_camp(): bool
```

### is\_ai\_base\_common

```
object:is_ai_base_common(): bool
```

### is\_attackable\_unit

```
object:is_attackable_unit(): bool
```

### is\_ai

```
object:is_ai(): bool
```

### is\_minion

```
object:is_minion(): bool
```

### is\_hero

```
object:is_hero(): bool
```

### is\_building

```
object:is_building(): bool
```

### is\_missile

```
object:is_missile(): bool
```

### is\_invisible

```
object:is_invisible(): bool
```

### is\_visible

```
object:is_visible(): bool
```

### is\_targetable

```
object:is_targetable(): bool
```

### is\_alive

```
object:is_alive(): bool
```

### is\_dead

```
object:is_dead(): bool
```

### is\_enemy

```
object:is_enemy(): bool
```

### is\_ally

```
object:is_ally(): bool
```

### dist\_to\_local

```
object:dist_to_local(): number
```

### get\_attack\_damage

```
object:get_attack_damage(): number
```

### get\_bonus\_attack\_damage

```lua
object:get_bonus_attack_damage(): number
```

### get\_spell\_book

```
object:get_spell_book(): c_spell_book
```

### get\_buff\_manager

```lua
object:get_buff_manager(): c_buff_manager
```

### get\_object\_name

```lua
object:get_object_name(): string
```
