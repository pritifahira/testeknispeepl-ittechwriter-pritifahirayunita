# Bahasa C Deret Fibonaci

## Pseudocode

```
BEGIN
    INPUT n
    FUNCTION fibonacci(x):
        IF x <= 1 THEN
            RETURN x
        ELSE
            RETURN fibonacci(x - 1) + fibonacci(x - 2)
        ENDIF
    END FUNCTION
    OUTPUT "Deret Fibonacci hingga n adalah:"
    FOR i = 0 TO n-1 DO
        OUTPUT fibonacci(i)
    ENDFOR
END
```

created by: Priti Fahira Yunita at 10/9/2025

