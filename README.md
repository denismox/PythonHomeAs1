# PythonHomeAs1
# Инструкция Пользователя для Budget APP
## Запуск Приложения
1. Откройте командную строку на вашем компьютере.
2. Используя командную строку, перейдите в директорию установки приложения командой cd, например: 'cd path_to_bookkeeper'.
3. Введите команду 'poetry install' для установки необходимых зависимостей.
4. После завершения установки, запустите приложение командой 'poetry run python bookkeeper/view/mainWindow.py'.
## Интерфейс Приложения
![telegram-cloud-photo-size-2-5233311758213569165-y](https://github.com/denismox/PythonHomeAs1/assets/84687793/949204b2-48a5-439d-b5a0-035f6713b7c9)
### Левая Панель
Список Транзакций: отображает все ваши покупки, включая категории, сумму и дату.
Изменение Транзакции: чтобы изменить покупку, сделайте двойной клик по соответствующей записи в списке.
### Правая Панель
Добавление Категории: нажмите на кнопку Add Category для создания новой категории расходов.
Изменение Категории: выберите категорию и нажмите Edit Selected Category, чтобы внести изменения.
Удаление Категории: выберите категорию и нажмите Delete Selected Category, чтобы удалить её.
Добавление Транзакции: введите сумму, комментарий и выберите категорию для новой транзакции, затем нажмите Add Transaction.
### Бюджет и Оставшиеся Средства:
Установка Месячного Бюджета: введите сумму в поле Budget и нажмите Change Monthly Budget.
Автоматический Расчёт: приложение автоматически распределит месячный бюджет на дневной и недельный лимиты.
### Отслеживание Бюджета
Оставшаяся Сумма: показывает разницу между установленным бюджетом и тратами.
Ежедневный и Еженедельный Лимиты: отображает ограничения, на основе вашего бюджета.
### Управление Бюджетом
Нажав на кнопку Change Mounthly Budget можно изменить лимит на день/неделю/месяц. Необходимо ввести сумму на месяц, на неделю и день приложение рассчитает самостоятельно
![telegram-cloud-photo-size-2-5233311758213569187-y](https://github.com/denismox/PythonHomeAs1/assets/84687793/b8faa10b-9261-42f9-b684-c2e104092502)

