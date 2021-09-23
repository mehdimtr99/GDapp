1)Ajouter dans le fichier C:\Windows\System32\drivers\etc\hosts cette ligne : 192.168.10.10  GDapp.com
2)Il faut ajouter aussi dans database le profile directeur(admin):
        use gestion_demandesdb
        insert into groupes values(1,'direction');
        insert into employes values(1,"said",'2021-09-19 00:00:00','said@said.com','$2y$10$atPQ2okhb5PMsN1pjAIMgOOQ0bmVXQwrPPhj641vQYGhy6hZRgsNm','directeur',1,0);

3) login:
        email : said@said.com
        password : saidsaid