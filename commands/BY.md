## BY -- Set/Read the squelch status

### Set

```
BY p1,p2
```

### Get

```
BY p1
```

Returns: `p1,p2`

### Parameters

| p1 | Band   |
| -- | ------ |
| 0  | Band A |
| 1  | Band B |

| p2 | Squelch status |
| -- | -------------- |
| 0  | closed         |
| 1  | open           |

### Example

```
> BY 0
< BY 0,0
```
