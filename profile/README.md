#### **Tl;dr semua pihak saling merasa gak enak.**

```mermaid
sequenceDiagram
    participant Saya
    participant Ortu
    participant TS as Tukang Sayur
    participant II as Ibu Ibu

    Ortu->>Saya: Kasih kertas pesanan
    Saya->>Saya: Cek kertas pesanan
    loop Untuk setiap kertas pesanan
        Saya->>TS: Berikan kertas pesanan
        II-->>TS: Menunggu dengan perasaan menahan <br> marah (asumsi Saya)
        TS->>TS: Ambilkan semua barang yang ada di kertas
        TS->>Saya: Berikan barang 
        TS->>Saya: Tuliskan harga di kertas
        note over TS: Merasa tidak enak kepada saya dan ibu-ibu
        note over Saya: Merasa tidak enak karena <br> ibu-ibu yang ngantri jadi nunggu
    end
    Saya->>TS: Berikan total harga
    TS->>Saya: Kembalikan kertas dengan harga yang ditulis
    Saya->>Ortu: Kembalikan kertas pesanan dengan harga
```

#### Solusi: 

![proof of concept](https://github.com/Swalayand/catetin/blob/main/images/photo_2021-07-05_14-14-28.jpg)

Komponen:
1. [Precio 3a Scale](https://www.tokopedia.com/search?st=&q=3A%20Scale%20Timbangan%20Digital%20precio&srp_component_id=02.01.00.00&srp_page_id=&srp_page_title=&navsource=)
2. [sniffrr](https://github.com/Swalayand/sniffrr)

Baca [di sini](https://docs.google.com/document/d/18hRJtzPNbdbdG6hcYwAB81uORbHmQXsep5LHddbixRM/edit?usp=sharing) untuk mengetahui latar belakang.

#### Terimakasih

Terimakasih [@mamangopik](https://github.com/mamangopik/), [@faaiz282](https://github.com/faaiz282), Fauzan Askarillah dan semua orang yang mau membersamai saya dalam proses awal yang sulit.
