Een **kwadratische vergelijking** is een vergelijking van de vorm 

$$ax^2 + bx + c = 0\,,$$

waarin $$a, b, c \in \mathbb{R}$$ en $$a \neq 0$$.

De grootheid

$$\Delta = b^2 - 4ac$$

is de **discriminant** van de kwadratische vergelijking. Het teken van $$\Delta$$ bepaalt het aantal reële oplossingen:

- als $$\Delta > 0$$ dan zijn er twee verschillende reële oplossingen $$x_1 \neq x_2$$

- als $$\Delta = 0$$ dan zijn er twee gelijke reële oplossingen $$x_1 = x_2$$

- als $$\Delta < 0$$ dan zijn er geen reële oplossingen voor de vergelijking

De reële oplossingen kunnen bepaald worden met de zogenaamde wortelformule:

$$x_{1} = \frac{-b - \sqrt{\Delta}}{2a}\ \ \ \text{en}\ \ \ x_{2} = \frac{-b + \sqrt{\Delta}}{2a}$$

### Invoer

Vraag de gebruiker naar de drie parameters $$a$$, $$b$$ en $$c$$ van een kwadratische vergelijking, elk op een afzonderlijke regel.

### Uitvoer

Een regel die aangeeft hoeveel verschillende reële oplossingen de kwadratische vergelijking heeft. De oplossingen zelf moeten ook vermeld worden (als die er zijn). Kijk naar onderstaande voorbeelden voor de gevraagde syntax.

### Voorbeeld 1

#### Invoer:

```
1
4
-5
```

#### Uitvoer:

```
Er zijn 2 reële oplossingen: -5.0 en 1.0
```

### Voorbeeld 2

#### Invoer:

```
1
-12
36
```

#### Uitvoer:

```
Er is 1 reële oplossing: 6.0
```

### Voorbeeld 3

#### Invoer:

```
4
2
7
```

#### Uitvoer:

```
Er zijn geen reële oplossingen
```

### Voorbeeld 4

#### Invoer:

```
0
0
3
```

#### Uitvoer:

```
Ongeldige vergelijking
```
