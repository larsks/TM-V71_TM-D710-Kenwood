## DM -- DTMF memory

### Set

    DM p1,p2

### Get

    DM p1

returns: p1,p2

### Parameters

| p1  | function         |
| --- | ---------------- |
| 0-9 | DTMF channel 0-9 |

| p2               | function                                                                                  |
| ---------------- | ----------------------------------------------------------------------------------------- |
| nnnnnnnnnnnnnnnn | DTMF code 16 digits. For codes with fewer digits, replace the remaining digits with SPACE |
