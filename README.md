# Lectura

Aplicatie pentru management-ul cartilor citite sau in curs de citire . De asemenea , pentru unele carti din programa de BAC sau selectate de catre noi se gasesc si teste , in gen quiz , cu intrebari din fiecare opera. 

## Structuri folosite in cadrul aplicatiei (fisiere)

books.txt -> descrie cartile din biblioteca utilizatorului<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;->N numarul de carti pe fiecare linie , urmat de N linii cu titlul operelor , intre ghilimele<br/>

In folderul books/ se gasesc N fisiere care descriu fiecare carte (titlu , autor , nr pagini citite/totale)->books/$titlu.txt<br/>

## Structuri folosite in cadrul aplicatiei (assets)

assets/recomandate.txt -> descrie cartile recomandate de noi<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;->N numarul de carti pe fiecare linie , urmat de N linii cu titlul operelor , intre ghilimele<br/>
                  
assets/$titlu_intrebari.txt -> descrie intrebarile deja existente <br/>
                            &nbsp;&nbsp;&nbsp;&nbsp;-> pe prima linie N nr de intrebari<br/>
                            &nbsp;&nbsp;&nbsp;&nbsp;-> urmeaza N secvente care descriu o intrebare<br/>
                          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ->'Intrebare'<br/>
                              &nbsp;&nbsp;&nbsp;&nbsp;->X : nr de raspunsuri posibile<br/>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;->X linii cu fiecare raspuns ('raspuns')<br/>
                              &nbsp;&nbsp;&nbsp;&nbsp;->Y : indicele raspunsului corect<br/>
<br/>
Se gasesc exemple pentru structura in assets/
<br/>

