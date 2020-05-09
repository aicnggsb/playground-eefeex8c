# Calcul de distance entre un satellite et son recepteur GPS

Afin d'estimer la distance entre un satellite et un recepteur GPS, la fonction <i>tempsParcours</i> calcule l'écart de temps, en secondes, entre l'heure d'arrivée et l'heure d'envoi du message.
```python
def tempsParcours(h1, m1, s1, h2, m2, s2):
  t1=h1*3600+m1*60+s1
  t2=h2*3600+m2*60+s2
  return t2-t1
```

@[]({"stubs": ["exercice01.py"]})

?[Que contiennent les variables t1 et t2 ?]
-[ ] Une distance en mètre
-[ ] Une distance en kilomètre
-[x] Une durée en seconde
-[ ] Une durée en minute
-[ ] Une durée en heure



