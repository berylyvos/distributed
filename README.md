# distributed
### Architecture

```mermaid
  flowchart TD
    Client --> 1[Portal Service] --> 2[Log Service] & 3[Business Service]
    3 --> 2
    1 <-.-> 4[Registry Service]
    2 <-.-> 4
    3 <-.-> 4
```

### Acknowledgement
软件工艺师@bilibili [BV1ZU4y1577q](https://www.bilibili.com/video/BV1ZU4y1577q)
