# Exercice 1

```
VAR
T: tab;
n: integer;

BEGIN

- 1  FOR i:1 to n-1 DO
        [min←i]
        FOR j:i+1 to n DO
          IF ( T[j] < T[min]) {
            min ← j
          }
        ENDFOR
        IF ( min <> i) {
          x ←T[i]
          t[i]←T[min]
          t[min]←x
       }
      ENDFOR

END
```
