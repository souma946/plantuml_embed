## example

### Description
---
This table is for XXX.

### Columns
---
| Field | Type | Default |  Nullable | Comment |
| --- | --- | --- | --- | --- | 
|  e1_id | number | 0 | No | Comment |
| name | text | "" | Yes    | Name column |
| description | text | "" | Yes | Description column |

### Constraints
---
| Name | Type | Definition |
| --- | --- | --- |
|  PRIMARY | PRIMARY KEY | PRIMARY KEY(e1_id) | 

### Indexes
---
| Name | Definition |
| --- | --- |
| idx_name | KEY idx_name(name) | 
