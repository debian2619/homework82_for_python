Задача
Создать информационную систему позволяющую работать с сотрудниками некой компании \ студентами вуза \ учениками школы

Визуализация структуры представлена в файле application_diagram.draw.io

Модули и файлы:

Модуль main : запускает контроллер
Модуль controller : связывает ui и operations_shell
Модуль ui : показывает пользователю доступные действия и приглашаюшает выбрать одно из них
Модуль operations_shell : содержит доступные действия с программой
Модуль operations_content : содержит логику действий
Модуль logger : регистрирует время и наименование запроса, сделенного пользователем
Файлы personal_info.csv.txt, department.csv.txt, salary.csv.txt, log.txt : базы данных
Описание программы

Программа запускается из модуля main.

Пользователь увидит иструкции, что можно сделать с программой.

Также пользователю предлагается выбрать одно из действий:

показать содержание всех файлов
внести нового сотрудника:
При этом пользователь последовательно внесёт данные для столбцов из всех файлов, а данные будут распределены по соответствующим файлам.