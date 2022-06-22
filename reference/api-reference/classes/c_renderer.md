# c\_renderer

## Functions

### line

| Argument   | Type                         | Required |
| ---------- | ---------------------------- | -------- |
| start\_pos | [`vec2`](../structs/vec2.md) | +        |
| end\_pos   | [`vec2`](../structs/vec2.md) | +        |
| color      | `color`                      | +        |
| thickness  | `number`                     | +        |

`g_render:line(start_pos, end_pos, color, thickness):` `void`

### box

| Argument  | Type                         | Required |
| --------- | ---------------------------- | -------- |
| position  | [`vec2`](../structs/vec2.md) | +        |
| size      | [`vec2`](../structs/vec2.md) | +        |
| color     | `color`                      | +        |
| rounding  | `number`                     | +        |
| thickness | `number`                     | +        |

`g_render:box(position, size, color, rounding, thickness):` `void`

### filled\_box

| Argument | Type                         | Required |
| -------- | ---------------------------- | -------- |
| position | [`vec2`](../structs/vec2.md) | +        |
| size     | [`vec2`](../structs/vec2.md) | +        |
| color    | `color`                      | +        |
| rounding | `number`                     | +        |

`g_render:circle(position, color, radius, segments):` `void`

### circle

| Argument | Type                         | Required |
| -------- | ---------------------------- | -------- |
| position | [`vec2`](../structs/vec2.md) | +        |
| color    | `color`                      | +        |
| radius   | `number`                     | +        |
| segments | `number`                     | +        |

`g_render:circle(position, color, radius, segments):` `void`

### filled\_circle

| Argument | Type                         | Required |
| -------- | ---------------------------- | -------- |
| position | [`vec2`](../structs/vec2.md) | +        |
| color    | `color`                      | +        |
| radius   | `number`                     | +        |
| segments | `number`                     | +        |

`g_render:filled_circle(position, color, radius, segments):` `void`

### circle\_3d

| Argument  | Type                         | Required |
| --------- | ---------------------------- | -------- |
| position  | [`vec3`](../structs/vec3.md) | +        |
| color     | `color`                      | +        |
| radius    | `number`                     | +        |
| flags     | `number`                     | +        |
| segments  | `number`                     | +        |
| thickness | `number`                     | +        |

`g_render:circle_3d(position, color, radius, flags, segments, thickness):` `void`

### triangle

| Argument  | Type                         | Required |
| --------- | ---------------------------- | -------- |
| left      | [`vec2`](../structs/vec2.md) | +        |
| right     | [`vec2`](../structs/vec2.md) | +        |
| bottom    | [`vec2`](../structs/vec2.md) | +        |
| color     | `color`                      | +        |
| thickness | `number`                     | +        |

`g_render:triangle(left, right, bottom, color, thickness):` `void`

### filled\_triangle

| Argument | Type                         | Required |
| -------- | ---------------------------- | -------- |
| left     | [`vec2`](../structs/vec2.md) | +        |
| right    | [`vec2`](../structs/vec2.md) | +        |
| bottom   | [`vec2`](../structs/vec2.md) | +        |
| color    | `color`                      | +        |

`g_render:filled_triangle(left, right, bottom, color):` `void`

### load\_texture\_from\_file

| Argument   | Type     | Required |
| ---------- | -------- | -------- |
| file\_path | `string` | +        |

`g_render:load_texture_from_file(file_path):` `texture_t`

### image

| Argument | Type                         | Required |
| -------- | ---------------------------- | -------- |
| position | [`vec2`](../structs/vec2.md) | +        |
| size     | [`vec2`](../structs/vec2.md) | +        |
| texture  | `texture_t`                  | +        |

`g_render:image(position, size, texture):` `void`

### get\_screensize

`g_render:get_screensize():` [`vec2`](../structs/vec2.md)

### text

`g_render:text(position, color, text, font, size)`

| Argument | Type                               | Required |
| -------- | ---------------------------------- | -------- |
| position | [`vec2`](../structs/vec2.md)       | +        |
| color    | ``[`color`](../structs/color.md)`` | +        |
| text     | `string`                           | +        |
| font     | `string`                           | +        |
| size     | `number`                           | +        |

### get\_text\_size

`g_render:get_text_size(text, font, size): vec2 | nil`

| Argument | Type     | Required |
| -------- | -------- | -------- |
| text     | `string` | +        |
| font     | `string` | +        |
| size     | `number` | +        |
