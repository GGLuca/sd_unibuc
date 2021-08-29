# Metodologii de cercetare cantitativă în psihologie 

### Școala Doctorală Psihologie și Științele Educației / \@UniBuc

![GitHub last commit](https://img.shields.io/github/last-commit/GGLuca/sd_unibuc?label=last%20update%253A%20&style=flat-square)

**Obiective**:

Acest curs este destinat studenților înscriși la [Școala Doctorală pentru domeniile psihologie și științe ale educației](http://doctorat.unibuc.ro/psihologie/prezentarea-scolii/). Dintr-o perspectivă absolut generală, oferă o introducere în subiecte avansate de statistică sau metodologie, cu accent pe înțelegerea inferenței în științele comportamentale și sociale. Cursul are ca scop consolidarea și dezvoltarea conceptuală cu privire la metodologia cercetării, abordând printre altele, procese ce pot fi uneori destul de complexe precum testarea ipotezelor sau cum lucrul cu modelele statistice.

Dar în mod mai special, aș dori să vă familiarizați cu evoluții recente în cercetarea științifică din domeniul psihologiei. De aceea, în mare parte, acest curs este structurat în așa fel încât să parcurgem împreună diferențele majore între abordarea Fischeriană și cea clasică, ce este incertitudinea și vom aplica modele Bayesiene. Da, va fi un curs de statistică Bayesiană.

Acesta este un curs nou pentru mine și nu sunt sigur ce voi aborda. Dar, cu siguranță voi preda elementele de bază: Probabilitatea subiectivă, distribuții apriori, distribuții posterioare, inferența Bayesiană, factori Bayes etc. Voi preda, de asemenea, tehnici de calcul bayesian, inclusiv MCMC. Vom învața împreună corelațiile sau regresiile simple și multiple Bayesiene, interpretarea rezultatelor și cu puțină rabdare și cum se raportează în scris.

Vom învăța mult despre modele, și mai precis să le priviți mult mai sceptici, cu multă incertitudine, dar în același timp să va simțiți confortabili cu această nesiguranță.

Acest curs este practic, și de fapt aveți 14 ore de seminar, în care învățarea conceptelor și construirea de modele în R merg mână în mână. De aceea una din cerințe importante este să aveți un laptop cu R deja instalat (vezi capitolul *software necesar* de mai jos.). Cu timpul, vom învăța cum să vizualizăm, să gestionăm și să simulăm date în R; vom lucra cu platforme de date și partajare de cod. Insist să invățați R. Daca doriți să faceți cercetare fundamentală nu veți putea trece de el. Așa ca puneți-vă centurile de siguranță.

Ca un ultim cuvânt, în mod normal, ar trebui să fiți deja familiarizați cu ceea ce înseamnă statisticile elementare în paradigma frecventistă, dar voi aborda subiectele ca și cum ați uitat o bună parte din ele. ;)

**Detalii curs**:  
Ore curs: 14  
Ore seminar: 14  
ECTS: 8  
Finalizare: Colocviu (Dată nespecificată încă)

**Cine și cum?**

:man_teacher: George Gunnesch-Luca  
:spider_web: [Pagină web](https://www.psychologie.rw.fau.de/team/wissenschaftliche-mitarbeiterinnen/george-luca/)  
:email: g.luca[at]drd.unibuc.ro  
:classical_building: Birou: Dacă știți unde e, să-mi spuneți și mie :)

**Pagina cursului**:  
<https://github.com/GGLuca/sd_unibuc> (provizoriu; s-ar putea să primească propria adresa).  
Slack: <https://sdfpse.slack.com>

**Orele și locația cursului**:  
Se va anunța la timp. Voi face tot posibilul să fie față în față.

**Cunoștințe anterioare**:  
Cursul necesită o ințelegere a fundamentelor analizei statistice și metodologiei cercetării, dar voi încerca să predau de parcă toți suferiți de amnezie retrogradă. Nu e așa, și sunt convins că știți mai multe dspre regresii decât credeți voi.

**Software necesar**:  
Pentru laboratoare și pentru o mare parte din exemplele din clasă, vom folosi R, un limbaj de programare statistică open-source (și gratuit). Mai jos, veți găsi instrucțiuni extrem de sumare pentru a instala R și RStudio pe calculatorul personal (recomandarea mea).

1.  Instalați R de la adresa <https://cran.r-project.org/>. Este disponibil pentru Mac OS, Windows și Linux. Alegeți linkul corespunzător, descărcați și instalați.

2.  Instalați RStudio de la <https://www.rstudio.com/products/rstudio/download/>. Alegeți "RStudio Desktop" gratuit (până la capăt, în stânga). Puteți rula R și fără RStudio, dar vă recomand cu căldură să folosiți RStudio (pentru că!).

## Conținut Curs

**Provizoriu**

**Introducere în mediul de lucru pe acest semestru**

-   Explorarea ecosistemului R: Introducere în R si RStudio (instalare); Primul contact

-   Manipularea de date în R: Citirea datelor; Elemente de bază; Elemente avansate de manipulare; Un studiu de caz

-   Vizualizare: Ggplot2 pentru vizualizare; Introducere in gramatica graficelor; Folosirea avansată a ggplot2, aplicare pe un set de date real

-   Modelare: Elemente de statistica descriptiva (medii, distribuții, abateri standard); Elemente de baza (testul t, ANOVA); Corelația; Cazul regresiei lineare simple si multiple.

-   Comunicarea rezultatelor: RMarkdown; Formatarea în RMarkdown, folosirea codului R în RMarkdown; Cum creăm tabele estetice sau științifice în RMarkdown; Pachetul papaja: generarea de documente dinamice în R

**Analiza Bayesiană a datelor, partea I:**

Introducerea

-   Ce este statistica, la ce o folosim? Incertitudinea, probabilitatea, *likelyhood*.

-   Comparație între analiza frecventistă și analiza bayesiană a datelor.

-   Testarea frecventistă a ipotezei nule

-   Avantajele analizei bayesiene a datelor. Modele bayesiene de cunoaștere.

**Analiza Bayesiană a datelor, partea II:**

Elementele de bază

-   Distribuția posterioară, anterioară, *likelyhood*.

-   Exemplu simplu de inferență bayesiană; Regula lui Bayes în acțiune.

-   Funcții de verosimilitate, i.e., likelyhood comune; Funcții prior comune.

**Analiza Bayesiană a datelor, partea III:**

Elemente practice

-   Cum se face inferența. Efectuarea analizei bayesiene a datelor.

-   O regresie liniară simplă.

-   Verificări predictive posterioare. Interval credibil vs. interval de încredere.

Construirea modelelor bayesiene cu brms.

Evaluarea modelelor: Vizualizarea și interpretarea rezultatelor.

Testarea ipotezelor.

Evaluarea inferenței: Au funcționat lucrurile? Câteva exemple interesante: Dovezi pentru rezultatele nule. Tratarea varianței inegale. Modelul beta binomial umflat zero-unu. Regresia logistică ordinală. Regresie cu ponderi strict pozitive.

**Modele aditive generalizate**:

-   Introducere; Problema funcțiilor polinomiale,

-   Vizualizarea și interpretarea GAM

Veți învăța cum să realizați diagrame care să arate modul în care diferite variabile conlucrează . Apoi, veți diagnostica problemele din modele care apar din cauza nepotrivirii datelor sau a relațiilor ascunse între variabile și veți învăța cum să remediați iterativ aceste probleme.

# Resurse gratuite

## Pentru R

-   [R for Data Science](https://r4ds.had.co.nz). O introducere în manipularea si vizualizarea datelor în R.
-   [Data visualization: A practical introduction](http://socviz.co). O introducere în vizualizare, bineînțeles în R.
-   [Introduction to Data Analysis](https://michael-franke.github.io/intro-data-analysis/index.html). Introducere în analiza de date în R, inclusiv reprezentarea grafică, manipularea datelor și analiza bayesiană a datelor.
-   [An Introduction to Statistical and Data Sciences via R](https://moderndive.com/). Carte online gratuită care introduce concepte statistice folosind multe dintre aceleași instrumente pe care le folosim în clasă.
