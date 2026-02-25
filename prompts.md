## Primer Prompt

### IA utilizada: Grok

Necesito que generes el archivo index.html utilizando HTML con una estructura semántica correcta para un componente que debe ocupar el 100% del viewport (100vw y 100vh). Incluye la configuración base de un documento HTML y establece correctamente los parámetros del viewport para garantizar un diseño responsive y una correcta adaptación al tamaño del dispositivo. Además, debe "linkear" un archivo  llamado "styles.css". No quiero estilos inline ni etiquetas <style>, únicamente la estructura. Dentro de este contenedor deben existir 5 elementos repetidos que funcionarán como bloques visuales, cada uno con clases preparadas para aplicar posteriormente un layout con CSS Grid.

## Segundo Prompt

Ahora genera el archivo style.css aplicando los estilos base del componente. El contenedor principal debe ocupar el 100% del viewport utilizando unidades como 100vw y 100vh. Primero eliminan márgenes y paddings por defecto del navegador y define box-sizing: border-box para controlar correctamente el modelo de caja. El fondo del contenedor principal debe ser azul oscuro, mientras que los 5 bloques internos deben tener un color beige claro. Cada bloque debe tener dimensiones proporcionales utilizando unidades relativas como rem o porcentajes en lugar de valores fijos en px. Además, deben tener bordes completamente redondeados usando border-radius para lograr una forma tipo cápsula.No hagas todavía la alineación con Flexbox ni CSS Grid. En esta etapa solo define colores, dimensiones y espaciado. Mantén una buena organización del CSS utilizando clases con una especificidad controlada.

## Tercer prompt

Ahora ajusta el archivo style.css para implementar el layout exacto utilizando CSS Grid. El contenedor principal debe centrar todo el contenido tanto vertical como horizontalmente dentro del viewport usando propiedades como display, justify-content y align-items. La distribución debe organizar los 5 bloques de la siguiente manera: tres elementos en la fila superior y dos elementos en la fila inferior. Usa grid-template-columns y grid-template-rows. Define un gap consistente entre los elementos para controlar el espaciado sin usar  márgenes individuales. Asegúrate de que la alineación sea precisa y que los elementos mantengan proporciones coherentes dentro del contenedor.

## Cuarto Prompt

Realiza un ajuste visual en los estilos css. Las figuras internas deben tener una forma tipo cápsula vertical, es decir, deben ser alargadas en sentido vertical y con bordes completamente redondeados en la parte superior e inferior. Ajusta las dimensiones para que la altura sea mayor que el ancho y utiliza un border-radius suficientemente alto (por ejemplo 999px o 50%) para lograr el efecto de cápsula. Además, ajusta la paleta de colores: el fondo azul debe ser un poco más claro que el actual (manteniendo un tono azul oscuro pero menos saturado), y el color beige de las figuras no debería ser tan blanco, haz que tenga un tono crema y un poco mas amarillo. Mantén el uso de unidades relativas, evita modificar la estructura HTML y conserva la organización y especificidad del CSS. Este ajuste debe ser únicamente visual, respetando el layout ya implementado con Grid o Flexbox.

## Quinto Prompt

Ajusta el layout y las proporciones del componente para que ocupe exactamente el 100% del viewport sin generar scroll horizontal ni vertical. Actualmente los elementos están desproporcionados y desbordan el contenedor. El contenedor principal debe mantener width: 100vw y height: 100vh, y centrar el conjunto completo utilizando correctamente justify-content y align-items. Revisa que no existan márgenes externos en body que estén afectando el cálculo del espacio disponible. Los cinco bloques internos deben mantener una proporción equilibrada y consistente. No deben crecer excesivamente ni ocupar más espacio del necesario. Ajusta sus dimensiones usando unidades relativas (rem o %) y controla el comportamiento del layout para que no se estiren de forma indebida. Revisa grid-template-columns y asegúrate de que las columnas no sean fracciones demasiado grandes.
Mantén la distribución en dos filas (tres elementos arriba y dos abajo), centradas y con un gap uniforme entre ellas.

Finalmente, después de haber aplicado los prompts en la Inteligencia Artificial Grok, realicé algunos ajustes en el color y el posicionamiento de las figuras, pues con el código dado se obtenían colores más claros de lo que se pedía, además de muy poco espaciado entre las figuras.
