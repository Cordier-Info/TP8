1. 
Prouvons que $p\times a^n$ est un invariant de boucle.
Pour cela, on pose $a_k$, $n_k$ et $p_k$, les valeurs de $a$, $n$ et $p$ après le k<sup>ème</sup> passage dans la boucle et on suppose que $p_k\times a_k^{n_k} = cste$.  

 - Initiation : p<sub>0</sub>×a<sub>0</sub><sup>n<sub>0</sub></sup> = \cdots$ (en utilisant les valeurs initiales)  
 - Conservation : supposons que $p_k\times a_k^{n_k} = a^n$. À la boucle suivante, deux cas se présentent :
   - si $n_k$ est pair, alors $a_{k+1} = \cdots$, $n_{k+1} = \cdots$ et $p_{k+1}=\cdots$.    
     Donc $p_{k+1}\times a_{k+1}^{n_{k+1}} = \cdots$.  
     - si $n_k$ est impair, alors $a_{k+1}=\cdots$, $p_{k+1}=\cdots$ et  $n_{k+1}=\cdots$.  
       Donc $p_{k+1}\times a_{k+1}^{n_{k+1}} = \cdots$.  
       $p_k\times a_k^{n_k}$ est bien un invariant quelque soit $k$.
- Terminaison : la boucle s'arrête quand $n=0$, ou $n_f = 0$ en appelant $f$ la dernière boucle. Et on a nécessairement $n_{f-1} = \cdots$ en début de boucle.<br>En sortie de denière boucle, on a  $p_f = p_{f-1}\times a_{f-1}$. Et comme $n_{f-1}=\cdots$, $p_f = \cdots$.  
  La fonction retourne donc bien $a^n$.
