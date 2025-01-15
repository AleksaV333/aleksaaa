# aleksaaa
https://github.com/AleksaV333/aleksaaa
SQL UPIT 
SELECT knjiga.naslov
FROM knjiga
JOIN autor ON knjiga.autor = autor.id
WHERE autor.prezime_ime = 'Ivo Andrić'
ORDER BY knjiga.naslov ASC;