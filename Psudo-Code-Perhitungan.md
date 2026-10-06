# Algoritma

## Algoritma Deskriptif

```
1. Mulai
2. Masukan Nilai A = 1
3. Masukan Nilai B = 1
4. Masukan Nilai C = 0
5. Hitung A x B + C
6. Tampilkan Hasil perhitungan
7. Selesai
```

## Flowchart
``` mermaid
flowchart TD
    start((Mulai))
    inputA[/Masukan Nilai A/]
    inputB[/Masukan Nilai B/]
    inputC[/Masukan Nilai C/]
    proses[Hasil = A x B + C]
    hasil[/Tampilkan Hasil/]
    selesai(((Selesai)))
    start --> inputA --> inputB --> inputC --> proses --> hasil --> selesai
```

## Pesudo Code

### Perhitungan

```pseudo-code
DECLARE A : INTEGER
DECLARE B : INTEGER
DECLARE C : INTEGER
DECLARE Hasil : INTEGER

A <- 1
B <- 1
C <- 0

Hasil <- A * B + 0
OUTPUT "Hasil A*B+0 = ", Hasil
```
