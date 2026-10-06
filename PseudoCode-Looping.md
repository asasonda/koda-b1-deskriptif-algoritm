``` mermaid
flowchart TD
    start((Mulai)) --> init[i <- 1]
    init --> check{i <= 10?}
    check -- yes --> kondisional{i % 2 == 0}
    kondisional -- yes --> out[/Fizzbuzz/]
    out --> increment[i++]
    kondisional -- no --> print[/Output i/]
    increment --> check
    print --> increment
    check -- no --> selesai(((selesai)))

```

```pseudocode
FOR i <- 1 TO 10 STEP 1
    IF i % 2 = 0 THEN
        OUTPUT "Fizzbuzz"
    ELSE
        OUTPUT i
    ENDIF
NEXT i
```
