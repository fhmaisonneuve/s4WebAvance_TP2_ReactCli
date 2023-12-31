Techniques avancées en programmation Web 
582-41F-MA 
 
 

TP 2 
Création d’un site web à l’aide de la librairie React.js  


par:  François Hébert (e2296133) 


---
## DOCUMENTATION

RÉFÉRENCES:

- LIEN VERS LE GITHUB: **[GIT DU PROJET](https://github.com/fhmaisonneuve/s4WebAvance_TP2_ReactCli)**

- LIEN VERS LE PROJET(WEBDEV): **[https://e2296133.webdev.cmaisonneuve.qc.ca/webavancetp2/](https://e2296133.webdev.cmaisonneuve.qc.ca/webavancetp2/)** 

- LIEN VERS LE VIDEO: **[SCREENRECORD](https://github.com/fhmaisonneuve/s4WebAvance_TP2_ReactCli/raw/master/__requis/s4webavance_presentation.mp4)**
 ---  

## REQUIS DÉMANDÉS

Votre projet doit répondre aux critères suivants. 
- [x] Créer un projet React.js CLI 
```
npx create-react-app s4webavance_tp2_reactclI
npm install bootstrap --save
npm install react-icons --save
npm i react-router-dom
```
- [x] • Un menu de navigation entre les pages (Accueil / produits) 
- [x] • Pour  la  conception  (CSS),  vous  pouvez  utiliser  le  framework  bootstrap (vanilla, aucun modèle autorisé) ou développer votre propre css. 


Deux Livraisons : 
- [x] • Premier  scénario  -  Créez  une  version  de  production  avec  le  premier scénario et la publiez sur WebDev. 
```
-Ajouter dans package.json: ", homepage": "https://e2296133.webdev.cmaisonneuve.qc.ca/react/"
npm run build
copier sur le server(ftp)
```


- [x] • Deuxième scénario - Maintenez le même projet et les mêmes fonctionnalités mais maintenant vous allez le tester avec un serveur JSON (simulé),  cette  dernière  version  doit  être  publiée  sur  GitHub.  
```
npm i json-server
-Ajouter dans package.json: "server": "json-server --watch db.json --port 5000"
npm run server
```
- [x] Enregistrez une  courte  vidéo  de  votre  écran  (max  3  min)  avec  le  projet  en  cours d'exécution sur votre environnement local. Présentez toutes les pages et fonctions au fur et à mesure que le côté serveur change. 

- [x] Envoyez la vidéo avec le projet

   
- [x] 15.Enregistrez le projet avec une extension ZIP et ajouter la documentation dans la racine (1pt)


