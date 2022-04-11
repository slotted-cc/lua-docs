# rectangle\_t

## Constructors

`rectangle_t:new(start, end, width_start)`

## Members

* `direction:` [`vec3`](vec3.md)``
* `perpendicular:` [`vec3`](vec3.md)``
* `r_end:` [`vec3`](vec3.md)``
* `r_start:` [`vec3`](vec3.md)``
* `width: number`

## Functions

### to\_polygon

| Argument        | Type     | Required |
| --------------- | -------- | -------- |
| offset          | `number` | +        |
| override\_width | `number` | +        |

### intersection

| Argument | Type     | Required |
| -------- | -------- | -------- |
| circle   | `circle` | +        |
