---
date: 2019-11-21
title: Stretnutie č. 8
categories:
  - Sprint Wywar
author_staff_member: Adriana
---
- Stretnutia sa zúčastnili:
    - Ing. Kamil Burda
    - Bc. Adriana Ághová
    - Bc. Martin Civáň
    - Bc. Zuzana Cukerová
    - Bc. Matúš Kováč
    - Bc. Matúš Pilňan
    - Bc. Andrej Schmidt
    - Bc. Viliam Villár

- Ukončenie šprintu ŠARIŠ
    - prezentovanie odovzdávaných User stories
    - Ukončenie šprintu v Jire (prenesenie 'BEHAPASS-18' do dalšieho šprintu - 8 story points)
    - Hodnotenie vzniknutého problému 
        - Riešenie: rozdelovať US na menšie časti, čo zabezpečí lepšiu predstavu o potrebných úkonoch pre ukončenie US. (lepšií odhad story point)
    
- Plánovanie šprintu Wywar
    - Doplnenie backlogu
    - Zoradenie backlogu podľa priority
    - Diskusia model (z dôvodu estimate 13)
        - Problém ako ho rozčleniť na menšie celky
      	- Aký model vybrať ?
      	- Sú v scikit dáke SVM lazy ?
      	- Lazy (instance-based)
      	    - k-NN (ball tree)
      	- Asynchrónne spracovanie 
      	- Dôležíte je dosiahnuť identifikáciu za behu
      	- Identifikovať naraz rádovo desiatky používateľov
    - Výsledok diskusie:
        - Offline model (prvá iterácia)
        - Všetkých používateľov naraz -> closed-set ident.
        - Alebo postupné pridanie -> open-set ident.
        - Metriky prepočítavať dopredu (pred registráciou)
        - Vyhodnotiť outlier-ov (neskôr)
        - Použiť k-NN
        - Metriky predpočítavať do predu (pred registraciou)
            - Vyčlenenie do novej US


![Review šprintu]({{ site.baseurl }}/images/Review_3.png)

[Report 8]({{ site.baseurl }}/reports/Stretnutie8.html)