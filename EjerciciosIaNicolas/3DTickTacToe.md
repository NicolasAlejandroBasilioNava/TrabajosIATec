## Estrategia de Victoria (en nivel 2D)
### Las posiciones más importantes en el primer par de tiradas que se hacen son, dependiendo de si tú empiezas o no;
**Tirando Primero** 
1. Ganar una esquina como primer tiro
2. De ser posible ganar el centro en el segundo, de esta forma la victoria casi asegurada
   
**Tirando Segundo**
1. Primer tiro asegurar el centro de ser posible y en caso de que el centro este ocupado es ganar las esquinas.
2. Como segundo tiro, en caso de que el contrincante este por ganar tapar la victoria y si no ganar una esquina cercana a sus tiros

## Estrategia de Victoria (en 3D)
### Siendo las posiciones más importantes como se muestra en la siguiente lista de mayor a menor importancia
1. Centro del plano intermedio
2. Esquinas de los planos exteriores
3. Aristas de los planos exteriores
4. Esquinas de plano intermedio
5. Aristas de plano intermedio
6. Centros de los planos exteriores

### Ahora si planteamos una estrategia para ganar dependeremos totalmente de nuestros primero dos tiros
**Tirando Primero**
1. El primer tiro ira indiscutiblemente al centro del plano intermedio, esto debido a que es el que cubre más posibilidades de conectar 3
2. El segundo tiro, ya que lo más probable es que el jugador se quiera adueñar de una de las esquinas exteriores, ira en un centro externo del plano en el que haya colocado su tiro. **En caso de que haya tomado un centro de un plano exterior**, para este caso se tomara una esquina exterior
3. Si ocurrió lo más probable en el segundo tiro, tenemos que dar el tiro en una esquina del plano exterior donde colocamos en el centro que nos habilite la doble amenaza tanto en ese plano como en la diagonal que se genera tomando en cuenta el centro del plano intermedio. **Para el segundo caso**, aquí se tirará en la esquina central paralela al tiro anterior, generando así una doble amenaza en una línea entre los tres planos y la diagonal del plano intermedio.

**Tirando Segundo**

SECUENCIA DE PERCEPCION