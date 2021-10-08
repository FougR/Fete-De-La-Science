# Documentation M5Stack
### Présentation
> Dans le cadre de la fête de la science 2021, le lycée Livet vous montre un robot capable de vous indiquer dans quelle poubelle est à mettre le déchet que vous lui montrer. Ce robot est controlé par ce qu'on appelle un M5Stack.

> Pour faire simple, le **M5Stack** est un kit de dévelopement qui contient un *ESP32* (micro-controleur avec wifi et bluetooth), un écran, une baterie et trois boutons.
En gros, il faut voir ça comme un **mini ordinateur** que l'on va controler avec un language appelé **Micropython** (c'est une version de *Python* spécialisée pour les micro-controleur)

### Commandes utiles pour l'activitée
**Effacer le contenu de l'écran**
```python
lcd.clear()
```

 **Afficher un texte sur l'écran** 
```python
lcd.print("text", x, y, lcd.COLOR)
```
| Argument | Définition |
| ------ | ------ |
| x | Coordonées x du texte |
| y | Coordonées y du texte |
| text | Contenu de ton texte |
| COLOR | Couleur du texte |

**Afficher une image sur l'écran** 
```python
lcd.image(x, y, "lien_image", ZOOM)
```
| Argument | Définition |
| ------ | ------ |
| x | Coordonées x de l'image |
| y | Coordonées y de l'image |
| lien_image | Lien de l'image |
| ZOOM | Valeur de 0 (max) à 3 (min) |

**Afficher un rectangle**
```python
lcd.rect(x, y, lenX, lenY, lcd.COLOR, lcd.COLOR2)
```
| Argument | Définition |
| ------ | ------ |
| x | Coordonées x du rectangle |
| y | Coordonées y du rectangle |
| lenX | Taille des côtés horizontaux |
| lenY | Tailles des côtés verticaux |
| COLOR | Couleur du bord du rectangle |
| COLOR2 | Couleur de remplissage du rectangle |

**Afficher un cercle**
```python
lcd.circle(x, y, radius, lcd.COLOR, lcd.COLOR2)
```
| Argument | Définition |
| ------ | ------ |
| x | Coordonées x du cercle |
| y | Coordonées y du cercle |
| radius | Rayon du cercle |
| COLOR | Couleur du bord du cercle |
| COLOR2 | Couleur de remplissage du cercle |
