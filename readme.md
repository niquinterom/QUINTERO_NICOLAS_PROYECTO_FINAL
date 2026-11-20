Justificación de unidades de medida 

Para garantizar un diseño accesible, escalable y adaptable a distintos dispositivos, se seleccionaron las siguientes unidades relativas en el CSS:

1. **`%` en la raíz (`html { font-size: 100%; }`) y anchos fluidos (`width: 100%`):** Permite respetar la configuración de tamaño de fuente que el usuario tenga definida en su navegador y asegura que las imágenes y tablas ocupen todo el ancho disponible de su contenedor sin desbordarse.
2. **`rem` en tipografías (`font-size: 2.2rem`, `1.7rem`, `1rem`):** Mantiene una jerarquía visual proporcional en toda la web. Si el usuario aumenta el zoom o el tamaño base de letra del navegador, todos los títulos y textos escalan de forma armónica.
3. **`rem` en espaciados y contenedores (`padding: 1.5rem`, `gap: 1.5rem`, `max-width: 68.75rem`):** Garantiza que los márgenes, rellenos y anchos máximos crezcan en proporción al tamaño de la letra, evitando que los textos queden apretados dentro de las tarjetas al hacer zoom.
4. **`ch` en párrafos (`max-width: 65ch`):** Limita el ancho de las líneas de texto a aproximadamente 65 caracteres, lo que mejora la legibilidad y evita la fatiga visual al leer párrafos largos en pantallas grandes.
5. **`vh` en la cabecera (`.cabecera { min-height: 35vh; }`):** Ajusta la altura mínima del encabezado al 35% de la altura visible de la pantalla (viewport), logrando una portada equilibrada tanto en monitores de escritorio como en pantallas de portátiles o móviles.