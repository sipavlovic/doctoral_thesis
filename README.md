
SUSTAV ZA RAZVOJ APLIKACIJA USMJERENIH NA BAZE PODATAKA
DOKTORSKI RAD

SAŽETAK
Razvoj informacijskih sustava za rad s bazama podataka ima brojne specifičnosti, kako u
dijelu razvojnog procesa, tako i u njihovu korištenju. Cilj ovog rada jest utvrditi specifičnosti
aplikacija usmjerenih na baze podataka, te predložiti efikasan sustav za razvoj takvih
aplikacija.
Predloženi sustav za razvoj aplikacija usmjerenih na baze podataka sastoji se od apstraktnog
modela objekata koji zajedno čine jedinstvenu cjelinu obavljajući funkcije komunikacije s
bazom podataka, lokalne pohrane podataka na klijentskoj strani, kontrole ispravnosti unesenih
podataka, upravljanja podsustavom događaja i upravljanja transakcijskim mehanizmom i
zaključavanjem slogova u bazi podataka. Osim apstraktnog modela, nužan element sustava za
razvoj aplikacija usmjerenih na baze podataka čini korisničko sučelje, pa je stoga u ovom radu
detaljno objašnjen skup elemenata korisničkog sučelja prilagođen zahtjevima unosa podataka,
te njihov odnos sa događajnim podsustavom apstraktnog modela. U radu je opisan sustav
repozitorija u kojem su zapisani elementi apstraktnog modela koji zajedno čine izvorni kod
aplikacije i koji omogućuje kvalitetniji razvoj aplikacija usmjerenih na baze podataka,
naročito onda kada se taj razvoj odvija s većim brojem članova u razvojnom timu. Sustav
repozitorija može zapisivati izvorni kod u bazu podataka i na taj način iskoristiti prednosti
transakcijskog mehanizma, pretraživanja i obrade velike količine strukturiranih podataka s
ciljem boljeg praćenja dinamike razvoja i odnosa među elementima aplikacije.
Sustav za razvoj aplikacija usmjerenih na baze podataka opisan u ovom radu nije ovisan o
nekoj konkretnoj tehnologiji i može biti implementiran na bilo kojoj hardverskoj i softverskoj
platformi, pod uvjetom da ona omogućuje rad s relacijskom bazom podataka i odgovarajućim
korisničkim sučeljem, pa ovaj rad može poslužiti kao osnova za izradu konkretnog sustava
koji će biti korišten u praksi.

Ključne riječi:
Aplikacija, baza podataka, razvoj aplikacija, korisnik, sustav, razvojna okolina, apstraktni
model.

SYSTEM FOR DEVELOPING DATABASE ORIENTED APPLICATIONS
DOCTORAL THESIS

ABSTRACT
Development of database information systems has many special characteristics, in
development process as well as in use. In this paper those special characteristics of database
applications is determined and a system for the efficient develoment of such applications is
proposed.
Proposed system for database application development consists of an abstract model of
objects that together form a single unit performing the function of communication with the
database, local data storage on the client side, controling the data validaton, the event
management subsystem and transaction management mechanism with record locking in
database. In addition to the abstract model, an important element of the system for database
application development is the user interface and therefore in this paper a set of user interface
elements adapted to the requirements of data entry, and their relationship with the event
subsystem of abstract model is explained in detail. This paper describes a repository system in
which elements of abstract model are stored which makes the source code of application and
improves the quality of database application development, especially with a larger number of
members in the development team. The system repository is able to write source code to the
database and thus take advantage of the transaction mechanism, searching and processing
large amounts of structured data in order to do a better control of development process
dynamics and the relationship between the elements of the application.
System for database application development described in this paper is not dependent on any
particular technology and can be implemented on any hardware and software platform,
provided that it can work with relational database and appropriate user interface, so this paper
can serve as a guide to produce a specific system implementation that will be used in practice.

Keywords:
Application, database, application development, user, system, development environment,
abstract model.
