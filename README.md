## Clone Project ini
```bash
> git clone https://github.com/Arief-zx/AnonymousBot
```
## Install MongoDB
> Cara Install di <a href="https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/">Windows</a><br/><br/>
> Cara Install di <a href="https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/">MacOs</a><br/><br/>
> Cara Install di <a href="https://docs.mongodb.com/manual/administration/install-on-linux/">Linux</a></br><br/>
Atau bisa menggunakan <a href="https://www.mongodb.com/cloud/atlas/efficiency?utm_source=google&utm_campaign=gs_apac_indonesia_search_core_brand_atlas_desktop&utm_term=mongo%20atlas&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=12212624350&gclid=Cj0KCQiAj9iBBhCJARIsAE9qRtAQJcOiNr05S5hAZuJL01Q7ZMEmPdEJwm7hk4-y9hrfy0N5VQfvOCgaAtsXEALw_wcB">Mongo Atlas</a>

## Config
Edit di `src/libs/settings.json`
```bash
{
 > "prefix": "z", //Isi sesuai Prefix yang kamu mau
 > "ownerNumber": "62xxxxxx" //Isi nomor hp kamu
}
```
## Database Config
Edit di `.env`
```bash
> MONGO_URI=mongodb://localhost:27017/anonymxs //ganti sesuai ip Database, jika menggunakan localhost bisa skip
```

## Run
```bash
> cd Anonymxs
> npm i
> npm start
```

## Command & Fitur
| Anonymxs |  Command  |                       Fungsi                       |
|----------|:---------:|:--------------------------------------------------:|
|     ✅    | zregister |   Mendaftar akun, pakai username? pull request :)  |
|     ✅    |   zstart  |       Memulai mencari Partner (lawan Bicara)       |
|     ✅    |   znext   | Menghentikan Sesi sebelumnya dan mencari Sesi baru |
|     ✅    |   zstop   |                  Menghentikan Sesi                 |
<br>

| Anonymxs      |               Fitur              |
|---------------|:--------------------------------:|
|       ✅       |       Bicara antar Partner       |
| Bayar, xixixi | Mengirim Sticker/Sticker Animasi |
| Bayar, xixixi |          Mengirim Lokasi         |
| Bayar, xixixi |     Mengirim Foto/Gif & Video    |
| Bayar, xixixi |        Mengirim Voice Note       |
| Bayar, xixixi |         Reply Chat Partner       |

## Big Thanks to:
<a href="https://github.com/sProDev"><img src="https://img.shields.io/badge/Suluh%20Sulistiawan-For%20making%20the%20Flowchart-blue"></a><br/>
<a href="https://github.com/MhankBarBar"><img src="https://img.shields.io/badge/MhankBarBar-For%20making%20the%20Baileys%20Bot%20base%20xd-blue"></a><br/>
<a href="https://github.com/adiwajshing"><img src="https://img.shields.io/badge/adiwajshing-For%20Baileys%20Library-blue"></a>
