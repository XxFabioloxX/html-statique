# Formats d'images pour le WEB

## `JPG` / `JPEG` (*bitmap = pixel*)

### Million de couleurs 

    photos / portraits / montages
    ! Format de compression " destructive "

---

## `PNG`

### Million de couleurs et/ou palette de couleurs indexées

    Comporte de la transparence Alpha (% de transparence)
    ! Format de compression par suppresision de couleurs non-utilisées
    Photos / portraits / montages / picto / logo / illustration

---

## `GIF` (*bitmap = pixel*)

    255 couleurs + transparence (classique / pas alpha)
    Animation avec une série d'images
    picto / logo / illustration

---

>Pour tout ça :
>>Resolution DPI (*dot pr inch*)<br>
>>+ Min "`72 DPI`" <br>
>>+ Max "`120 DPI`" > *Rétina*

---

# `SVG` (pas bitmap)

>+ Vectoriel (du texte - code format XML)

---

<a href="https://fr.wix.com/blog/formats-fichiers-comment-utiliser">lien</a>

---
---

# Hexadecimal

> 0 à 9 - A à F
>>0123456789ABCDEF

        Rouge       Vert        Bleu

    #   F   F       F   F       F   F       -> Blanc   

    #   0   0       0   0       0   0       -> Noir

    #   F   F       0   0       0   0       -> Rouge pétant

    #   0   0       F   F       0   0       -> Vert flashy

    #   0   0       0   0       F   F       -> Bleu pronconcé


---

# `RGB` 
>                                       R     G   B
>       body { background-color : rgb ( 255 , 0 , 0)}
>                                       #FF0000

# `RGBA`

>body { background-color : rgb`a` ( 255 , 0 , 0, `0.5`)} 
>>                         |           |         
>>                        ->Alpha 50%<-

---
---

