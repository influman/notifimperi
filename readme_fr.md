# Installation
Gestion des Notifications TTS via API ImperiHome  
Compatible avec chatBOT et Ask.
    
  
### Ajout du périphérique
Cliquez sur "Configuration" / "Ajouter ou supprimer un périphérique" / "Store eedomus" / "Notifications TTS Imperihome" / "Créer"  

  
*Voici les différents champs à renseigner:*

* [Obligatoire] - L'IP fixe du device sur lequel tourne Imperihome (avec API activée)
* [Obligatoire] - Le port d'accès à l'API Imperihome 

  
### Utilisation
Prédéfinissez des notifications dans les valeurs du périphérique créé par le plugin.  
Respectez bien la forme des valeurs et l'url du script appelé, à l'instar des valeurs par défaut fournies à la création.  
*NB1 : Ne supprimez pas la valeur cachée 9999 - [CHATBOT], dédiée au plugin du même nom.*  
*NB2 : Ne supprimez pas la valeur cachée 99999 - [ASK], dédiée au plugin du même nom.*  
 
Vous pouvez intégrer la valeur d'un ou plusieurs périphériques existants via son code API entre crochet, exemple : [123456].  

Lancez ensuite vos notifications depuis vos règles.  

