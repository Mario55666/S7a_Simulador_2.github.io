# Simulador de los Tres Cerebros – Clínica Palmas

## Descripción del proyecto

Este proyecto es una herramienta educativa interactiva desarrollada para la asignatura **Semiótica de la Imagen** de la Universidad Tecnológica del Perú. Su objetivo es demostrar cómo la **teoría de los tres cerebros** de Paul MacLean –reptiliano, límbico y neocórtex– se aplica en el diseño de una pieza gráfica real: un flyer promocional de la **Clínica Palmas**.

El usuario puede explorar los elementos visuales del flyer, comprender qué mensajes subconscientes activa cada capa cerebral y poner a prueba sus conocimientos mediante un cuestionario. La interfaz combina una estética médica profesional (colores suaves, iconografía de salud) con una lógica de capas superpuestas que permite visualizar cómo cada cerebro procesa distintos estímulos.

## Contexto académico

- **Curso:** Semiótica de la Imagen · 2026 · Semana 7  
- **Docente:** Mg. Mario Quiroz  
- **Institución:** Universidad Tecnológica del Perú  
- **Tema:** Aplicación de la teoría de los tres cerebros (Paul MacLean) al diseño gráfico publicitario.

## Funcionalidades principales

- **Flyer interactivo con capas:** el diseño se compone de tres imágenes PNG superpuestas:
  - `LIMBICO.png`: fondo con ambiente cálido y slogan emocional (“Cuidado que nace del corazón, confianza que te hace bien”). Representa la capa límbica.
  - `REPTILIANO.png`: símbolos de alerta y supervivencia (cruz médica, gráfico de pulso, color rojo). Representa la capa reptiliana.
  - `NEOCORTEX.png`: información racional (dirección completa, teléfono, correo electrónico). Representa la capa neocórtex.

- **Botones de selección de cerebro:** al hacer clic en *Reptiliano*, *Límbico* o *Neocórtex*, la capa correspondiente se vuelve nítida mientras las otras se desenfocan u ocultan. El panel derecho muestra información detallada sobre ese cerebro:
  - Elemento gráfico asociado.
  - Mensaje subconsciente (p. ej., *“Atención inmediata, seguridad ante la enfermedad”*).
  - Psicología subyacente.
  - Pregunta que responde (p. ej., *«¿Es seguro?»*).
  - Aplicación práctica en diseño de clínicas.

- **Panel informativo dinámico:** se actualiza al instante según la capa seleccionada, con colores distintivos para cada cerebro (rojo para reptiliano, amarillo para límbico, azul para neocórtex).

- **Botones de control inferior:**
  - **🔆 VISTA COMPLETA NÍTIDA:** muestra todas las capas sin desenfoque, permitiendo apreciar el diseño global del flyer.
  - **🔄 RESTABLECER DESENFOQUE:** vuelve al estado de enfoque del último cerebro activo.

- **Cuestionario interactivo:** cuatro preguntas de opción múltiple que evalúan la comprensión de la teoría aplicada al flyer. Al finalizar, se muestra el número de aciertos y un mensaje de retroalimentación.

- **Botón de contacto al docente:** un enlace de correo (`c12139@utp.edu.pe`) que abre el cliente de correo predeterminado para facilitar consultas académicas.

## Tecnologías utilizadas

- HTML5, CSS3 y JavaScript (ES6) puros, sin librerías externas.
- Diseño responsivo, adaptable a distintos tamaños de pantalla.
- Uso de imágenes PNG con transparencia para la superposición de capas.
- Estética de clínica con paleta de colores médicos (rojo, azul claro, blanco) y tipografía clara.

## Instrucciones de uso

1. **Abrir el archivo:** descargue o clone el repositorio y abra `index.html` en cualquier navegador moderno (Chrome, Firefox, Edge, etc.).
2. **Explorar las capas:**
   - Haga clic en los botones superiores (*Reptiliano*, *Límbico*, *Neocórtex*) o directamente sobre las imágenes del flyer.
   - Observe cómo se desenfocan las capas no seleccionadas y cómo cambia la información en el panel derecho.
3. **Activar vista completa nítida:** pulse el botón **🔆 VISTA COMPLETA NÍTIDA** para ver todas las capas nítidas a la vez. A partir de ahí, puede volver a seleccionar cualquier cerebro para recuperar el efecto de enfoque selectivo.
4. **Restablecer desenfoque:** use el botón **🔄 RESTABLECER DESENFOQUE** para volver al estado de enfoque del último cerebro activo.
5. **Responder el cuestionario:** marque una opción por cada pregunta y presione **Comprobar respuestas**. Recibirá un resultado inmediato.
6. **Contactar al docente:** si tiene dudas, use el botón **Enviar mensaje al docente** para escribir un correo electrónico.

## Notas importantes

- Las imágenes (`REPTILIANO.png`, `LIMBICO.png`, `NEOCORTEX.png`) deben ubicarse en la misma carpeta que el archivo `index.html`. Si faltan, se mostrará un patrón de fondo de respaldo.
- Se recomienda utilizar imágenes PNG con transparencia para garantizar la correcta superposición de las capas.
- La capa `NEOCORTEX.png` tiene el z-index más alto para que su texto (dirección, teléfono, email) sea siempre legible, incluso cuando está debajo de otras capas en la vista completa.

## Créditos

- **Docente:** Mg. Mario Quiroz  
- **Curso:** Semiótica de la Imagen · 2026 · Semana 7  
- **Universidad Tecnológica del Perú**  
- Basado en la teoría de los tres cerebros de **Paul MacLean**.

## Licencia

Este proyecto es de uso educativo y libre distribución para fines académicos. Queda prohibido su uso con fines comerciales sin autorización expresa de los autores.