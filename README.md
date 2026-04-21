# poo_reto_2
Elija un problema de la vida real (sistema de gestión de biblioteca, negocio de compra-venta, automóvil, etc) que se pueda modelar a través de objetos y clases. Plantee las relaciones de clases, composiciones, propiedades y comportamientos del sistema en uno mas diagramas tipo UML.

![alt text](<Diagrama tienda-1.webp>)


El sistema modela una tienda que gestiona un inventario de frutas organizadas mediante herencia en diferentes categorías. Las ventas conectan los productos con los clientes, permitiendo registrar compras y calcular totales. La clase Fruta actúa como base común, mientras que sus subclases especializan el comportamiento y características. La composición asegura que las frutas pertenecen a la tienda, y las asociaciones permiten la interacción entre clientes y ventas.

 # Tipos de relaciónes utilizadas

 # Composición(♦):
 Esta es una relación donde un objeto contiene a otros. En el diagrama se ve en el caso Tienda ♦── Fruta, ya que la Tienda tiene Fruta como parte de su inventario y si la tienda deja de existir, las frutas también.

 # Asociación(—): 
 Es una relación general entre clases donde interactuan pero son independientes.
Tienda ── Venta
Venta ── Cliente

 # Herencia(△):
 Es una relación donde una clase hija hereda atributos y métodos
de una clase padre.
Fruta ⟶ Bayas, Drupas, Cítricos, etc.
Luego: Bayas ⟶ Fresa, Mora, etc.
