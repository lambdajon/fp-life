### Task

Agar musbat son o‘tgan bo‘lsa 1, manfiy raqam o‘tkazilgan bo‘lsa (-1) va 0 o‘tgan bo‘lsa 0 qaytaradigan belgi funksiyasining bajarilishini yozing.

### Example

```shell
GHCi> sign (-100)
-1
```

### Solution

```haskell
  sign x = if x >= 0 then (if x == 0 then 0 else 1) else (-1)
```
