# Gestor-para-notas-escolares
Lo que se requiere desarrollar aca es un gestor de notas academicas el cual pueda ser utilizado por varios estudiantes con la finalidad de consultar sus notas y promedios.
El sistema se tiene planteado que funcione como una consola y permita regristrar, visualizar, modificar, entre otros, las calificaciones de los cursos que el estudiante ha cursado.

Algunos de los requisitos que deben ser funcionales son, guardar la información de un nuevo usuario como lo es su nombre, edad, correo, etc. Debe mostrar en pantalla la información
registrada de cada usuario. Actualizar los datos de un usuario existente. Borrar completamente la información del usuario del sistema si fuese necesario. Mostrar todos los regristros y 
datos basicos.

Los requisitos no funcionales quiere decir que es sistema se desarrollará en Python, funcionando solamente en consola, solo se llegara a utilizar funciones basicas del lenguaje, sin 
instalar modulos adicionales. El sistema empleará bucles como (While/Mientras) y condicionales como (If/Si) esto para facilitar el manejo de opciones. El formato del programa sera escrito
en pseudocodigo para poder implementarlo en Python.

INICIO

  OPCION = 0

  MIENTRAS OPCION != 5 HACER
    // Muestra las opciones
    IMPRIMIR "MENU PRINCIPAL"
    IMPRIMIR " 1. Nota 1"
    IMPRIMIR " 2. Nota 2"
    IMPRIMIR " 3. Nota 3"
    IMPRIMIR " 4. Nota 4"
    IMPRIMIR " 5. Salir"
    Nota=0
    // Pide la opción al usuario
    LEER OPCION

    // Revisa la opción elegida
    SI OPCION == 1 ENTONCES
      <accion_Nota_1>
    SINO SI OPCION == 2 ENTONCES
      <accion_Nota_2>
    SINO SI OPCION == 3 ENTONCES
      <accion_Nota_3>
    SINO SI OPCION == 4 ENTONCES
      <accion_Nota_4>
    SINO SI OPCION == 5 ENTONCES
    <accion_Nota= Nota+1>
      IMPRIMIR "TOTAL NOTA:", Nota
    SINO
      IMPRIMIR "Opción no válida."
    FIN SI
  FIN MIENTRAS

FIN
