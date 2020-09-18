
<h1> Daha Rusakova </h1>

<p>email: rusackowadasha@yandex.ru </p>
<h2>About myself</h2>
<p>I'm highly motivated student from Saint-Peterburg. 
I don't have work experience, but I'm learning a lot now. And I like it. I love seach new information and study it. 
And yes I learn very quickly. 
I also very fast find a common language with people.</p>

<h2> SKILLS </h2>
<h5>1. Java/JavaScript </h5> 
    reasonably experienced
<h5>2. C++ </h5> 
    reasonably experienced
<h5>3. Teamwork </h5> 
    reasonably experienced
<h5>4. Time Management </h5> 
    reasonably experienced

<h2>Code examples</h2>



```
#include <iostream>//Подключаем библиотеку ввода и выводы;

using namespace std;
class Chess {
private:
	int x;//Координата Х;
  
	int y; //Координата У;
	int c = 0; //Счетчик для четности;
	int z = 0;
public:
	void SetX(int rX, int rY);
	int prov(int x, int y);
	//Вывод результата;
	void print(); 
	//Методы для запроса данных с клавиатуры;
	void printX();
	void printY();
};
void Chess::SetX(int rX, int rY) {
	x = rX;
	y = rY;
	
	
}
//Выясняем четность суммы поля. Четная(с = 0) - черная, нечетная(с = 1) - белая. Меняем значени счетчика;

int Chess::prov(int x, int y) {
	if ((x > 8) | (y > 8)) {
		cout << "Введенные координаты выходят за пределы поля доски" << endl;
		
	}
	else {
		if ((x + y) % 2 != 0) {
			c = 1;
		}
		return c;
		z == 1;
	}
}
//Вывод результата;
void Chess::print() {
	if (z == 1) {
		if (c == 1) {
			cout << "Данное поле является белым";
		}
		else {
			cout << "Данное поле является черным";
		}
	}
}
//Методы для запроса данных с клавиатуры;
void Chess::printX() {
	cout << "Введите значение по оси Ох: ";
}
void Chess::printY() {
	cout << "Введите значение по оси Оу: ";
}
int main() {
	system("color f1");
	setlocale(LC_ALL, "Russian");//Подключаем русский текст в консоли;
	Chess x; //Создаем объект класса;
	
	int x1;
	x.printX();
	//Ввод х;
	cin >> x1; 

	int y1;
	x.printY();
	//Ввод У;
	cin >> y1;

	//Вызов методов класса chess;
	x.SetX(x1, y1);
	x.prov(x1, y1);
	x.print();

	return 0;
}
```
<h2> Work Experience </h2>
No

<h2>Education </h2>
1. SUAI (2021)
<br>
2. JavaRush

<h2> Languages </h2>
<h4>English</h4>
Good (B1)
