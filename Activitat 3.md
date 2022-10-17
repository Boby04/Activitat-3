# Activitat 3:

Per fer aquesta activitat comptem amb que **ja s'ha configurat el servei Owncloud a una Màquina Virtual** (MV).

**3.1.-** Llista els Virtual Hosts d'Apache per tal de veure si **owncloud.XYZ.com** està habilitat amb la comanda:

```
apache2ctl -S
```

**RESPOSTA**

**3.2.-** A Owncloud podem veure que hi ha una serie de carpetes per defecte, mostra la ruta real a les tres carpetes dins de la teva MV.

![image](https://user-images.githubusercontent.com/110727546/194824543-c49bf482-ac93-432f-884c-d89487e587f3.png)


**RESPOSTA**

**3.3.-** Al directori **Learn more about owncloud** hi ha informació en forma de fitxers pdf. Consulta'ls i respon aquestes preguntes:

- **Quin són els tres tipus de protecció de dades que ofereix Owncloud?**

```
1. Encryption in Transit
2. Encryption at Rest with Master Key in Hardware Security Module (HSM)
3. End-to-End Encryption
```


- **Fes una petita descripció de cada un d'ells.**

1. Encryption in Transit

  - El xifratge en trànsit està disponible a ownCloud per disseny i per defecte. El mateix passa amb totes les connexions als servidors d'emmagatzematge, directoris i autenticació o als serveis d'edició col·laborativa admesos. És igualment obligatori per garantir el secret de les dades.

2. Encryption at Rest with Master Key in Hardware Security Module (HSM)

  - Per tal d'excloure l'administrador del sistema de la capacitat de desxifrar fitxers, ownCloud permet posar la clau mestra en un HSM. Això significa que la clau del fitxer s'envia a l'HSM i s'hi desxifra des d'un procés dins de l'aplicació ownCloud. Quan el connector està habilitat per a un usuari, aquest usuari pot xifrar qualsevol carpeta buida. Per a cada fitxer penjat, l'usuari pot veure a quantes persones i a qui s'ha enviat aquest fitxer.
 
4. Ed-to-End Encryption

  - Per tal d'assegurar veritablement que ni els administradors del sistema ni ningú més de la vostra organització puguin accedir a les dades xifrades, només el xifratge d'extrem a extrem és viable.
solució. Aquest és el nivell més alt de dades secret combinat amb el més alt nivell de protecció de dades.


- **Per quina raó ens recomana utilitzar Owncloud per als documents de Microsoft Office de la nostra empresa?**

Perquè es fàcil d'utilitzar i molt eficient a l'hora de mantindre els arxius segurs, i sobretot per a les empreses, això és un problema, perquè l'emmagatzematge sensible documents i dades d'usuari aporta una sèrie de riscos, amenaces i responsabilitats. Amb ownCloud, el vostre personal aconsegueix usabilitat i productivitat funcions a l'igual que els proveïdors de núvols públics, però mantens el control de la preciosa companyia
dades.

- **Això passa a tots els països?**

Sí això passa a la majoria dels països

- **Quina és la llicència d'OWncloud Enterprise?**

La llicència per a Owncloud Enterprise és *"ownCloud Commercial License"*

- **I la d'Owncloud Standard?**

La llicència per a Owncloud Standard és *"AGPLv3"*

- **Es poden veure videos en Streaming directament des de Owncloud?**

Sí, es poden veure videos en Streming des de Owncloud desde 2012

- **Es poden connectar directoris de Google Drive a Owncloud?**

Sí es poden connectar 

- **I Dropbox?**

Sí es poden connectar 

- **Compta Owncloud amb antivirus? En cas afirmatiu com es diu?**

Sí, Owncloud compta amb antivirus, es diu *"ClamAV"*



**3.4.-** Mostra els següents canvis de paràmetres d'usuari:

1. Posa't una imatge d'usuari.
2. Afegeix el teu mail de l'Institut.
3. Canvia l'idioma a català.
4. Mostra la versió d'Owncloud instal·lada.

**RESPOSTA**

**1.**
2.
3.
4.


