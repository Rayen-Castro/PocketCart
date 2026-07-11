# PocketCart

---

### ¿que és?

Vas al super, tienes un presupuesto o un límite para comprar, asi que con la calculadora de tu teléfono vás agregando los precios de las cosas que quieres comprar, pero tambien debes intercambiar entre usar la calculadora y las notas para ver que te falta de la lista de compra, pero entre eso, se te olvida si ya agregaste el precio del pollo que sostienes al calculo de la calculadora, o encontraste un producto alternativo en oferta y tendrías que borrar todo tu cálculo de la calculadora para compararlo con el producto original.
Es un problema tan general y tan cotidiano que parece insignificante, pero si eres perfeccionista, necesitas algo más práctico, eso plantea PocketCart.

---

### arquitectura de la idea

El objetivo primario de la página es de poder crear una lista de productos con precios que se puedan comprar con el presupuesto que se tiene, al total de la compra;

OBJETIVOS MVP:

- Interfaz Móvil: la pagina se centrará en ser adaptada a pantallas de teléfonos actuales.
- Input de presupuesto: el campo basico para agregar el presupuesto del user.
- Lista dinámica: botón para añadir un producto con nombre y precio como campos.
- contador en tiempo real: conforme se agregan productos, el precio total de la lista se refleja abajo, y se resta al presupuesto dado por el user para dar la cantidad que queda

AÑADIR A FUTURO:

- Listas guardadas: después de crear la lista en la pantalla, esta se puede guardar en local storage con nombre propio como "compras del mes" o "asado del finde".
- Categorías (duda?): Separar los productos por "Fruver", "Aseo", "Carnes".
- Modo Historial: Ver cuánto gastaste el mes pasado versus este mes.

---

### stack para el mvp

Al ser una página poco exigente, solo se ocupará React como framework y localstorage para base de datos.
En futuro, si se escala lo suficiente, se espera llegar a usar el stack MERN.
