#Поиск медианы

Тип ввода выбирается через ключ -t, возможные варианты: keyboard(с клавиатуры), file(из файла) и random(генерируются случайные массивы).По умолчанию используется ввод с клавиатуры. Например:

  ./median -t file : ввод из файла.
  
  ./median : ввод с клавиатуры.
  
  Формат файла для ввода : первая строка - длина каждого массива N, следующие строчки - элементы массивов, записанные через пробел(строк может быть любое кол-во, но они должны начинаться и заканчиваться элементами,а не пробелами).
  
  Вывод - значение медианы и время ее поиска, строк две - первый метод(используется библиотека statistics) и второй(используется метод getMedian(используется метод дихотомии))
#Разбиение числа на k слагаемых

 Ввод только с клавиатуры.
 
  Вывод - кол-во разбиений и время его поиска.Строк две - первый метод(getDepartition1 - мой алгоритм) и второй метод(getDepartition2 - используется реккурентная формула из интернета)
