The New Project

1. Створити в своєму середовищі новий каталог з назвою "new-project":

$	cd ~
$	mkdir new-project

2. Перейти до каталогу "new-project":

$ 	cd new-project

3. Ініціалізувати новий публічний Git-репозиторій всередині каталогу "new-project".

$	git init

3.1 Створити порожній публічний репо на Гітхабі із іменем "new-project".

3.2 Встановити зв'язок між локальним проектом та проектом на Гіті:

$	git remote add origin https://github.com/4LEXNIK/new-project.git


4. Створити новий файл з назвою "README.md" і додати до нього початковий текст:

$	echo "The New Project" > README.md

5. Підготувати файл "README.md" до коміту:

$	git add README.md


6. Закомітити зміни у репозиторій з коміт повідомленням “init”:

$	git commit -m "init"

6.1 Змінити ім'я основної гілки з master на main:

$	git branch -M main

6.2 Запушити зміни до публічного репозіторію:

$	git push -u origin main

(це робиться тільки з початку, далі можна виконувати команду git push не вказуючи аргументи)

7. Створити нову гілку з назвою "development" і перейдіть до неї.

$	git checkout -b development

8. Додати інструкцію до файлу "README.md" і підготуйте її до коміту.

$	vim README.md
    Дописати інструкцію

$	git add README.md
    Зробити підготовку файлу до коміту.