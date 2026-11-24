# Resultados de caminos y filtros

### Candidatos a puentes conceptuales entre emociones. 

Archivos de formato .csv con los conteos de las palabras no emocionales (filtradas) en los caminos
___

### División por idioma.

- Filtrado por No Existencia en EmoPro
- Revisión en ConceptNet si una relación directa catalogaba la palabra como emoción
- Filtra también palabras que se encuentren en relación de sinonimia con las palabras de EmoPro

El nuevo esquema de nombramiento es:
Candidatos_puentes_*idioma*_*relaciónDeBúsqueda*_*E1Proto*_*E2Proto*
Donde *idioma* será inglés o español, *relaciónDeBúsqueda* que puede ser noSinonimia, entailmment (o implicatura), semánticas o ninguna, _E1Proto_ es la inicial de la primera emoción (F = Felicidad, E = Enojo, T = Tristeza, M = Miedo y A = Asco) y el grado de prototipicalidad (A = Alta, B = Baja). Lo mismo sucede para _E2Proto_
