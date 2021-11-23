# c\_renderer

## Functions

### line

```lua
g_render:line(start_pos, end_pos, color, thickness)
```

### box

```
g_render:box(position, size, color, rounding, thickness)
```

### filled\_box

```
g_render:filled_box(position, size, color, rounding)
```

### circle

```
g_render:circle(position, color, radius, segments)
```

### filled\_circle

```
g_render:filled_circle(position, color, radius, segments)
```

### circle\_3d

```
g_render:circle_3d(position, color, radius, flags, segments, thickness)
```

### triangle

```
g_render:triangle(left, right, bottom, color, thickness)
```

### filled\_triangle

```
g_render:filled_triangle(left, right, bottom, color)
```

### load\_texture\_from\_file

```
g_render:load_texture_from_file(file_path): texture_t
```

### image

```
g_render:image(position, size, texture)
```

### get\_screensize

```
g_render:get_screensize(): vec2
```
