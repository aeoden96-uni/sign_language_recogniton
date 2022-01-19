# Sign language recogniton

U ovom projektu radimo na implementaciji prepoznavača znakovnog jezika.

Konkretno program će prepoznavati pojedina slova znakovne abecede.Pošto postoji više varijanti abecede za različite regije, program bi trebao raditi za sve varijante.

![alt text](hands.png "Title"),

Analizirat ćemo više modela i vidjeti koji su najučinkovitiji i koji daju pouzdane rezultate. Za samo implementaciju, koristit ćemo Pythonovu biblioteku za strojno učenje TensorFlow,a za same podatke za učenje modela još nismo našli adekvatan dataset, ali ukoliko naš dataset za učenje i bude premali, možemo ga povećati tako da postojeće slike transformiramo,rotitamo,promijenimo im svjetlinu i slično.



Također, učenje modela će se provoditi na Google Colab-u,online okruženju za izvršavanje Python skripti,tako da svi članovi tima mogu izvršiti projekt,neovisno o njihovoj snazi računala. 

Testiranje modela će se vršiti pomoću web-kamere ili manualno preko slike/videa.
Nismo ih još istražili,ali Pyhon ima broj raznih biblioteka za učitavanje i procesiranje videa i videa web-camere ,što je jedan od glavnih razloga zašto ga koristimo.
