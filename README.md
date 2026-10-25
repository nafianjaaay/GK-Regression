# GK-Regression Dataset

Data primer log penglihatan (*vision log*) kamera robot kiper.

## Struktur Data

Data tersimpan dalam format CSV dengan kolom `Y,U,V`:
- `data_yuv/ball/`: Data piksel bola oranye ( `yuv_2023_1_15_21_55.csv`)
- `data_yuv/field/`: Data piksel rumput hijau lapangan ( `yuv_2023_1_15_21_50.csv`)
- `data_yuv/line/`: Data piksel garis putih lapangan ( `yuv_2023_1_15_21_58.csv`)

## Format Kolom
- **Y**: Luminansi (Kecerahan piksel, skala 0–255)
- **U**: Krominansi Biru (skala 0–255)
- **V**: Krominansi Merah (skala 0–255)
