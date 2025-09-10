# Bahasa C Deret Fibonaci

## Pseudocode Teknis

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

## Pseudocode Dokumen Bisnis

```
MULAI
    Minta pengguna memasukkan jumlah bilangan Fibonacci (n)
    Untuk setiap angka dari 0 sampai n-1:
        Hitung nilai Fibonacci menggunakan aturan:
            - Jika angka <= 1, nilainya adalah angka itu sendiri
            - Jika lebih besar, jumlahkan dua angka sebelumnya
        Tampilkan hasil
SELESAI
```

created by: Priti Fahira Yunita at 10/9/2025

