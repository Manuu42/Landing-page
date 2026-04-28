# Documentación del Proyecto: HYDRA

## 1. Descripción General
**HYDRA** es una landing page premium diseñada para la venta de una botella de agua inteligente. El proyecto incluye un flujo completo desde la presentación del producto hasta la simulación de una compra (checkout).

---

## 2. Estructura de Archivos
- **index.html**: Página principal (Landing Page). Contiene las secciones de Inicio, Beneficios, App y Llamado a la Acción (CTA).
- **checkout.html**: Página de finalización de compra. Implementa un formulario de 3 pasos y un resumen dinámico del pedido.
- **style.css**: Hoja de estilos compartida. Contiene el sistema de diseño, variables de color y media queries para adaptabilidad móvil.
- **IMG/**: Directorio que contiene los recursos visuales (como `bottle.png`).

---

## 3. Sistema de Diseño
El diseño sigue una estética moderna, limpia y tecnológica ("premium high-tech").

- **Paleta de Colores:**
  - `Primary`: #00a859 (Verde Esmeralda - Acción y Marca)
  - `Secondary`: #111827 (Navy Profundo - Textos y Fondos)
  - `Background`: #f9fafb / #ffffff
- **Tipografía:**
  - Se utiliza la fuente **Outfit** de Google Fonts por su legibilidad y estilo geométrico moderno.
- **Componentes Clave:**
  - **Botones**: Usan sombras profundas y transiciones suaves.
  - **Tarjetas**: Bordes redondeados (`12px`) con efectos de elevación al pasar el mouse.
  - **Animaciones**: Animación de flotación en la imagen hero y scroll suave entre secciones.

---

## 4. Funcionalidades del Checkout
La página de checkout (`checkout.html`) está diseñada para maximizar la conversión imitando plataformas profesionales:
1. **Paso 1 (Tus datos)**: Recolección de información personal.
2. **Paso 2 (Envío)**: Opción de entrega a domicilio (Gratis configurado por defecto).
3. **Paso 3 (Pago)**: Interfaz de pago seguro con iconos de tarjetas.
4. **Resumen Lateral**: Se mantiene visible (sticky) para que el usuario siempre vea lo que está comprando.

---

## 5. Instrucciones de Mantenimiento

### Cambiar el Color de Marca
Para cambiar el color verde principal por otro (ej. azul), solo debes modificar la variable en la línea 2 de `style.css`:
```css
:root {
    --primary: #00a859; /* Cambiar este código hexadecimal */
}
```

### Actualizar Imagen del Producto
Para cambiar la botella, reemplaza el archivo `IMG/bottle.png` por uno nuevo con el mismo nombre, o actualiza la ruta en `index.html` y `checkout.html`. Se recomienda usar imágenes en formato `.png` con fondo transparente.

### Adaptabilidad (Responsive)
El sitio usa un sistema de Grid y Flexbox que se ajusta automáticamente. Los puntos de quiebre están definidos para dispositivos móviles (máx `968px`).

---

## 6. Tecnologías Utilizadas
- **HTML5**: Estructura semántica.
- **CSS3**: Variables, Flexbox, Grid y Animaciones.
- **Google Fonts**: Integración de tipografía premium.
- **IA Generativa**: Imágenes de producto diseñadas a medida.

---
*Ultima actualización: 24 de Abril, 2026*
