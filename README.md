## Проект по django "Запись на тестдрайв"
### Руководство пользователя.
Проект представляет собой сайт из трех страниц с функцией записи на тестдрайв.
На главной странице отображаются активные записи клиентов.
<img width="733" height="465" alt="image" src="https://github.com/user-attachments/assets/d90f045c-6212-4770-b5e1-eaa033e0faa3" />

Страница "О компании" содержит описание деятельности компании.
<img width="1317" height="637" alt="image" src="https://github.com/user-attachments/assets/e939b5f5-aef4-4a53-8622-9e05a2f8f620" />

Для записи на тестдрайв нужно перейти на страницу "Тестдрайв" и заполнить форму.
<img width="665" height="520" alt="image" src="https://github.com/user-attachments/assets/0278c8be-c5ce-4e7d-83cd-bf60ed531b08" />

После заполнения формы и её отправки новая запись появится на главной странице.
### Руководство программиста.
> Django — это высокоуровневый Python веб-фреймворк, который позволяет быстро создавать безопасные и поддерживаемые веб-сайты.
Начало работы со средой:
```
# Создаю вирт. среду
python -m venv .venv
# Активирую вирт. среду
.venv\Scripts\activate
# Усланавливаю библиотеку
pip install django==5
# Создаю проект
django-admin startproject testdrive
# Перехожу в папке проекта
cd testdrive
# Создаю приложение
python manage.py startapp myapp
# Перейдите в файл settings.py и в разделе INSTALLED_APPS впишите (вконце) название приложения "myapp"
# Запускаю проект
python manage.py runserver
```
