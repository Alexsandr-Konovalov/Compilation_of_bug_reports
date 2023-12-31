﻿На [странице с тестовой формой авторизации](http://testingchallenges.thetestingmap.org/login/login.php). Данная форма авторизации должна реализовывать следующие требования:

- Корректными данными для авторизации являются: username — `admin`, password — `admin`;
- В форме авторизации выводится сообщение `Logged In Successfully` при вводе корректных авторизационных данных;
- В форме авторизации выводится сообщение `Enter Both Username And Password`, если хотя бы одно из полей не заполнено;
- В форме авторизации выводится сообщение `Username Not Found`, если введено любое другое значение username;
- В форме авторизации выводится сообщение `Incorrect password`, если введён верный username и неверный пароль;
- Все сообщения выводятся над кнопкой `Log In`;
- Форма авторизации предлагает выбрать один из четырёх языков интерфейса: английский, французский, итальянский, немецкий;
- Выбранный язык не сбрасывается после попытки авторизации.

Провести интуитивное тестирование, сравнивая получаемые результаты с описанными выше требованиями. Если фактический результат расходится с требованиями, то описать найденный баг (составить баг-репорт).

***
[bug_reports >>](https://github.com/Alexsandr-Konovalov/Compilation_of_bug_reports/blob/main/bug_reports.md)
