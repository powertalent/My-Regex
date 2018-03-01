# My-Regex
My Regular Expression Collection

1. Find all text outside bracket （ex : 「」）
```Regex
[^「」\r\n]*(?=(「.*?」|$))
```
