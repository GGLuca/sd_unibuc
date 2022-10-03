# Metodologii de cercetare cantitativă în psihologie

### Școala Doctorală Psihologie și Științele Educației / \@UniBuc

![GitHub last commit](https://img.shields.io/github/last-commit/GGLuca/sd_unibuc?label=last%20update%253A%20&style=flat-square)

**Obiective**:

Acest curs este destinat studenților înscriși la [Școala Doctorală pentru domeniile psihologie și științe ale educației](http://doctorat.unibuc.ro/psihologie/prezentarea-scolii/). Dintr-o perspectivă absolut generală, el oferă o introducere în subiecte avansate de statistică sau metodologie, cu accent pe înțelegerea inferenței în științele comportamentale și sociale. Cursul are ca scop consolidarea și dezvoltarea conceptuală cu privire la metodologia cercetării, abordând printre altele, procese ce pot fi uneori destul de complexe precum testarea ipotezelor sau cum lucrul cu modelele statistice.

Dar în mod mai special, ca o dorință personală, aș dori să vă familiarizați cu evoluții recente în cercetarea științifică din domeniul psihologiei. De aceea, în mare parte, acest curs este structurat în așa fel încât să parcurgem împreună diferențele majore între abordarea Fischeriană și cea clasică, ce este incertitudinea și vom aplica modele Bayesiene.

Acesta este un curs nou, mai exact el se află în a doua lui iteraţie - și nu exisă certitudini în ceea ce privește conținutul exact. Dar, cu siguranță voi preda elementele de bază, fundamentele: Probabilitatea subiectivă, distribuții apriori, distribuții posterioare, inferența Bayesiană, factori Bayes etc. De asemenea, vom lucra împreună cu tehnici de calcul bayesian, inclusiv MCMC. Iar pentru că avem probleme reale de rezolvat, vom face preponderent modelare statistică. Regresiile simple și multiple Bayesiene, comparare de modele, și predicții.

Vom învăța mult despre modele, și mai precis să le priviți mult mai sceptici, cu multă incertitudine, dar în același timp să va simțiți confortabili cu această nesiguranță. Evident, vom interpreta rezultatele și cu puțină rabdare vom vedea și um se raportează în scris. Un plan aproximativ l-am listat mai jos.

Acest curs este practic, și de fapt aveți 14 ore de seminar, în care învățarea conceptelor și construirea de modele în R merg mână în mână. De aceea este important să vă uitaţi peste capitolul *software necesar* de mai jos.). Cu timpul, vom învăța cum să vizualizăm, să gestionăm și să simulăm date în R; vom lucra cu platforme de date și partajare de cod. Insist să invățați R. Daca doriți să faceți cercetare fundamentală nu puteţi să-l ocoliţi. Așa că puneți-vă centurile de siguranță.

**Detalii curs**:\
Ore curs: 14\
Ore seminar: 14\
ECTS: 8\
Finalizare: Colocviu (Dată nespecificată încă)

**Cine și cum?**

:man_teacher: George Gunnesch-Luca\
:spider_web: [Pagină web](https://www.psychologie.rw.fau.de/team/wissenschaftliche-mitarbeiterinnen/george-luca/)\
:envelope: george.luca[at]drd.unibuc.ro\
:classical_building: Birou: Dacă știți unde e, să-mi spuneți și mie :)

**Pagina cursului**:\
<https://github.com/GGLuca/sd_unibuc>

**Orele și locația cursului**:

| Data            | Ora           | General                       | Subiect                         | Slideuri |
|:--------------|:--------------|:--------------|:--------------|:--------------|
| 7.10            | 09:00 - 14:00 | Introducere, mediu de lucru   | R/RStudio 1                     | 🐣       |
| 8.10            | 09:00 - 14:00 |                               | R/Rstudio 2                     | 🐥       |
| 28.10           | 09:00 - 11:00 | Fundaţia inferenţei Bayesiene | Teorema lui Bayes               | 🐤       |
| 29.10           | 09:00 - 11:00 |                               | Beta-Binomial                   | 🐔       |
| 4.11            | 09:00 - 11:00 |                               | Normal-Normal                   | 🐱       |
| 5.11            | 09:00 - 11:00 | Calcul Bayesian               | Markov Chain Monte Carlo (MCMC) | 🐶       |
| 25.11           | 09:00 - 11:00 |                               | Diagnostic MCMC                 | 🐴       |
| 26.11           | 09:00 - 14:00 | Extensii                      | Regressie Logistica             | 🐻       |
| 9.12 (*ONLINE*) | 09:00 - 14:00 |                               | Regressie Poisson               | 🐉       |
|                 |               | Colocviu                      |                                 | 🤯       |

**Cunoștințe anterioare**:\
Cursul necesită o ințelegere a fundamentelor analizei statistice și metodologiei cercetării.

**Important!: Software necesar**:\
Pentru laboratoare și pentru o mare parte din exemplele din clasă, vom folosi R, un limbaj de programare statistică open-source (și gratuit). Mai jos, veți găsi instrucțiuni extrem de sumare pentru a instala R și RStudio pe calculatorul personal (recomandarea mea).

1.  **Un cont pe [Rstudio Cloud](https://rstudio.cloud/). Este gratuit, și de fapt vom incepe primele ore în cloud. Ceva mai târziu:**
2.  Instalați **R** de la adresa <https://cran.r-project.org/>. Este disponibil pentru Mac OS, Windows și Linux. Alegeți linkul corespunzător, descărcați și instalați.
3.  Instalați **RStudio** de la <https://www.rstudio.com/products/rstudio/download/>. Alegeți "RStudio Desktop" gratuit (până la capăt, în stânga). Puteți rula R și fără RStudio, dar vă recomand cu căldură să folosiți RStudio (pentru că!)
4.  JASP: <https://jasp-stats.org/>. Program gratuit și open-source pentru analiză statistică, creat de Universitatea din Amsterdam. Este conceput pentru a fi ușor de utilizat și familiarizat cu utilizatorii SPSS.

## Resurse gratuite

## Pentru R

-   [R for Data Science](https://r4ds.had.co.nz). O introducere în manipularea si vizualizarea datelor în R. Perfect pentru începători.
-   [Modern Statistics with R](https://modernstatisticswithr.com/).
