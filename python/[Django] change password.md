ID를 알고 있다면 간단하게 명령어로 변경
$ python manage.py changepassword [ID]

ID를 모르면 python shell로 변경
$ python manage.py shell

$ from django.contrib.auth.models import User
$ User.objects.filter(is_superuser=True)
$ super_id = User.objects.get(username='id')
$ super_id.set_password('password')
$ super_id.save()
$ exit()
