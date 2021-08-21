# Metodologii de cercetare cantitativă în psihologie
### Școala Doctorală Psihologie și Științele Educației / UniBuc 

![GitHub last commit](https://img.shields.io/github/last-commit/GGLuca/sd_unibuc?label=last%20update%3A%20&style=flat-square)

__Obiective__:  

Acest curs este destinat studenților înscriși la ,[Școala Doctorală pentru domeniile psihologie și științe ale educației](http://doctorat.unibuc.ro/psihologie/prezentarea-scolii/). Oferă o introducere în subiecte avansate de statistică sau metodologie, cu accent pe înțelegerea inferenței în științele comportamentale și sociale.  Cursul are ca scop consolidarea și dezvoltarea conceptuală cu privire la metodologia cercetării, abordând printre altele, procese ce pot fi uneori destul de complexe precum testarea ipotezelor sau cum lucrul cu modelele statistice.  

O alta parte, la fel de importantă este familiarizarea cu evoluții recente în cercetarea științifică din domeniul psihologiei. De fapt, în mare parte, acest curs este structurat si centrat pe paradigma probabilității Bayesiane. Vom parcurge împreună diferențele majore între abordarea Fischeriană și cea clasică, ce este incertitudinea și vom aplica modele complete Bayesiene.  

Acesta este un curs practic în care învățarea conceptelor și construirea de modele în R merg mână în mână. De aceea una din cerințe importante este să aveți un laptop cu R deja instalat (vezi capitolul *software necesar* de mai jos.). În timp, vom învăța cum să vizualizăm, să gestionăm și să simulăm date în R; vom lucra cu platforme de date și partajare de cod (*oh the joy* :)

__Detalii curs__:  
Ore curs: 14  
Ore seminar: 14  
ECTS: 8  
Finalizare: Colocviu (Dată nespecificată încă)

__Instructor__:  
:expressionless: George Gunnesch-Luca  
[Pagină web](https://www.psychologie.rw.fau.de/team/wissenschaftliche-mitarbeiterinnen/george-luca/)  
Email: g.luca[at]drd.unibuc.ro  

__Pagina cursului__:    
www: https://github.com/GGLuca/sd_unibuc  
Slack: https://sdfpse.slack.com  

__Orele și locația cursului__:  
Se va anunța la timp  

__Lectură__:  
Obligatoriu: 

Opțional: 

__Cunoștințe anterioare__:  
Cursul necesită o ințelegere a fundamentelor analizei statistice și metodologiei cercetării. 

Dacă 

__Software necesar__:  
Pentru laboratoare și pentru o mare parte din exemplele din clasă, vom folosi R, un limbaj de programare statistică open-source (și gratuit). Mai jos, veți găsi instrucțiuni extrem de sumare pentru a instala R și RStudio pe calculatorul personal (recomandarea mea).  

1. Instalați R de la adresa https://cran.r-project.org/. Este disponibil pentru Mac OS, Windows și Linux. Alegeți linkul corespunzător, descărcați și instalați.  

2. Instalați RStudio de la https://www.rstudio.com/products/rstudio/download/. Alegeți "RStudio Desktop" gratuit (până la capăt, în stânga). Puteți rula R și fără RStudio, dar vă recomand cu căldură să folosiți RStudio (pentru că!).

Nu știți nimic despre R sau vă e frică de el? [Nu-i bai!](https://youtu.be/0DF4Cb-NeyM?t=1583). Până termin de înregistrat cursul nou, aveți la dispozitie o serie de workshop-uri sau tutoriale, ca de exemplu [excelentul workshop](https://www.youtube.com/playlist?list=PLzH57eq4okPYPdHc-eJV7FnAWw_iHHvNk) a lui Cristi Opariuc-Dan. De asemenea, cursul va începe cu o introducere în R, dar ea nu va fi atât de cuprinzătoare ca un curs specializat.

# Conținut

## Idei:

### Introducere în mediul de lucru pe acest semestru.

+ Explorarea ecosistemului R  
Introducere în R si RStudio (instalare); Primul contact

+ Manipularea de date în R  
Citirea datelor; Elemente de bază; Elemente avansate de manipulare; Un studiu de caz 

+ Vizualizare  
Ggplot2 pentru vizualizare; Introducere in gramatica graficelor; Folosirea avansată a ggplot2, aplicare pe un set de date real

+ Modelare  
Elemente de statistica descriptiva (medii, distribuții, abateri standard); Elemente de baza (testul t, ANOVA); Corelația; Cazul regresiei lineare simple si multiple.

+ Comunicarea rezultatelor  
RMarkdown; Formatarea în RMarkdown, folosirea codului R în RMarkdown; Cum creăm tabele estetice sau științifice în RMarkdown; Pachetul papaja: generarea de documente dinamice în R


Analiza Bayesiană a datelor, partea I

Comparație între analiza frecventistă și analiza bayesiană a datelor.  
Obiecții la testarea frecventistă a ipotezei nule.  
Avantajele analizei bayesiene a datelor.  
Modele bayesiene de cunoaștere.  
Un exemplu simplu de aruncare a unei monede.  
Distribuția posterioară, anterioară, *likelyhood*, mărimea eșantionului.  
Analiza Bayesiană a datelor, partea II
Exemplu simplu de inferență bayesiană.
Regula lui Bayes în acțiune.
Funcții de verosimilitate comune.
Funcții prior comune.
Cum se face inferența.
    Efectuarea analizei bayesiene a datelor.
        O regresie liniară simplă.
        Verificări predictive posterioare.
        Interval credibil vs. interval de încredere.
Conținut:

    Construirea modelelor bayesiene cu brms.
        Evaluarea modelelor:
            Vizualizarea și interpretarea rezultatelor.
            Testarea ipotezelor.
        Evaluarea inferenței: Au funcționat lucrurile?
    Câteva exemple interesante:
        Dovezi pentru rezultatele nule.
        Tratarea varianței inegale.
        Modelul beta binomial umflat zero-unu.
        Regresia logistică ordinală.
        Regresie cu ponderi strict pozitive.




1. Introducere  
  * Condiții formale
  * Organizarea cursului
  * 
Analiza Bayesiană a datelor, Partea I  
Analiza Bayesiană a datelor, Partea II  
Analiza Bayesiană a datelor, Partea II  

# Resurse gratuite

## Pentru R

+ [R for Data Science](https://r4ds.had.co.nz) O introducere în manipularea si vizualizarea datelor în R.   
+ [Data visualization: A practical introduction](http://socviz.co) O introducere în vizualizare, bineînțeles în R.  


<li><a href="https://michael-franke.github.io/intro-data-analysis/index.html">An Introduction to Data Analysis</a>: Introduction to data analysis in R including plotting, data wrangling, and Bayesian data analysis.</li>
<li><a href="https://statlearning.com/">An introduction to statistical learning</a>: Introduction to statistical learning including regression, classification, resampling, and unsupervised learning techniques.</li>
<li><a href="https://moderndive.com/">An Introduction to Statistical and Data Sciences via R</a>: Free online book that introduces statistical concepts using many of the same tools we are using in class (<code>ggplot2</code>, <code>dplyr</code>, sampling methods, &hellip;).</li>
<li><a href="https://www.openintro.org/book/stat/">OpenIntro Statistics</a>: Introduction to statistics.</li>
<li><a href="https://statsthinking21.org/">Statistical thinking for the 21st century</a>: Online book written by Russ Poldrack for the undergraduate statistics course in psychology here at Stanford (Psych 10).<br /></li>
<li><a href="https://statswithr.github.io/book/index.html">An introduction to Bayesian thinking</a>: Companion book to the <a href="https://www.coursera.org/specializations/statistics">Statistics with R</a> course on coursera.<br /></li>
<li><a href="https://crumplab.github.io/statistics/">Answering questions with data</a>: Introductory statistics textbook.</li>
<li><a href="http://adv-r.had.co.nz/">Advanced R</a>: The book is designed primarily for R users who want to improve their programming skills and understanding of the language.</li>
<li><a href="https://moderndive.com/index.html">Statistical Inference via Data Science: A moderndive into R and the tidyverse</a>: A gentle introduction to the practice of analyzing data and answering questions using data the way data scientists, statisticians, data journalists, and other researchers would.</li>
<li><a href="https://benwhalley.github.io/just-enough-r/">Just enough R</a>: Basic introduction into some of the core R concepts.</li>
<li><a href="https://www.tmwr.org/">Tidy Modeling with R</a>: Introduction to modeling in R using the tidyverse.</li>
</ul>

