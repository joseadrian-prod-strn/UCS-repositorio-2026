#  UCS - Universidad de las Ciencias de la Salud "Hugo Chávez Frías"

![C++](https://img.shields.io/badge/Lenguaje-C%2B%2B-blue)
![Estado](https://img.shields.io/badge/Estado-En%20Desarrollo-green)
![Licencia](https://img.shields.io/badge/Licencia-Académica-orange)

---

##  Descripción del Proyecto

Este proyecto es una representación conceptual desarrollada en **C++** que modela la estructura, misión, visión y funcionamiento académico de la **Universidad de las Ciencias de la Salud "Hugo Chávez Frías" (UCS)**.

Simula un sistema institucional orientado a la formación de profesionales en el área de la salud, destacando valores éticos, compromiso social y excelencia académica.

---

##  Objetivos

* Representar la estructura organizativa de la UCS mediante programación orientada a objetos.
* Simular áreas académicas y programas de formación.
* Mostrar información institucional de forma estructurada.
* Aplicar conceptos de C++ en un entorno educativo.

---

##  Tecnologías Utilizadas

* Lenguaje: **C++**
* Paradigma: Programación Orientada a Objetos (POO)
* Compilador sugerido: `g++`

---

##  Estructura del Proyecto

```
UCS-Proyecto/
│
├── main.cpp
├── universidad.h
├── universidad.cpp
├── facultad.h
├── facultad.cpp
├── estudiante.h
├── estudiante.cpp
└── README.md
```

---

##  Instalación y Compilación

1. Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/ucs-proyecto.git
cd ucs-proyecto
```

2. Compila el proyecto:

```bash
g++ main.cpp universidad.cpp facultad.cpp estudiante.cpp -o ucs
```

3. Ejecuta el programa:

```bash
./ucs
```

---

##  Ejemplo de Implementación

```cpp
#include <iostream>
#include "universidad.h"

using namespace std;

int main() {
    Universidad ucs;

    ucs.mostrarInformacion();
    ucs.mostrarCarreras();
    ucs.mostrarValores();

    return 0;
}
```

---

##  Clase Universidad

```cpp
class Universidad {
private:
    string nombre;
    string pais;
    string mision;
    string vision;

public:
    Universidad();
    void mostrarInformacion();
    void mostrarCarreras();
    void mostrarValores();
};
```

---

##  Áreas de Formación

* 🩺 Medicina Integral Comunitaria
* 💉 Enfermería
* 😷 Odontología
* 💊 Farmacia
* 🌎 Salud Pública

---

##  Valores Institucionales

* Ética
* Humanismo
* Compromiso social
* Solidaridad
* Responsabilidad

---

##  Ejemplo de Salida del Sistema

```
===== INFORMACIÓN INSTITUCIONAL =====
Nombre: Universidad de las Ciencias de la Salud Hugo Chávez Frías
País: Venezuela

===== MISIÓN =====
Formar profesionales integrales en el área de la salud...

===== VISIÓN =====
Ser una institución líder en educación médica...

===== CARRERAS =====
- Medicina Integral Comunitaria
- Enfermería
- Odontología

===== VALORES =====
- Ética
- Humanismo
- Solidaridad
```

---

##  Modelo de Estudiante

```cpp
class Estudiante {
private:
    string nombre;
    int edad;
    string carrera;

public:
    Estudiante(string n, int e, string c);
    void mostrarDatos();
};
```

---

## 🏛️ Modelo de Facultad

```cpp
class Facultad {
private:
    string nombre;
    string area;

public:
    Facultad(string n, string a);
    void mostrarFacultad();
};
```

---

##  Futuras Mejoras

* Sistema de inscripción de estudiantes
* Base de datos simulada
* Interfaz gráfica
* Registro de notas
* Gestión de profesores

---

##  Contribuciones

Este proyecto es de carácter académico. Puedes contribuir mediante:

* Fork del repositorio
* Creación de nuevas funcionalidades
* Mejora del código

---

##  Licencia

Este proyecto es de uso académico y educativo.

---

## 👨‍💻 Autor

**[Jose Adrian]**
Estudiante / Desarrollador

---

##  Nota Final

Este proyecto representa una integración entre la programación en C++ y el enfoque educativo de la UCS, destacando la importancia de la tecnología en la formación de profesionales de la salud.

---

