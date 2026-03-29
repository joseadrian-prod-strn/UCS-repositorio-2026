/*******************************************************
 * Proyecto: UCS - Universidad de las Ciencias de la Salud
 * Autor: [Jose Adrian Gonzalez]
 * Lenguaje: C++
 * Descripción: Trabajo Repositorio
 *   Sistema conceptual que representa la estructura,
 *   misión y visión de la Universidad de las Ciencias
 *   de la Salud "Hugo Chávez Frías".
 *******************************************************/

#include <iostream>
#include <string>
using namespace std;

// Clase que representa la universidad
class Universidad {
private:
    string nombre;
    string pais;
    string mision;
    string vision;

public:
    Universidad() {
        nombre = "Universidad de las Ciencias de la Salud Hugo Chávez Frías (UCS)";
        pais = "Venezuela";
        mision = "Formar profesionales integrales en el área de la salud con ética, compromiso social y excelencia académica.";
        vision = "Ser una institución líder en la formación de talento humano en salud a nivel nacional e internacional.";
    }

    void mostrarInformacion() {
        cout << "===== INFORMACIÓN INSTITUCIONAL =====" << endl;
        cout << "Nombre: " << nombre << endl;
        cout << "País: " << pais << endl;
        cout << "Misión: " << mision << endl;
        cout << "Visión: " << vision << endl;
    }
};

// Función principal
int main() {
    Universidad ucs;
    ucs.mostrarInformacion();

    cout << "\n===== ÁREAS DE FORMACIÓN =====" << endl;
    cout << "- Medicina Integral Comunitaria" << endl;
    cout << "- Enfermería" << endl;
    cout << "- Odontología" << endl;
    cout << "- Farmacia" << endl;
    cout << "- Salud Pública" << endl;

    cout << "\n===== VALORES =====" << endl;
    cout << "- Ética" << endl;
    cout << "- Humanismo" << endl;
    cout << "- Compromiso social" << endl;
    cout << "- Solidaridad" << endl;

    return 0;
}
