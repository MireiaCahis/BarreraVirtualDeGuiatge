**PROPÒSIT:**
El propòsit d’aquest codi és l’elaboració d’una barrera virtual de guiatge composta per un con truncat invertit seguit d'un cilindre.

Aquest codi és el concepte d’una barrera virtual que podria ser utilitzada en una cirurgia per tal de guiar el braç robòtic per introduir una eina quirúrgica 
fins a un punt d'interès de l'interior d'un pacient. Aquesta proporciona la seguretat d'entrar de manera precisa i segura sense malmetre cap teixit o òrgan proper. 

**REQUERIMENTS D'INSTAL·LACIÓ:**
Per tal de poder executar aquest codi, és primordial haver-se descarregat prèviament una màquina virtual amb el simulador fora de línia d’Universal Robots. 

Tenint aquest pas previ, es pot descarregar el codi en format .urp que pot ser obert a partir del simulador fora de línia del cobot UR3e d’Universal Robots.

    1. Descarregar el fitxer .urp del repositori.
    2. Descarregar el fitxer .installation del repositori.
    3. Col·locar els fitxers descarregats dins la carpeta de fitxers del cobot UR3e de la màquina virtual (**Programs UR3**).
    4. Obrir el programa **URSim UR3**. 
    5. Obrir el fitxer .urp de la carpeta i tot seguit obrir el fitxer .installation.

En aquest repositori també es pot trobar el codi en format .txt que permet llegir el codi sense la necessitat de ser descarregat i obert amb el simulador fora de línia. 

**MANUAL D'USUARI:**
En aquest manual d'usuari s'indica una petita guia per activar el funcionament del codi.

    1. Assegurar la correcta configuració del TCP i el Payload de l'eina utilitzada.
    2. Modificar els valors de les variables de l'inici del robot per personalitzar la barrera virtual (Opcional).
    3. Aproximar l'eina del robot a l'inici de la barrera virtual tot prement el botó de moviment lliure de la consola del robot.
    4. Activar l'execució del codi de la consola del robot.
    5. Moure manualment el braç robòtic dins el volum limitat passant pel con truncat invertit i tot seguit el cilindre fins arribar al punt d'interès. 
    5. Observar com la barrera virtual limita la sortida dels límits i permet visualitzar cap a quina zona dirirgir-se.
