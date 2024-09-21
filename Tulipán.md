#include <iostream>
using namespace std;

// Definir los códigos de color ANSI para la consola
#define RESET   "\033[0m"
#define MAGENTA "\033[35m"
#define GREEN   "\033[32m"

int main() {
    // Dibujar un tulipán con arte ASCII y colores
    cout << MAGENTA;  // Poner los pétalos en color magenta

    cout << "      _._      " << endl;
    cout << "   \\ /   \\ //    " << endl;
    cout << "    \/     \\/    " << endl;
    cout << "   /.-'''-.\\   " << endl;

    cout << GREEN;  // Cambiar el color al verde para el tallo
    cout << "      | |      " << endl;
    cout << "      | |      " << endl;
    cout << "     /   \\     " << endl;
    cout << "    |     |    " << endl;
    cout << "               " << endl;

    cout << RESET;  // Restablecer el color predeterminado

    // Mostrar el mensaje final en verde
    cout << GREEN << "Mi pastora tampoco será espectadora" << RESET << endl;

    return 0;
}
<!---
Pame0103/Pame0103 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
