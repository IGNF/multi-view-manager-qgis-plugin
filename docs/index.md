<table>
<colgroup>
<col style="width: 21%" /><col style="width: 78%" />
</colgroup>
<tbody>
<tr>
<td rowspan="2">
  <img src="images/Image0.jpg"
  style="width:1.38681in;height:1.47153in" alt="logo_IGN_pour_lettre" />
</td>

<td style="text-align: center; font-size: 24px;"><strong>Plugin Vues v1.4.3</strong>
</td>
</tr>

<tr>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<div  style="background-color: white; border: 1px solid black; padding: 10px; text-align: justify;">
  <h2 style="color: #00ADC5">Sommaire</h2>
</div>

- [1. Prérequis](#1-prérequis)
- [2. Résumé](#2-résumé)
- [3. Installation](#3-installation)
- [4. Présentation](#4-présentation)
  - [4.1 Lancement du plugin](#41-lancement-du-plugin)
  - [4.2 Fonctionnalités](#42-fonctionnalités)
    - [4.2.1 Ajouter une vue](#421-ajouter-une-vue)
    - [4.2.2 Supprimer une vue](#422-supprimer-une-vue)
    - [4.2.3 Renommer une vue](#423-renommer-une-vue)
    - [4.2.4 Déplacer un onglet vue](#424-déplacer-un-onglet-vue)
    - [4.2.5 Modifier une vue](#425-modifier-une-vue)
    - [4.2.6 Importer une vue](#426-importer-une-vue)  

  
<div  style="background-color: #00ADC5; border: 1px solid black; padding: 5px; text-align: justify;margin-bottom:10px;">
  <h2 id="1-prérequis" style="color: white;margin:0;" >1. Prérequis</h2>
</div>  

Version de QGIS 3 : 3.28 ou supérieure.    


<div  style="background-color: #00ADC5; border: 1px solid black; padding: 5px; text-align: justify;margin-bottom:10px;">
  <h2 id="2-résumé" style="color: white;margin:0;">2. Résumé</h2>
</div>  
  
Le plugin Vues permet de sauvegarder le style et les visibilités des couches du projet actif dans la barre d’état de QGis sous forme d’onglets.  
Il permet aussi de supprimer ces vues, de les modifier et de les organiser.  
  
<div  style="background-color: #00ADC5; border: 1px solid black; padding: 5px; text-align: justify;margin-bottom:10px;">
  <h2 id="3-installation" style="color: white;margin:0;">3. Installation</h2>
</div>  
  
Le plugin Vues s’installe avec l’exécutable d’installation.  
  
<div  style="background-color: #00ADC5; border: 1px solid black; padding: 5px; text-align: justify;margin-bottom:10px;">
  <h2 id="4-présentation" style="color: white;margin:0;">4. Présentation</h2>
</div>  
  
### <span style="color: white; background-color: #00ADC5; padding: 2px 5px;">4.1 Lancement du plugin</span>
<div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
		<img  src="images/Image1.png"  style="vertical-align: middle;" />  
		<img  src="images/Image2.jpg"  style="vertical-align: middle;" />
</div>  
  
Le plugin Vues se lance dans le menu IGN ou en cliquant sur l’icône représentant un œil dans la barre d’outils selon le choix enregistré dans le plugin Maitre.  

### <span style="color: white; background-color: #00ADC5; padding: 2px 5px;">4.2 Fonctionnalités</span>
<div  style="text-align: center;"> 
	<img  src="images/Image3.jpg" />
</div>  
  
#### <span style="color: #00ADC5">4.2.1 Ajouter une vue</span>  

-	Modifier les styles des couches du projet selon le rendu désiré.    
-	Cliquer sur le bouton ![Image4](images/Image4.png)  
-	Entrer le nom de la vue.  
  
#### <span style="color: #00ADC5">4.2.2 Supprimer une vue</span>  
  
-	Clic droit sur l’onglet vue à supprimer  
-	![Image5](images/Image5.png)  

#### <span style="color: #00ADC5">4.2.3 Renommer une vue</span>  

- Clic droit sur l’onglet vue à renommer  
- ![Image6](images/Image6.png)  
- Saisir le nouveau nom et confirmer avec le bouton OK  
  
#### <span style="color: #00ADC5">4.2.4 Déplacer un onglet vue</span>  
  
- Sélectionner l’onglet de la vue à déplacer. Il apparaît en vert.  
- Cliquer sur les flèches ![Image7](images/Image7.png) pour déplacer l’onglet vers la gauche ou vers la droite.  

  
#### <span style="color: #00ADC5">4.2.5 Modifier une vue</span>  

- Sélectionner l’onglet de la vue à modifier. Il apparaît en vert.  
- Modifier les styles et/ou visibilités des couches dans le panneau Couches.  
- Cliquer sur le bouton ![Image8](images/Image8.png) et confirmer.  
  

#### <span style="color: #00ADC5">4.2.6 Importer une vue</span>  
  
La création de vues avec ce plugin crée un répertoire VUES à la racine du projet.  
Le bouton ![Image9](images/Image9.png) permet d’importer une vue déjà créée dans un autre projet  

- Naviguer et sélectionner le répertoire VUES à partir duquel importer une vue  
- Cocher la ou les vues disponibles à importer  

<div  style="text-align: center;"> 
	<img  src="images/Image10.png" />
</div>

- Cliquer sur le bouton "Importer" pour ajouter la vue dans le projet.  
Si une vue du même nom existe déjà, l’outil fait une mise à jour de celle-ci
