# temp-crhome
Необходимо установить `python3` (и прописать его в path) и `chromium` (должно работать и с хромом, но нужно изменить chromium на chrome в launch.py)

На windows не тестировалось, могут быть проблемы с путями к файлам.

Перед запуском перейти в директорию содержащую `launch.py`, создать каталог `profiles` если отсутствует.

Запуск командой 

`python3 launch.py <профиль>`

где `<профиль>` это имя профиля без пробелов латиницей или цифрами.

Если профиля с таким именем нет, то он будет создан.

Если не указывать имя профиля, то будет создан профиль со случайным именем

UserAgent и прокси выбираются случайными для каждого профиля, списки для выбора содержатся в соответствующих файлах, примеры приведены там же.
Защиты от повторного выбора нет
