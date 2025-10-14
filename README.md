#include <iostream>
using namespace std;
int main () {
	setlocale(0, "");
	int choice;
	cout << "Введите время года" << endl;
	cout << "[1] - Лето" << endl;
	cout << "[2] - Осень" << endl;
	cout << "[3] - Зима" << endl;
	cout << "[4] - Весна" << endl;
	cout << "Введите число 1-4" << endl;
	cin >> choice;
	if (choice == 1) {
		cout << "Сейчас лето, оденьтесь легко";
	}
	if (choice == 2) {
		cout << "Сейчас осень, возьмите зонт и оденьтесь теплее";
	}	
	if (choice == 3) {
		cout << "Сейчас зима, оденьтесь очень тепло";
	}
	if (choice == 4) {
		cout << "Сейчас весна, возьмите зонт и оденьте ветровку";
	}
	else
		cout << "Ошибка, вы ввели число не входящее в промежуток 1-4" << endl;
}
