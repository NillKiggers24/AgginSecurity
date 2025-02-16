# AgginSecurity

Наш проект — это интеллектуальная система фильтрации, которая интегрируется в корпоративные чаты и предотвращает утечку чувствительных данных
Встроенный фильтр на основе модели distilbert, проверяет сообщения на наличие конфиденциальной информации.
Если сообщение содержит запрещенные данные (например, номер карты, паспортные данные и тд), оно не отправляется, а пользователь видит предупреждение.
Все попытки отправки конфиденциальной информации сохраняются в истории опасных запросов и видны пользователям с правами администратора.

Встроенный фильтр на основе модели distilbert( дополнительно обученная на определенных данных ) проверяет сообщения на наличие конфиденциальной информации.
Если сообщение содержит запрещенные данные (например, номер карты, паспортные данные, кредиты и тд), оно не отправляется, а пользователь видит предупреждение.
Все попытки отправки конфиденциальной информации сохраняются в истории опасных запросов и видны пользователям с правами администратора.

В настройках есть вкладка "Уведомления", где отображается история всех попыток отправки конфиденциальной информации.
Каждая запись содержит отправителя, текст сообщения, дату и время.

Панель администратора:
Администратор может просматривать аналитику:
График заблокированных запросов — показывает количество попыток отправки конфиденциальной информации по датам.
График всех сообщений — отображает общее количество отправленных сообщений по датам.
Администратор может просматривать логи всех сообщений, включая заблокированные.
Администратор может добавлять и удалять правила фильтрации для защиты конфиденциальной информации.


