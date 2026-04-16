# ListasEnlazadas-Js
Diferencias de Sintaxis entre Java y Node.js (JavaScript)
1. Tipado de datos
Java:
int numero = 10;
String texto = "Hola";
JavaScript:
let numero = 10;
let texto = "Hola";

Diferencia: Java es fuertemente tipado, mientras que JavaScript es dinámico.
2. Definición de clases
Java:
public class Lista {}
JavaScript:
class Lista {}

Diferencia: Java usa modificadores como public o private; JavaScript no de la misma forma.
3. Métodos
Java:
public int size() { return size; }
JavaScript:
size() { return this._size; }

Diferencia: Java define tipo de retorno, JavaScript no.
4. Acceso a atributos
Java:
current.getNext();
current.getValue();
JavaScript:
current.next;
current.value;

Diferencia: Java usa getters, JavaScript accede directamente.
5. Uso de this
Java:
head = newNode;
JavaScript:
this.head = newNode;

Diferencia: En JavaScript es obligatorio usar this dentro de clases.
6. Comparación de valores
Java:
value.equals(other);
JavaScript:
value === other;

Diferencia: Java usa .equals(), JavaScript usa ===.
7. Manejo de null
Java:
while (current != null)
JavaScript:
while (current !== null)

Diferencia: JavaScript usa comparación estricta.
8. Tamaño de la lista
Java:
size++;
JavaScript:
this._size++;

Diferencia: JavaScript usa propiedades internas con this.
9. Estructura de nodos
Java:
node.setNext(next);
JavaScript:
node.next = next;

Diferencia: Java usa métodos, JavaScript modifica directamente.
10. Exportación de clases
Java: No aplica
JavaScript:
module.exports = DoublyLinkedList;
Diferencia: JavaScript usa módulos para exportar clases.



