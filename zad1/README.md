Описание задачи в файле <Task.md>

Алгоритм работы:

Написала блок схемы в файле <blockshem.drawio.png>;

Написала в отдельном методе создание изначального массива, который задается с массива и выводит его на печать в оформленном виде;

Создала метод по отбору из изначального массива элементов, с количеством символов меньше заданных 3. Через for по условию меньше 3, если подходит то,записать элемент в новый массив.

 Далее создать видимость удаления пустых позиций массива:
     -сначала, с помощью метода Where, мы отбираем или получаем все не пустые 
     значения массива и помещаем их в  коллекцию типа IEnumerable<string>.

     -А затем, с помощью метода ToArray, создаётся новый массив, в который копируются 
     все отобранные значения из полученной ранее коллекции.

     -При этом старый массив (сам объект) ещё какое-то время остается в памяти, 
     дожидаясь сборщика мусора, и он всё так же по-прежнему содержит пустые элементы.
Выводим в консоль исправленный и отредактированный массив.

4.Вызываем методы из главного меню.