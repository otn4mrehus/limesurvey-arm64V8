# limesurvey-arm64V8
Limesurvey For Armbian 64 [STB-B680H] 

## Struktur Direktori File
```
+ Limesurvey
  - db/
  - app/
  - docker-compose.yaml

```
## Jalankan Docker Compose
#### Running Project Stack Docker
###### <i>Pilih salah satu</i>
```
docker-compose -p 'limesurvey' stop | start | restart
```
#### Hapus Project Stack Docker
```
docker-compose -p 'limesurvey' down -v 
```
