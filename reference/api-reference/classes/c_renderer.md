# c\_renderer

## Functions

### line

| Argument   | Type     | Required |
| ---------- | -------- | -------- |
| start\_pos | `vec2`   | +        |
| end\_pos   | `vec2`   | +        |
| color      | `color`  | +        |
| thickness  | `number` | +        |

```lua
g_render:line(start_pos, end_pos, color, thickness)
```

### box

| Argument  | Type     | Required |
| --------- | -------- | -------- |
| position  | `vec2`   | +        |
| size      | `vec2`   | +        |
| color     | `color`  | +        |
| rounding  | `number` | +        |
| thickness | `number` | +        |

```
g_render:box(position, size, color, rounding, thickness)
```

### filled\_box

| Argument | Type     | Required |
| -------- | -------- | -------- |
| position | `vec2`   | +        |
| size     | `vec2`   | +        |
| color    | `color`  | +        |
| rounding | `number` | +        |

```
g_render:filled_box(position, size, color, rounding)
```

### circle

| Argument | Type     | Required |
| -------- | -------- | -------- |
| position | `vec2`   | +        |
| color    | `color`  | +        |
| radius   | `number` | +        |
| segments | `number` | +        |

```
g_render:circle(position, color, radius, segments)
```

### filled\_circle

| Argument | Type     | Required |
| -------- | -------- | -------- |
| position | `vec2`   | +        |
| color    | `color`  | +        |
| radius   | `number` | +        |
| segments | `number` | +        |

```
g_render:filled_circle(position, color, radius, segments)
```

### circle\_3d

| Argument  | Type     | Required |
| --------- | -------- | -------- |
| position  | `vec3`   | +        |
| color     | `color`  | +        |
| radius    | `number` | +        |
| flags     | `number` | +        |
| segments  | `number` | +        |
| thickness | `number` | +        |

```
g_render:circle_3d(position, color, radius, flags, segments, thickness)
```

### triangle

| Argument  | Type     | Required |
| --------- | -------- | -------- |
| left      | `vec2`   | +        |
| right     | `vec2`   | +        |
| bottom    | `vec2`   | +        |
| color     | `color`  | +        |
| thickness | `number` |          |

```
g_render:triangle(left, right, bottom, color, thickness)
```

### filled\_triangle

| Argument | Type    | Required |
| -------- | ------- | -------- |
| left     | `vec2`  | +        |
| right    | `vec2`  | +        |
| bottom   | `vec2`  | +        |
| color    | `color` | +        |

```
g_render:filled_triangle(left, right, bottom, color)
```

### load\_texture\_from\_file

| Argument   | Type     | Required |
| ---------- | -------- | -------- |
| file\_path | `string` | +        |

```
g_render:load_texture_from_file(file_path): texture_t
```

### image

| Argument | Type        | Required |
| -------- | ----------- | -------- |
| position | `vec2`      | +        |
| size     | `vec2`      | +        |
| texture  | `texture_t` | +        |

```
g_render:image(position, size, texture)
```

### get\_screensize

```
g_render:get_screensize(): vec2
```
