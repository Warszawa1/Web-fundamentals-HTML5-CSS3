# Web Fundamentals: HTML5, CSS3
### _Creación de un portfolio_

![](https://cdn-icons-png.flaticon.com/128/774/774469.png)



### Consideraciones generales:

- No se permite el uso de librerías y frameworks externos como Bootstrap, Spectre.css o similares.
- Se deberá crear una o más hojas de estilo CSS para aplicar el diseño deseado a la web.
- La página web debe visualizarse correctamente en las versiones actuales de Google Chrome, Mozilla Firefox y Microsoft       Edge.
- No se requiere el uso de interacción mediante JavaScript.



### Descripción de la práctica

Nuestro objetivo es contruir un portfolio sobre nosotros, con las siguientes secciones:
- README con toda la información necesaria para facilitar la forma de evaluar la práctica
- Barra de navegación con links a cada elemento del portfolio. Todos los links tendrán que tener el estado hover suavizado  con una transición. Estos links no son necesarios en la versión mobile como viene en los anexos.
- Header deberá tener 1 imagen de fondo, optimizada para distintas resoluciones (opcional).
- Una sección con nuestras skills de programación y progreso de las mismas. Esta sección tiene que contar con barras de       progreso animadas con animaciones css.
 
- Formulario de contacto con estos inputs. Todos ellos tienen que tener tanto los tipos correctos como la validación html
  de cada input.

    - Nombre - (requerido)
    - Apellidos - (requerido)
    - Teléfono - (requerido)
    - Unos radio button para responder a la pregunta "¿Cómo me conociste?" - (requerido):
         - [ ] Universidad
         - [ ] Colegio
         - [ ] Github 
        
    - Tag de github (Usar regexp para la validación - @username)
    - Descripción (max 180 chars) - (requerido)
    - Boton de guardado
    - Footer con links a nuestras redes sociales. Importante tener en cuenta que son links a un recurso externo y no queremos dejar información nuestra en esas webs

    ### Detalles de implementación

- La estructura de la web tendrá en cuenta las etiquetas de contenido semántico.
- Debéis incluir las media queries necesarias para que el diseño sea responsive. Tiene que ser **MOBILE FIRST**, sino no será
  apto.
- Las animaciones o interactividad propuesta deben realizarse exclusivamente mediante técnicas CSS sin el uso de librerías 
    externas.
- Tiene que entregarse a través de Github. No se valorará, pero un buen uso de commits será algo positivo.