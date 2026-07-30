# Changelog
perubahan penting pada `MD Engine` didokumentasikan dalam file ini.

## MD Engine 2.0.0.3+dev [#Attachment](https://drive.google.com/drive/folders/1b5HyGccvt-XvHryczTat4MDOoW4OOUTs?usp=share_link)

## MD Engine 1.0.0 [#Attachment](https://drive.google.com/drive/folders/1TRqLbq-bz-91Ue_HK8PHjntd_tG8L2io?usp=share_link)

## 2023 Sept R6
### Added
- Penambahan Admin global Custome PPOB di MMB
- edit harga beli saja di tabel transaksi untuk custome denom
### Changed
- Optimasi u/ ppob custome
### Fixed
- Gopay Tubrukan dgn ppob custome 
- Optimized auto up
- Ceklist lepas replace denom 000
- set selisih 1 .. set hrg jual parsing di isi hrg produk
- MMB autoup di set 1 tdk akan merubah harga jual

## 2023 Agt R4
### Added
- Replace custome denom 000 to supplier
- Add pay ppob custome "betha"
### Changed
- Custome Replay tambah saldo via Admin
  ```
    <tujuan> <reseller> <nohpupline> <namareseller> <depositawal> <jumlah> <deposit> <sn> <hutang> <datetime>
  ```
### Fixed 
- Update hrg jual beli di dalam parsing (Runtime Err)
- Optimasi Script WA Center
- Auto Up set(1) tdk merubah harga jual mmb xmpp

### Changed
- Curl 8.1.1 to 8.2.1

## 2023 Juni R7
### Fixed
- Tiket Deposit xmpp
- Fix TP Pulsa Indosat
- Fix Replace Karakter `|` MMB xmpp
- Fix script corrupt di laravel api2
- Fix matikan parsing via sms,wa,telegram,jabber
- Fix Set Status Reseller
### Changed
- Curl 8.1.0 to 8.1.1
### Added
- Wa Api (U/ Broadcase Iklan/Promo)
- Modul APK support kirim notifikasi ke WhatsApp
- Addon MMB wa
- support Target custome mmb wa
## 2023 APR R7
### Fixed
- Config Request
- trx tanpa pin saat menggunakan kode produk
- Gagalkan produk tidak terdaftar dan tidak nyelonong di trx tanpa kode
- Fix display Tot dep, piutang, rebat, poin di daftar reseller
- Fix Tiket Deposit
- Fix MMC xmpp
- Fix notif long wapi

## 2023 MAR R8
### Added 
- Rename Terminal Home
- Auto insert Hrg default beli/jual di edit parsing (jika harga 0)
### Changed
- Curl 7.88.1 to 8.0.1
- Rename Checkbox Filter WA jadi Send To WA
### Fixed
- I-Simple Dinamis Produk
- Expired System
- Fixed Kirim Pesan ke multi center WA (Random)
- Fixed tambah deposit yg belum menentukan pilihan reseller
- Fix digipos Api
- Fix Api apk_v3 varian combination
- Tuning form reseller
- Fix Apk v3 Price Option of combination
### Added
- Send Iklan/Promo ke WhatsApp
- Button Dealer dan Agen di Kirim Pesan Manual
- Kirim Pesan WA ke Nomer yang belum tersimpan di contact
- Add Button Hal from Trx
- Tabel Reseller New
### Removed
- Tabel Reseller old
