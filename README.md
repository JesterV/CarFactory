Программа описывает Завод по созданию машины.
Для упрощения вью работают с консолью. при желании их без проблем можно заменить на UI.

Апп работает на модулях с MVC (т.к. код простой, то контроллеры заменены на команды).
CarCreator проходится по всем зарегестрированным модулям и собирает машину из предложенных деталей.

В текущей реализации имеется три модуля деталей (body, electric, engine).
Для добавления нового типа детали достаточно создать новый модуль в намспейсе CarFactory.Module и добавить его модуль в CarFactoryModules.

CarFactoryModules является точкой входа для отделных модулей Завода.
Для отключения модуля достаточно закоментировать/удалить строчку создания модуля из класса CarFactoryModules.


<img width="466" alt="Снимок экрана 2023-09-05 в 21 01 32" src="https://github.com/JesterV/CarFactory/assets/8759232/29a27635-5ce3-4e12-b4b1-a99452a9fbec">
