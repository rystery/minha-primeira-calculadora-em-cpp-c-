#include "teste.h"
#include <iostream>
#include <string>
#include <windows.h>



int main()
{

	int a = 14;
	int b = 3;

	std::cout << "digita o 1 numero: ";
	std::cin >> a;

	std::cout << "digita o 2 numero: ";
	std::cin >> b;

	int resultado = a + b;

	std::cout << "O resultado e: " << resultado;

}
