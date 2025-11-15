Introducción
El proyecto es una tienda en línea llamada CLOTHESSTORE, especializada en la venta de ropa y accesorios. La página web está construida con tecnologías web modernas y consume una API pública para mostrar los productos. Incluye un carrito de compras, una pasarela de pago simulada y la generación de un ticket en PDF con formato de recibo térmico.

Objetivos principales
Crear una interfaz de usuario atractiva y responsiva que muestre los productos en tarjetas.

Implementar un carrito de compras que permite agregar, modificar y eliminar productos.

Simular una pasarela de pago con validación de formulario.

Generar un ticket de compra en PDF con diseño similar a un recibo térmico.

Importancia del proyecto
Este proyecto demuestra cómo integrar varias tecnologías web para crear una aplicación de comercio electrónico funcional. Sirve como base para emprendedores que desean iniciar un negocio en línea, y como material educativo para desarrolladores que buscan aprender sobre el desarrollo web full-stack.


2. Configuración del archivo HTML
En el index.html, configuramos la estructura básica de HTML5 e incluimos las dependencias externas: Bootstrap 5, Font Awesome, Google Fonts, jQuery, y jsPDF. También enlazamos nuestros propios archivos CSS y JS.

4. Diseño de la interfaz de usuario
Utilizamos Bootstrap 5 para crear una interfaz responsiva. Diseñamos un navbar, una sección hero, una sección de productos y varios modales (para detalles del producto, carrito y pago). Aplicamos la paleta de colores definida mediante variables CSS.

6. Consumo de la API
Mediante la Fetch API, consumimos la API de FakeStore para obtener los productos. Los productos se muestran en tarjetas dentro de la sección de productos. Cada tarjeta tiene una imagen, título, descripción truncada y precio.

8. Funcionalidad del carrito
Implementamos las funciones para agregar productos al carrito, actualizar cantidades, eliminar productos y calcular el total. El carrito se almacena en el localStorage para persistir los datos entre sesiones.

10. Pasarela de pago
Creamos un formulario de pago con validación básica. Al confirmar el pago, se generará un PDF con los detalles de la compra.

12. Generación del PDF
Utilizamos la biblioteca jsPDF para generar un ticket en PDF con formato de recibo térmico (80 mm de ancho). El PDF incluye el nombre de la tienda, fecha, nombre del cliente, lista de productos, cantidades, precios y total.

14. Pruebas y ajustes
Probamos la aplicación en diferentes dispositivos y navegadores para asegurar la responsividad y funcionalidad. Ajustamos estilos y corregimos errores.
