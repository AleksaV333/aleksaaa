# aleksaaa
https://github.com/AleksaV333/aleksaaa
SQL UPIT 
SELECT knjiga.naslov
FROM knjiga
JOIN autor ON knjiga.autor = autor.id
WHERE autor.prezime_ime = 'Ivo Andrić'
ORDER BY knjiga.naslov ASC;

10.	Ulogirajte se na web http://student.veleri.hr/phpmyadmin s podacima:
baza: 5g, username: 5g, password: 5grupa – Tamo ćete naći 2 tablice: popis stavki i računa – svaki račun može imati više stavaka. Napraviti SQL upit kojim se vraćaju sve stavke određenog računa. 
11.	U README.md datoteci spremite SQL naredbu.
12.	Potvrdite izmjene u lokalnom repozitoriju
13.	Napravite prebacivanje na udaljeni repozitorij
