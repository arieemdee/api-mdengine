# WS Parse
### MMC
```
- cara daftarnya 192.168.1.12ws@xml
- URL Callback = http://192.168.1.12/ws/report/?
```

### MMB 
```
- http://<ip>:<port>/ws/trx/?kdrs=<username>&password=<password>&kdproduk=KV100&tujuan=<tujuan>&trxid=<trxid>
- Cek Saldo = <ip>:<port>/ws/trx/?kdrs=rs001
```

# API Parse
### MMC
```
- Create Username : - kdrs@xml , lintas software usernomd@xml 
                    - 192.100.23.92@xml
- Url Callback
  http://8.215.29.1:8888/ws/report/?pesan=
  http://8.215.29.1:8888/ws/report/cb84.php
```


### MMB
```
- <ip>:<port>/api/trx/index/91/<username>/HX25/<tujuan>/<password>/<trxid>
```
