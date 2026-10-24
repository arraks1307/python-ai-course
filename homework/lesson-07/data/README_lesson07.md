# README: данные урока 7 (Titanic)

**Источник:** учебная таблица `titanic.csv` из документации pandas 2.3.3.
https://raw.githubusercontent.com/pandas-dev/pandas/v2.3.3/doc/data/titanic.csv

**Размер:** 891 строка (пассажиры), 12 столбцов.

**Файлы в папке:**
- `titanic_lesson07.csv` — исходная таблица;
- `quality_lesson07.csv` — отчёт о пропусках;
- `manifest_lesson07.json` — описание сохранения;
- `README_lesson07.md` — этот файл.

**Пропуски:** Age — 177, Cabin — 687, Embarked — 2. В остальных полях пропусков нет.

**Что изменялось:** ничего. Данные сохранены без очистки.

**Что проверю при очистке:** допустимые значения (Survived 0/1, Pclass 1–3), повторы PassengerId, пропуски в Age, Fare равный 0 и очень большие значения.
