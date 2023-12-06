### Ranas y Sapos

##### Medida de Rendimiento
* Todas las ranas de la izquierda toma el lugar que inicialmente tenian las de la derecha y viceverza +1
* Una rana se mueve y deja espacio para otro movimiento 0
* Ninguna rana puede hacer un movimiento -1

##### Secuencia de Percepción
Tomando en cuenta el siguiente posicionamiento: (R3, R2, R1, E, S1, S2, S3)

Donde R y S se refieren a las ranas y sapos respectivamente, y E se refiere al espacio libre
1. (R3, R2, R1, S1, E, S2, S3)
2. (R3, R2, E, S1, R1, S2, S3)
3. (R3, E, R2, S1, R1, S2, S3)
4. (R3, S1, R2, E, R1, S2, S3)
5. (R3, S1, R2, S2, R1, E, S3)
6. (R3, S1, R2, S2, R1, S3, E)
7. (R3, S1, R2, S2, E, S3, R1)
8. (R3, S1, E, S2, R2, S3, R1)
9. (E, S1, R3, S2, R2, S3, R1)
10. (S1, E, R3, S2, R2, S3, R1)
11. (S1, S2, R3, E, R2, S3, R1)
12. (S1, S2, R3, S3, R2, E, R1)
13. (S1, S2, R3, S3, E, R2, R1)
14. (S1, S2, E, S3, R3, R2, R1)
15. (S1, S2, S3, E, R3, R2, R1)