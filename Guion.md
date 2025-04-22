

## 📌 Objetivo del storytelling:
Explorar cómo se comportan los usuarios en una app de citas, qué patrones hay en sus perfiles, y qué factores podrían influir en las conexiones exitosas.

### 📘 Introducción: Amor en tiempos de algoritmos
“Cada perfil es una historia. Pero… ¿pueden los datos contarnos qué hay detrás de un match? Analizamos casi 60.000 perfiles de OkCupid para descubrir patrones, contrastes y curiosidades del amor digital.”


### 📊 Parte 1: ¿Quién está buscando el amor online? (contexto)

__Visualizaciones:__
- BN usuarios ✅
- Gráfico pie: usuarios por género ✅
- Media por eddad ✅
- Gráfico de barras: distribución edad por género ✅
- Gráfico circular o stacked bar: sexo y orientación ✅
- Gráfico de barras: religión vs género ✅
- Gráfica: etnia ✅
- Mapa: concentración geográfica ✅
- Religión vs orientación ✅
- Datos: año, país, etc. ✅

📌 Insight: “La mayoría tiene entre 25 y 35 años. Predominan usuarios heterosexuales, pero hay diversidad de orientaciones.”

### 💭 Parte 2: ¿Qué muestran (y ocultan) los perfiles?

__Visualizaciones:__
- Histograma: ```profile_completeness``` ✅
- Boxplot: ```essay_word_count``` por género  ✅
- Barras: frecuencia de hábitos (fumar, beber, drogas) ✅
- Barras: hijos por género o búsqueda de hijos ✅

- Análisis cruzado estilo de vida Mapa de calor (heatmap) cruzando ```diet_grouped``` y ```religion_grouped``` 
- Barras por smokes o drinks cruzado con ```likes_received``` ¿Los hábitos influyen en la actividad o popularidad? ✅
=======
- Análisis cruzado estilo de vida Mapa de calor (heatmap) cruzando ```diet_grouped``` y ```religion_grouped``` ✅
- Barras por smokes o drinks cruzado con ```likes_received``` ✅
¿Los hábitos influyen en la actividad o popularidad?


📌 Insight: “Los hombres tienden a escribir menos en su perfil. Las mujeres completan más su perfil y mencionan más hábitos saludables.”

### 💌 Parte 3: ¿Qué influye en conseguir más likes y matches?

__Visualizaciones:__

- Scatterplot: ```likes_received``` vs. ```essay_word_count``` o ```profile_completeness```
- Boxplot: ```mutual_matches``` por ```body_type_grouped```, ```education_grouped```, etc. ✅
- Porcentaje perfil completo  ✅ (falta % en el eje)
- Tipo de cuerpo vs likes receives ✅
- Tiempo y uso Boxplot o barras de ```time_spent_daily``` por orientación, género o edad  ✅
- Gráfico de dispersión: ```profile_completeness``` vs. ```likes_received``` ¿Influye tener el perfil completo? ¿Quién pasa más tiempo en la app? ✅
=======
- Boxplot: ```mutual_matches``` por ```body_type_grouped```, ```education_grouped```, etc. ✅
- Porcentaje perfil completo  ✅
- Tipo de cuerpo vs likes receives ✅
- Tiempo y uso Boxplot o barras de ```time_spent_daily``` por orientación, género o edad  ✅
- Gráfico de dispersión: ```profile_completeness``` vs. ```likes_received``` ✅
¿Influye tener el perfil completo? ¿Quién pasa más tiempo en la app?


📌 Insight: “Los perfiles más completos tienden a recibir más likes. Las personas con educación universitaria también destacan.”

### 🔎 Parte 4: Swipe right o swipe left, ¿cómo decidimos?
__Visualizaciones:__
- Barras: ```swipe_right_ratio``` por sexo ✅
- Boxplot: ```time_spent_daily``` por tipo de relación o estado civil
-  Swiping behavior Tarta o barra de proporción por ```swipe_right_label``` Media de ```swipe_right_ratio``` por sexo/orientación ¿Quién es más selectivo? ¿Quién da más likes?
- Comparación entre lo que buscan y lo que ofrecen (si cruzamos variables como status y orientation)
=======
- Barras: ```swipe_right_ratio``` por sexo  ✅
- Boxplot: ```likes``` por tipo de relación o estado civil ✅
- Swiping behavior Tarta o barra de proporción por ```swipe_right_label``` ✅
- Media de ```swipe_right_ratio``` por sexo/orientación ¿Quién es más selectivo? ¿Quién da más likes? ✅
Comparación entre lo que buscan y lo que ofrecen (si cruzamos variables como status y orientation)


📌 Insight: “Los hombres hacen más swipe right que las mujeres. Quienes buscan relaciones serias tienden a pasar más tiempo en la app.”

### ✅ Conclusión: ¿Qué aprendimos del amor digital?
“Más allá del algoritmo, la autenticidad y la comunicación parecen marcar la diferencia. Un perfil completo, honesto y con propósito tiene más probabilidades de generar conexión.”