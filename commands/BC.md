## BC -- Set/Get PTT and CTRL band

### Set

    BC p1,p2

### Get

    BC

Returns: `p1,p2`

### Parameters

| p1 | function    |
| -- | ----------- |
| 0  | Ctrl A Band |
| 1  | Ctrl B band |

| p2 | function   |
| -- | ---------- |
| 0  | PTT A Band |
| 1  | PTT B band |

### Example

```
> BC
< BC 1,1
> BC 0,0
< BC 0,0
> BC
< BC 0,0
```
