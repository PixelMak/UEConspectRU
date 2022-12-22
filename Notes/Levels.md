Система levels в Unreal позволяет динамически подгружать уровни во время игры для повышения производительности и оптимизации.

Вкладка: **Windows -> Levels**.

![](Files/Images/Pasted%20image%2020221218131647.png)

Люые объекты можно выделить в отдельный level, выбрав **Levels -> Create New With Selected Actors**. Или добавить в текущий (ctrl + m).

Существуют два способа подгрузки уровней:
- Blueprints: **Load Stream Level** и **Unload Stream Level**.
- Level Streaming Volume. Для этого:
   1. Добавить Level Streaming Volumes.
   2. В Levels нажать на иконку Summon Level Details.
   3. Добавить Streaming Volumes для выбранных уровней.