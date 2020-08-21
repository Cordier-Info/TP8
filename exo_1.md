1. 
Prouvons que p×a<sup>n</sup> est un invariant de boucle.
Pour cela, on pose a<sub>k</sub>, n<sub>k</sub> et p<sub>k</sub>, les valeurs de a, n et p après le k<sup>ème</sup> passage dans la boucle et on suppose que p<sub>k</sub>×a<sub>k</sub><sup>n<sub>k</sub></sup> = cste.  

- Initiation : p<sub>0</sub>×a<sub>0</sub><sup>n<sub>0</sub></sup> = ... (en utilisant les valeurs initiales)  
- Conservation : supposons que p<sub>k</sub>×a<sub>k</sub><sup>n<sub>k</sub></sup> = a<sub>n</sub>. À la boucle suivante, deux cas se présentent :
  - si n<sub>k</sub> est pair, alors a<sub>k+1</sub> = ..., n<sub>k+1</sub> = ... et p<sub>k+1</sub> = ....    
    Donc p<sub>k+1</sub>×a<sub>k+1</sub><sup>n<sub>k+1</sub></sup> = ... .  
  - si n<sub>k</sub> est impair, alors a<sub>k+1</sub> = ..., p<sub>k+1</sub> = ... et n<sub>k+1</sub> = ... .  
    Donc p<sub>k+1</sub>×a<sub>k+1</sub><sup>n<sub>k+1</sub></sup> = ....  
  
  p<sub>k</sub>×a<sub>k</sub><sup>n<sub>k</sub></sup> est bien un invariant quelque soit k.

- Terminaison : la boucle s'arrête quand n = 0, ou n<sub>f</sub> = 0 en appelant f la dernière boucle. Et on a nécessairement n<sub>f-1</sub> = ... en début de boucle.<br>
En sortie de denière boucle, on a p<sub>f</sub> = p<sub>f-1</sub>×a<sub>f-1</sub> = p<sub>f-1</sub>×a<sub>f-1</sub><sup>n<sub>f-1</sub></sup> = ...  

La fonction retourne donc bien a<sup>n</sup>.
