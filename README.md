#  Guía de Configuración de Página Web en Odoo :rocket:
Configuración de una tienda en línea básica utilizando Odoo. 

> [!IMPORTANT]
> Esta guía describe los pasos para configurar una página web en Odoo utilizando el botón de edición, y cómo aplicar diversas funcionalidades específicas como la creación de texto con IA, bloques de creación, inserción de un logo y personalización de enlaces.

## Objetivos
1. Configurar el sitio web de forma personalizada.
2. Configurar el comercio electrónico a las necesidades del negocio.
3. Efectuar los primeros enlaces entre la aplicación de CRM con la pagina web.

> [!NOTE]
> Tu sitio web es gratuito por siempre con el plan de una aplicación gratis. Incluye alojamiento, soporte ilimitado y mantenimiento, no tiene anuncios y lo mejor de todo es que tu nombre de dominio tampoco tiene costo.

## 1. Creación de Texto con IA

### Paso 1: Habilitar la Función de Creación de Texto con IA
- [X] Crea textos increíbles con ChatGPT. Con una simple instrucción puedes pedirle a Odoo que genere, mejore o cambie el tono del contenido de tu sitio web.
- [X] Odoo permite la integración de módulos de Inteligencia Artificial (IA) para generar contenido textual automáticamente en la página web.
- [ ] Sigue los siguientes pasos:

1. Dirígete a la página web que deseas editar.
2. Haz clic en el botón **Editar** en la parte superior derecha de la página.
> [!WARNING]
> ![image](https://github.com/user-attachments/assets/5fa1dc08-e9a5-4d16-b105-594b2eb513e9)
4. Selecciona el bloque de texto en el que desees utilizar la IA.
5. En el menú del bloque, selecciona la opción **Generar Texto con IA**.
6. Especifica las directrices para el contenido y elige el estilo de escritura que prefieras.

<img src="https://github.com/user-attachments/assets/4cfc139c-d2bb-4074-b1bc-7b42ed5d41e2" width="800" height="400">

> [!NOTE]
> La función de creación de texto con IA puede necesitar la instalación de un módulo adicional.

## 2. Bloques de Creación

### Paso 2: Arrastra y Suelta Bloques de Creación
Odoo te permite crear páginas web dinámicas mediante bloques de creación. Puedes arrastrar y soltar diferentes bloques, como textos, imágenes, tablas, y más:

1. En el modo de edición, selecciona la opción **Bloques de Creación** desde el panel de la derecha.
2. Elige el bloque que desees, como **Título**, **Texto** o **Imágenes**.
3. Arrastra el bloque al área deseada de la página.
4. Personaliza el contenido dentro del bloque según tus necesidades. :airplane:

<img src="https://github.com/user-attachments/assets/dc65ee54-c0c8-4b0f-9619-5297e8856e73" width="600" height="300">
   
Si deseas agregar filtros o efectos en las imágenes, simplemente selecciona el bloque de imagen y ajusta las opciones desde el panel.

> [!TIP]
> Puedes animar elementos seleccionando la opción de animación en el menú de edición del bloque.


## 3. Crear una Oportunidad a través del Registro en "Contáctanos"

El formulario de **Contáctanos** puede utilizarse para capturar oportunidades (leads) y gestionarlas dentro del módulo de CRM. Sigue estos pasos para configurarlo:

1. Navega a la página **Contáctanos** en tu sitio web.
2. Haz clic en **Editar** y selecciona el formulario de contacto.
3. Configura los campos requeridos, como nombre, correo electrónico, mensaje, etc.
4. En las propiedades del formulario, selecciona **Acción** y elige **Crear Oportunidad**.

<img src="https://github.com/user-attachments/assets/1aff2b06-563b-4a48-a047-d4b2ee678de4" width="800" height="400">
   
6. Guarda los cambios. Ahora, cualquier formulario completado se registrará como un lead en el CRM.

> [!WARNING]
> Este formulario es fundamental para registrar leads en la base de datos, permitiendo realizar un seguimiento adecuado desde el módulo CRM.


## 4. Insertar el Logo de la Empresa

### Paso 4: Personalizar el Logo
Para insertar el logo de tu empresa en la página web, sigue estos pasos:

1. Entra en el modo de edición de la página.
2. Selecciona el bloque de encabezado o el área donde deseas insertar el logo.
3. Haz clic en el bloque de imagen y selecciona **Subir Imagen**.
4. Elige el archivo del logo de tu empresa desde tu dispositivo.
5. Ajusta el tamaño y la posición del logo según sea necesario.

> [!CAUTION]
> El logo debe estar en formato PNG o SVG para obtener mejores resultados visuales.

## 5. Personalizar los Enlaces de los Botones

### Paso 5: Cambiar los Enlaces de los Botones en la Página
Para cambiar los enlaces de los botones en tu página web en Odoo, sigue estos pasos:

1. Haz clic en el botón que deseas editar mientras estás en modo de edición.
2. Aparecerá un menú de configuración. Selecciona la opción **Enlace**.
3. Puedes configurar el botón para que dirija a una página específica escribiendo el nombre de la página o buscando una página existente a traves de "/".

<img src="https://github.com/user-attachments/assets/dbe9998a-bbdb-462b-94ff-5b8e828e3dcc" width="800" height="400">
   
4. Para vincular a una sección dentro de la misma página, escribe `#` seguido del nombre del ancla que has configurado previamente.
5. Guarda los cambios para que se reflejen en la página web.


## 6. Configuración del Blog en la Página Web de Odoo

Este módulo te llevará a través del proceso de configuración de un blog en la página web de Odoo, permitiéndote crear y gestionar publicaciones de blog directamente desde tu sitio web.

### Paso 1: Activar el Módulo de Blog

Para comenzar, necesitas asegurarte de que el módulo de **Blog** esté activado en tu instancia de Odoo. Sigue estos pasos:

1. Navega al **Panel de Aplicaciones** en Odoo.
2. Busca el módulo **Blog** en la lista de aplicaciones disponibles.
3. Si aún no está instalado, haz clic en el botón **Instalar** para habilitar el módulo de Blog.

### Paso 2: Crear un Nuevo Blog

Una vez que el módulo de Blog esté activado, puedes proceder a crear un nuevo blog:

1. Desde el **Panel de Blogs**, selecciona **Crear**.

<img src="https://github.com/user-attachments/assets/a8836134-5d58-464a-a1b4-0a8ba7f76ce3" width="400" height="300">
<img src="https://github.com/user-attachments/assets/443b54ce-1cb1-4c0b-8032-e09c1fb203db" width="600" height="300">



2. Introduce el nombre de tu blog en el campo correspondiente (por ejemplo: "Noticias de la Empresa").
3. Guarda el blog para comenzar a añadir publicaciones.

### Paso 3: Añadir una Nueva Publicación de Blog

Para crear contenido en tu blog, sigue estos pasos:

1. Abre el blog que acabas de crear o uno existente.
2. Haz clic en el botón **Nueva Publicación**.
3. Rellena los campos siguientes:
   - **Título:** El nombre de la publicación.
   - **Cuerpo del artículo:** El contenido principal del artículo de blog. Puedes formatear el texto, agregar imágenes, videos, y otros elementos multimedia utilizando las herramientas de edición disponibles.

<img src="https://github.com/user-attachments/assets/5f76fa99-3bec-4cb4-89b6-f1e8fd33c3f6" width="600" height="300">
     
   - **Etiquetas:** Añade etiquetas relevantes para clasificar la publicación y facilitar la búsqueda.

4. Opcionalmente, puedes programar la publicación para una fecha futura o publicarla inmediatamente haciendo clic en **Publicar**.

### Paso 4: Configuración de la Página del Blog

Puedes personalizar el diseño y la configuración de la página principal de tu blog de la siguiente manera:

1. Entra en el **Modo de Edición** de la página web.
2. Navega a la sección de blogs y haz clic en el botón **Editar**.
3. Utiliza los **Bloques de Creación** para agregar o reorganizar elementos en la página del blog, como títulos, imágenes destacadas, o secciones de comentarios.
4. Personaliza el diseño de la página usando las herramientas de diseño de Odoo, como el cambio de fuentes, colores y estilos de los bloques.

### Paso 5: Promoción del Blog

Promociona tu blog directamente desde Odoo para llegar a más audiencias:

1. En la página de edición del blog, busca la opción **Promocionar** en la barra superior.
2. Selecciona los canales de promoción deseados, como correo electrónico, redes sociales, o notificaciones push.
3. También puedes habilitar el **SEO** para optimizar la visibilidad del blog en los motores de búsqueda. Asegúrate de rellenar los campos de título, descripción, y palabras clave relevantes para el SEO.

### Paso 6: Gestión de Comentarios

El módulo de Blog en Odoo permite la interacción con los lectores mediante comentarios en las publicaciones. Para gestionar los comentarios:

1. Dirígete a la página de configuración del blog.
2. Activa la opción de **Comentarios** si aún no está habilitada.
3. Los comentarios pueden moderarse desde el panel de administración de blog, donde puedes aprobar, eliminar o responder a los comentarios de los lectores.

> [!WARNING]
> Activa la moderación de comentarios para garantizar que los comentarios inapropiados no se publiquen automáticamente.

### Paso 7: Mantenimiento del Blog (a manera informativa)

> [!NOTE]
> Es importante mantener el blog actualizado y organizado. A continuación, algunas buenas prácticas:

- **Frecuencia de Publicación:** Define un calendario de publicaciones y mantenlo constante.
- **Actualización de Contenido Antiguo:** Revisa publicaciones antiguas periódicamente para actualizarlas con información nueva.
- **Monitoreo de Rendimiento:** Utiliza las herramientas de análisis de Odoo para ver las estadísticas de visitas, tiempo en página y rendimiento de las publicaciones del blog.

> [!IMPORTANT]
> Con esta guía, ahora puedes crear, personalizar y gestionar un blog en tu página web de Odoo. El blog es una excelente herramienta para interactuar con tus clientes y aumentar la visibilidad de tu empresa.


## Otros Requerimientos de Personalización

Puedes realizar más personalizaciones en la página web y el módulo de comercio electrónico:

- **Agregar elementos multimedia:** Puedes insertar videos, galerías de imágenes, y audios desde el menú de edición.
- **Personalización del comercio electrónico:** Dentro del módulo de comercio electrónico, puedes configurar los productos, las categorías, y las opciones de pago de forma directa desde el panel de administración.
- **Filtros avanzados:** Usa filtros personalizados para mostrar ciertos productos o servicios basados en categorías o tags específicos.

---

> [!NOTE]
> Con esta guía, puedes aprovechar al máximo las herramientas de edición web de Odoo para personalizar tu sitio según tus necesidades empresariales.



