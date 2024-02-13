# Cotizador automático de seguros 

## License

[Mozilla Public License 2.0](https://choosealicense.com/licenses/mpl-2.0/)

## Author

- **Nombre:** Esvin Danilo Ambrocio Chan
- **Carnet:** 24003541

## Insisos del proyecto

### Requerimientos

Crear un cotizador para la empresa "TK-U", el cual deberá recabar la siguiente información:

  1. Nombre del asegurado.
  2. Edad del asegurado.
  3. Consultar si el asegurado tiene cónyuge.
  4. En caso afirmativo, obtener la edad del cónyuge.
  5. Consultar si el asegurado tiene hijos y, de ser así, la cantidad de hijos.

Es importante tener en cuenta que la persona asegurada debe ser mayor de edad.

Además, el cotizador debe incluir los siguientes recargos la precio base:

  - Aplicar un recargo por edad.
    - 18 a 24 años del 10% del precio base.
    - 25 a 49 años del 20% del precio base.
    - 50 años o más del 30% del precio base
  - Aplicar un recargo por la edad del cónyuge.
    - 18 a 24 años del 10% del precio base.
    - 25 a 49 años del 20% del precio base.
    - 50 años o más del 30% del precio base
  - Aplicar un recargo por cada hijo.

### Algoritmo

  1. Solicitar el nombre del asegurado.
  2. Solicitar la edad del asegurado.
  3. Verificar si el asegurado es mayor de edad.
  4. Si el asegurado no es mayor de edad, mostrar un mensaje indicando que no es elegible para el seguro y finalizar.
  5. Calcular recargo por edad
  6. Solicitar si el asegurado tiene cónyuge.
  7. Si el asegurado tiene cónyuge:
     1. Solicitar la edad del cónyuge.
     2. Calcular recargo por edad del conyuge
  8. Solicitar la cantidad de hijos del asegurado.
  9. Calcular los recargos basado y en la cantidad de hijos.
  10. Calcular el precio total del seguro sumando el precio base y los recargos correspondientes.
  11. Mostrar la cotización con el precio total del seguro.