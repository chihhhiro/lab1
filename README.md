text = 'здравствуйте, вы проходите анкету'
print(text.capitalize ())

first_name = input ('Введите ваше имя:')
last_name = input ('Введите вашу фамилию:')
date_year = input ('Введите ваш год рождения:')
x = input ('Нравится ли Вам курс?')
y = input ('Что вы ожидаете в дальнейших занятиях?')
full_name = first_name + last_name
age = 2023 - int(date_year)
answer1 = x
answer2 = y
print('Вы заполнили следующие данные:')
print('Вас зовут:', first_name, last_name)
print('Вам:', age)
print('Ваш ответ к первому вопросу:', answer1)
print('Ваш ответ ко второму вопросу:', answer2)
