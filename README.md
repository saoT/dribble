**Dribble React**

Reproduire une des deux interfaces de Dribble en utilisant dribble: 

+ [Une grid avec modal](https://dribbble.com/)
+ [Une fiche avec présentation](https://dribbble.com/shots/3018657-Brand-Elements-in-Action)

## API Proxy :

Vous pouvez remplacer les "fake" données de vos interfaces avec les données de api.dribbble.com

La documentation de l'API : 
http://developer.dribbble.com/v1/

Un proxy est en place à cette adresse :
https://simplon-p6-proxy.herokuapp.com (correspond à https://api.dribbble.com/v1)

Avec le proxy, vous pouvez effectuer toutes les requêtes GET de l'API.

exemples :

* https://simplon-p6-proxy.herokuapp.com:3000/shots
* https://simplon-p6-proxy.herokuapp.com/shots?list=animated
* https://simplon-p6-proxy.herokuapp.com/shots?list=animated&timeframe=week&sort=recent
* https://simplon-p6-proxy.herokuapp.com/shots/3219901
* https://simplon-p6-proxy.herokuapp.com/users/237483
* https://simplon-p6-proxy.herokuapp.com/users/237483/shots
* https://simplon-p6-proxy.herokuapp.com/users/237483/projects
* https://simplon-p6-proxy.herokuapp.com/users/237483/likes



