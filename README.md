# Semana-7
# Gestión de Mascotas en una Clínica Veterinaria – Proyecto de Constructores y Destructores en Python

## Descripción General

Este programa es una aplicación de consola desarrollada en Python que simula un sistema básico para la gestión de mascotas en una clínica veterinaria. Permite registrar mascotas (perros y gatos), almacenar su información, agregar vacunas, reproducir sonidos característicos y describirlas. 

El proyecto fue creado para cumplir con la tarea académica de implementar y demostrar el uso de **constructores (`__init__`)** y **destructores (`__del__`)** en programación orientada a objetos (POO).

---

## Objetivo de la Tarea

- Aplicar los conceptos de constructores y destructores para desarrollar un programa en Python.
- Usar el IDE PyCharm para la implementación.
- Publicar el código en un repositorio personal de GitHub accesible públicamente.
- Demostrar claramente cómo funcionan los constructores y destructores mediante el código y los comentarios.
- Asegurar buenas prácticas de programación y una estructura clara del código.

---

## Funcionamiento del Programa

- El programa inicia solicitando al usuario que registre una mascota, especificando su especie (perro o gato), nombre y edad.
- Usa un **constructor (`__init__`)** para inicializar cada objeto mascota con sus atributos privados, tales como nombre, edad y un historial de vacunas.
- Se ofrece un menú interactivo donde el usuario puede:
  - Mostrar la información de la mascota.
  - Agregar vacunas al historial.
  - Escuchar el sonido característico (con polimorfismo para perros y gatos).
  - Añadir una descripción personalizada.
  - Eliminar manualmente la mascota, activando el **destructor (`__del__`)**.
  - Salir del programa.
- El destructor se activa específicamente cuando el objeto mascota es eliminado manualmente con la sentencia `del`. Esto simula la limpieza o cierre de recursos, y muestra un mensaje que confirma la eliminación.

---

## Uso de Constructores y Destructores

- **Constructor (`__init__`)**:  
  Se utiliza para inicializar los atributos de cada objeto mascota al momento de crearlo, asegurando que cada instancia tiene su estado propio. Además, muestra un mensaje confirmando el registro.

- **Destructor (`__del__`)**:  
  Se define para ejecutar una acción cuando un objeto es eliminado de la memoria. En este programa, muestra un mensaje indicando que la mascota fue eliminada del sistema, mostrando una forma simple de limpieza o cierre.

---

## Características Técnicas

- Programación Orientada a Objetos (POO) con conceptos de:
  - Herencia: clases `Perro` y `Gato` heredan de la clase base `Mascota`.
  - Polimorfismo: método `hacer_sonido` redefinido según la especie.
  - Encapsulación: atributos privados protegidos con guion bajo.
- Manejo de entrada de datos con conversión a tipos adecuados (`int` para edad).
- Menú interactivo para facilitar la operación del usuario.


---

## Nota Final

Este proyecto cumple con todos los requisitos de la tarea, demostrando el correcto uso de constructores y destructores, acompañado de una adecuada estructura y documentación que facilitan su comprensión y mantenimiento.

