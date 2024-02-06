Shift_Engie_Bot

Телеграм бот на aiogram3 с использованием aiogram-calendar и python-oracle для получения данных напрямую с сервера базы данных Oracle.

Этот бот умеет:
1) Моментально предоставлять информацию в виде сообщения пользователю об завтрашней смене 
2) По текстовому запросу формата дд.мм.ГГГГ показывать рабочую смену на интересующую дату (если дата верна и таблица со сменами заполнена на запрашиваемый день)
3) Показывать календарь и с него делать запрос на интересующую дату
4) Устанавливать напоминания о завтрашней смене

Бот разрабатывался для использования с Oracle 11.2 в корпоративной сети, по этому все IP адреса в проекте необходимо заменить на Ваши.
В проекте для доступа к Oracle используется Instant Client, установите его и измените путь в oracle_db.py, либо используйте Thin Client (также требуется изменение oracle_db.py)
Не забудьте установить requirements.txt перед запуском бота.
