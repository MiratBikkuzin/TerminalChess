<p> План проекта:
* Разделяем поровну все типы фигур в шахматаx. Пишем 
для каждой отдельный класс с данным функционалом:
    *документация к использованию
    *инициализатор, принимает три аргумента - x, y, color
    (координаты на шахматном поле, которые в дальнейшем с 
    ходом пользователя, будут перезаписываться)
    *access_check (парамаетры: x, y) - проверка на доступность введенной позиции,
    если верно - то перемещаемся на данную позицию на доске.
    Вражеская фигура(дургой color) - удаляем экземпляр ее класса и становимся на данную позицию. 
    *correct (параметры: None) - выделяет все доступные ходы на доске.
*совместно создаем класс board и Karol
*добавляем авторизацию
*создаем БД и записываем под каждый hash все завершенные партии.</p>
