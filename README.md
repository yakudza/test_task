# test_task

project_urls

http://127.0.0.1:8010/items/  - will show list of existing items, and form for add new item (REST)
http://127.0.0.1:8010/latest/feed/1  - will return all feed link to all items (RSS)
http://127.0.0.1:8010/login/  - login page
http://127.0.0.1:8010/logout/ - logout page
http://127.0.0.1:8010/register/  - registration page
http://127.0.0.1:8010/profile/  - profile page
http://127.0.0.1:8010/food/  - main page with item list
http://127.0.0.1:8010/food/add - page with add item form
http://127.0.0.1:8010/food/<ID>/ - item details page
http://127.0.0.1:8010/food/update/<ID>/  - edit item page
http://127.0.0.1:8010/food/delete/<ID>/  - delete item

http://127.0.0.1:8010/admin/  django admin page


requirements.txt
django===5.1.2
factory_boy==3.3.1
django-allauth[socialaccount]
djangorestframework==3.15.2
#social-auth-app-django==5.4.2
django-celery
celery[redis]
flower
django-extensions==3.2.3
