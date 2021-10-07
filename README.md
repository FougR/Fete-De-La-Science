# Documentation M5Stack
### Présentation
> Dans le cadre de la fête de la science 2021, le lycée Livet vous montre un robot capable de vous indiquer dans quelle poubelle est à mettre le déchet que vous lui montrer. Ce robot est controlé par ce qu'on appelle un M5Stack.

> Pour faire simple, le **M5Stack** est un kit de dévelopement qui contient un *ESP32* (micro-controleur avec wifi et bluetooth), un écran, une baterie et trois boutons.
En gros, il faut voir ça comme un **mini ordinateur** que l'on va controler avec un language appelé **Micropython** (c'est une version de *Python* spécialisée pour les micro-controleur)

### Commandes utiles pour l'activité
 **Afficher un texte sur l'écran** 
```python
lcd.print(x, y, "text", COLOR)
```
| Argument | Définition |
| ------ | ------ |
| x | Coordonées x du texte |
| y | Coordonées y du texte |
| text | Contenu de ton texte |
| COLOR | Couleur du texte |

**Afficher une image sur l'écran** 
```python
lcd.print(x, y, "text", COLOR)
```
| Argument | Définition |
| ------ | ------ |
| x | Coordonées x du texte |
| y | Coordonées y du texte |
| text | Contenu de ton texte |
| COLOR | Couleur du texte |
