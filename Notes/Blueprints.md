### Blueprints

- **Add Custom Event** - Создать свой собественный event.
- **Cast to name** - Получить ссылку на определеённый Blueprint. Из него можно вызвать **Custom Event**.
- **Get All Actors Of Class** - Получить массив объектов определённого типа.
- **Length** - Получить длину массива.
- **Set Input Mode Game/UI only** - Переключение ввода между интерфейсом и игрой.
- **Show Mouse Cursor** - Показать/убрать курсор.
- **Get Player Controller** - Получить ввод игрока. Относится к Set Input и показать/убрать курсор.
- **Create Widget** - Создаёт виджет. Принимает класс типа Widget Blueprint.
- **Add to Viewport** - Выводит виджет на экран.
- **Append** - Можно складывать строки.
- **Event Construct/Destruct** - Стандартные конструктор и деструктор.
- ++, == - Разные простые операции.
- **Make/Break** - создаёт или разбивает различиные объекты на части. К примеру **Make Vector** и **Break Vector**.
- **Vector Snap To Grid** - Помещает объект в сетку unreal, подобно тому, как вы делали бы это вручную в рдекторе с выравниванием по сетке.
![[Pasted image 20221208125515.png]]

### Функция Cast to

Любой объект в UE можно попытаться привести к любому другому классу.
Функция возвращает True в случае удачного сравнения, False в случае неудачи, а так же ссылку на текущий объект, но со свойтвами приводимого класса.

### Цвета связей

Фиолетый - ссылка на класс.
Синий - ссылка на объект класса.
Белый - порядок действий.
Розовый - строка?
Красный - булево значение.