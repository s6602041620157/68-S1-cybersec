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
## APP
```sh
docker compose -f app.yaml up # monitoring
docker compose -f app.yaml up -d # backgroud
```