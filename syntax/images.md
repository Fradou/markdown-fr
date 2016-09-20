# Images

'''markdown
#Inline
![Alternative text](/path/to/img.jpg "Optimal title")

#Reference
![Alternative text][id]
[id]: url/to/image  "Optional title"

As you may have noticed, picture in markdown are very close to links.  
The difference is the following :
* brackets must be preceded by an exclamation point ;
* they may contain an alternative text, which is displayed when the picture isn't loaded.

---

Voilà un quizz au sujet des images dans Markdown :

Selectionnez les images valides :
- [ ] `[Google logo](https://www.google.ru/logo.png)`
- [x] `![](https://www.google.ru/logo.png)`

> Les images doivent être précédés d'un point d'exclamation.
Le texte alternatif et le titre sont optionnels.

Qu'est ce qui est bon dans la ligne suivante : '''![Funny cat]((http://cats.ru/funny.png "Partage ça")```
- [x] si l'url est 404, "Funny cat" va être affiché.
- [ ] le point d'exclamation peut être omis dans cette case
- [ ] si l'url est 404, "Partage ça" va être affiché
- [x] quand la souris passe au dessus, "Partage ça" sera affiché

> De la même manière que pour les liens, les images peuvent avoir 3 parties : le texte alternatif, l'url et la titre. Un point d'exlamation est nécessaire.

---


# Images

```markdown
# Inline
![Alternative text](/path/to/img.jpg "Optional title")

# Reference
![Alternative text][id]
[id]: url/to/image  "Optional title"
```
Comme vous avez dû le remarquer, les images en Markdown sont très semblables aux liens.  
La différence est la suivante :
* les crochets doivent être précédés par un point d'exclamation ;
* ils peuvent contenir un texte alternatif, qui s'affiche quand l'image ne peut être chargée.

---

Here's a quiz about markdown images.

Select the valid images:
- [ ] `[Google logo](https://www.google.ru/logo.png)`
- [x] `![](https://www.google.ru/logo.png)`

> Images must be prefixed with an exclamation mark.
The alternative text and a title are optional.

What is true about the following line: ```![Funny cat](http://cats.ru/funny.png "Share this")```
- [x] if the url is 404, "Funny cat" will be displayed
- [ ] exclamation mark can be omitted in this case
- [ ] if the url is 404, "Share this" will be displayed
- [x] on mouse over the image "Share this" will be displayed

> Similarly to links, images can have 3 parts: the alternative text, the url and a title. An exclamation mark is nesessary.

---
