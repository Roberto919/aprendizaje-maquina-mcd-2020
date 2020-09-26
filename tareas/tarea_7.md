# Tarea 7 

### José Roberto Pérez Chávez

Leer la sección 6.1 (Regularización ridge) de las notas y sus dos ejemplos(el de bodyfat y el de clasificación con datos simulados).

1. En el ejemplo de grasa corporal, 

   - ¿Qué pasa con los coeficientes cuando el coeficiente lambda de regularización aumenta? 
     - *Los coeficientes se acercan más a cero conforme la lambda aumenta. Esto deriva en una reducción de la varianza pero potencialmente un incremento en el sesgo.*

   - ¿Es cierto que cada coeficiente individual se acerca a 0 conforme la regularización aumenta? 
     - *Todos los coeficientes se acercan a cero salvo $\beta_0$, el cual no es penalizado.*
   - ¿Qué cantidad se acerca a cero conforme la regularización aumenta?
     - *La varianza*

2. ¿Por qué es buena idea estandarizar los coeficientes antes de aplicar regularización? (Piensa en las escalas de los coeficientes)

   - *Por que, si los coeficientes están a distintas escalas, la penalización afectará de forma de forma distinta a cada coeficiente.*

3. En el siguiente ejemplo de simulación, 

   - ¿Cómo se seleccionaría el parámetro de regularización óptimo? 
     - *El mejor parámetro de regularización se debe elegir conforme al desempeño del modelo en el set de prueba.*

   - ¿Por qué la devianza de prueba tiene una forma de U?
     - *Porque existe un punto medio entre tener un valor bajo del parámetro $\lambda$ (baja penalización, varianza alta y potencialmente sesgo bajo) y un valor alto del parámetro $\lambda$ (alta penalización, varianza baja y potencialmente sesgo alto) que nos dará el menor error posible en las predicciones de nuestro modelo en el set de prueba.*

4. En este mismo ejemplo 

   - ¿Qué crees que pase con la devianza de entrenamiento? 
     - *Aumentará. La devianza será mayor con el modelo regularizado que con el modelo sin regularizar.*

   - ¿Tendrá una forma de u también?
     - *No este será siempre mayor conforme aumente el valor del parámetro $\lambda$.*


