## AS -- Set/Get reverse

### Set

    AS p1,p2

### Get

    AS p1

Returns: `p1,p2`

### Parameters

| p1 | function |
| -- | -------- |
| 0  | A band   |
| 1  | B band   |

| p2 | function |
| -- | -------- |
| 0  | Normal   |
| 1  | Reverse  |

### Example

```
> AS 0
< AS 0,0
> AS 0,1
< AS 0,1,0
```

### Notes

This documentation is partially incorrect; when reverse is enabled, the radio returns three paramters (`p1,p2,p3`).
