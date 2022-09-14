#TP1

##Page Login

![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `#f03c15` pour les Grid Layout qu'on les utilise dans le structure genérale du la classe container.  
![#3b3b3b](https://via.placeholder.com/15/f03c15/f03c15.png) `#3b3b3b` pour les flex Layout qu'on les utilise dans la structure de la classe Body.  
![#224900](https://via.placeholder.com/15/f03c15/f03c15.png) `#224900` pour les flex Layout qu'on les utilise dans la structure de l'item-b dans la premiére partie du de la classe BODY et du l'item-c dans la deuxiéme partie.  
![#ffff00](https://via.placeholder.com/15/f03c15/f03c15.png) `#ffff00` pour les flex Layout qu'on les utilise dans la structure de la classe form qu'elle est dans l'item-c.  
<img src="https://github.com/Master-2-MIAGE-MBDS/web-integration-responsive-design-MatallahMouncif/blob/main/Capture/FLogin.png"  title="Login" width=300px height=600px>  
La structure générale de la page est diviser de la facon dans la photo. Ca était fait par le code CSS suivant :  
```html
<h2>Example of code</h2>



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
  
  Aprés on a le Body qui contient deux items item-b et items-c on a séparé ces deux par ajouté un flex comme le code suivant
  .body{
    
    grid-area: body;
    display: flex;
    flex-direction: column;
    align-items: center; 
    
  
  }
  On a donné un flex=1 pour item-b est flex=3 pour item-c. 
  
  
 Aprés dans le item-b on a trois items c'est l'image et les deux paragraphs tout sont séparés par un flex par le code suivant
 ```html
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

  
  Et pour l'item-c on a un form dans ce dernier on a trois parties input chaqu'une est séparés tout seule par un flex. Vous trouverez le code d'item-c et du form
   .item-c {grid-area: item-c;
    height: 100%;
    width: 100%;
    flex: 3;
    display: flex;
    flex-direction: column;
    align-items: center; 
    } 
    
    
  
  






