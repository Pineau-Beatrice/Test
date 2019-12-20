# Dans ce fichier, nous allons simplement faire la différence entre le mois dans lequel on se trouve et mars .
select (Month(sysdate)-3) into total_mois from dual 
