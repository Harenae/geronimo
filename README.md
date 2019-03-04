# geronimo
Данная библиотека содержит набор функций, которые я разработал. С функциями можно ознакомится ниже, библиотека в свободном доступе!

Матемматические функции:

  bool Odd(int i) - Принимает одно целочисленное, возвращает True/False. Данная функция проверяет на то является ли число парным.
  
  int Factoril(int i) - Принимает одно целочисленное, возвращает целочисленное. Данная функция возвращает факториал переданного числа.
  
  int Fibo(int i) - Принимает одно целочисленное, возвращает целочисленное. Данная функция возвращает елемент последовательности Фибоначи с индексом i.
  
Вектора:

  double LengthOfVector_2dot(int[] A,int[] B) - Принимает два целочисленных масива размерностью по 2 элемента А[x,y]. Возвращает число с плавающей запятой, результат длина вектора между двумя точками в декартовой системе координат.
  
  double Perimeter_3dot(int[] A,int[] B,int[] C) - Принимает три целочисленных массива размерностью по 2 элемента A[x,y]. Возвращает число  плавающей запятой, результат периметр треугольника заданного тремя точками в декартовой системе координат.
  
  double RadiusOfTheInscribedCircle(int[] A,int[] B,int[] C) - Принимает три целочисленных массива размерностью по 2 элемента A[x,y]. Возвращает число  плавающей запятой, результат радиус круга вписанного в треугольник, который задан тремя точками в декартовой системе координат.
  
  double AreaOfaTriangle(int[] A, int[] B, int[] C) - Принимает три целочисленных массива размерностью по 2 элемента A[x,y]. Возвращает число  плавающей запятой, результат площадь треугольника заданного тремя точками в декартовой системе координат.
  
  double SquareOfTheInscribedCircle(int[] A, int[] B, int[] C) - Принимает три целочисленных массива размерностью по 2 элемента A[x,y]. Возвращает число  плавающей запятой, результат площадь круга вписанного в треугольник, который задан тремя точками в декартовой системе координат.
  
Преобразование:

  float ConvertToFloat(string line) - Принимает строку и пытается её преобразовать в тип с плавающей запятой, при неудаче запускается цикл с требованием ввести правельное число, при удачном завершении возвращает введенное число с типом float.
  
  double ConvertToDouble(string line) - Принимает строку и пытается её преобразовать в тип с плавающей запятой, при неудаче запускается цикл с требованием ввести правельное число, при удачном завершении возвращает введенное число с типом double.
  
  byte ConvertToByte(string line) - Принимает строку и пытается её преобразовать в целочисленное, при неудаче запускается цикл с требованием ввести правельное число, при удачном завершении возвращает введенное число с типом byte(0,255).
  
  int ConvertToInt32(string line) - Принимает строку и пытается её преобразовать в целочисленное, при неудаче запускается цикл с требованием ввести правельное число, при удачном завершении возвращает введенное число с типом int.

Массивы:

  void PrintValues_Stack(IEnumerable myCollection) - Принимает любые множества данных, массивы, списки, стеки, очереди... Результат, выводит на экран содержимое переданной колеции
