## Prueba Tecnica

En esta prueba tecnica evaluamos **capacidad de aprendizaje, estilo de codigo, buenas practicas de desarrollo** y creatividad.

La prueba consiste en crear una aplicacion con el framework [Meteor](https://www.meteor.com) la cual debe tener la siguiente funcionalidad.
Altamente recomendado guiarse por el [siguiente tutorial de Meteor y React](https://react-tutorial.meteor.com/), la clave es traducir la funcionalidad explicada en el tutorial y adaptarlo a los requerimientos a continuacion: 

1.  Pantalla con formulario de creacion de medicos, los datos a validar son nombres, apellido paterno, apellido materno RUT (validar con libreria [RUT.js](https://github.com/jlobos/rut.js/)) y especialidad medica. En el campo especialidad medica se debe hacer un componente estilo select con los datos de este [link](https://gist.github.com/rodcisal/ef7839215d8d17ff9cf07b19e5e7593d), como **label** se debe usar el key **nombre** de cada objeto del array de especialidades medicas. El componente debe ser creado usando React y es recomendado usar libreria para manejo de formularios [react-hook-form](https://github.com/react-hook-form/react-hook-form). Guardar datos recogidos anteriormente en una coleccion MongoDB usando funcionalidad de Meteor.
2. Pantalla de despligue de todos los medicos en base de datos, se debe mostrar una tabla de medicos desplegando la informacion recogida en el punto 1.  Una fila por medico
3. Crear UI usando algun framework de componentes de UI. Recomendado [Tailwind](https://tailwindcss.com/) pero es de libre eleccion, sugerencia usar el que domines mejor.

El punto 1 y 2 deben estar en una misma pantalla. Sugerencia: formulario de creacion de medicos en la parte superior de la pantalla y la tabla en la parte inferior. Al crear un nuevo medico se debe limpiar el formulario y mostrar en tiempo real el nuevo medico agregado a la coleccion.

Al terminar crear un repositorio publico en github y enviar link por email a rodrigocisternas@docmovi.com para posterior revision.

Buena suerte!
Gracias!

