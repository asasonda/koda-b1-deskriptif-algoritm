# Algoritma

## Algoritma Deskriptif Ganjil Genap

### Check Ganjil Genap

```
1. Mulai
2. Masukan Bilangan
3. Lakukan check bilangan menggunakan modulo
4. Jika bilangan habis dibagi 2 maka bilangan tersebut Genap
5. Jika bilangan tidak habis dibagi 2 maka bilangan tersebut bilangan Ganjil
6. Selesai
```

## Flowchart Ganjil Genap

### Check Ganjil Genap

```mermaid
flowchart TD
    start((Mulai)) --> Input[/Masukkan Angka/]
    Input --> proses[angka % 2 == 0]
    proses--> check{sisa bagi = 0?}
    check -- Ya --> genap[Bilangan adalah Genap]
    check -- Tidak --> ganjil[Bilangan adalah Ganjil]

    genap --> selesai(((stop)))
    ganjil --> selesai
```
