# TP1

## Page Login

![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `#f03c15` pour les grid layout qu'on les utilise dans le structure genérale du la classe container.  
![#3b3b3b](https://via.placeholder.com/15/3b3b3b/3b3b3b.png) `#3b3b3b` pour les flex layout qu'on les utilise dans la structure de la classe Body.  
![#224900](https://via.placeholder.com/15/224900/224900.png) `#224900` pour les flex layout qu'on les utilise dans la structure de l'item-b dans la premiére partie du de la classe BODY et du l'item-c dans la deuxiéme partie.  
![#ffff00](https://via.placeholder.com/15/ffff00/ffff00.png) `#ffff00` pour les flex Layout qu'on les utilise dans la structure de la classe form qu'elle est dans l'item-c.  
<img src="https://github.com/Master-2-MIAGE-MBDS/web-integration-responsive-design-MatallahMouncif/blob/main/Capture/FLogin.png"  title="Login" width=300px height=600px>  
Seulement dans La structure générale de la page on utilise les grid layout. Cette page est divisé a trois partie 
- Header: le texte Sign in  
- Body : On a deux parties item-b et item-c :
   - item-b se divise a trois parties une pour l'image et les deux autres pour le texte écrit.
   - item-c contient une classe form ou cette derniére contient deux parties input de taille différentes répartitionnés avec un flex. 
        - Premiére partie : contient une classe POP dans un div qui contient deux inputs Username et password. le flex dans cette div est 2
        - Deuxiéme partie : contient un input submit avec un flex = 1
 - Footer : Contient un text


Le code Css du Grid layout de la structure genérale de la page: 
      
```css
.container {
    
    height: 100%;
    grid-template-columns:  auto;
    grid-template-rows: 10% auto 5%;
    display: grid;
  
  
  grid-template-areas:
  "header "
  "body"
  "footer";
  }
  ```
  
 Exemple ou on utilise le flex : dans item-b on a trois parties était fait de la façon suivantes  
 
 ```css
  .item-b { height: 100%;
    width: 100%;
    grid-area: item-b ;
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
   background-color: #cfd8dc; 
  }
   ```
  Les autres Flex sont presuqes de la meme façon.
    
  ## Page Ads mobile sans Media Queries:  
   ### Le Css de cette page est Mobile_AdsCSS.css et le Html est Mobile_Ads.html. 
   ### Cette page est juste pour le mobile. Je n'ai utilisé pas du Media Queries dans ce CSS. 
   ### La version concaténé du desktop et mobile vous la trouverz dans le Css Dektop_AdsCSS.css et le Html est Deskotp_Ads.html.
   
   Le Grid c'est la meme chose comme Login.   
   Pour les flex aussi c'est la meme chose que Login sauf des changements mineurs par exemple a la place du flex-direction : column on utilise flex-direction : row.
   La seule différences c'est dans Header on utilise aussi un flex.
  
  
 ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `#f03c15` pour les Grid Layout qu'on les utilise dans le structure genérale du la classe container.  
![#3b3b3b](https://via.placeholder.com/15/3b3b3b/3b3b3b.png) `#3b3b3b` pour les flex Layout  de la classe "header" dans le Header et dans la classe "body" dans le Body qu'on les utilise dans la structure de la classe Body.  
![#224900](https://via.placeholder.com/15/224900/224900.png) `#224900` pour les flex Layout qu'on les utilise dans la classe "Ads" qu'elle est dans la div de la classe "header" pour séparé les deux bouton du submit.
![#ffff00](https://via.placeholder.com/15/ffff00/ffff00.png) `#ffff00` pour les flex Layout qu'on les utilise dans la structure de la classe "item-b qu'elle se répéte dans le Body.



   

<img src="https://github.com/Master-2-MIAGE-MBDS/web-integration-responsive-design-MatallahMouncif/blob/main/Capture/FFMobile_Ads.png"  title="Login" width=300px height=600px>  




   

   
 ## Page Ads mobile-desktop Avec Media Queries : 
   ### Le Css de cette page est Dektop_AdsCSS.css et le Html est Deskotp_Ads.html.   
   ### Une toute nouvelle page avec son propre CSS en utilisant le meme CSS de la Mobile_Ads.css juste en rajoutant plus d'Ads et en utilisant des media Queries. comme    vous voyez dans le gif.  
   
   
![Mobile_To_Desktop](https://github.com/Master-2-MIAGE-MBDS/web-integration-responsive-design-MatallahMouncif/blob/main/Capture/Version_Desktop.html%20and%204%20more%20pages%20-%20Personal%20-%20Microsoft_%20Edge%202022-09-14%2019-49-59.gif)

   
   






 
 
  
  






