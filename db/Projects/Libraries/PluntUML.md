[**PlantUML**](https://plantuml.com/) [ru](https://plantuml.com/ru/)

[C4-PlantUML](https://github.com/plantuml-stdlib/C4-PlantUML)
[Baytars](https://gitlab.com/Baytars/C4-PlantUML)

#habr [Модель C4, DFD и диаграмма Ганта на PlantUML](https://habr.com/ru/articles/896630/)

*Пример*
```plantuml
Bob -> Alice : hello
Alice -> Wonderland: hello
Wonderland -> next: hello
next -> Last: hello
Last -> next: hello
next -> Wonderland : hello
Wonderland -> Alice : hello
Alice -> Bob: hello
```