# Sizing Components Motor Listrik

Materi pembelajaran mengenai perhitungan dan pemilihan komponen pada sistem motor listrik, khususnya MCB/MCCB, contactor, overload relay, kabel, serta rangkaian DOL dan Star-Delta.

Repository ini dibuat sebagai pendamping video pembelajaran mata kuliah **Mesin-Mesin Listrik** di Program Studi Teknologi Rekayasa Otomasi, Universitas Diponegoro.

## Tujuan Pembelajaran

- Memahami fungsi komponen pada rangkaian motor listrik.
- Menghitung arus nominal motor induksi tiga fasa.
- Memahami dasar pemilihan MCB/MCCB, contactor, dan overload relay.
- Mempelajari pemilihan komponen pada rangkaian DOL dan Star-Delta.
- Memahami pentingnya memeriksa katalog pabrikan dan standar instalasi.

## Materi yang Dibahas

1. Pengenalan sizing components.
2. Data motor dan perhitungan arus nominal.
3. Pemilihan MCB/MCCB.
4. Pemilihan contactor.
5. Pemilihan overload relay.
6. Pertimbangan ukuran kabel.
7. Sizing komponen rangkaian DOL.
8. Sizing komponen rangkaian Star-Delta.
9. Pengaruh posisi overload relay terhadap pengaturannya.
10. Validasi pemilihan komponen.

## Contoh Perhitungan

Contoh data motor:

| Parameter | Nilai |
|---|---:|
| Daya keluaran motor | 5,5 kW |
| Tegangan antar-fasa | 380 V |
| Faktor daya | 0,92 |
| Efisiensi | 85,7% |

Rumus perkiraan arus nominal motor tiga fasa:

\[
I = \frac{P}{\sqrt{3}\times V\times \cos\varphi\times\eta}
\]

Dengan daya keluaran 5.500 watt:

\[
I = \frac{5500}{1{,}732\times380\times0{,}92\times0{,}857}
\]

Hasil perhitungan:

**Arus nominal ≈ 10,59 A**

Hasil ini merupakan contoh perhitungan berdasarkan data yang digunakan dalam materi. Untuk pemilihan komponen pada motor nyata, periksa juga data pada nameplate motor dan rekomendasi pabrikan.

## Catatan Teknis

Angka pengali dalam contoh sizing merupakan metode pembelajaran dan tidak selalu berlaku untuk semua instalasi. Pemilihan akhir harus mempertimbangkan karakteristik motor, metode starting, rating perangkat, kemampuan hantar arus kabel, koordinasi proteksi, katalog pabrikan, dan standar yang berlaku.

Pada rangkaian Star-Delta, pemilihan contactor dan pengaturan overload relay bergantung pada konfigurasi rangkaian serta posisi pemasangan relay.

## File Repository

Repository ini dapat berisi:

- `Sizing_Components_Revisi_Font_Aman.pptx` — materi presentasi.
- `Script_Presentasi_Sizing_Components.txt` — naskah video presentasi.
- `README.md` — informasi dan ringkasan materi.

Nama file di atas perlu disesuaikan dengan file yang benar-benar diunggah ke repository.

## Identitas

**Nama:** Yogatama Prabantara  
**Program Studi:** Teknologi Rekayasa Otomasi  
**Institusi:** Sekolah Vokasi, Universitas Diponegoro  
**Mata Kuliah:** Mesin-Mesin Listrik

---

Materi ini dibuat untuk tujuan pembelajaran dan tidak menggantikan proses perancangan, verifikasi, maupun pemeriksaan keselamatan instalasi oleh personel yang kompeten.
