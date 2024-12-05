# grupab-bp
https://github.com/bpoljak/grupab-bp.git

1. korak :
    git clone (link repozitorija)
2. korak:
    cd grupab-bp
    git config user.email (moj email)
    git config user.name (moj username)
3. korak:
    cd quasar-project
    npm i
    quasar dev
4. korak:
    quasar new page VrstaPage
    - dodan page u MainLayout
    - Dodan page u routes

5. korak:   
    SQL upiti:
    1. Upit: SELECT COUNT(*) AS broj_biljaka FROM biljka
    2. Upit: SELECT biljka.id, biljka.naziv, biljka.vrsta FROM biljka INNER JOIN vrsta WHERE biljka.id=vrsta.id

6. korak:
