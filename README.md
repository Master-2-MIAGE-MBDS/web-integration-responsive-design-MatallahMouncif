#TP1
##Page Login
<img src="/Downloads/Login" alt="Employee data" title="Login2" width=100px height=300px>
La structure générale de la page est diviser de la facon dans la photo. Ca était fait par le code CSS suivant :
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
  
  
  Aprés on a le Body qui contient deux items item-b et items-c on a séparé ces deux par ajouté un flex comme le code suivant
  .body{
    
    grid-area: body;
    display: flex;
    flex-direction: column;
    align-items: center; 
    
  
  }
  On a donné un flex=1 pour item-b est flex=3 pour item-c. 
  
  
 Aprés dans le item-b on a trois items c'est l'image et les deux paragraphs tout sont séparés par un flex par le code suivant
 
 .item-b { height: 100%;
    width: 100%;
    grid-area: item-b ;
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
   background-color: #cfd8dc; 
  }
  
  Et pour l'item-c on a un form dans ce dernier on a trois parties input chaqu'une est séparés tout seule par un flex. Vous trouverez le code d'item-c et du form
   .item-c {grid-area: item-c;
    height: 100%;
    width: 100%;
    flex: 3;
    display: flex;
    flex-direction: column;
    align-items: center; 
    } 
    
    
  
  






