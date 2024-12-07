# PC_5
Link: https://github.com/Controles-ICDERebatta/PC_5/raw/refs/heads/main/PC%20_%205FINAL.html

En el primer ejercicio, se usó la función "clip" para formar los 2 mapas solicitados.

En el segundo ejercicio, se crearon sub-sets de polígonos utilizando "unary_union" en lugar de "union_all" ya que este último no se encuentra disponible en geopandas. También se usaron métodos como disolución y se hizo "plot" con el resultado obtenido.

En el tercer ejercicio, se seleccionó Junín como un punto para aplicar "convex hull" y convertirlo en un geodataframe. Con el fin de conseguir un resultado similar al del ejemplo en colab, se utilizó los "medium airports" en lugar de los "large airports" para hacer "plot" con el hull previamente realizado. De esta forma se obtuvo un mapa del país elegido con los aeropuertos medianos representados con puntos azules mientras forman un polígono.

En el cuarto ejercicio, se realizó "spatial overlay" sobre los mapas conseguidos anteriormente. Para ello se necesitaron las zonas norte, sur, este y oeste del país así como sus intersecciones. De esta forma se puede visualizar el país con divisiones según las intersecciones.

