### ADUser-Duplicate - используется для поиска дублирующихся пользователей в AD. В блоке region используется два примера: поиск по DisplayName (раскомментировать одну строку), и по сочитанию ФИО (sn + givenName).
Отчет ведется в консоль и по завершению выводится в txt-файл, в котором выводится общее кол-во пользователей, которые будут проверяться между собой (например, если 1тыс. пользователей, то это 1млн сравнений), с новой строки перечислены все пользователи, которые имеют дубликаты и их число в скобках, а так же в конце общее кол-во таких пользователей, время выполнения скрипта и текущую дату.
