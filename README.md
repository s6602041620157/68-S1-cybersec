# Cyber Security

## Information
- Amonrat Ngamsompon (Modtanoy)
- 6602041620157
- s6602041620157@email.kmutnb.ac.th

## Evironment 
```sh
cp env.simple .env
```
## Running a services
## Database 
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # backgroud
```
## admin 
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # backgroud
```