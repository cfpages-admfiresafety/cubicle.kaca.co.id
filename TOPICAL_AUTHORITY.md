# Topical Authority — cubicle.kaca.co.id

## Role and boundary

cubicle.kaca.co.id berperan sebagai penyedia fabrikasi dan pemasangan sistem cubicle/partisi kaca tempered untuk toilet, kantor, dan pembagian ruang. Hub edukasi ini membantu pemilik proyek, desainer, kontraktor, pengelola fasilitas, serta tim pengadaan menyusun kebutuhan, menilai opsi, mengoordinasikan pemasangan, dan merawat sistem. Batasnya bukan katalog stok, daftar harga tetap, gambar kerja final, perhitungan struktur, desain aksesibilitas atau area basah final, dan bukan sumber klaim jenis/ketebalan kaca, kapasitas hardware, beban, keselamatan, privasi, standar, sertifikasi, garansi, maupun performa tanpa bukti produk dan proyek yang berlaku.

## Context used

- Empat sitemap utama diperiksa: `sitemap-complete.xml`, `page-sitemap.xml`, `post-sitemap1.xml`, dan `post-sitemap2.xml`. Sitemap lengkap memuat 215 URL unik dan selaras dengan 215 file HTML.
- Dari 215 URL sitemap lengkap, 102 adalah pola `toilet-<kota>` dan 101 adalah pola `kantor-<kota>`. Keduanya diperlakukan sebagai dua keluarga intent, bukan 203 topik geografis.
- Rute bermakna non-lokasi adalah homepage, `cubicle`, `cubicle/kantor`, `cubicle/toilet`, `partisi`, `berita`, `tentang-kami`, `kontak-kami`, dan dua arsip kategori.
- Homepage publik memakai H1 “Cubicle Kaca Tempered Partisi”, menyebut fabrikasi/pemasangan, dan menaut ke cubicle kantor, cubicle toilet, serta partisi kaca.
- Hub produk menguatkan konteks semantik: cubicle kantor/partisi kantor, cubicle toilet/partisi kamar mandi, serta partisi kaca ruangan.
- Mode lean dipertahankan. Isu kaca, hardware, dukungan, beban, pecah, area basah, aksesibilitas, toleransi, standar, dan sertifikasi dicatat sebagai gerbang publikasi.

## Ignored template noise

- 203 halaman pertukaran nama kota pada keluarga `toilet-<kota>` dan `kantor-<kota>` dihitung, tetapi isi dan metadata berulangnya tidak dianalisis.
- Image `<loc>` yang berulang di sitemap Rank Math tidak dihitung sebagai halaman atau intent editorial.
- Arsip kategori, berita, upload, cache, manifest, serta file teknis tidak dipakai untuk memperluas taksonomi.
- README dan metadata template tidak dibaca karena sitemap XML, homepage, dan hub produk sudah memberi konteks keputusan yang cukup.

## Topical map

| Topic ID | Parent topic | Reader outcome | Boundary | Article target |
|---|---|---|---|---:|
| CUB-01 | Dasar sistem cubicle dan partisi kaca | Memahami komponen, istilah, dan batas sistem sebelum memilih | Fondasi konsep; tidak menetapkan jenis atau ketebalan kaca produk tertentu | 6 |
| CUB-02 | Brief dan pemilihan sistem | Menerjemahkan fungsi ruang, pengguna, dan anggaran menjadi shortlist sistem | Edukasi kebutuhan lintas aplikasi; permintaan penawaran tetap di rute komersial | 6 |
| CUB-03 | Jenis, ketebalan, dan olahan kaca | Menilai opsi kaca dan dokumen yang mendukung pemilihannya | Jenis, ketebalan, heat treatment, dan performa hanya boleh disebut berdasarkan bukti aktual | 6 |
| CUB-04 | Privasi, cahaya, dan pengalaman ruang | Mengatur transparansi, visual privacy, pencahayaan, dan batas klaim akustik | Fokus pengalaman ruang; bukan spesifikasi kaca, film, atau performa teruji tanpa data | 6 |
| CUB-05 | Hardware, frame, dan konektor | Memilih sistem bukaan, frame, fitting, serta kompatibilitas komponennya | Kapasitas, material, dan kompatibilitas hardware wajib mengikuti data sistem | 6 |
| CUB-06 | Dukungan, beban, dan koordinasi struktur | Mengenali jalur beban, kondisi tumpuan, dan pemicu review insinyur | Bukan perhitungan struktur atau persetujuan kapasitas bangunan | 6 |
| CUB-07 | Pecah, keselamatan, dan respons insiden | Mengurangi paparan risiko dan menyiapkan respons bila kaca rusak | Bukan jaminan aman atau pengganti penilaian profesional, standar, dan prosedur lokasi | 6 |
| CUB-08 | Cubicle dan partisi kantor | Merencanakan zonasi, sirkulasi, pintu, dan perubahan layout kantor | Khusus ruang kerja; tidak mengambil intent toilet, general partition, atau rute jasa lokasi | 6 |
| CUB-09 | Cubicle toilet dan area basah | Merencanakan privasi, celah, hardware, air, ventilasi, dan pembersihan toilet | Khusus cubicle toilet; kelayakan wet-area harus dibuktikan untuk sistem aktual | 6 |
| CUB-10 | Aksesibilitas dan penggunaan inklusif | Mengidentifikasi kebutuhan ruang gerak, pintu, hardware, dan koordinasi fasilitas | Panduan brief dan review; bukan deklarasi patuh atau desain aksesibilitas final | 6 |
| CUB-11 | Survei, dimensi, dan toleransi | Menghasilkan data lapangan dan koordinasi ukuran yang dapat diperiksa | Bukan shop drawing final; angka toleransi mengikuti sistem dan proyek aktual | 6 |
| CUB-12 | Pemasangan dan antarmuka bangunan | Mengoordinasikan kesiapan lokasi, urutan kerja, sambungan, dan serah terima | Bukan metode pemasangan universal atau pengganti instruksi produsen/pemasang | 6 |
| CUB-13 | Pembersihan, inspeksi, dan pemeliharaan | Menjalankan perawatan rutin serta mengenali kondisi yang perlu ditindaklanjuti | Tidak menjanjikan higienitas atau umur layanan; insiden pecah dimiliki CUB-07 | 6 |
| CUB-14 | Desain custom, sampel, dan persetujuan | Mengendalikan brief, visual, mockup, sampel, dan perubahan desain | Proses persetujuan; bukan janji semua bentuk, finish, atau konfigurasi dapat dibuat | 6 |
| CUB-15 | Pengadaan, harga, logistik, dan garansi | Menyiapkan RFQ, membandingkan biaya, mengatur pengiriman, dan membaca garansi | Harga dan garansi harus aktual; transaksi tetap berada di rute kontak/produk | 6 |
| CUB-16 | Standar, sertifikasi, QA, dan dokumentasi | Memeriksa relevansi bukti kepatuhan dan kelengkapan serah terima | Tidak menyatakan patuh atau tersertifikasi tanpa dokumen, ruang lingkup, dan verifikasi aktual | 6 |

## Internal-link rule

Setiap artikel menaut ke hub topiknya, satu artikel pendamping dalam topik yang sama, dan satu atau dua topik tetangga yang mendukung langkah berikutnya. Artikel pemilihan dapat mengarah ke hub komersial `cubicle`, `cubicle/kantor`, `cubicle/toilet`, atau `partisi`; tidak ada artikel baru berbasis kota. Setiap pembahasan jenis/ketebalan kaca, heat treatment, hardware, support, beban, risiko pecah, keselamatan, privasi teruji, area basah, aksesibilitas, toleransi, standar, sertifikasi, garansi, dan harga harus menahan angka atau klaim sampai dokumen produk/proyek yang relevan tersedia.

## First publication wave

Terbitkan 12 aset fondasi dan keputusan terlebih dahulu: `CUB-01-01`, `CUB-02-01`, `CUB-02-02`, `CUB-03-01`, `CUB-05-01`, `CUB-06-01`, `CUB-07-01`, `CUB-08-01`, `CUB-09-01`, `CUB-10-01`, `CUB-11-01`, dan `CUB-15-01`. Gelombang ini membangun kosakata, brief, jalur pemilihan, dan gerbang bukti bagi dua aplikasi utama tanpa memperluas halaman lokasi.
