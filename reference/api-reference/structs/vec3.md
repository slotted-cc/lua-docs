# vec3

## Members

* `x: number`
* `y: number`
* `z: number`

## Functions

### length

```
vec:length(): number
```

### length2d

```
vec:length2d(): number
```

### dist\_to

| Argument | Type   | Required |
| -------- | ------ | -------- |
| other    | `vec3` | +        |

```
vec:dist_to(other): number
```

### dot

| Argument | Type   | Required |
| -------- | ------ | -------- |
| other    | `vec3` | +        |

```
vec:dot(other): number
```

### cross

| Argument | Type   | Required |
| -------- | ------ | -------- |
| other    | `vec3` | +        |

```
vec:cross(other): number
```

### normalized

```
vec:normalized(): vec3
```

### angle\_between

| Argument | Type   | Required |
| -------- | ------ | -------- |
| other    | `vec3` | +        |

```
vec:angle_between(other): float
```

### rotated

| Argument | Type     | Required |
| -------- | -------- | -------- |
| angle    | `number` | +        |

```
vec:rotated(angle): vec3
```

### extend

| Argument | Type     | Required |
| -------- | -------- | -------- |
| to       | `vec3`   | +        |
| distance | `number` | +        |

```
vec:extend(to, distance): vec3
```

### to\_screen

```lua
vec:to_screen(): vec2 | nil
```
