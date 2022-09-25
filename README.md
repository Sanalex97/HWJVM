# HWJVM
Task1
1. Включается подсистема загрузки классов (в нее для загрузки передается класс JvmComprehension)
2. Происходит подготовка класса к выполнению и его проверка на валидность
3. Происходит инициализация класса (static методов)
4.  Происходит добавление в области памяти методов и полей класса: создается фрейм с методом main и методом printAll. В них добавляются поля методов и объекты классов Object, Integer. Сами же классы (Object, Integer)добавляются в heap. 
5.  Сборщик мусора удалит из памяти поле со значение uselessVar = 700, так как оно не используется

Task2


![Classes](https://user-images.githubusercontent.com/72032908/192158389-526187d7-ecb7-4322-b0a1-bf7b58aaa472.jpg)



![Heap](https://user-images.githubusercontent.com/72032908/192158709-f1eda56f-f403-4693-bd6f-31ffe8e1d87e.jpg)



![Metaspace](https://user-images.githubusercontent.com/72032908/192158396-e6aec810-6c8f-4e15-baa4-25a455128518.png)
