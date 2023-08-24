## Nouveautés 📬
- Nouvelle police.
- Récupération des logos ligne par API.
- Compatibilité avec 100% du réseau IDFM (normé API de la PRIM), métro, tram, bus, RER.
- Correction de bugs (chiffre négatif, bouton on/off du TTS).
- Vérificateur de clé API.
- Refonte de l'interface graphique principale.
- Changement du mode de transport automatique ex: "1er métro/bus/RER/tram".
- Optimisations de l'application.
- TTS adaptatif au mode de transport.
- Récupération automatique du logo du mode de transport.
- Récupération automatique de la couleur de la ligne.

# My MIV

Votre écran de station personnel ! Affiche les prochains trains sur un quai donné, compatible sur tout le réseau Ile de France Mobilité: métro, tramway, bus, RER.

Disponible pour smartphone et tablette, vous pouvez l'embarquer partout ! Plus de raison de rater votre métro !

## Compatibilité actuelle:

Toutes lignes Ile de France Mobilités: Métro, BUS, RER, Tram (Conformes à l'API PRIM).

## Utilisation de l'appli

▶ La première chose à faire est de vous créer un compte sur la [Plateforme Régionale d'Information pour la Mobilité (PRIM)](https://prim.iledefrance-mobilites.fr/) d'Ile de France Mobilité.

<img  src="https://srv.fbr.ninja/index.php/s/dDsqQo2TkRygNjS/preview"  width="90%">

▶ Ensuite générez votre clé API.

<img  src="https://srv.fbr.ninja/index.php/s/stgcndArX7HWym9/preview"  width="50%"><img  src="https://srv.fbr.ninja/index.php/s/pHsneteTJkJ2Yat/preview"  width="50%">

▶ Rendez-vous sur le site [QrCode Monkey](https://www.qrcode-monkey.com/fr/#text) copiez votre clé API et générez un QrCode (vous allez voir c'est très pratique !).

<img  src="https://srv.fbr.ninja/index.php/s/gbbMqPpo8N7iqRy/preview"  width="90%">

▶ Installer l'APK [disponible ici](https://github.com/Florian1548/My-MIV/tree/main/My%20MIV%20app) choisissez la bonne version (tablette ou téléphone).

▶ Si votre appareil vous le demande [autorisez les sources inconnues](https://apprendre.pandasuite.com/article/952-autoriser-application-source-inconnue-android).

▶ Une fois dans l'application, entrez votre clé API ou scannez le QrCode précédemment créer !

<img  src="https://srv.fbr.ninja/index.php/s/N3ojXZFLadWKQ79/preview"  width="90%">

▶ Le stopPoint correspond à l'identifiant du quai que vous souhaitez programmer, pour le trouver, [rendez-vous ici](https://prim.iledefrance-mobilites.fr/fr/donnees-statiques/arrets).

<img  src="https://srv.fbr.ninja/index.php/s/gPpxfwmLoTpMK8b/preview"  width="90%">

▶ Allez dans "Tableau" puis cherchez votre station, filtrez votre mode de transport pour plus de facilité.

<img  src="https://srv.fbr.ninja/index.php/s/dNdpTLPmyiHNwZF/preview"  width="50%"><img  src="https://srv.fbr.ninja/index.php/s/E2Mm984orRwCrcr/preview"  width="50%">

▶ Une ligne passant dans une station à minimum 2 stopPoint (arRID) le quai aller et le quai retour, il vous suffit de tester l'un des deux (menu automatique en développement de mon coté 🖥️).

<img  src="https://srv.fbr.ninja/index.php/s/A9drntMm2ieWp2K/preview"  width="50%"><img  src="https://srv.fbr.ninja/index.php/s/q8AMarHrBRsFMRm/preview"  width="50%">

Et voilà ! Plus aucun train ou métro ne vous échappera 👀 !

⚠️ Pour revenir dans le menu de configuration, il vous suffit de cliquer dans le coin en haut à gauche de l'écran !
