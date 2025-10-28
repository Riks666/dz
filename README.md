#include <iostream>

//честность
/*int main()
{
	setlocale(LC_ALL, "RU");
	int a;
	std::cout << "Введите число: " << std::endl;
	std::cin >> a;
	
	if (a % 2==0)
	{
		std::cout << "Вы ввели четное число." << std::endl;
	} 
	
	else if(!(a % 2 == 0))
	{
		std::cout << "Вы ввели нечетное число." << std::endl;
	}
}*/

//a<100
int main()
{
	setlocale(LC_ALL, "RU");
	int a;
	std::cout << "Введите число мешьше 100: " << std::endl;
	std::cin >> a;
	if (a < 10) {
		std::cout << "Количество цифр: 1" << std::endl
			<< "Сумма цифр: " << a << std::endl;
	}
	else if(a < 100) {
		int c1 = a / 10;
		int c2 = a % 10;
		int cym = c1 + c2;
		std::cout << "Количество цифр: 2" << std::endl
			<< "Сумма цифр: " << cym << std::endl;
	}
	else if (a > 100) {
		std::cout << "Введени число больше 100 >:(" << std::endl;
	}
}

//дюйм
/*int main()
{
	setlocale(LC_ALL, "RU");
	float a = 2.54;//cm
	int v = 0;
	std::cout << "Выберите что вы хотете сделать:" << std::endl
		<<"1. Перевести см в дюймы"<<std::endl
		<<"2. Перевести дюймы в см"<<std::endl;
	std::cin >> v;

	if (v == 1) {
		float с = 0;
		float с1 = 0;
		std::cout << "Введите см: " << std::endl;
		std::cin >> с;
		с1 = с / a;
		std::cout << с << "см в дюймох будет =" << с1 << std::endl;
	}
	
	if (v == 2) {
		float d = 0;
		float d1 = 0;
		std::cout << "Введите дюйм: " << std::endl;
		std::cin >> d;
		d1 = d * a;
		std::cout << d << " дюйм в см будет =" << d1 << std::endl;
	}
}*/
