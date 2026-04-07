# Summing-Amplifier-GUI-MATLAB-Project
Acest proiect consta intr-o aplicatie dezvoltata in mediul MATLAB care simuleaza si vizualizeaza comportamentul circuitelor de tip Amplificator Sumator cu doua intrari (vi1 si vi2). Aplicatia este conceputa cu un scop educativ, permitand utilizatorilor sa interactioneze in timp real cu parametrii circuitului si sa observe efectele asupra semnalului de iesire.

Functionalitati principale:
Proiectul dispune de un meniu principal care ofera acces la doua module de simulare:
-Sumator Inversor
-Sumator Neinversor

Pentru ambele tipuri de circuite, interfata grafica permite utilizatorului sa:
-Modifice parametrii componentelor: Se pot ajusta valorile rezistentelor din circuit (R1, R2, R3, R4 etc.) direct din interfata.
-Seteze caracteristicile semnalelor de intrare: Utilizatorul poate modifica amplitudinea si frecventa pentru cele doua semnale de intrare.
-Aleaga tipul de semnal: Pentru fiecare intrare, se poate selecta forma de unda dorita dintr-un meniu drop-down: curent continuu (DC), sinusoidal, dreptunghiular sau semnal tip dinte de ferastrau.
-Adauge o componenta continua (DC): Se poate adauga o componenta continua de 1V semnalelor de intrare prin bifarea unei casete speciale.
-Vizualizeze graficele: Aplicatia genereaza automat grafice in timp real, reprezentand atat semnalele de intrare (Vi1 si Vi2), cat si tensiunea de iesire rezultata (Vo).
-Simuleze limitari reale: Iesirea circuitului este limitata la valorile de alimentare ale amplificatorului operational (de exemplu, +/-12V).

Structura fisierelor:
Start.m, sum1.m, sum2.m, sumator1.m, sumator2.m: Scripturile si functiile sursa MATLAB care genereaza interfata grafica si realizeaza calculele matematice din spate.
Teorie.docx: Documentatia proiectului care include notiuni teoretice de baza, schemele circuitelor si demonstratiile formulelor matematice folosite (ex: Teorema lui Millman).
sum.pptx: O prezentare detaliata a interfetei grafice si a modului de utilizare a aplicatiei.
