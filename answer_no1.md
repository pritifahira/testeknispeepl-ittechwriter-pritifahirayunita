# Cara Mengoperasikan Sepeda Ontel (Kayuh)

## 1. Pseudocode

```
BEGIN
    INPUT kondisi_sepeda
    IF kondisi_sepeda = "baik" THEN
        DUDUK di sadel
        LETAKKAN kaki pada pedal
        PEGANG tangan pada setang
        WHILE terus_mengayuh DO
            KAYUH pedal bergantian kanan–kiri
            JAGA keseimbangan
            IF ingin_berhenti = TRUE THEN
                LEPASKAN kayuhan
                TEKAN rem perlahan
                TURUNKAN kaki ke tanah
                EXIT LOOP
            ENDIF
        ENDWHILE
    ELSE
        OUTPUT "Sepeda tidak bisa digunakan"
    ENDIF
END
```

## 2. Diagram Alur (Flowchart)

```mermaid
flowchart TD
    A[Mulai] --> B[Periksa kondisi sepeda]
    B --> C{Kondisi baik?}
    C -- Tidak --> Z[Sepeda tidak bisa digunakan] --> J[Selesai]
    C -- Ya --> D[Duduk di sadel]
    D --> E[Letakkan kaki di pedal]
    E --> F[Pegang setang dengan kedua tangan]
    F --> G{Terus mengayuh?}
    G -- Ya --> H[Kayuh pedal bergantian]
    H --> I[Jaga keseimbangan]
    I --> G
    G -- Tidak --> K{Ingin berhenti?}
    K -- Ya --> L[Lepaskan kayuhan]
    L --> M[Tekan rem perlahan]
    M --> N[Turunkan kaki ke tanah]
    N --> J[Selesai]
```

created by: Priti Fahira Yunita at 10/9/2025
