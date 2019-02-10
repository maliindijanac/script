1. kreirati folder sa nazivom projekta,
2. pokrenuti u vs code,
3.u terminalu pokrenuti express --ejs imefoldera,
4. u terminalu pokrenuti npm install,
5. npm install mongojs --save,


6. kreirati mymongo.js u rutama, tu definisati konekciju i formu onoga sto imamo u HTML-u,
  - ne zaboraviti promijeniti ime baze i kolekcije,
7. "users" preimenovati u odgovarajuci fajl, dodati require mymongo i mymongo.js (u ovom dokumentu definiramo CRUD),
8. u app.js promijeniti imena za routes,

nakon ovih koraka, aplikaciju je moguce provjeriti na localhostu

9. u "user.js" promijeniti GET metodu i sve ostale metode, ime baze prilagoditi imenu u aplikaciji (npr.mongomodel --> mymongo)
   ---> ne zaboraviti promjene napraviti u svim rutama,

BAZA

10. postman ina web app za testiranje crud-a

11. za manuelno popunjavanje baze, mongo.exe :

-- show dbs  -> lista postojećih baza
-- use imebaze -> "ulaz" u bazu ime baza
-- db.imenik.save({ime:"amina", telefon:"11111"});     --> kreiranje novog reda u kolekcijei IMENIK . ako ne postoji kolekcija imenik biće kreirana
-- db.imenik.find().pretty();    --> lista svih redova u  kolekciji imenik
-- db.imenik.find({ime:"amina"}).pretty();    --> lista redva iz kolekcije imenik sa uslovom ime="amina"


FRONT END

12. npm install angular-ui-bootstrap, i prebaciti ga iz node modules u public,
13. napraviti appctrl.js u public folderu
 --> u njemu definisemo ajax pozive funkcija
14. u fajlu index.ejs dodati linkove za bootstrap, angular itd.
15. u index.ejs dodati ng-app = "ime aplikacije" i ng-controller = "ime kontrolera"
16. u index.ejs se dodaje HTML za dugmad, tabele i ostalo,

MODALNI PROZORI

17. kreirati imemodala.html dokument za svaki modal koji je potreban,


GIT CLONE

git clone linkprojekta.git na primjer https://github.com/maliindijanac/moviesapp.git
otvoriti novi folder (moviesapp)
npm install,
nodemon; ili npm start
