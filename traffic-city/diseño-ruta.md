# Diseñar Ruta

Caminos:
    A --- B --- C
    |     |     |
    D --- E --- F


Camino evitando las zonas bloqueadas:
    - A →  D →  E →  F

    Así pasa por todas las zonas menos la bloqueada. 

Me siento con suerte:

    A --- B --- C
    |     |     |
    D ----+---- F
    |     |     |
    | --- H --- I
    |     |     |
    J --- K --- L

    Todos los caminos:
    - A → B → H → K 
    - A → D → J → K
    - A → B → H → I → J → K 
    - A → B → C → F → I → L → K
    - A → B → C → F → I → H → K
    - A → B → C → F → D → J → K


    Camino más corto:
    - A → B → H → K 
    - A → D → J → K